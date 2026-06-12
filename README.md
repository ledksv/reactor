# Reactor — HackTheBox

**Platform:** HackTheBox
**Status: Active — walkthrough locked pending machine retirement.**

Full writeup will be published on [l3dsec.com](https://l3dsec.vercel.app) upon retirement.

## Enumeration

```bash
nmap -sC -sV -p- <TARGET_IP>
```

```
PORT     STATE SERVICE VERSION
3000/tcp open  http    Next.js web application
```

Single web application on port 3000. Response header confirms the framework:

```bash
curl -sI http://<TARGET_IP>:3000/
# X-Powered-By: Next.js
```

Full version identified as **Next.js 15.0.3** via JS chunk inspection.

## // remaining sections locked

This machine is still active on HackTheBox. Full walkthrough will be published upon retirement.

> For educational purposes only. Only test systems you own or have explicit written permission to test.
