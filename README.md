# 5G-research

# Overview
A **5G Network** should be able to:

1. Have cross-environment approach
2. Support Legacy Systems to regards to radio-new-radio.
3. Perform authentication, set QoS, apply policy and charging rules.
4. Have clear cloud source.
5. Reduce latency for transmission of data based on the Edge Computing to facilitate sensor interactions.

> Back-end engine is improved by not-device use.

6. Base on geo-location boarders can be bound and expanded from MMOs participation.
7. Inner-communication systems such as Bluetooth can transmit self communication to reduce overall density for self-driving cars and AI robots.

>  In US for example current Tesla Autopilot is classified as Level 2 under SAE International six levels (0 to 5) of vehicle automation. As for AI robots:  China AI Development Report 2018 correspond to stunning progress and in US one of known names is Boston Dynamics. Both have improvements into Logistics and others.

# Transmitting infrastructure
Simplified before transmitting: 

* Per wave regulations a government owns the transmitting space generally referred as Air-Interface and Spectrum. A government approves this Spectrum based on regulations. In UK for example, such Spectrum was release to cover the new technologies such as 5G.   
* MNOs stand on 3GPP outlined standards and agreement to achieve what is referred as *roaming*. 
* The **Critical infrastructure** (referred to emergency services, electricity, water supply, etc.) is observed by a governments world wide.

# Simplified Architecture

![Untitled Diagram drawio](https://user-images.githubusercontent.com/101095778/157032513-8401abc0-f183-44ca-9add-652cbaf12b02.png)


# Interfaces
Interfaces used in 5G:

| Interface | Description |
--- | --- |
| UE | The UMTS Subscriber or UE (User Equipment) is a combination of ME (Mobile Equipment) and SIM / USIM (Subscriber Identity Module / UMTS Subscriber Identity Module). |
| R(AN) | The Radio Access Network performs the radio functionality of the network, as well as providing the connection to the CN (Core Network). The RAN typically includes a controller ( RNC (Radio Network Controller) in 3GPP (Third Generation Partnership Project) and BSC (Base Station Controller) in 3GPP2 (Third Generation Partnership Project 2)) and several transmitter/receivers ( Node B in 3GPP, BTS (Base Transceiver Station) in 3GPP2).|
| UPF | The User Plane Function is related to the 3GPP 5G Architecture. It is similar to the roles played by the Serving/Packet Gateway in a 4G LTE system. The UPF supports features and capabilities to facilitate user plane operation. Examples include: packet routing and forwarding, interconnection to the Data Network, policy enforcement and data buffering.|
| DN | The Data Network is related to the 3GPP 5G Architecture. It identifies Service Provider services, Internet access or 3rd party services.|
| AMF | The Core Access and Mobility Management Function is part of the 3GPP 5G Architecture. Its primary tasks include: Registration Management, Connection Management, Reachability Management, Mobility Management and various function relating to security and access management and authorization.|
| SMF | The Session Management Function is related to the 3GPP 5G Architecture and is one of the main functions in the Next Generation Core. As such, it includes various functionality relating to subscriber sessions, e.g. session establishment, modify and release.|
| PCF | The Policy Control function is related to the 3GPP 5G Architecture. This function supports the unified policy framework that governs network behaviour. In so doing, it provides policy rules to control plane function(s) to enforce them. In order to facilitate this the subscription information is gathered from the Unified Data Management function.|
| AF | The AF is a logical element of the 3GPP PCC framework which provides session related information to the PCRF in support of PCC rule generation.|
| AUSF | The Authentication Server Function is part of the 3GPP 5G Architecture. It is used to facilitate 5G security processes. |
| UDM | The Unified Data Management is related to the 3GPP 5G Architecture. This supports the ARPF (Authentication Credential Repository and Processing Function) and stores the long-term security credentials used in authentication for AKA. In addition, it stores subscription information.|

> Generally UDR can also be implemented as processing power can be increased due to Edge Computing.

Common reference points:

| Reference Point | Description |
--- | --- |
| N1 | Between UE and AMF (Access and Mobility Management Function) |
| N2|  Between RAN (Radio Access Network) or gNB (i.e. 5G base station) and AMF |
| N3 | Between RAN or gNB (i.e. 5G base station) and UPF (User Plane Function)  |
| N4 | Between SMF (Session Management Function) and UPF  |
| N5 | Between PCF (Policy Control Function) and AF (Application Function). |
| N6 | Between UPF and DN (Data Network) |
| N7 | NG7 is reference point between SMF and PCF. NG7r is reference point between vPCF and hPCF. |
| N8 | Between Unified Data Management (UDM) and AMF. |
| N9 | Between two core UPFs. |
| N10 | Reference point between UDM and SMF. |
| N11 | Between SMF and SMF. |
| N12 | Between AMF and AUSF (Authentication Server Function). |
| N13 | Between UDM and AUSF. |
| N14 | Between two AMFs. |
| N15 | Between PCF and AMF (in Non-roaming scenario) / Between V-PCF and AMF (in Roaming scenario) |

# URLLC 
## Concept: 
URLLC is one of the three facets of 5G, alongside MMTC (Massive Machine Type Communication) and eMBB (enhanced Mobile Broadband). In particular, URLLC features two parts; ultra-reliability which constitutes network reliability of beyond 99.999%, coupled with very low latency for packet transmission (in the order of 1ms and below). Note that the two are mutually exclusive in that some services will require both ultra-reliability and low latency, whereas other services may require one or the other.


# References

* [Self-driving car](https://en.wikipedia.org/wiki/Self-driving_car)
* [China’s AI attorney claims to prosecute crimes ‘with 97% accuracy’](https://nypost.com/2021/12/27/chinas-ai-attorney-prosecutes-crimes-with-97-accuracy/)
* [BostonDynamics](https://www.bostondynamics.com/)
* [5G network reference point architecture](https://www.rfwireless-world.com/Terminology/5G-network-reference-point-architecture.html)
* [Architecture](https://www.grandmetric.com/2017/06/05/5g-core-network-a-short-overview/)
* [MPIRICAL Dictionary](https://www.mpirical.com/glossary/amf-core-access-and-mobility-management-function)
* [Official 5G Map Deployment](https://www.speedtest.net/ookla-5g-map)
* [Harmonized ITU IMT-2020 Standards of 3GPP 5G Technologies Lay The Foundation for a Successful Global Ecosystem](https://www.delloro.com/knowledge-center/white-papers/harmonized-itu-imt-2020-standards-of-3gpp-5g-technologies-lay-the-foundation-for-a-successful-global-ecosystem/)
* [[Seminar] August 14, 2019 – Artem Krasilov – Ultra-reliable low-latency communications in 5G systems](http://wireless.iitp.ru/wnl-seminar-ultra-reliable-low-latency-communications-in-5g-systems/)
