<h1 align="center">Prevention and Mitigation of DDOS</h1>
<h2>Team Members</h2>
<ol type="1"><li>Navneet Priyadarshi(22BCS074)</li><li>Shruthik Sai(22BCS096)</li><li>Sanchay Awana(22BCS109)</li><li>Shaik Guffran Ahmed(22BCS112)</li></ol>
<hr>
<h2>About DDOS attack</h2>
<p>A Distributed Denial-of-Service (DDoS) attack is a malicious attempt to disrupt the normal functioning of a server, service, or network by overwhelming it with a flood of traffic. This traffic typically comes from multiple sources, making it distributed and harder to mitigate.</p>
<hr>
<h2>Type of DDOS attack we are trying to prevent:</h2>
<p>
In our project, we are trying to prevent the following types of DDoS attacks:

1. <b>Volumetric Attacks</b>: These are aimed at consuming the bandwidth of a targeted server, by involving large amounts of traffic.
2. <b>Protocol Attacks</b>: These attacks consume server resources, such as CPU and memory, by exploiting weaknesses in the protocol stack.
3. <b>Application Layer Attacks</b>: These attacks target the application layer, aiming to exhaust server resources by sending seemingly legitimate requests that are resource-intensive to process.

We focus on detecting and mitigating these attacks in real-time, preventing them from affecting the performance and availability of the targeted system.</p>
<hr>
<h2>What are we trying to do?(Target of our project)</h2>
<p><h3>Objective:</h3>
Detect and mitigate DDoS attacks to prevent service disruption.
<h3>Features:</h3>
<ul><li>Monitors network traffic in real-time to identify patterns indicative of a DDoS attack.<br></li>
<li>Classifies traffic as legitimate or malicious based on predefined attack signatures and abnormal traffic patterns.<br></li>
<li>Implements mitigation strategies such as traffic filtering and rate-limiting to block malicious traffic while ensuring that legitimate requests are processed smoothly.</li>
</ul>
Our project uses various machine learning algorithms and various network monitoring tools to enhance the accuracy and effectiveness of attack detection and mitigation.
<hr>
<h2>Implementation Details:</h2>

1. <b>Traffic Data Collection</b>: 
   - Traffic data is collected from the network, which is then analyzed to detect unusual patterns.
   
2. <b>Traffic Classification</b>:
   - Machine learning algorithms, specifically supervised learning techniques, are applied to classify network traffic as normal or DDoS attack traffic.
   
3. <b>Mitigation Techniques</b>:
   - Once a DDoS attack is detected, mitigation measures such as IP blacklisting and traffic filtering are applied to block malicious traffic.
   - We also implement rate-limiting for suspected IPs to prevent further damage.
4. <b>Alerting and Logging</b>:
   - The system sends alerts when an attack is detected, and logs all malicious activities for future analysis.
<hr>
<h2>Security Measures:</h2>
<ul>
<li><b>Traffic Filtering</b>: Filters out malicious traffic based on known attack signatures and traffic patterns.<br></li>
<li><b>Rate Limiting</b>: Controls the traffic flow from suspected sources to prevent excessive requests from overwhelming the server.<br></li>
<li><b>IP Blocking</b>: Blocks IP addresses that are found to be generating attack traffic, preventing them from accessing the server.<br></li>
<li><b>Real-Time Monitoring</b>: Continuously monitors traffic to ensure immediate detection and response to attacks.<br></li>
</ul>
In addition to these measures, we also use anomaly detection to identify any deviations from normal traffic patterns.
  <hr>
<h2>Progress:</h2>
Completed 
<hr>
<h2>Conclusion:</h2>
In this project, we have implemented a DDoS attack detection and mitigation system. By combining traffic monitoring, machine learning, and network filtering techniques, our system is capable of preventing DDoS attacks and ensuring the availability and stability of the targeted systems.
<hr>
</p>

