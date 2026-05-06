# Hardened-Terminal
This repository contains a Seatbelt profile for hardening macOS' built-in Terminal.app.

## Rationale

Terminal Emulators, I believe, are often an oversight in security, and is an inherent attack surface due to their complexity mostly from parsing escape codes and the like.  
Matters do not get any better since macOS do not sandbox `Terminal.app` out of the box.  

I think the risk does become realistic enough to warrant protection when connecting to untrusted remote SSH servers, for example.

Thus, I wrote this seatbelt profile for macOS, which is intended to reduce this attack surface.
