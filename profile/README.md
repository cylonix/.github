# Cylonix

![Cylonix](./landing.jpeg)

Cylonix is an open source client application for the Cylonix Secure Access Service Edge (SASE) service. On devices, it runs a modified version of Tailscale™ (WireGuard-based mesh VPN) to provide secure, private connectivity.

## Features

- Exit Node as a Service  
  Terminate your WireGuard mesh on a privacy-first infrastructure.  
- Data Privacy  
  End-to-end encryption using WireGuard ensures your traffic remains confidential.  
- Optional Enterprise Security  
  - Cilium-based firewall for fine-grained network policy enforcement  
  - VPP-based policy routing engine for high-performance traffic steering  
- Lightweight by Default  
  Most users need only the WireGuard mesh network; enterprise users can layer on Cilium and VPP for advanced control.

## Architecture

1. WireGuard mesh network termination  
2. (Enterprise only) Cilium firewall integration  
3. (Enterprise only) VPP policy routing engine

The default WireGuard mesh is sufficient for secure peer-to-peer connectivity. Enterprises can enable Cilium and VPP components to enforce security policies and route traffic at scale.

## More about Cylonix

[Cylonix https://cylonix.io](https://cylonix.io)


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
