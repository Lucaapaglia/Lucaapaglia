# Luca Paglia

**IT Support & Service Desk · Copenhagen, Denmark**

During an informal IT support internship at Rosario City Council, I helped staff set up Windows and macOS workstations, install software and troubleshoot configuration issues. I'm looking for an onsite IT support or service desk role in Copenhagen.

[Connect on LinkedIn](https://www.linkedin.com/in/luca-paglia/) · [Explore my Windows helpdesk lab](https://github.com/Lucaapaglia/windows-enterprise-helpdesk-lab)

## Three tickets from my Windows lab

I built a Windows Server 2025 domain and joined a Windows 11 workstation to it. I used the workstation to check what a user could actually do after each fix.

| Support ticket | What I found and verified |
| --- | --- |
| [A Finance user gets “Access is denied”](https://github.com/Lucaapaglia/windows-enterprise-helpdesk-lab/blob/main/tickets/001-finance-share-access.md) | The account was missing from the Finance group. After I restored membership and the user signed in again, they could open the share and create a file. |
| [Windows refuses a domain user's sign-in](https://github.com/Lucaapaglia/windows-enterprise-helpdesk-lab/blob/main/tickets/002-workstation-inherited-domain-controller-policy.md) | Security event 4625 led me to a workstation inheriting domain controller policy. After I corrected the OU placement and restarted the PC, a standard user could sign in. |
| [The server answers by IP, but Group Policy fails](https://github.com/Lucaapaglia/windows-enterprise-helpdesk-lab/blob/main/tickets/005-incorrect-dns-breaks-domain-services.md) | Port 445 answered by IP while the server name timed out. After I corrected the client's DNS setting, the name resolved and both user and computer policy updated. |

## Account administration and user support

- **Active Directory and PowerShell.** I used a delegated helpdesk account to onboard and offboard lab users. The scripts preview changes with `-WhatIf`. I also tested a fresh sign-in after disabling an account. [Scripts](https://github.com/Lucaapaglia/windows-enterprise-helpdesk-lab/tree/main/scripts) · [Delegated account tests](https://github.com/Lucaapaglia/windows-enterprise-helpdesk-lab/blob/main/docs/delegated-helpdesk-administration.md)
- **Writing for users.** A missing drive letter and a permission error can look like the same problem. This guide helps a Finance user tell them apart and report exactly what happened. [My Finance drive is missing](https://github.com/Lucaapaglia/windows-enterprise-helpdesk-lab/blob/main/docs/finance-drive-help.md)

I also built a browser-based chess analysis board with React and Stockfish. Its automated tests run in GitHub Actions. [Chess project](https://github.com/Lucaapaglia/chessapp)

**Languages** · English (fluent), Danish (B1), Spanish (native), Italian (conversational)
