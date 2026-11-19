# Screenshot Index – TechStore AWS E-Commerce ALB Project

These screenshots were supplied by the project owner and renamed for GitHub documentation.

| File | Description |
|---|---|
| `01-EC2-Instances-Overview.png` | EC2 console showing four running instances. |
| `02-EC2-Instances-Console-View.png` | EC2 console view showing the four instances and their status checks. |
| `03-EC2-Security-Group-Inbound-Rules.png` | EC2 security group inbound rules (SSH, HTTP and HTTPS are visible). |
| `04-Home-Target-Group-Overview.png` | Home target group showing two registered targets, both healthy. |
| `05-Mobile-Target-Group-Health-Status.png` | Mobile target group status; the target is shown as unhealthy in this capture. |
| `06-Mobile-Target-Group-Details.png` | Additional view of the Mobile target group, also showing an unhealthy target. |
| `07-ALB-Overview.png` | Application Load Balancer overview showing Active status and internet-facing scheme. |
| `08-ALB-Resource-Map-Routing.png` | ALB resource map showing listener rules, target groups and target health. |
| `09-ALB-Listener-Rules.png` | HTTP:80 listener rules for laptop, mobile and default home routing. |
| `10-Home-Page-Website-Output.png` | TechStore home page browser output. |
| `11-Mobile-Page-Website-Output.png` | TechStore mobile page browser output. |
| `12-Laptop-Page-Website-Output.png` | TechStore laptop page browser output. |
| `13-Home-Target-Group-Registered-Targets.png` | Home target group registered targets showing two healthy instances. |

## Important observation

The supplied Mobile Target Group screenshots show **1 unhealthy target**. The Home Target Group screenshot shows **2 healthy targets**. Resolve the Mobile target health check before describing all target groups as healthy in the README.

Before publishing screenshots in a public repository, consider masking the AWS account ID and any public IP addresses visible in the console screenshots. Never publish access keys, secret keys, passwords, or private keys.
