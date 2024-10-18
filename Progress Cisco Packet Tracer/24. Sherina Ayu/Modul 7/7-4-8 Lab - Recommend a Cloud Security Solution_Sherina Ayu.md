# Lab - Recommend a Cloud Security Solution

## Biodata
<table>
    <tr>
        <th>Nama</th>
        <td>Sherina Ayu W. P.</td>
    </tr>
    <tr>
        <th>Kelas</th>
        <td>TI 3G</td>
    </tr>
    <tr>
        <th>NIM</th>
        <td>2241720130</td>
    </tr>
</table>

## Objectives
- **Part 1**: Research and Recommend a Cloud Model and a Cloud Service Model
- **Part 2**: Identify Shared Responsibility for Cloud Services and Cloud Security
- **Part 3**: Identify Five Security Threats Related to Cloud Computing
- **Part 4**: Identify Five Security Measures for Deploying eCommerce in Cloud

## Background / Scenario
A startup company is considering a cloud solution for their eCommerce business. The company designs and sells customized clothing and home decoration items to customers around the world. The company hopes the cloud solution can provide key functions including:

- Product search and display with multiple presentations (searching, zooming, and viewing from different angles, etc.)
- Product ordering (order confirmation, delivery tracking and notification, order history, etc.)
- Customer service
- Advertising and promotion
- Sales tracking and reporting

As an IT security specialist, you are asked to research and prepare a report evaluating potential cloud solutions and their security implications.

## Required Resources
- A computer with internet access

## Instructions
### Part 1: Research and Recommend a Cloud Model and a Cloud Service Model
Cloud models include public cloud, private cloud, hybrid cloud, and community cloud. Cloud service models include Software as a Service (SaaS), Platform as a Service (PaaS), and Infrastructure as a Service (IaaS).

Which cloud service model would you recommend to meet the feature requirements of the company? Explain.

> For startup eCommerce businesses, I recommend using Platform as a Service (PaaS). PaaS allows companies to develop and manage features such as product search, order tracking, and customer service without worrying about the underlying infrastructure. The platform is flexible enough to handle advanced product presentations, order confirmations, and customer notifications, and is scalable to accommodate global customers.
> 
> Alternatively, Software as a Service (SaaS) offers a ready-made eCommerce platform but lacks customization, which can limit a business's ability to create unique features. On the other hand, Infrastructure as a Service (IaaS) provides full control over the infrastructure, but is more complex to manage, which can be challenging for startups.

### Part 2: Identify Shared Responsibility for Cloud Services and Cloud Security
Think about shared responsibility for security between the company and a cloud provider for the cloud service model recommended. Use the table below and mark each box with Client, Shared, or Cloud Provider.

Record your chosen cloud service model:
> Below is the shared responsibility for security between the company (client) and the cloud provider, based on the PaaS model.

| Responsibility                              | Client     | Shared     | Cloud Provider         |
|---------------------------------------------|------------|------------|-------------------------|
| Data encryption    |            | Shared     |                         |
| Application security                         | Client     |            |                         |
| Operating system patches/updates             |            | Shared     |                         |
| Network security                             |            | Shared     |                         |
| Infrastructure security (physical data center)|            |            | Cloud Provider          |
| User access management                       | Client     |            |                         |
| Compliance with regulations                  |         | Shared     |                         |
| Database security                            |            | Shared     |                         |
| Disaster recovery                            |            | Shared     |                         |


### Part 3: Identify Five Security Threats Related to Cloud Computing
List at least 5 security threats related to cloud computing.

| Threat               | Description                                                                                  |
|----------------------|----------------------------------------------------------------------------------------------|
| Threat 1             | Data breaches happen when unauthorized users access sensitive data in the cloud. |
| Threat 2             | Weak Identity and Access Management (IAM) can lead to unauthorized access to cloud resources. |
| Threat 3             | Account hijacking occurs when attackers gain control of a cloud account, leading to misuse. |
| Threat 4             | Insecure APIs or interfaces can leave cloud services vulnerable to attacks like injection or denial of service. |
| Threat 5             | DDoS (Distributed Denial of Service) attacks flood cloud services with traffic, making them unavailable. |

### Part 4: Identify Five Security Measures for Deploying eCommerce Cloud Solution
Perform an internet search to find out security measures required to secure an eCommerce cloud solution.

