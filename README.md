# Secure Registration Protocol (Secure EBIA / SEBIA)

This repository contains the materials related to a research work on securing online registration protocols based on Email-Based Identification and Authentication (EBIA).

The work proposes a modified protocol that improves security while preserving usability, and formally verifies its properties using ProVerif.

## Contents

- Paper:  
  [On securing online registration protocols: verification of a new proposal](doc/securereg.pdf)

- ProVerif model (main source):  
  [registration-ack.pv](src/registration-ack.pv)

## Summary

The proposed protocol enhances traditional EBIA by:
- Introducing an explicit acknowledgment (ACK) from the mail server
- Using an SSL/TLS registration ticket to bind sessions
- Preventing known attacks on standard email-based registration flows

Security properties (confidentiality and authenticity) are formally verified using ProVerif under the Dolev–Yao model.

## Notes

This repository is a snapshot of the original research artifacts (circa 2014), shared for reference and reproducibility.

