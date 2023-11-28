<h1> Analyzing Network Structure & Security</h1>

 
<h2>Scenario</h2>
<i>This scenario is based on a fictional company:</i>
<br>
<br>
I am a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. My organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, my organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

* A new firewall rule to limit the rate of incoming ICMP packets
* Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
* Network monitoring software to detect abnormal traffic patterns
* An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, I am tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). I will use the CSF to help me navigate through the different steps of analyzing this cybersecurity incident and integrate my analysis into a general security strategy:

* Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

* Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

* Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

* Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

* Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

<br />


<h2>Incident Report Analysis</h2>

 <table id='simple_table' >
<tr>
	<td>Summary</td>
	<td> The company experienced a security event when all network services suddenly
stopped responding. The cybersecurity team found the disruption was caused
by a distributed denial of services (DDoS) attack through a flood of incoming
ICMP packets. The team responded by blocking the attack and stopping all
non-critical network services, so that critical network services could be
restored.
</td>
</tr>
<tr>
	<td>Identify</td>
	<td>A malicious actor or actors targeted the company with an ICMP flood attack. The entire internal network was affected. All critical network resources needed to be secured and restored to a functioning state.</td>
</tr>
<tr>
	<td>Protect</td>
	<td>The cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.</td>
</tr>
<tr>
	<td>Detect</td>
	<td>The cybersecurity team configured source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets and implemented network monitoring software to detect abnormal traffic patterns. </td>
</tr>
<tr>
	<td>Respond</td>
	<td>For future security events, the cybersecurity team will isolate affected systems to prevent further disruption to the network. They will attempt to restore any critical systems and services that were disrupted by the event. Then, the team will analyze network logs to check for suspicious and abnormal activity. The team will also report all incidents to upper management and appropriate legal authorities, if applicable.</td>
</tr>
<tr>
	<td>Recover</td>
	<td>To recover from a DDoS attack by ICMP flooding, access to network services need to be restored to a normal functioning state. In the future, external ICMP flood attacks can be blocked at the firewall. Then, all non-critical network services should be stopped to reduce internal network traffic. Next, critical network services should be restored first. Finally, once the flood of ICMP packets have timed out, all non-critical network systems and services can be brought back online.</td>
</tr>
</table>
