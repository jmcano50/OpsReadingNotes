*Juan Miguel Cano*
*December 08, 2023*

# Readings: VPC

**How can one host within a VPC any services that need to be public?**

- Use a public subnet with a Network Address Translation (NAT) gateway or instance.

**What are examples of services that would live in the publicly-accessible part of the VPC? The privately-accessible part?**

- Examples: Web servers, load balancers.

- Private services: Database servers, internal APIs.

**What are the trade-offs of using a VPC vs traditional infrastructure?**

- VPC pros: Scalability, isolation, security.
- VPC cons: Learning curve, complexity.
- Traditional pros: Familiarity.
- Traditional cons: Limited scalability, less isolation.

Resources Used:
- https://chat.openai.com/share/b134d8e7-4e27-4f6f-a8c0-b13100f9b252

- https://www.cloudflare.com/learning/cloud/what-is-a-virtual-private-cloud/
