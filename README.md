# DRM: PrecePt
FRI diploma assignment

locally simulated implementation of PrecePt license management protocol

run init.py to prepare test environment

## Notes:
- server currently issues the license WITHOUT asymetrically encrypting it due to the limitations of the current implementation (RSA plaintext size)
- communication is currently simulated: messages are written to the "comms" folder
- all PKI elements currently available to all parties; will be changed when all phases are implemented and tested
