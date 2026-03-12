# Cloud Journey (Public Proof Log)
**Why I'm here**
I’m transitioning into cloud to build a durable career, solve real problems, and create
options for my family.
**My Focus (next 90 days)**
- AWS foundations (IAM, S3, EC2, CloudWatch)
- IaC with Terraform
- Documenting every build (README, screenshots, LinkedIn)
**Week 1 – Identity & First Wins**
- Set up GitHub + LinkedIn for cloud visibility
- Wrote this public proof log
- Next up: S3 + IAM “Public Access Problem” lab
**Projects (live/soon)**
Automate Snapshot and Server Recovery with IaC
**How I document**
Each project includes: problem → approach → commands/code → screenshots →
lessons learned → what I'd do differently.
**Contact/Connect**
- LinkedIn: http://www.linkedin.com/in/e-jeród-powe-msc-cissp-ceh-78176583
- Notes: If you’re hiring for junior cloud/security roles, I’m documenting proof every
week.
## Week 1 Problem Statement
A public e-commerce site (CloudMart) experienced downtime when images stored in
S3 became inaccessible due to misconfigured bucket permissions.
## Investigation Process
- Reproduced the Access Denied issue.
- Reviewed S3 public access settings.
- Compared IAM roles and bucket policies.
## Solution
Implemented a least-privilege S3 bucket policy allowing controlled public object
access.
## Validation
- Tested object URLs in a browser, verified public access.
- Confirmed no unauthorized uploads possible.
## Result
✅ Product images restored.
✅ Permissions secured.
✅ Cost: $0 (AWS Free Tier).
## Skills Highlighted
AWS S3 • IAM • Cloud Security • Troubleshooting • Documentation
## Week 2 Problem Statement
A public e-commerce site (CloudMart) is manually creating snapshots and needs to automate snapshots and server recovery using IaC.
## Investigation Process
-Identify the server(s) that need snapshots
## Solution
Configured terriform to automatically create snapshots to be used for server recovery.
##Result
✅  Minimized Downtime: With a reliable server recovery plan in place, your organization can quickly recover from a disaster, minimizing the impact on your customers, employees, and overall business operations.
✅  Data Protection: Server recovery ensures that critical data is backed up regularly, reducing the risk of data loss or corruption in case of a disaster.
✅  Business Continuity: A well-planned server recovery process helps ensure that your organization can continue to operate, even in the event of a disaster, by providing a temporary solution until normal operations can resume.
✅  Cost Savings: Minimizing downtime and data loss can result in significant cost savings, as you won't need to spend resources on rebuilding or replacing lost data or hardware.
✅  Compliance with Regulations: Server recovery plans can help organizations comply with Regulations such as HIPAA, PCI-DSS, and GDPR, which require businesses to have a disaster recovery plan in place.
✅  Improved Customer Customer Satisfaction: By minimizing downtime and ensuring business continuity, you can maintain customer satisfaction and trust, even during a crisis.
✅  Reduced Risk of Data Breaches: A server recovery plan can help reduce the risk of data breaches by ensuring that sensitive data is backed up regularly and protected from unauthorized access.
✅  Enhanced Reputation: Having a reliable server recovery plan in place can enhance your organization's reputation as a responsible and prepared business.
✅  Increaded Agility: With a server recovery plan, you can quickly respond to changing business conditions or unexpected events, ensuring that your organization remains agile and competitive.
✅  Comprehensive Planning: Developing a server recovery plan forces organizations to consider all aspects of their operations, including IT, people, and processes, leading to a more comprehensive understanding of their business.
By implementing a robust server recovery plan, you can ensure that your organization is prepared for any unexpected event, minimizing the impact on your business and customers.
## Skills Highlighted
Disaster Recovery • Cloud Security • Troubleshooting • Documentation
