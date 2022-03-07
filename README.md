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


# Interfaces

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
| N16 | Between two SMFs (Roaming between V-SMF and H-SMF) | 

# References

* [Self-driving car](https://en.wikipedia.org/wiki/Self-driving_car)
* [China’s AI attorney claims to prosecute crimes ‘with 97% accuracy’](https://nypost.com/2021/12/27/chinas-ai-attorney-prosecutes-crimes-with-97-accuracy/)
* [BostonDynamics](https://www.bostondynamics.com/)
