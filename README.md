# codepath-week9
Codepath Week 9 Submission.

# Deployed Honeypot
(1) Dionaea honeypot, deployed over HTTP

# Issues Encountered
- Numerous issues were encountered with the MHN setup process.
- There was no detail provided on how to ACCESS the admin page--I had to research that it was, by default, port 80.
- Was unable to access the admin page for the MHN even after opening Port 80 on my firewall. I discovered that I needed to open port 80 on the Google container, however, which allowed me to access the admin page.
- The install process for `install.sh` required login credentials and then tried to install a now deleted repository from the repository owner HurricaneLabs. I had to navigate to the `install_hpfeeds.sh` file to change the host from HurricaneLabs to couozu (thanks, anonymous GitHub user!)

# Data Collected: number of attacks, number of malware samples, etc.
- 35 attacks. This will increase indefinitely as the honeypot continues to exist.

# Unresolved Questions
- How are these attacks even occuring on a site which hasn't advertised its presence anywhere on the Internet?
