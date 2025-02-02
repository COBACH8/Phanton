---
title: dnscheck.tools - check your dns resolvers
source: https://www.dnscheck.tools/
author: 
published: 
created: 2024-11-25
description: A tool to test for DNS leaks, DNSSEC validation, and more
tags:
  - clippings
---
Hello! Your public IP addresses are:

detecting...

Your DNS resolvers are:

detecting...

Your DNS security:

pending...

## ABOUT

dnscheck.tools is a tool to test for [DNS leaks](https://en.wikipedia.org/wiki/DNS_leak), [DNSSEC](https://en.wikipedia.org/wiki/Domain_Name_System_Security_Extensions) validation, and more.

## USAGE

Load [dnscheck.tools](https://www.dnscheck.tools/) in any web browser to identify your current DNS resolvers and check DNSSEC validation.

### DNS TEST QUERIES

dnscheck.tools is also a custom DNS test server! Make test queries like:

$ dig \[SUBDOMAIN.\]go\[-ALG\]\[-NET\].dnscheck.tools TXT

### SUBDOMAIN

The SUBDOMAIN is composed of DNS response options, separated by a hyphen. Options may include:

- any of:
- ***<random>*** - a random number, up to 8 hexadecimal digits; useful for cache busting
- **compress** - force the use of DNS message compression in the response
- **\[no\]truncate** - force or disable message truncation for responses over UDP
- **watch** - mirror corresponding requests to the [/watch/*<random>*](https://www.dnscheck.tools/watch) page; requires *<random>*
- up to one of:
- **padding*<n>*** - add *<n>* bytes of EDNS0 padding, up to 4000, to A, AAAA, and TXT responses
- **txtfill*<n>*** - add *<n>* bytes of padding as TXT data, up to 4000, to TXT responses
- up to one of:
- **formerr** - respond with "format error"
- **servfail** - respond with "server failure"
- **nxdomain** - respond with "non-existent domain"
- **notimpl** - respond with "not implemented"
- **refused** - respond with "query refused"
- **noreply** - do not respond
- **nullip** - respond with all-zero IP (0.0.0.0 for A; :: for AAAA)
- up to one of:
- **nosig** - do not provide any DNSSEC signature in the response
- **badsig** - provide an invalid DNSSEC signature when signing the response
- **expiredsig\[*<t>*\]** - provide an expired DNSSEC signature when signing the response, *<t>* seconds in the past (default 1 day)

### ALG & NET

The zone, go\[-ALG\]\[-NET\], sets DNSSEC signing and network options.

- ALG may be one of:
- **alg13** - sign the zone using ECDSA P-256 with SHA-256 (default)
- **alg14** - sign the zone using ECDSA P-384 with SHA-384
- **alg15** - sign the zone using Ed25519
- **unsigned** - do not sign the zone
- NET may be one of:
- **ipv4** - offer only IPv4 authoritative nameservers
- **ipv6** - offer only IPv6 authoritative nameservers

The zone "go" is equivalent to "go-alg13" and has both IPv4 and IPv6 authoritative nameservers.

### EXAMPLES

See some information about your DNS resolvers:

$ dig go.dnscheck.tools TXT

For our Windows friends:

\> nslookup -q=TXT go.dnscheck.tools

Getting cached results? Introduce a random number:

$ dig 123456.go.dnscheck.tools TXT

Test if your resolvers are validating DNSSEC. This should produce an error:

$ dig badsig-123456.go.dnscheck.tools TXT

Want to watch a stream of DNS requests coming from your resolvers? Goto dnscheck.tools/watch/123456 and specify the watch option:

$ dig watch-123456.go.dnscheck.tools TXT

## SOURCE

See [GitHub](https://github.com/brianshea2/addr.tools). Bug reports and pull requests welcome.

## PRIVACY POLICY

No personal data is collected. This site doesn't use cookies. Cheers!