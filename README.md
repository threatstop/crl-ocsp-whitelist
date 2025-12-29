# crl-ocsp-whitelist

This repo contains several whitelists of OCSP and CRL resources designed to be used to scrub hostname and IP address indicators from automated thread feed generation, such as from sandboxes. Many of these systems engage in a wide variety of otherwise benign traffic and existing whitelist methods (Majestic/Umbrella, etc) don't fully accomodate for things like OCSP/CRL checks.

There are three feeds for CRL and three or OCSP.  Hostnames, IPv4 addresses and IPv6 addresses. Eventually this will be automatically generated on a routine basis. IP addresses do NOT fully accomodate CDNs so the list is far from exhaustive, but the hostnames should be relatively complete based on the authoritative CAs accepted by Mozilla.

For any additional questions, contact Joel Esler at jesler@threatstop.com.

This repo and data is licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)
