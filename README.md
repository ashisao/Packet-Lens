# PacketLens

PacketLens is a network traffic analysis tool that identifies suspicious activity such as abnormal IP behavior, repeated connections, and the use of high-risk ports. It simulates network-level threat detection similar to SOC (Security Operations Center) monitoring.

## Features

- Network log parsing and analysis  
- Detection of high activity IPs (possible scanning)  
- Identification of suspicious ports (22, 23, 3389, 445)  
- Risk scoring system (0–100)  
- Severity classification (Low, Medium, High)  
- Alert generation for anomalous behavior  
- Downloadable network incident report  
- Interactive dashboard using Streamlit  

## Tech Stack

- Python  
- Streamlit  
- Regex  

## How it Works

1. User inputs network traffic logs  
2. Logs are parsed to extract IPs and ports  
3. Repeated connections and suspicious ports are detected  
4. Risk score and severity are calculated  
5. Alerts are generated and displayed  
6. A downloadable report can be generated  

## Live Demo

https://your-packetlens-link.streamlit.app

## Use Case

PacketLens simulates network traffic monitoring in a SOC environment by detecting potential scanning activity and risky port usage, helping analysts identify suspicious behavior quickly.
