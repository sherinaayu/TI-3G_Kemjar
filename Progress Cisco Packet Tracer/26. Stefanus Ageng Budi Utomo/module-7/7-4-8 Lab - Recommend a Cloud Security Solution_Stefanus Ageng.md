# Lab - Recommend a Cloud Security Solution

## Biodata
<table>
    <tr>
        <th>Nama</th>
        <td>Stefanus Ageng Budi Utomo</td>
    </tr>
    <tr>
        <th>Kelas</th>
        <td>TI 3G</td>
    </tr>
    <tr>
        <th>NIM</th>
        <td>2241720126</td>
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
    1. Scalability:<br> Cloud services allow businesses to easily scale up or down based on demand. This is especially beneficial for eCommerce platforms that experience fluctuating traffic, such as during holiday sales.
    2. Cost Efficiency:<br> Cloud providers offer a pay-as-you-go model, reducing upfront infrastructure costs. Businesses can avoid the expense of purchasing and maintaining physical servers, paying only for the resources they use.
    3. Flexibility and Accessibility:<br> Cloud services enable access from anywhere with an internet connection, making it easier for employees and customers to interact with the platform.
    4. Disaster Recovery:<br> Cloud providers often offer automated backups and disaster recovery options, ensuring that critical data and services can be restored quickly in case of a failure or cyberattack.
    5. Automatic Updates:<br> Cloud providers frequently update their infrastructure, ensuring that businesses are running on the latest, most secure versions of the software and hardware.
    6. Enhanced Collaboration:<br> Cloud platforms support real-time collaboration among team members, which is especially useful for distributed teams working on the same project.

2. Can the company rely on the cloud solution provider for everything including services and security? Explain.

    > no, while cloud providers offer many services, including security features, companies should not rely solely on them for all security measures because this some points:

- Shared Responsibility Model:<br> Cloud security is a shared responsibility between the provider and the customer. Cloud providers ensure the security of the cloud infrastructure (e.g., physical servers, networking, storage), while customers are responsible for security in the cloud, which includes securing their data, managing access controls, and ensuring compliance with regulatory standards​.
- Custom Security Requirements:<br> Every business has unique security needs based on its industry, size, and regulatory requirements. While cloud providers offer general security measures like encryption and firewalls, companies may need to implement additional layers such as multi-factor authentication, advanced data encryption, and specific compliance protocols (e.g., PCI DSS for eCommerce).
- Application-Level Security:<br> Securing applications and data stored in the cloud remains the responsibility of the customer. For example, protecting customer data through proper encryption, monitoring traffic for anomalies, and maintaining secure APIs are tasks the business must handle.
- End-User Security Practices:<br> Cloud providers can’t control the security behavior of a company's employees or customers. Implementing practices like strong password policies, phishing education, and regular security audits falls on the business.
