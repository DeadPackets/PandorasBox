# PandorasBox

The goal of this repository is to provide a Github Action that downloads popular/needed Red Teaming tools (.NET, native, Powershell, etc...) and run them through several obfuscators/protectors and finally providing an archive of ready-to-use tools.

This has a number of uses:
    - Generating needed tools before an engagement
    - Re-compiling the entire toolkit during an engagement to prevent blue team from catching you
    - Research how different protects/obfuscators bypass different AV/EDR solutions

## The pipeline

This Github Action does the following (in order):
    1. Setup a Windows machine with all the necessary build tools and SDKs
    2. Clone and download all the needed scripts and tools
    3. Provide a clean build of all tools without tampering/obfuscation (maybe light obfuscation)
    4. Create an obfuscated version of all scripts and tools
    5. Create a report of number of detections (using ANTISCAN.me or VirusTotal or ThreatCheck)
    6. Create a password protected archive as a build artifact and upload it onto Github as a release

## Tools included

TODO

## Obfuscators/Protectors used

TODO

## Credits

TODO