1. PCI Compliance: <br>Ensure your platform complies with Payment Card Industry (PCI) standards. This involves maintaining a firewall, encrypting sensitive data, updating antivirus software, and regularly testing security systems. Compliance helps protect cardholder data and avoid breaches​ <br>
[CLOUDWAYS](https://www.cloudways.com/blog/ecommerce-security-tips/)
[DOT SECURITY](https://dotsecurity.com/insights/blog-must-have-security-measures-ecommerce-websites)
2. HTTPS and Data Encryption:<br> Using HTTPS encrypts the data transfer between the user and the server, preventing attackers from intercepting sensitive information like login credentials and credit card details. <br>
[DOT SECURITY](https://dotsecurity.com/insights/blog-must-have-security-measures-ecommerce-websites)

3. Secure Payment Processing: <br>Employ secure payment gateways that offer fraud protection, multi-factor authentication (MFA), and real-time monitoring to protect financial transactions​.<br>
[DOT SECURITY](https://dotsecurity.com/insights/blog-must-have-security-measures-ecommerce-websites)

4. Two-Factor Authentication (2FA): <br>Add an extra layer of security by requiring 2FA for all logins. This can prevent unauthorized access even if passwords are compromised​.<br>
[CLOUDWAYS](https://www.cloudways.com/blog/ecommerce-security-tips/)

5. Web Application Firewall (WAF): <br>A WAF can filter and monitor HTTP requests, blocking malicious traffic and protecting against threats like SQL injection and cross-site scripting (XSS)​.<br>
[CLOUDWAYS](https://www.cloudways.com/blog/ecommerce-security-tips/)

6. Regular Updates and Patching: <br>Frequently update the platform, including plugins, to patch vulnerabilities and improve security. Automated updates can simplify this process​.<br>
[CLOUDWAYS](https://www.cloudways.com/blog/ecommerce-security-tips/)

7. Data Backup: <br>Regularly back up data and store it securely off-site. This ensures recovery in case of attacks like ransomware or accidental data loss.<br>​
[CLOUDWAYS](https://www.cloudways.com/blog/ecommerce-security-tips/)
[DOT SECURITY](https://dotsecurity.com/insights/blog-must-have-security-measures-ecommerce-websites)


## Reflection Questions
1. What are some benefits of deploying online services in cloud?
    Deploying online services in the cloud offers a range of benefits, including:

1. Scalability
On-Demand Resource Allocation: Cloud services can dynamically scale resources (compute, storage, etc.) up or down based on the demand. This means you can handle traffic spikes without having to invest in expensive infrastructure upfront.
Elasticity: You can expand or reduce your resources automatically as user demand fluctuates, ensuring you only pay for what you use.
2. Cost Efficiency
Pay-As-You-Go Model: Cloud providers offer a consumption-based pricing model, which helps businesses avoid the capital expenses of purchasing hardware and instead pay for resources as they use them.
No Maintenance Costs: The cloud provider manages hardware maintenance, updates, and other operational aspects, freeing your team to focus on core business activities.
3. High Availability and Reliability
Redundancy: Cloud platforms often distribute services across multiple data centers in different geographic locations, ensuring high availability and disaster recovery. This minimizes downtime and ensures reliable access.
Auto-Scaling and Load Balancing: Cloud providers offer built-in load balancing and automated scaling features to distribute traffic efficiently, further enhancing reliability.
4. Faster Deployment and Time to Market
Rapid Setup: Cloud platforms provide ready-to-use infrastructure and pre-configured environments, allowing businesses to deploy services faster compared to traditional infrastructure setup.
DevOps and CI/CD Integration: Many cloud platforms have integrated DevOps tools, enabling faster and automated deployment pipelines (CI/CD), leading to quicker updates and feature releases.
5. Global Reach
Geographic Distribution: Cloud providers have data centers across the globe, allowing businesses to deploy their services closer to their users, reducing latency and improving the user experience.
Easier Expansion: Companies can quickly deploy services in new regions without the need to set up physical infrastructure, making global expansion more feasible.
6. Security and Compliance
Built-in Security Features: Most cloud providers offer a wide range of security features such as data encryption, firewalls, identity management, and security monitoring tools.
Compliance Standards: Cloud providers comply with industry regulations such as GDPR, HIPAA, and SOC, which helps businesses meet legal and security requirements without heavy investment in security infrastructure.

2. Can the company rely on the cloud solution provider for everything including services and security? Explain.

    > no, while cloud providers offer many services, including security features, companies should not rely solely on them for all security measures because this some points:

- Shared Responsibility Model:<br> Cloud security is a shared responsibility between the provider and the customer. Cloud providers ensure the security of the cloud infrastructure (e.g., physical servers, networking, storage), while customers are responsible for security in the cloud, which includes securing their data, managing access controls, and ensuring compliance with regulatory standards​.
- Service Configuration and Management
Cloud Service Misconfiguration: Many security incidents arise not from flaws in the cloud provider’s infrastructure, but from misconfigurations by the customer. For instance, public access to storage buckets or improperly configured firewalls can expose sensitive data.
Responsibility for Security Tools: While the cloud provider offers security tools, it’s up to the customer to configure and use them correctly. For example, setting up multi-factor authentication (MFA), defining encryption policies, or enabling logging and monitoring tools (like AWS CloudTrail or Azure Security Center) is the customer’s job.
- Custom Security Requirements:<br> Every business has unique security needs based on its industry, size, and regulatory requirements. While cloud providers offer general security measures like encryption and firewalls, companies may need to implement additional layers such as multi-factor authentication, advanced data encryption, and specific compliance protocols (e.g., PCI DSS for eCommerce).
- Governance and Risk Management
Data Governance: Companies must implement data governance policies that define who owns the data, how it is accessed, and what the lifecycle of that data looks like in the cloud. Cloud providers do not dictate how a company manages its own data beyond providing the tools.
Backup and Disaster Recovery: While cloud providers offer tools for backup and disaster recovery, the customer is responsible for implementing and managing these strategies to ensure business continuity in case of a disaster or outage.
- Application-Level Security:<br> Securing applications and data stored in the cloud remains the responsibility of the customer. For example, protecting customer data through proper encryption, monitoring traffic for anomalies, and maintaining secure APIs are tasks the business must handle.
- End-User Security Practices:<br> Cloud providers can’t control the security behavior of a company's employees or customers. Implementing practices like strong password policies, phishing education, and regular security audits falls on the business.
