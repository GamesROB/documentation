---
name: Bug report
about: File a bug report to help us improve!
title: '[Bug]: '
labels: [needs attention, bug]
assignees: ''

---

Thanks for taking the time to file a bug report! We use this nifty issue template to make it as straight-forward as possible!


## Steps to reproduce
Give us a list of steps to reproduce your issue!

1. Start the '...'
1. Run '....'
2. Look at '....'
3. Observe the error


## Logs
Give us a copy of your server log file! We recommend [mclo.gs](https://mclo.gs) which is included and automatically removes IPs and other sensitive stuff!


## What's your host OS version?
What's your host's OS version (if you're using a Shared Host, say which one aswell/instead!)

On Windows: Output from `systeminfo | findstr /B /C:"OS Name" /C:"OS Version"`

On Linux: Output from `sudo apt install lsb-release -y & lsb_release -as` (If you're not on a Debian-based distro, you may need to use a different package manager than `apt`!)

On a Shared Host: Just tell us which one you're using!


## Java Version
What's your exact Java version?

Run `java -version` from your Terminal, CMD, or in PowerShell (this works over SSH)!

On a Shared Host? Check your control panel or ask your hosting company's support for what exact Java version and brand they use!


## Client Version
What clientside version are you using? (Make sure your bug happens with Vanilla clients!)


## Screenshots
If possible, add [**imgur.com**](https://imgur.com/upload) screenshots to help us understand your problem. **YOU MUST** use [imgur.com](https://imgur.com/upload) and censor out all private/personally identifiable information!


## Agreements
Do you agree to all of the following (and confirm they are all true)?
- [ ] I'm running my server in online mode (either directly on my backends or on my proxy)
- [ ] The issue occurs with a fresh, clean install of the repo (or I've forked this repository, published my changes, and linked it under **Additional Information** below)
- [ ] I've removed all private/personally identifiable information from this report and anything referenced in this report
- [ ] This isn't a security issue because security issues should be reported following the information in [`SECURITY.md`](https://github.com/GamesROB/documentation/security/policy), **NOT** through GitHub issues


## Additional Information
If you have any other context or relevant information/insight about the problem, put it here.
