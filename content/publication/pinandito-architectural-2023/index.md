---
title: Architectural Design of Representational State Transfer Application Programming
  Interface with Application-Level Base64-Encoding and Zlib Data Compression
authors:
- Aryo Pinandito
- Agi Putra Kharisma
- Eriq Muhammad Adams Jonemaro
date: '2023-01-01'
publishDate: '2023-12-28T23:57:25.430523Z'
publication_types:
- article-journal
abstract: Representational State Transfer (REST) is an architectural style that underlies
  the protocol of HyperText Transfer Protocol (HTTP) and is used by web applications.
  The implementation of REST principles in web services is often known as RESTful
  API. The standard communication used in RESTful APIs uses HTTP without involving
  data compression. There are quite a lot of RESTful API clients in the form of mobile
  applications that use metered networks. Thus, reducing the required bandwidth during
  transmission is suggested to be beneficial. The data compression technique is widely
  known to reduce data size, but this additional step may yield side effects such
  as increased memory usage and processing time. This study aims to investigate how
  the data compression process, which specifically uses Zlib and Base64 encoding,
  may put additional load on the whole process of delivering content to a RESTful
  API. The performance and characteristics in terms of bandwidth saved when distributing
  JSON data from a RESTful API in compressed format are also be investigated. According
  to the experiment result, it is suggested that the compression process can reduce
  network bandwidth by up to 66% with negligible additional memory usage for the compression
  and decompression processes.
---
