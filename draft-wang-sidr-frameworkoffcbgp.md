---
title: "draft-wang-sidr-frameworkoffcbgp"
abbrev: "fcbgp"
category: std

docname: draft-wang-sidr-frameworkoffcbgp-latest
submissiontype: IETF  # also: "independent", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "Routing"
workgroup: "Secure Inter-Domain Routing"
keyword:
 - BGP Security
 - Inter-Domain Forwarding
venue:
  group: "Secure Inter-Domain Routing"
  type: "Working Group"
  mail: "sidr@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/sidr/"
  github: "LucasWang86/framework-of-fcbgp"
  latest: "https://LucasWang86.github.io/framework-of-fcbgp/draft-wang-sidr-frameworkoffcbgp.html"

author:
  -
      fullname: Ke Xu
      org: Tsinghua University
      city: Beijing
      country: China
      email: xuke@tsinghua.edu.cn
  -
      fullname: Xiaoliang Wang
      org: Tsinghua University
      city: Beijing
      country: China
      email: wangxiaoliang0623@foxmail.com
  -
      fullname: Zhuotao liu
      org: Tsinghua University
      city: Beijing
      country: China
      email: zhuotaoliu@tsinghua.edu.cn
  -
      fullname: Li Qi
      org: Tsinghua University
      city: Beijing
      country: China
      email: qli01@tsinghua.edu.cn
  -
      fullname: Jianping Wu
      org: Tsinghua University
      city: Beijing
      country: China
      email: jianping@cernet.edu.cn

normative:

informative:
    X.680:
      title: "Information technology -- Abstract Syntax Notation One (ASN.1): Specification of basic notation"
      target: "https://itu.int/rec/T-REC-X.680-202102-I/en"
      date: Feb. 2021
      author:
        - ins: ITU-T
      seriesinfo: "Recommendation ITU-T X.680"
    X.690:
      title: "Information technology - ASN.1 encoding rules: Specification of Basic Encoding Rules (BER), Canonical Encoding Rules (CER) and Distinguished Encoding Rules (DER)"
      target: "[https://itu.int/rec/T-REC-X.680-202102-I/en](https://www.itu.int/rec/T-REC-X.690-202102-I/en)"
      date: Feb. 2021
      author:
        - ins: ITU-T
      seriesinfo: "Recommendation ITU-T X.690"

--- abstract

This document defines a standard profile for the framework of Forwarding Commitment BGP (FC-BGP). A FC is a digitally signed object that provides a means of verifying that an IP address prefix is announced from `AS a` to `AS b`. When validated, a FC's eContent can be used for detection and mitigation of route hijacking and provide protection for the AS_PATH attribute in BGP-UPDATE.

--- middle

# Introduction

TODO Introduction


# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
