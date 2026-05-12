# DDoSing DEFCON 2026

Me and a team of hackers are heading to DEFCON 34 in 2026 and setting up in the DDoS village. We are creating a contest using hacked temu repeaters to create a DDoSing botnet that offense DDoSers can use to take down our targets. 

This repo documents the journey :) 



## The Team
- Saad Baig 
- Rich Compton
- David Nichols
- Ethan Paige


_A special thanks to our sponsors for giving us the infrastructure we needed for this project_
- Cloudflare 
- Netscout 
- Reddit


## Infrastructure
HPE ProLiant DL360 Gen9 1RU Blade Server 
- 2× E5-2620 v3 = 6 core 12 thread 1
- 60GB Ram 
- Proxmox is installed on Raid1 580GB OS Disk
- 2.2TB Logical Array (5 drives total)

Cisco WS-C3750X-48 48 port switch


## Beginnings

It started with me introducing David and Ethan to Rich Compton. Compton runs the DDoS Village at DEFCON and he asked us if we wanted to help us with his community. 

So we started braingstorming what we should do that encompasses DDoS. Because Compton has been working on the Kimwolf botnet at Comcast, he is well versed in DDoS campaigns. 

We decided to buy some cheap temu WiFi repeaters and hack into them since that was how KimWolf was leveraging its DDoS power. 

