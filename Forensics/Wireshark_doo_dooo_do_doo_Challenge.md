# Wireshark doo dooo do doo... (CTF Challenge Writeup)

## Description

This challenge, **Wireshark doo dooo do doo...**, was a part of picoCTF 2021 in the **Forensics** category. It was valued at **50 points**, indicating an easy to medium difficulty level for participants. The objective of the challenge was to analyze a provided network capture file (`shark1.pcapng`) using Wireshark (a network protocol analyzer) to uncover a hidden flag. In essence, the task tests basic packet analysis skills: inspecting captured traffic, extracting useful information (in this case, an obscured flag), and applying a simple decryption to reveal the flag.

**Screenshot 1 – Challenge Overview:**  
The first screenshot shows the challenge prompt on the picoCTF platform. It displays the challenge title “Wireshark doo dooo do doo…” along with its category (Forensics) and the instruction “Can you find the flag? shark1.pcapng.” This sets the objective: download and analyze the provided PCAP file to locate the hidden flag.

![Challenge Overview](images/Screenshot-01.png)


**Screenshot 2 – Downloading the PCAP File:**  
This image shows the use of a command line tool (like wget) to download the PCAP file. It emphasizes that contestants need to retrieve the file as the first step before any analysis can be done.

![Downloading PCAP File](images/Screenshot-02.png)


**Screenshot 3 – Displaying the PCAP File:**  
Here, the PCAP file is opened and displayed in Wireshark. The screenshot demonstrates the typical interface with a list of packets captured during network traffic, which sets the stage for further investigation.

![Displaying PCAP File](images/Screenshot-03.png)


**Screenshot 4 – Exporting HTTP/Text Files:**  
This image captures the process of exporting parts of the capture—specifically HTTP or text files—from Wireshark. The goal is to isolate the encoded message (displayed in ROT13) for further analysis.

![Exporting HTTP/Text Files](images/Screenshot-04.png)




