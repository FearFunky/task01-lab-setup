# Cybersecurity Virtual Lab Setup

**Zyroo Internship Program — Task 01**

## Objective
To set up a cybersecurity practice lab using Kali Linux, Docker, and OWASP Juice Shop.

## Tools Used
- Kali Linux
- Docker
- OWASP Juice Shop

## Lab Setup
OWASP Juice Shop was deployed as a Docker container on Kali Linux. A custom Docker bridge network named `zyroo-lab` was created.

## Connectivity Verification
The application was tested using the following command:

```bash
curl -I http://127.0.0.1:3000
```

The successful HTTP response confirmed that Juice Shop was accessible locally from the Kali Linux host.

## Network Safety
The application port is bound to `127.0.0.1:3000`, limiting published-port access to the local host. The Docker bridge network is not configured as internal-only.

## Evidence
The repository includes screenshots showing:
- OWASP Juice Shop in the browser
- Docker network configuration
- Kali Linux network configuration
- Successful connectivity test
- Additional lab evidence

## Conclusion
The OWASP Juice Shop environment was deployed using Docker, and local HTTP connectivity was verified successfully.

This lab is intended for authorized cybersecurity learning and testing only.
# Cybersecurity Virtual Lab Setup

**Zyroo Internship Program — Task 01**

## Objective
To set up a cybersecurity practice lab using Kali Linux, Docker, and OWASP Juice Shop.

## Tools Used
- Kali Linux
- Docker
- OWASP Juice Shop

## Lab Setup
OWASP Juice Shop was deployed as a Docker container on Kali Linux. A custom Docker bridge network named `zyroo-lab` was created.

## Connectivity Verification
The application was tested using the following command:

```bash
curl -I http://127.0.0.1:3000
```

The successful HTTP response confirmed that Juice Shop was accessible locally from the Kali Linux host.

## Network Safety
The application port is bound to `127.0.0.1:3000`, limiting published-port access to the local host. The Docker bridge network is not configured as internal-only.

## Evidence
The repository includes screenshots showing:
- OWASP Juice Shop in the browser
- Docker network configuration
- Kali Linux network configuration
- Successful connectivity test
- Additional lab evidence

## Conclusion
The OWASP Juice Shop environment was deployed using Docker, and local HTTP connectivity was verified successfully.

This lab is intended for authorized cybersecurity learning and testing only.
Improve README documentation
