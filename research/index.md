---
layout: page
title: Research
published: true
---
My Research work focuses on analysis, design, and testing of integrated circuits and systems with applications in high-speed secure wireless links, pulse-based radar, THz security imaging and medical monitoring.

###  Ultra-Wideband Impulse Transceiver

In recent years, the research community has reported high-frequency energy detectors in CMOS that operate up to several THz. Currently, the only way to sample a picosecond signal is via photoconductive detection with a femtosecond laser and a PCA. The laser produces 100-fsec optical pulses to generate electron-hole pairs with a short (~1psec) lifetime at the center of the PCA. These electron and holes interact with the electric field of the incoming wave to generate DC current. Since the lifetime of the electron and holes is ~1psec, they can support a picosecond sampler. Although these systems have a large effective bandwidth (hundreds of GHz), the repetition rate of the fsec laser (≤ 100 MHz) limits their sampling rate. Furthermore, these systems require an expensive laser, sensitive optical alignment, and a mechanical delay line to scan a sampling time with steps smaller than 100 fsec.

The proposed idea is to implement laser-free, fully electronic samplers sample picosecond pulses with a sampling rate exceeding 50 GHz. 
(More information coming soon after successful publication)
[[Link](http://www.ece.rice.edu/~ab28/){:target="_blank"}]


### Ultra-Wideband Time-Transfer

Tight synchronization of a distributed array with widely-spaced sparse elements is a key enabler in coherent combining of signals in space. The objective of this project is to build a wireless synchronization link capable of synchronizing a master node to multiple slave nodes with timing jitter of less than 100fsec. One technique for achieving time synchronization among array elements is to use crystal oscillators at each node. Most commercial Temperature Compensated Crystal Oscillators (TCXOs) have a frequency stability of 1 to 5ppm. With this level of stability and a carrier frequency of 100GHz, the local oscillator (LO) frequencies of the transmitting nodes can vary by 500kHz. This frequency difference will cause a phase error of 9° in 50ns (500kHz × 50ns × 360°=9°). This large phase error can severely degrade the level of coherency in arrays with widely spaced antennas. A time-domain waveform sensitive circuitry is designed to generate a timing reference from the LOS signal. To increase the accuracy of the timing reference the circuit extracts the zero crossing of the LOS pulse. To further improve the accuracy, the zero-crossing of the main impulse is separated from the ringing effects caused by nearby objects (antenna packaging, DC biasing wires, etc).

(An ultra-wideband impulse receiver capable of detecting sub-200psec pulses is presented. The chip detects a specific zero-crossing of an incoming pulse and mitigates the undesired effects of ringing. The time detection sensitivity of the chip is limited by the jitter of the incoming pulse rather than the pulse width. A mean RMS jitter of 94fsec is recorded, which translates to the localization accuracy of sub-30μm. The chip is fabricated in IBM 130nm SiGe BiCMOS process technology.)
[[Link](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=7444359&newsearch=true&queryText=H.%20Aggrawal){:target="_blank"}]
  

### Ultra-wideband Pulse-based Directional Modulation

Ultra-wideband Pulse-based Directional Modulation is used for used for secure communication and precision localization. The driving vision of this project is to develop the foundations for realizing hardware layer security in next-generation highly-directional high-data-rate wireless networks. We propose _**spatial encoding**_ as a technique that produces useful and decodable information only at the desired location in space. Thwarting this adversary will broadly enhance security features spanning from privacy to prevention of unauthorized access to physical resources. A patent has been granted on the underline IP.

(A new techniques for ultra- wideband joint spatial coding is introduced in order to establish a secure line- of-sight (LOS) wireless communication link, performing precision localization of point objects, and generating high-resolution images from complex scenes. In the proposed technique, symbol generation and coding are jointly performed by multiple widely spaced transmitters. This method enables the transmission of directionally-modulated signals that can only be decoded at the desired angle, resulting in a secure communication link. It is also shown that joint spatial coding by multiple transmitters that are synchronized with each other enables the precise localization of multiple point objects and allows high-resolution 3-dimensional imaging of distributed objects. The technique is demonstrated experimentally in the frequency range 3–10GHz by generating and detecting ultra-wideband pulses.)
[[Link](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=7411369&newsearch=true&queryText=H.%20Aggrawal){:target="_blank"}]<br>

### Hi-speed Analog to Digital Converter

A high-speed analog to digital (ADC) is developed in 45nm CMOS technology. The architecture uses Active Cancellation to mitigate the parasitic leakages in a transmission gate and increase the isolation. This increased isolation increases the performance of ADCs. A patent has been granted on the underline IP.
 
(A 40GS/s Track-and-Hold Amplifier with active cancellation capability is presented to mitigate the effect of leakage in transmission gate during the holding mode. A single-ended RF input signal is converted to a differential signal that feeds the active cancellation network. A record SFDR3 of 62dB with 40GS/s and 5GHz input frequency is reported in 45nm CMOS SOI. A droop voltage of 20μv/ns is measured. An isolation of 32dB at 1GHz between the holding and tracking modes is recorded.)
[[Link](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6848630&newsearch=true&queryText=H.%20Aggrawal){:target="_blank"}]<br>
