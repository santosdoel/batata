---
title: Oilrig
description: OilRig is a threat group with suspected Iranian origins that has targeted Middle Eastern and international victims since at least 2014. 
published: true
date: 2019-05-01T14:33:56.875Z
tags: 
---

<h2>Summary</h2>

<p>
OilRig is a threat group operating primarily in the Middle East by targeting organizations in this region that are in a variety of different industries; however, this group has occasionally targeted organizations outside of the Middle East as well. It also appears OilRig carries out supply chain attacks, where the threat group leverages the trust relationship between organizations to attack their primary targets.

OilRig is an active and organized threat group, which is evident based on their systematic targeting of specific organizations that appear to be carefully chosen for strategic purposes. Attacks attributed to this group primarily rely on social engineering to exploit the human rather than software vulnerabilities; however, on occasion this group has used recently patched vulnerabilities in the delivery phase of their attacks. The lack of software vulnerability exploitation does not necessarily suggest a lack of sophistication, as OilRig has shown maturity in other aspects of their operations. Such maturities involve:

-Organized evasion testing used the during development of their tools.
-Use of custom DNS Tunneling protocols for command and control (C2) and data exfiltration.
-Custom web-shells and backdoors used to persistently access servers.

OilRig relies on stolen account credentials for lateral movement. After OilRig gains access to a system, they use credential dumping tools, such as Mimikatz, to steal credentials to accounts logged into the compromised system. The group uses these credentials to access and to move laterally to other systems on the network. After obtaining credentials from a system, operators in this group prefer to use tools other than their backdoors to access the compromised systems, such as remote desktop and putty. OilRig also uses phishing sites to harvest credentials to individuals at targeted organizations to gain access to internet accessible resources, such as Outlook Web Access.</p>

<h2>Known Aliases</h2>
<b>
<ul>
 
  <li>APT 34</li>
  <li>Cobalt Gypsy </li>
  <li>Twisted Kitten</li>
  <li>Crambus</li>
  <li>HELIX KITTEN</li>
  <li>Chrysene</li>
 
</ul>
  </b>

<h2>Campaign Blogs</h2>
<ul>
  <li><a href='https://unit42.paloaltonetworks.com/the-oilrig-campaign-attacks-on-saudi-arabian-organizations-deliver-helminth-backdoor/'> Helminth Backdoor Campaign</a></li> 
  <li><a href='https://researchcenter.paloaltonetworks.com/2017/10/unit42-oilrig-group-steps-attacks-new-delivery-documents-new-injector-trojan/'> Agent Injector Campaign</a></li> 
  <li><a href='https://unit42.paloaltonetworks.com/unit42-striking-oil-closer-look-adversary-infrastructure/'> Credential Harverster Campaign</a></li> 
</ul>
 
<h2>Unit 42 Blogs </h2>

<ul>
  <li><a href='https://unit42.paloaltonetworks.com/dns-tunneling-in-the-wild-overview-of-oilrigs-dns-tunneling/'>DNS Tunneling in the Wild: Overview of OilRig’s DNS Tunneling</a></li> 

  <li><a href='https://unit42.paloaltonetworks.com/dns-tunneling-how-dns-can-be-abused-by-malicious-actors/'>DNS Tunneling: how DNS can be (ab)used by malicious actors</a></li> 

  <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-uses-updated-bondupdater-target-middle-eastern-government/'> OilRig Uses Updated BONDUPDATER to Target Middle Eastern Government</a></li> 

   <li><a href='https://unit42.paloaltonetworks.com/unit42-oopsie-oilrig-uses-threedollars-deliver-new-trojan/'> OopsIE! OilRig uses ThreeDollars to Deliver New Trojan</a></li>
 
  <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-targets-middle-eastern-government-adds-evasion-techniques-oopsie/'> OilRig targets a Middle Eastern Government and Adds Evasion Techniques to OopsIE</a></li> 
  
   <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-targets-technology-service-provider-government-agency-quadagent/'> OilRig Targets Technology Service Provider and Government Agency with QUADAGENT</a></li> 
  
   <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-deploys-alma-communicator-dns-tunneling-trojan/'> OOilRig Deploys “ALMA Communicator” – DNS Tunneling Trojan</a></li> 
  <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-performs-tests-twoface-webshell/'> OilRig Performs Tests on the TwoFace Webshell</a></li> 
  
  <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-uses-rgdoor-iis-backdoor-targets-middle-east/'> OilRig uses RGDoor IIS Backdoor on Targets in the Middle East</a></li>
  
  <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-performs-tests-twoface-webshell/'> 		OilRig Performs Tests on the TwoFace Webshell</a></li>
  
  <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-uses-ismdoor-variant-possibly-linked-greenbug-threat-group/'>OilRig uses ISMDoor variant; Possibly Linked to Greenbug Threat Group</a></li>
  
  <li><a href='https://unit42.paloaltonetworks.com/unit42-oilrig-malware-campaign-updates-toolset-and-expands-targets/'>OilRig Malware Campaign Updates Toolset and Expands Targets</a></li>
  
</ul>

<h2>Oilrig Playbooks</h2>
<ul>
<b>
<a href='https://pan-unit42.github.io/playbook_viewer/'>Oilrig Playbooks</a>
</b>
  </ul>
<h2> ATAT Links</h2>
<ul>
   <li><a href='https://atat.unit42.org/investigation/edit/2f524afc31c4406b8d00dbedbb03d627'>OilRig Investigation</a></li>
</ul>
