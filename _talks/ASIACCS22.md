---
title: "The 5G Key-Establishment Stack: In-Depth Formal Verification and Experimentation"

collection: talks

type: "Conference proceedings talk"

permalink: /talks/ASIACCS22

date: 2022-05-30

venue: 'ASIACCS'

location: "Nagasaki, Japan"
---

In this presentation, we study the security of each part of the 5G authenticated key-establishment (AKE) procedures. We also look at the consequences this AKE (in)security has over critical mobile-networks' objects such as PDU sessions. We carry out our formal analyses using the Tamarin formal protocol-verifier. We augmented the standard Dolev-Yao model with different levels of trust and threat, considering: honest, honest-but-curious, as well as rogue radio nodes. Lastly, we also present an emulator of the 5GAKE_stack. This can be a useful 5G API-like tool for the community, to experiment with the 5GAKE_stack, since the 5G networks are not yet fully deployed, and mobile networks are proprietary and closed loops.
