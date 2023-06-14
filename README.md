# Side-Channel-Analysis
Side Channel Analysis of ASCON-128

With the advent of IoT, a huge number of edge devices share data across
the internet. These edge devices are typically resource constrained and need to
operate on lower power than traditional devices. Within this context, lightweight
ciphers are extremely essential to provide encryption capabilities to such devices
without significantly draining power. Given that such devices are deployed on the
network edge, an adversary could have physical access over it, which opens up new
attack vectors that engineers need to consider. We look at one such attack vector, side
channel attacks, and specifically power side channel attacks. This project presents a
side channel assessment of lightweight cryptographic ciphers in the NIST lightweight
crypto standard finalists, focusing on the ASCON family of ciphers. In line with
the threat model, we deploy the ASCON cipher on a hardware Field Programmable
Gate Array (FPGA) target, collect power traces and attempt to recover the secret
key using attacks such as Differential Power Analysis (DPA) and Correlation Power
Analysis (CPA). We use the ChipWhisperer platform to collect and analyse the power
traces for side channel leakage. The results of the analysis provide insights into
the susceptibility of the ASCON cipher to side-channel attacks and highlight the
importance of implementing countermeasures to mitigate the risk of side-channel
leakage. This work contributes to the ongoing efforts to standardize lightweight
cryptography and to ensure the security of cryptographic systems in the face of
side-channel attacks.
