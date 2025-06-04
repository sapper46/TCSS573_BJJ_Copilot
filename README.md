BJJ COPILOT – NODE-RED BASED SMART COACHING SYSTEM

This project presents a complete IoT-driven coaching assistant for Brazilian Jiu Jitsu (BJJ) athletes, built using Raspberry Pi, Node-RED, and Microsoft Azure Custom Vision. Designed for solo training, the BJJ Copilot observes athlete positions using a camera and classifies them in real time. It scores matches according to IBJJF rules, provides verbal cues through a Bluetooth speaker, and uploads performance metrics to InfluxDB for visualization in Grafana.

FEATURES:
- Real-time image capture and classification (11 BJJ positions)
- Verbal coaching via audio prompts
- Scoring logic compliant with IBJJF rule set
- Temperature and boundary monitoring
- Cloud-connected ML inference using Azure
- Data logging to InfluxDB and visualization in Grafana

HARDWARE:
- Raspberry Pi (Linux OS)
- GrovePi sensor board
- USB camera, Bluetooth speaker, thermometer, laser range finder

NOTES:
This system was designed for a single athlete and tailored to their strategy. Future development could incorporate LLM-based adaptive coaching or extend to multi-user setups.

📄 Final project submitted as part of TCSS 573: Internet of Things  
🎓 University of Washington Tacoma | March 2025  
👤 Author: Dave Coughran (sapper46@uw.edu)  

