# Preparation for Google Professional Cloud Network Engineer
_[DISCLAIMER] Links dan materials yang ada disini dipergunakan untuk tambahan materi belajar. Sumber belajar yang saya dokumentasikan sendiri ini tidak merepresentasikan informasi resmi dari pihak Google Cloud, meskipun beberapa link dan material bersumber resmi dari Google Cloud._

---
## Exam Preparation Materials
### 1. Exam Guide
- [Professional Cloud Network Engineer: Certification Exam Guide](https://cloud.google.com/certification/guides/cloud-network-engineer)

    > Membahas 5 domain/section yang akan ditanyakan diujian. Bisa dicek beberapa poin mana yang tidak dimengerti untuk dipelajari lebih lanjut.

### 2. Exam Readiness
- [Professional Cloud Network Engineer Sample Questions](https://docs.google.com/forms/d/e/1FAIpQLServ0tNGkr-dYAfmez_Gdk74dmVypZjzUKrkVFtFcArzhmPow/viewform)

    > Simulasi ujian via Google Forms untuk mengenali format pertanyaan ujian GCP PCNE nanti.

## Hands-on Labs (Optional)
### 1. Free Labs
- [Google Cloud Skills Boost](https://www.cloudskillsboost.google/catalog?price%5B%5D=free)

    > Kumpulan lab Google Cloud yang disediakan gratis. Untuk mencoba bisa mendaftar menggunakan akun Google kita.

- [Google Cloud Skill Badges](https://cloud.google.com/training/badges)

    > Gratis 30 hari untuk mengakses labs dan challenge labs. Kalau kita selesaikan semuanya, kita mendapatkan Google Cloud digital skill badge yang bisa dishare ke social media.

## Official Documentation
- [Routes](https://cloud.google.com/vpc/docs/routes) untuk mempelajari:
1. Perbedaan static, dynamic, subnet route, dan route lainnya.
2. Routing order.
3. Beberapa opsi pada static route next hop.

- [VPC-native clusters](https://cloud.google.com/kubernetes-engine/docs/concepts/alias-ips) untuk mempelajari:
1. Apa itu VPC-native clusters di Google Kubernetes Engine.
2. Perbandingan antara VPC-native clusters dengan routes-based cluster.
3. Perencanaan IP address range untuk beberapa pod dan service.
  
- [Best practices for GKE networking](https://cloud.google.com/kubernetes-engine/docs/best-practices/networking) untuk mempelajari:
1. Apa itu private cluster di Google Kubernetes Engine.
2. Keamanan control plane suatu cluster.

- [Configuring privately used public IPs for GKE](https://cloud.google.com/architecture/configuring-privately-used-public-ips-for-GKE) untuk mempelajari:
1. Bagaimana menggunakan public IP sebagai IP private untuk pod di cluster Kubernetes.

- [Private Google Access for on-premises hosts](https://cloud.google.com/vpc/docs/private-google-access-hybrid) untuk mempelajari:
1. Bagaimana kalau aplikasi di on-premise ingin akses Google API bukan melalui internet, tapi koneksi Interconnect atau VPN.

- [Serverless VPC Access](https://cloud.google.com/vpc/docs/serverless-vpc-access) untuk mempelajari:
1. Bagaimana agar serverless service bisa mengakses resource didalam VPC.
2. Support dari Serverless VPC Access.

- [Overview of VPC Service Controls](https://cloud.google.com/vpc-service-controls/docs/overview) untuk mempelajari:
1. Apa itu VPC Service Control.
2. Proteksi apa yang bisa diberikan VPC Service Control.

- [Service perimeter details and configuration](https://cloud.google.com/vpc-service-controls/docs/service-perimeters) untuk mempelajari:
1. Apa itu service perimeter.
2. Perbedaan enforce mode dan dry-run mode.

- [General DNS overview](https://cloud.google.com/dns/docs/dns-overview) untuk mempelajari:
1. Perbedaan Public, Private dan Split horizon DNS.

- [DNS zones overview](https://cloud.google.com/dns/docs/zones/zones-overview) dan [Cloud DNS peering](https://cloud.google.com/blog/products/networking/how-to-use-cloud-dns-peering-in-a-shared-vpc-environment) untuk mempelajari:
1. Pilihan forwarding DNS query dari on-prem ke Google atau dari Google ke on-prem.
2. Perbedaan forwarding zone, peering zone, managed reserve lookup zone, cross-project binding
