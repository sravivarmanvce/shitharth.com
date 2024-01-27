---
title: Handling tactful data in cloud using PKG encryption technique
authors:
- B. C. Gajarla
- A. V. Rebba
- K. S. Kakathota
- M. Kummari
- admin
date: '2021-01-01'
publishDate: '2024-01-24T08:50:26.159734Z'
publication_types:
- article-journal
doi: 10.1049/icp.2022.0366
abstract: With the availability of the cloud storage services, users can store data
  to the cloud and have the access to share the data to others. The cloud file may
  contain some sensitive information, this information shouldn&apos;t be exposed to
  others. The possible solution could be to encrypt the whole file which is shared
  before sending it to the cloud and to generate the signature to verify the encrypted
  file. Then, upload the encrypted file and signatures to the cloud. This enables
  the sensitive information to be private and only the owner can decrypt the file.
  Hence, it is not feasible to use by others. Distributing the decryption is the possible
  way to access it by others. However, it is not the efficient solution to implement
  this method in real scenarios. In order to overcome this approach, an efficient
  solution is implemented. In this new approach, sensitive information is kept private
  and can easily execute without any complications. Here, a sanitizer is used to sanitize
  the block which contains the sensitive information of the file. Firstly, the user
  binds the data blocks with respect to the sensitive information of the original
  data and generates a digital signature to that block and then sends it to the sanitizer.
  The sanitizer filters these data blocks and also sanitizes the data corresponding
  to the sensitive information. It also evaluates the corresponding signatures into
  valid ones. The signature is used to prove that the cloud truly possesses the data
  blocks. The third-party auditor is a public verifier, it verifies the data stored
  in the cloud on behalf of the user. This method supports the data sharing so that
  the sensitive information is protected in the cloud.
links:
- name: URL
  url: https://digital-library.theiet.org/content/conferences/10.1049/icp.2022.0366
---
