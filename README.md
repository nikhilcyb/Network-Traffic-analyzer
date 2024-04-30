# Network-Traffic-analyzer
Network Traffic Analyzer - Identify Network Issues and Security Threats (Python Tool)

This Python tool, Network Traffic Analyzer, helps network administrators and security professionals analyze network traffic captured in PCAP files. It provides valuable insights to identify network problems and potential security vulnerabilities.

Key Features: 

  •	PCAP Analysis: Open and examine network traffic stored in PCAP format.
  
  •	Bandwidth Usage: Calculate the total amount of data transferred across the network.

  •	Protocol Breakdown: See a distribution of the different protocols used in the captured traffic (e.g., TCP, UDP, etc.).
  
  •	Top Communicators: Identify the IP addresses that are sending and receiving the most data.
  
  •	Port Scan Detection: Uncover suspicious activity that might indicate port scanning attempts.
  
  
Planned Improvements:

  •	Visualizations: Generate graphs to analyze traffic patterns based on IP addresses.
  
  •	Performance Metrics: Calculate network performance metrics like latency, packet loss, throughput, jitter, and error rates.
  
Getting Started:

  1.	Installation:
     
    o	Clone the project repository.
    
    o	Navigate to the project directory.
    
    o	Install required libraries using pip install -r requirements.txt.


  2.	Usage:
     
    o	Run the following command to analyze a PCAP file: 
    
    o	python Network_traffic_analyzer.py <path_to_pcap_file> <port_scan_threshold>
    
      o	Replace <path_to_pcap_file> with the actual path to your PCAP file.
      
      o	Replace <port_scan_threshold> with a value to set the sensitivity for detecting port scans (higher value means stricter detection).


Contribute:

We welcome contributions from the community! If you'd like to help improve this tool, follow the instructions for creating a pull request.

