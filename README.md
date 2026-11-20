# NETWORKWALS-WEEK3-PASSWORD-CRACKING
Password Cracking with John the Ripper(JTR) Johnny and Networkwalks tools.

# Week 3 — Password Cracking & AI-Assisted Security Lab

## Overview

Week 3 focused on understanding password security and password-cracking techniques within a controlled cybersecurity laboratory environment.

The week included practical exercises involving John the Ripper (JTR), NW Tools, Kali Linux, and an optional AI-assisted cybersecurity workflow using Claude Desktop and HexStrike MCP.

## Objectives

- Understand the fundamentals of password-cracking in a controlled lab.
- Work with John the Ripper (JTR).
- Explore password-cracking workflows using NW Tools.
- Work with password-protected files in Kali Linux.
- Gain experience troubleshooting cybersecurity tools and their dependencies.
- Explore the use of AI-assisted workflows in cybersecurity.
- Configure an MCP server and connect it to Claude Desktop.
- Understand the challenges involved in integrating multiple security tools.

## Labs Completed

### W3-PM1 — Password Cracking with JTR

Worked through the password-cracking laboratory using John the Ripper.

Key learning areas:

- Password-cracking workflow
- Working with password hashes
- Using JTR in a controlled environment
- Understanding the importance of strong password policies

### W3-PM2 — Password Cracking with NW Tools

Worked through the password-cracking laboratory using NW Tools.

Key learning areas:

- Password-protected files
- Security testing in a controlled environment
- Understanding how password protection can be evaluated
- Comparing different approaches to password-security testing

## Optional Lab — AI-Assisted JTR with Claude & HexStrike MCP

I also explored the optional AI-assisted cybersecurity lab involving Claude Desktop and HexStrike MCP.

### Environment

- Kali Linux
- Python 3
- Python virtual environment
- Flask
- HexStrike AI
- Claude Desktop
- MCP (Model Context Protocol)

### Setup and Troubleshooting

During the setup, I encountered and resolved several environment and configuration issues.

#### Python dependencies

The HexStrike server initially failed because Flask was not installed in the Python virtual environment.

I created/used the project virtual environment and installed the required dependencies before testing the server again.

#### MCP configuration

I configured Claude Desktop to use the HexStrike MCP server and worked through configuration issues involving:

- MCP server paths
- Python virtual-environment paths
- JSON syntax
- Missing commas in the configuration
- Local server addresses
- MCP server availability

The final configuration referenced the Python interpreter inside the HexStrike virtual environment rather than relying on the system Python installation.

## Key Lessons

### 1. Tool knowledge is not enough

Using cybersecurity tools requires understanding the environment in which they operate. Dependencies, paths, permissions, configuration files, and networking can all affect whether a tool works.

### 2. Troubleshooting is part of cybersecurity

Several problems during this week's lab were not caused by the security tools themselves. They were related to Python dependencies, configuration syntax, file paths, and environment setup.

### 3. AI can complement cybersecurity workflows

The optional Claude + HexStrike MCP exercise introduced me to the idea of connecting AI systems with cybersecurity tooling through MCP.

This provided practical exposure to the intersection of:

**AI + Automation + Cybersecurity**

### 4. Controlled environments matter

All password-cracking and security-testing activities in this project were performed for educational purposes within a controlled laboratory environment.

## Technologies & Tools

- Kali Linux
- John the Ripper (JTR)
- NW Tools
- Python
- Flask
- HexStrike AI
- Claude Desktop
- MCP
- Linux CLI
- Git/GitHub

## Week 3 Takeaway

This week helped me move beyond simply learning cybersecurity concepts and into actually troubleshooting and integrating security tools.

The biggest lesson was that becoming effective in cybersecurity requires both **security knowledge and technical problem-solving skills**.

## Author
Alabi Abdulhameed Ayomikun
## Linkedin: 
https://lnkd.in/p/eHWusTR7
