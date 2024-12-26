# 5G_Performance
# Data and code to evaluate performance of a 5G-based infrastructure

This repository contains experimental material related to the paper entitled "Queueing-Based Performance Analysis of 5G Service Function Chains", 
by Mario Di Mauro and Raffaele Peluso.

We provide:

- Wireshark traces (realized via iperf3) of GTP/TCP and GTP/UDP data traffic across a 5G-based testbed realized with UERANSIM and Open5GS, involving gNB and UPF nodes.
- Log traces of gNB and AMF nodes which are involved in the "PDU Session Establihsment" procedure.
Both Wireshark traces and node logs are available here: https://drive.google.com/file/d/12VAbypxduReAoSfuAPSqSFWYKMUVJwGa/view?usp=sharing

Moreover, we provide python routines to process the Wireshark traces aimed at evaluating services times associated to gNB and UPF nodes, along with statistical indicators (mean, median, standard deviation, coefficient of variation,etc.).

Colab routine to process TCP files:
https://drive.google.com/file/d/101dVudxmTuqKfTzKmbd1g5t2PFw6xvrn/view?usp=sharing

Colab routine to process UDP files:
https://drive.google.com/file/d/1zNQaZ-uYvuESwyQqxkgGiXPiSKm8lh9L/view?usp=sharing
