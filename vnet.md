# VNETS

Mutt stuff about vnets.  Not too much here but...

Service tags and IP addresses / IP Ranges - https://docs.microsoft.com/en-us/azure/virtual-network/service-tags-overview#use-the-service-tag-discovery-api-public-preview

## SECURITY

* **Is VNet peering traffic encrypted?** No. Traffic between resources in peered VNets is private and isolated. It remains completely on the Microsoft Backbone.  Vnet peering traffic is not encrypted https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-faq .
