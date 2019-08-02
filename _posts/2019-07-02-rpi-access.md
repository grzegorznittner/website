---
layout: post
title: Accessing RaspberryPi from the Internet
---

Very often we run RPi from home network, we access it via SSH or VNC, all good, up until you need to access it while being outside of home network.

You can try to open ports via your local ISP, but that won't work in most scenarios.

There is also an option to install LogMeIn agents, but it may require premium accounts which are not free. In the past, I was actually using LogMeIn agent and the client, however, this time I wanted to give a try AWS services.

AWS provides service called Systems Manager (SSM) which lets you manage instance on-prem and in the cloud.
SSM requires you to install an agent on the instance and then provision it using AWS Console.
SSM Agent works on RPI which is a great news, that means we can manage our RPI from anywhere in the world via AWS Console.

...
