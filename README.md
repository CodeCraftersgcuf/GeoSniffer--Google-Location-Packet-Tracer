# GeoSniffer

## Overview
GeoSniffer is a versatile tool designed for analyzing network traffic and visualizing it on Google Maps. By leveraging the geographical information of packet origins and destinations, GeoSniffer provides valuable insights into network communication patterns.

## Requirements
Before using GeoSniffer, ensure you have the following:
- Wireshark software installed on your system to capture network traffic.
- Python installed on your system.
- Necessary Python libraries installed:
  - dpkt
  - socket
  - pygeoip

## Usage
1. **Capture Network Traffic:**
   - Use Wireshark to capture network traffic and save it in the "pcap" file format.
   - Save the captured "pcap" file in the same folder as the GeoSniffer Python code.

2. **Set Your Public IP Address:**
   - Obtain your public IP address using a website such as [Check My IP](https://www.whatismyip.com/) or similar.
   - Update the GeoSniffer Python code with your public IP address.

3. **Run GeoSniffer:**
   - Execute the GeoSniffer Python script by hitting the run button or using the command line.
   - The script will process the captured "pcap" file and generate an "output.kml" file.

4. **Upload to Google Maps:**
   - Navigate to [Google My Maps](https://www.google.com/mymaps).
   - Upload the generated "output.kml" file to visualize network traffic on Google Maps.

## Note
- GeoSniffer is intended for educational and research purposes only.
- Ensure compliance with all applicable laws and regulations regarding network monitoring and data privacy.
