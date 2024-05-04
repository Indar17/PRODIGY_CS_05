This is TASK-5my fifth task given to me as a cyber-security intern at Prodigy InfoTech.
Here is a simple packet sniffer tool in Python using the Scapy library. This tool captures network packets and displays relevant information like source and destination IP addresses, protocols, and payload data.

To use this tool, you need to install the Scapy library. You can install it using pip. You can do this by running the following command in your terminal of your IDE:

'pip install scapy'

Please note that this tool is for educational purposes only. Unauthorized packet sniffing or network analysis can be illegal and unethical. Always ensure you have the necessary permissions and authorizations before using such tools.

Also, this tool captures all IPv4 packets. If you want to capture specific types of packets, you can modify the filter parameter in the sniff function. For example, if you want to capture only TCP packets, you can use the filter "tcp". For more information on packet filters, you can refer to the Scapy documentation.

https://scapy.readthedocs.io/en/latest/