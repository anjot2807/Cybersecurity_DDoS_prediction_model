# Cybersecurity_DDoS_prediction_model
Predicting DDoS Attacks in Network Traffic
In today's digital landscape, Distributed Denial of Service (DDoS) attacks pose a significant threat to the availability and reliability of online services. These attacks overwhelm a target system with traffic from multiple sources, rendering it inaccessible to legitimate users. As organizations increasingly rely on digital infrastructure, the ability to detect and mitigate DDoS attacks has become critical. This dataset contains network flow records that can be used to predict whether a given flow is benign or indicative of a DDoS attack. Each record includes various features that provide insights into the nature of the network traffic.

About the Dataset
The Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv dataset is part of the CICIDS dataset, created by the Canadian Institute for Cybersecurity (CIC). The CICIDS dataset simulates realistic network traffic and includes various types of attacks, such as DDoS, brute force, and phishing. It is designed for evaluating intrusion detection systems (IDS) and cybersecurity algorithms.

The specific file focuses on a DDoS attack scenario that occurred on a Friday afternoon during regular working hours. It contains labeled features extracted from the captured network traffic.

You can access the dataset at this link: https://www.unb.ca/cic/datasets/index.html.

Key Features in the Dataset
Flow ID: Unique identifier for each network flow.

Source IP: IP address of the source.

Source Port: Port number used by the source.

Destination IP: IP address of the destination.

Destination Port: Port number used by the destination.

Protocol: Network protocol used (e.g., TCP, UDP).

Timestamp: Date and time when the flow started.

Flow Duration: Duration of the network flow in microseconds.

Total Fwd Packets: Number of packets sent from the source to the destination.

Total Backward Packets: Number of packets sent from the destination to the source.

Total Length of Fwd Packets: Total size (in bytes) of packets sent forward.

Total Length of Bwd Packets: Total size (in bytes) of packets sent backward.

Fwd Packet Length Max: Maximum size of forward packets.

Fwd Packet Length Min: Minimum size of forward packets.

Fwd Packet Length Mean: Mean size of forward packets.

Fwd Packet Length Std: Standard deviation of forward packet sizes.

Bwd Packet Length Max: Maximum size of backward packets.

Bwd Packet Length Min: Minimum size of backward packets.

Bwd Packet Length Mean: Mean size of backward packets.

Bwd Packet Length Std: Standard deviation of backward packet sizes.

Flow Bytes/s: Number of bytes transferred per second.

Flow Packets/s: Number of packets transferred per second.

Flow IAT Mean: Mean time between two consecutive packets in a flow.

Flow IAT Std: Standard deviation of time between packets.

Flow IAT Max: Maximum inter-arrival time between packets.

Flow IAT Min: Minimum inter-arrival time between packets.

Fwd IAT Total: Total inter-arrival time for forward packets.

Fwd IAT Mean: Mean inter-arrival time for forward packets.

Fwd IAT Std: Standard deviation of forward packet inter-arrival time.

Fwd IAT Max: Maximum forward packet inter-arrival time.

Fwd IAT Min: Minimum forward packet inter-arrival time.

Bwd IAT Total: Total inter-arrival time for backward packets.

Bwd IAT Mean: Mean inter-arrival time for backward packets.

Bwd IAT Std: Standard deviation of backward packet inter-arrival time.

Bwd IAT Max: Maximum backward packet inter-arrival time.

Bwd IAT Min: Minimum backward packet inter-arrival time.

Fwd PSH Flags: Number of forward packets with PSH (Push) flag set.

Bwd PSH Flags: Number of backward packets with PSH flag set.

Fwd URG Flags: Number of forward packets with URG (Urgent) flag set.

Bwd URG Flags: Number of backward packets with URG flag set.

Fwd Header Length: Total length of forward headers.

Bwd Header Length: Total length of backward headers.

Fwd Packets/s: Number of forward packets per second.

Bwd Packets/s: Number of backward packets per second.

Min Packet Length: Minimum packet length in the flow.

Max Packet Length: Maximum packet length in the flow.

Packet Length Mean: Mean packet length in the flow.

Packet Length Std: Standard deviation of packet length in the flow.

Packet Length Variance: Variance of packet length in the flow.

FIN Flag Count: Number of packets with the FIN (Finish) flag set.

SYN Flag Count: Number of packets with the SYN (Synchronize) flag set.

RST Flag Count: Number of packets with the RST (Reset) flag set.

PSH Flag Count: Number of packets with the PSH flag set.

ACK Flag Count: Number of packets with the ACK (Acknowledgement) flag set.

URG Flag Count: Number of packets with the URG flag set.

CWE Flag Count: Number of packets with CWE (Congestion Window Reduced) flag set.

ECE Flag Count: Number of packets with ECE (Explicit Congestion Notification Echo) flag set.

Down/Up Ratio: Ratio of downlink to uplink traffic.

Average Packet Size: Average size of packets in the flow.

Avg Fwd Segment Size: Average segment size in the forward direction.

Avg Bwd Segment Size: Average segment size in the backward direction.

Fwd Header Length.1: Duplicate of the Fwd Header Length variable.

Fwd Avg Bytes/Bulk: Average number of bytes sent per bulk in the forward direction.

Fwd Avg Packets/Bulk: Average number of packets sent per bulk in the forward direction.

Fwd Avg Bulk Rate: Average rate of bulk traffic in the forward direction.

Bwd Avg Bytes/Bulk: Average number of bytes sent per bulk in the backward direction.

Bwd Avg Packets/Bulk: Average number of packets sent per bulk in the backward direction.

Bwd Avg Bulk Rate: Average rate of bulk traffic in the backward direction.

Subflow Fwd Packets: Number of packets in the forward subflow.

Subflow Fwd Bytes: Number of bytes in the forward subflow.

Subflow Bwd Packets: Number of packets in the backward subflow.

Subflow Bwd Bytes: Number of bytes in the backward subflow.

Init_Win_bytes_forward: Initial window size in the forward direction.

Init_Win_bytes_backward: Initial window size in the backward direction.

act_data_pkt_fwd: Number of active data packets in the forward direction.

min_seg_size_forward: Minimum segment size in the forward direction.

Active Mean: Mean time a flow was active.

Active Std: Standard deviation of active time.

Active Max: Maximum active time of the flow.

Active Min: Minimum active time of the flow.

Idle Mean: Mean time the flow was idle.

Idle Std: Standard deviation of idle time.

Idle Max: Maximum idle time of the flow.

Idle Min: Minimum idle time of the flow.

Label: Classification label for the flow (e.g., normal or attack).
