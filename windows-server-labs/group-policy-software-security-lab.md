# Group Policy Software and Security Lab

## Goal

Configure software deployment and security settings using Windows Server Group Policy.

## Lab environment

- Windows Server
- Active Directory Domain Services
- Group Policy Management
- File server: FS01
- Shared software folder: \\FS01\Tarkvara$

## What I configured

- Created Group Policy Objects for software deployment
- Installed Google Chrome using MSI package
- Installed Mozilla Firefox using MSI package
- Used a shared software folder on FS01
- Linked policies to the correct OU
- Worked with ADMX and ADML policy files
- Configured security-related Group Policy settings

## Configured policies

- Install Google Chrome
- Install Mozilla Firefox
- Start Menu settings
- Disable screen saver
- Block USB storage
- Force Windows Update
- Block cmd / PowerShell for standard users

## What I learned

In this lab I learned how Group Policy can be used to deploy software, manage Windows settings and improve security in a Windows domain environment.

## Proof / screenshots

Screenshots from the original lab show:

- PolicyDefinitions folder
- Software installation GPO
- Chrome and Firefox MSI deployment
- Security policy settings
- Windows Update policy
- USB storage restriction
## Original report

[Download PDF report](../reports/group-policy-software-security-lab.pdf)
## Status

Completed
