---
title: "Searchable Symmetric Encryption System and Method of Processing Inverted Index"

authors:
- Qingji Zheng
- admin
- Jorge Guajardo Merchan

date: "2022-08-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: "United States Patent 11405192"
publication_short: ""

abstract: A searchable symmetric encryption (SSE) system and method of processing inverted index is provided. The SSE system includes genKey, buildSecureIndex, genToken, and search operations. A compress X is integrated into at least one of the buildSecureIndex and search operations. The compress then X takes each entry of an encrypted index, compresses entry of the encrypted index into a compressed entry, and then processes the compressed entry with a function. The function comprises a linked list function and on array function. The search operation decompresses the processed entry and output the decompressed entry. The SSE comprises a client device and a server. The genKey, buildSecureIndex, and genToken operations are integrated into the client device and the search operation is integrated into the server.

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Patent
   url: https://ppubs.uspto.gov/pubwebapp/
---