---

copyright:
  years: 2017, 2018
lastupdated: "2019-03-05"

keywords: explore, firewalls, fsa, fortigate, juniper, vsrx, vra, virtual router appliance, security, vyatta, comparison, features

subcollection: fortigate-10g

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}
{:note: .note}
{:important: .important}
{:row-headers .row-headers}

# Exploring Firewalls
{: #exploring-firewalls}

IBM© Cloud offers several firewalls to choose from. The table below compares the firewall solutions to help you choose the one that's right for you. To learn more about the individual offering, click its name in the table.

Scroll to the right to view the rest of the table!
{: important}

|        | [Security Groups](/docs/infrastructure/security-groups?topic=security-groups-getting-started) (VSI only) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Hardware Firewall ](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Hardware Firewall (Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) | [Cloud  Internet Services](/docs/infrastructure/cis?topic=cis-getting-started)
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful Packet Inspection**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|IP Firewall only|
|**Public Network Protection**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|
|**Private Network Protection**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|||||
|**Ingress Rules**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|IP Firewall only
|**Egress Rules**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||||
|**Single Tenant Appliance**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||![Checkmark icon](../../icons/checkmark-icon.svg)||
|**VLAN Protection**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||![Checkmark icon](../../icons/checkmark-icon.svg)||
|**Multi-VLAN Support**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|||||
|**NAT Support**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||||
|**SSL/IPsec VPN Termination**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||||
|**Open VPN Termination**|||![Checkmark icon](../../icons/checkmark-icon.svg)|||||Supported with single port on TCP/UDP|
|**HA Option**|N/A|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||![Checkmark icon](../../icons/checkmark-icon.svg)|Using Range and Load Balancers|
|**Manage from API & Portal**|Yes|Appliance GUI|Appliance GUI|Appliance GUI|Appliance GUI|Yes|Yes|Cloud console|
|**10Gbps Support**|N/A|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|||||
|**NGFW Add-ons (IPS, AV, WF)**||2019||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|||TLS encryption, IP Firewall rules, and Proxy Protocol v1
|**Cost**|$0/Month|Starting $299.00/month + Cost of Bare Metal Server | Starting $219.00/month + Cost of Bare Metal Server|Starting $4,999.00/month|Starting $999.00/month|Starting $99.00/month|Starting $999.00/month|Starting $275.00/Domain|
{: row-headers}
{: class="comparison-table"}
{: caption="A comparison of IBM's firewall offerings" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
