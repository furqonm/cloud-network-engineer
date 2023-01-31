# Preparation for Google Professional Cloud Network Engineer
_[DISCLAIMER] All links and materials in this repository are for exam preparation of Google Professional Cloud Network Engineer certification. The learning resources documented here do not represent official information from Google Cloud, although some resources are officially from Google Cloud._

---
## Exam Preparation Materials
### 1. Google Cloud Course
- [Networking in Google Cloud: Defining and Implementing Networks](https://www.cloudskillsboost.google/course_templates/35?catalog_rank=%7B%22rank%22%3A4%2C%22num_filters%22%3A1%2C%22has_search%22%3Atrue%7D&search_id=20681003)
- [Networking in Google Cloud: Hybrid Connectivity and Network Management](https://www.cloudskillsboost.google/course_templates/36?catalog_rank=%7B%22rank%22%3A3%2C%22num_filters%22%3A1%2C%22has_search%22%3Atrue%7D&search_id=20680988)

    > Official e-learning from Google Cloud. If you attended Networking in Google Cloud class before, we able to rewatch what we learned with this e-learning.

### 2. Exam Guide
- [Professional Cloud Network Engineer: Certification Exam Guide](https://cloud.google.com/certification/guides/cloud-network-engineer)

    > 5 domains/sections in an exam that we can cover to understand which topic we don't know and need to explore further.

### 3. Exam Readiness
- [Professional Cloud Network Engineer Sample Questions](https://docs.google.com/forms/d/e/1FAIpQLServ0tNGkr-dYAfmez_Gdk74dmVypZjzUKrkVFtFcArzhmPow/viewform)

    > Official exam questions for Google Professional Cloud Network Engineer via Google Forms.

### 4. Official Documentation
- [Routes](https://cloud.google.com/vpc/docs/routes) untuk mempelajari:
  - Perbedaan static, dynamic, subnet route, dan route lainnya.
  - Routing order.
  - Beberapa opsi pada static route next hop.

- [VPC-native clusters](https://cloud.google.com/kubernetes-engine/docs/concepts/alias-ips) untuk mempelajari:
  - Apa itu VPC-native clusters di Google Kubernetes Engine.
  - Perbandingan antara VPC-native clusters dengan routes-based cluster.
  - Perencanaan IP address range untuk beberapa pod dan service.
  
- [Best practices for GKE networking](https://cloud.google.com/kubernetes-engine/docs/best-practices/networking) untuk mempelajari:
  - Apa itu private cluster di Google Kubernetes Engine.
  - Keamanan control plane suatu cluster.

- [Configuring privately used public IPs for GKE](https://cloud.google.com/architecture/configuring-privately-used-public-ips-for-GKE) untuk mempelajari:
  - Bagaimana menggunakan public IP sebagai IP private untuk pod di cluster Kubernetes.

- [Private Google Access for on-premises hosts](https://cloud.google.com/vpc/docs/private-google-access-hybrid) untuk mempelajari:
  - Bagaimana kalau aplikasi di on-premise ingin akses Google API bukan melalui internet, tapi koneksi Interconnect atau VPN.

- [Serverless VPC Access](https://cloud.google.com/vpc/docs/serverless-vpc-access) untuk mempelajari:
  - Bagaimana agar serverless service bisa mengakses resource didalam VPC.
  - Support dari Serverless VPC Access.

- [Overview of VPC Service Controls](https://cloud.google.com/vpc-service-controls/docs/overview) untuk mempelajari:
  - Apa itu VPC Service Control.
  - Proteksi apa yang bisa diberikan VPC Service Control.

- [Service perimeter details and configuration](https://cloud.google.com/vpc-service-controls/docs/service-perimeters) untuk mempelajari:
  - Apa itu service perimeter.
  - Perbedaan enforce mode dan dry-run mode.

- [General DNS overview](https://cloud.google.com/dns/docs/dns-overview) untuk mempelajari:
  - Perbedaan Public, Private dan Split horizon DNS.

- [DNS zones overview](https://cloud.google.com/dns/docs/zones/zones-overview) dan [Cloud DNS peering](https://cloud.google.com/blog/products/networking/how-to-use-cloud-dns-peering-in-a-shared-vpc-environment) untuk mempelajari:
  - Pilihan forwarding DNS query dari on-prem ke Google atau dari Google ke on-prem.
  - Perbedaan forwarding zone, peering zone, managed reserve lookup zone, cross-project binding.
  - Forwarding targets dan routing methods.

- [DNS server policies](https://cloud.google.com/dns/docs/server-policies-overview) untuk mempelajari:
  - Penggunaan inbound dan outbound policy.
  - Alternative name servers dan routing methods.
