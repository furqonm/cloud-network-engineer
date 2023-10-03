# Google Cloud FAQ
## Compute Engine
### 1. Apa syarat untuk menggunakan Bring Your Own IP (BYOIP)?
#### 1). Customer harus bisa membuktikan kepemilikan ip addressnya lewat RPKI dan ROA.
> RPKI - Resource Public Key Infrastructure - Data yg diprovide oleh ISP yg berisi asosiasi antara public ip customer dengan ASN yg dimiliki customer.
> ROA - Route Origin Authority - Fungsi data ini sama, tapi bentuknya cryptographic certificate.
#### 2). Request ke Google via open case
> Customer membuat request via open case dengan kedua dokumen sebelumnya. Setelah itu tunggu approval dari Google.
#### 3). Setup PAP dan PDP
> Customer membuat PAP (ublic Advertised Prefix) -- dari prefix-prefix yg ada di RPKI, prefix mana yang akan digunakan.
> Lalu agar beberapa IP dari prefix PAP itu bisa diassign ke VM milik customer, dibuat terlebih dahulu PDP (Public Delegated Prefix) -- ini prefix-prefix yg bisa diassign ke beberapa resource milik mereka.
