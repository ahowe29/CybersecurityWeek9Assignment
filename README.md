# CybersecurityWeek9Assignment
Allie Howe

Time spent: 4 hours spent in total

> Objective: Setup a honeypot and provide a working demonstration of its features.

### Required: Overview & Setup

- [x] A basic writeup (250-500 words) on the `README.md` desribing the overall approach, resources/tools used, findings
- [x] A specific, reproducible honeypot setup, ideally automated. There are several possibilities for this:
- A Vagrantfile or Dockerfile which provisions the honeypot as a VM or container

### Required: Demonstration

- [x] A basic writeup of the attack (what offensive tools were used, what specifically was detected by the honeypot)
- [x] An example of the data captured by the honeypot (example: IDS logs including IP, request paths, alerts triggered)
- [x] A screen-cap of the attack being conducted

### Optional: Features
- Honeypot
- [ ] HTTPS enabled (self-signed SSL cert)
- [ ] A web application with both authenticated and unauthenticated footprint
- [ ] Database back-end
- [ ] Custom exploits (example: intentionally added SQLI vulnerabilities)
- [ ] Custom traps (example: modified version of known vulnerability to prevent full exploitation)
- [ ] Custom IDS alert (example: email sent when footprinting detected)
- [ ] Custom incident response (example: IDS alert triggers added firewall rule to block an IP)
- Demonstration
- [ ] Additional attack demos/writeups
- [ ] Captured malicious payload
- [ ] Enhanced logging of exploit post-exploit activity (example: attacker-initiated commands captured and logged)

### Required: writeup and Attack
- For this attack I utilized mhn-admin and mhn-honeypot-1 and set it up based on the assignment set up specifications.  My set up was guided by the information provided by Codepath.  I operated the attack under the url http://35.202.252.189.  I ran the nmap command to see the different attacks and downloaded 73 different attacks in a file called sessions.json.

## Video Walkthrough


Here's a walkthrough of implemented user stories:

![honeypot](https://user-images.githubusercontent.com/10890766/32419532-9566f636-c249-11e7-9594-55d723c9b547.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).


## Notes
This lab was fun.

## License

Copyright [2017] [Allie Howe]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
