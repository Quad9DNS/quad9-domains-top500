# quad9-domains-top500
The top 500 most-seen domain names in the Quad9 infrastructure.

 This file contains the daily "most-queried" domain responses as seen by the Quad9 recursive resolver systems.

 Caveats:
  - TLDs are not included as target domains.
  - Some domains may seem unexpected, but that may be due to large query volumes
    due to CDN usage, aggressive client applications, or data transport such as
    anti-virus checksum validation. Quad9 does attempt to prevent DNS tunneling
    but not all tunnel models may be discovered.
  - This list does not take into account TTL - some domains which have higher usage
    may not be shown here as local stub resolvers may cache the names for longer.
  - A higher position is not necessarily a good thing or mean that popularity is
    higher than another domain. While many domains are higher on the list because
    they have higher traffic, some are on the list because they have poor DNS
    TTL management.
  - Not all Quad9 sites are included in this sample set.
  - Query responses are statistically sampled.

 Questions?  Send to support@quad9.net
