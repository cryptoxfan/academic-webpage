---
title: "Method and System for Dynamic Searchable Symmetric Encryption with Forward Privacy and Delegated Verifiability"

authors:
- admin
- Qingji Zheng
- Lei Yang

date: "2022-01-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: "United States Patent 11222136"
publication_short: ""

abstract: A DSSE architecture network enables multi-user such as data owners and data users to conduct privacy-preserving search on the encrypted PHIs stored in a cloud network and verify the correctness and completeness of retrieved search results simultaneously is provided. The data owners and data users may be patients, HSPs, or combination thereof. An IoT gateway aggregates periodically collected data into a single PHI file, extract keywords, build an encrypted index, and encrypt the PHI files before the encrypted index and PHI files are transmitted to a cloud network periodically for storage thus enable the DSSE architecture network to achieve a sub-linear search efficiency and forward privacy by maintaining an increasing counter for each keyword at the IoT gateway. Since the PHI files are always transmitted and added/stored into the cloud storage over the cloud network, file deletion, file modification is eliminated. The cloud network therefore does not need to learn whether the newly stored PHI files contain specific keywords. Any number of HSPs such as data users provides healthcare services for the patient by searching, querying, and/or retrieving user's encrypted PHIs incrementally stored on the cloud network in a privacy and verifiable manner. The patient delegated verifiability is derived from a combination of a Bloom filter and aggregate message authentication code.

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Patent
   url: https://ppubs.uspto.gov/pubwebapp/
---