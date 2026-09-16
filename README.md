# OWASP Juice Shop Security Lab

## Overview

This repository documents my hands-on web application security learning using OWASP Juice Shop.

The lab is conducted in a controlled local environment for educational and ethical security testing.

## Lab Environment

- Operating System: Kali Linux
- Target Application: OWASP Juice Shop
- Deployment: Docker
- Target URL: http://localhost:3000
- Network Scope: Localhost

## Tools Used

- Docker
- Nmap
- cURL
- Kali Linux
- OWASP Juice Shop

## Progress

### 1. Docker Installation

Docker was installed and configured on Kali Linux.

Docker version was verified successfully.

### 2. OWASP Juice Shop Deployment

The OWASP Juice Shop Docker image was downloaded and deployed locally.

The application was successfully accessed through:

http://localhost:3000

### 3. HTTP Service Verification

The local application was tested using cURL.

The server returned:

HTTP/1.1 200 OK

### 4. Service Discovery

Nmap was used to examine TCP port 3000 and identify the service running on the local system.

### 5. Service Detection

Nmap service/version detection was performed against the local Juice Shop instance.

The service was not automatically identified by Nmap, so the HTTP response fingerprint was displayed for further analysis.

## Learning Objectives

- Understand web application reconnaissance
- Learn HTTP request and response analysis
- Understand service discovery
- Practice Nmap scanning
- Learn web application security concepts
- Perform security testing in an authorized local environment

## Scope

All security testing documented in this repository is performed against my own locally hosted OWASP Juice Shop instance.

No unauthorized systems are targeted.

## Status

🚧 Lab in Progress
