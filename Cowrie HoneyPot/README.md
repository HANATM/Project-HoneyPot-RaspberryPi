 <h1 center="align">What is a HoneyPot ?</h1>
 In cybersecurity, a honeypot is a decoy system or network that is intentionally designed to attract and deceive potential attackers. It is used as a security mechanism to gather information about the attackers, their methods, and their tools, allowing organizations to study and analyze their behavior in order to enhance their overall security posture. </br>
 A honeypot typically mimics a legitimate system or network and contains enticing data or vulnerabilities that might attract attackers. The honeypot appears as an attractive target, encouraging attackers to interact with it while being isolated from the actual critical systems and sensitive information of the organization. </br>

 <h1 center="align">HoneyPot implementation in a Network</h1>
<p align="center">
  <img src="Images/Honeypot-in-a-network.jpg" width="600" height="400">
</p>

The primary purpose of a honeypot is to monitor and learn about attack techniques, collect threat intelligence, and understand the latest trends in cybersecurity threats. By studying the actions of attackers within the controlled environment of a honeypot, organizations can gain insights into new attack vectors, identify previously unknown vulnerabilities, and develop effective countermeasures.

 <h1 center="align">Cowrie HoneyPot</h1>
 Cowrie is a honeypot software that emulates a vulnerable SSH and Telnet server. It is designed to capture and log the activities of attackers attempting to gain unauthorized access to the system. Cowrie is written in Python and is widely used in the cybersecurity community for research, analysis, and threat intelligence gathering.

<h1 center="align">Dispatching Cowrie output to an ELK stack </h1>
 -[**How to send Cowrie output to an ELK stack**](https://cowrie.readthedocs.io/en/latest/elk/README.html)</br>
