# Reflection Paper: Daily Cloud Services & Version Control

## 1. Cloud Services I Use Regularly

In my daily routine, I rely on several cloud-based services for communication, social networking, and content sharing:

1. **Instagram**
2. **Facebook**
3. **Messenger**

## 2. Service and Deployment Models

**Instagram**
- *Service Model:* SaaS (Software as a Service). Instagram is a fully managed application I access through a browser or app to share photos and view stories, without ever configuring servers or infrastructure myself.
- *Deployment Model:* Public Cloud. It runs on Meta's shared infrastructure and is open to anyone on the internet.

**Facebook**
- *Service Model:* SaaS. Facebook delivers a complete social networking platform where Meta manages all hardware, databases, and updates, leaving me to interact only with the software layer.
- *Deployment Model:* Public Cloud. It is hosted on shared infrastructure serving hundreds of millions of public users worldwide.

**Messenger**
- *Service Model:* SaaS. Messenger is cloud-hosted communication software; chat logs, media, and call routing are handled transparently, with no backend setup required from the user.
- *Deployment Model:* Public Cloud. It is accessible globally to anyone with an account and an internet connection, running on public-facing data centers.

## 3. Git & GitHub for Cloud Projects

Version control is critical when working with cloud infrastructure because modern systems are often defined and managed as code (Infrastructure as Code). Even small changes to server configurations, network rules, or deployment scripts can cause downtime or security issues if left untracked, so every change needs a clear, reviewable history.

Git and GitHub support this by letting teams work on separate branches without interfering with each other's progress. Pull requests allow changes to be reviewed before merging, catching mistakes early rather than after deployment. GitHub's commit history also makes it possible to trace exactly what changed, when, and by whom, and to roll back quickly to a stable state if something breaks. Together, these tools reduce errors, prevent accidental overwrites, and make collaborative cloud management safer and more transparent.
