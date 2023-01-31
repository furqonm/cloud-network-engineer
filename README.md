# Preparation for Google Professional Cloud Network Engineer
_[DISCLAIMER] All links and materials in this repository are for exam preparation of Google Professional Cloud Network Engineer certification. The learning resources documented here do not represent official information from Google Cloud, although some resources are officially from Google Cloud._

---
## Exam Preparation Materials
### 1. Google Cloud Course
- [Networking in Google Cloud: Defining and Implementing Networks](https://www.cloudskillsboost.google/course_templates/35?catalog_rank=%7B%22rank%22%3A4%2C%22num_filters%22%3A1%2C%22has_search%22%3Atrue%7D&search_id=20681003)
- [Networking in Google Cloud: Hybrid Connectivity and Network Management](https://www.cloudskillsboost.google/course_templates/36?catalog_rank=%7B%22rank%22%3A3%2C%22num_filters%22%3A1%2C%22has_search%22%3Atrue%7D&search_id=20680988)

    > Official e-learning from Google Cloud. If you attended Networking in Google Cloud class before, you are able to rewatch what you learned with this e-learning.

### 2. Exam Guide
- [Professional Cloud Network Engineer: Certification Exam Guide](https://cloud.google.com/certification/guides/cloud-network-engineer)

    > 5 domains/sections in an exam that we can cover to understand which topic we don't know and need to explore further.

### 3. Exam Readiness
- [Professional Cloud Network Engineer Sample Questions](https://docs.google.com/forms/d/e/1FAIpQLServ0tNGkr-dYAfmez_Gdk74dmVypZjzUKrkVFtFcArzhmPow/viewform)

    > Official exam questions for Google Professional Cloud Network Engineer via Google Forms.

### 4. Official Documentation

- [Routes](https://cloud.google.com/vpc/docs/routes)
  - Difference between static, dynamic, subnet route, other routing option.
  - Routing order.
  - Next hop options in routing.

- [VPC-native clusters](https://cloud.google.com/kubernetes-engine/docs/concepts/alias-ips)
  - What is VPC-native clusters in Google Kubernetes Engine?
  - Difference between VPC-native clusters than routes-based cluster.
  - An IPs address range planning for pod and service.
  
- [Best practices for GKE networking](https://cloud.google.com/kubernetes-engine/docs/best-practices/networking)
  - What is private cluster in Google Kubernetes Engine?
  - Control plane security.

- [Configuring privately used public IPs for GKE](https://cloud.google.com/architecture/configuring-privately-used-public-ips-for-GKE)
  - How to use public IP as private IP for the pod.

- [Private Google Access for on-premises hosts](https://cloud.google.com/vpc/docs/private-google-access-hybrid)
  - How an on-premise application access Google API without internet, instead via Interconnect or VPN.

- [Serverless VPC Access](https://cloud.google.com/vpc/docs/serverless-vpc-access)
  - How serverless resource can access resources inside the VPC.
  - Serverless VPC Access support.

- [Overview of VPC Service Controls](https://cloud.google.com/vpc-service-controls/docs/overview)
  - What is VPC Service Control?
  - What can VPC Service Control protect?

- [Service perimeter details and configuration](https://cloud.google.com/vpc-service-controls/docs/service-perimeters)
  - What is service perimeter?
  - Diffence of enforce mode and dry-run mode.

- [General DNS overview](https://cloud.google.com/dns/docs/dns-overview)
  - Difference between public, private and split horizon DNS.

- [DNS zones overview](https://cloud.google.com/dns/docs/zones/zones-overview) and [Cloud DNS peering](https://cloud.google.com/blog/products/networking/how-to-use-cloud-dns-peering-in-a-shared-vpc-environment)
  - How to forward DNS query from on-prem to Google or from Google to on-prem.
  - Difference between forwarding zone, peering zone, managed reserve lookup zone, and cross-project binding.
  - Forwarding targets and routing methods.

- [DNS server policies](https://cloud.google.com/dns/docs/server-policies-overview)
  - Inbound and outbound policy.
  - Alternative name servers and routing methods.
