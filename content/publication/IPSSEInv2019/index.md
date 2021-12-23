---
title: "Searchable Symmetric Encryption System and Method of Processing Inverted Index"

authors:
- Qingji Zheng
- admin
-  Jorge Guajardo Merchan

date: "2019-06-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: "United States Patent Application 20190190709A1"
publication_short: ""

abstract: A searchable symmetric encryption (SSE) system and method of processing inverted index is provided. The SSE system includes genKey, buildSecureIndex, genToken, and search operations. A compress X is integrated into at least one of the buildSecureIndex and search operations. The compress then X takes each entry of an encrypted index, compresses entry of the encrypted index into a compressed entry, and then processes the compressed entry with a function. The function comprises a linked list function and on array function. The search operation decompresses the processed entry and output the decompressed entry. The SSE comprises a client device and a server. The genKey, buildSecureIndex, and genToken operations are integrated into the client device and the search operation is integrated into the server.

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Patent Application
   url: https://appft.uspto.gov/netacgi/nph-Parser?Sect1=PTO2&Sect2=HITOFF&p=1&u=%2Fnetahtml%2FPTO%2Fsearch-bool.html&r=7&f=G&l=50&co1=AND&d=PG01&s1=%22Fan,+Xinxin%22&OS=%22Fan,+Xinxin%22&RS=%22Fan,+Xinxin%22
---