# Cybersecurity Virtual Lab Setup

## Task 01 — Zyroo Internship Program

### Objective
To set up a cybersecurity practice lab using Kali Linux, Docker, and OWASP Juice Shop.

### Tools Used
- Kali Linux
- Docker
- OWASP Juice Shop

### Setup
OWASP Juice Shop was deployed in a Docker container. A custom Docker bridge network named `zyroo-lab` was created.

### Verification
The Juice Shop web application was verified locally using:

`curl -I http://127.0.0.1:3000`

The successful HTTP response confirmed that the application was accessible from the Kali Linux host.

### Screenshots
See the `screenshots` folder for the browser, network configuration, IP address, and connectivity test evidence.

### Network Safety
The application port was bound to `127.0.0.1:3000` so it is not intentionally published on the host's external network interfaces. The Docker bridge network is not configured as internal-only.

### Scope
This lab is for authorized cybersecurity learning and testing only.
