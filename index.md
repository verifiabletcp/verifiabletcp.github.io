---
layout: default
---

# Verifiable TCP

The Transmission Control Protocol (TCP) is a fundamental Internet protocol responsible for transmitting data 
in daily Internet activities, such as checking emails, reading news, watching videos, messaging friends, making online orders, 
and many others. An essential component of TCP is the congestion-control algorithm implementations (CCAIs) that determine how 
fast TCP transmits data on the Internet. Therefore, CCAIs are imperative for the performance and stability of the Internet. 
However, many bugs have been detected and reported in the CCAIs. These bugs are mistakes made by CCAI developers, and some 
of them have potentially severe impacts on the performance and stability of the Internet. 

The goal of this project is to design and develop a new CCAI design and implementation methodology, called verifiable CCAI, which systematically enables CCAI developers to design and implement CCAIs with not only efficient performance but also verifiable correctness. The proposed verifiable CCAI methodology is inspired by the scalability of the flow modeling methods currently used by the networking community for performance evaluation but is tailored to the software verification methods proposed by the software engineering community.

# Documents

- Mingrui Zhang, Hamid Bagheri, and Lisong Xu, "Toward Non-Expert Customized Congestion Control", in IEEE International Conference on Communications (ICC), Montreal, Canada, June 2025

- Mingrui Zhang, Phuong Ha, Hamid Bagheri, and Lisong Xu, "Accuracy Evaluation of TCP FlightSize Estimation: Analytical and Experimental", International Conference on Computing, Networking and Communications (ICNC), Honolulu, Hawaii, February 2025

- Minh Vu, Hamid Bagheri, Lisong Xu, Wei Sun, Mingrui Zhang, "Scalable Verification of Multi-ACK Properties in Loss-Based Congestion Control Implementations", [IEEE International Conference on Network Protocols (ICNP)](https://icnp24.cs.ucr.edu/index.html), October 2024 [paper][[code](https://github.com/verifiabletcp/asm)]

- Mingrui Zhang, "Experimental Study of Linux Flight Size Estimation", Master Thesis, University of Nebraska-Lincoln, July 2023

- Minh Vu, "Network Protocol Implementation Testing and Verification under Packet Dynamics", PhD Dissertation, University of Nebraska-Lincoln, November 2021

# Code

- ACK-Scalable Method (ASM) for checking the multi-ACK properties of Linux TCP : [code repository with instructions](https://github.com/verifiabletcp/asm)


# Contributors

## Prof. Lisong Xu

## Prof. Hamid Bagheri

## PhD Students

- Mingrui Zhang
- Minh Vu
- Clay Stevens
- Fahmida Afrin
- Md Rashedul Hasan

## MS Students

- Mingrui Zhang

## Undergraduate Students 

- Shrey Agarwal
- Aiden Makovicka
- Uyen Tran
- Jessica Chen
- Patrick Murphy
- Khoa Tran
- Robert Sears
- Saicharith Vaitla

# Acknowledgement

This project is supported in part by [NSF FMitF](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2124116)
