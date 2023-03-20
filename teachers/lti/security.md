---
title: ANVILL Security & Privacy
description: An overview of LTI security and privacy policies.
published: true
date: 2020-10-16T16:37:02.551Z
tags: 
editor: markdown
---

# Overview

Whether the data stored in ANVILL is explicitly personally identifiable information (PII), such as email addresses, or less explicit such as video recordings, we treat all data with care and assume it that it is PII data.

ANVILL explicitly stores the following information, which is required to create an account, whether that account is created via social logins, LTI, or in ANVILL itself:

- First name
- Last name
- Email

ANVILL also stores media files, which are associated with a specific user account. This can include documents, audio, video, and images.

All of this data is protected from external access, and explicit access must be granted to the lesson that groups this content in order to view the data.

# Privacy Policy

We are FERPA compliant and have undergone a security review by the University of Oregon. We adhere to the University of Oregon privacy policy, which can be found here:

https://registrar.uoregon.edu/privacy

We do not share any user data with outside entities. We do not make any money on advertisement, data mining, etc. ANVILL is supported solely through funding from the University of Oregon.

# Security

All explicit user data (name, emails) are stored on University of Oregon servers, which is monitored by the ANVILL team as well as the security team in Information Services at UO.

All other data (media files, etc) are stored on Amazon Web Services S3 service. All these files are stored privately with AES 256 encryption. Access to these files is only given to logged in users that have explicit access to view the lesson the file is associated with.

# Infrastructure

The main ANVILL application uses Drupal 8 to handle data access. For a summary of the software and security practices we use please download the linked pdf:

<a href="/anvill_summary.pdf" target="_blank">ANVILL Security Summary</a>
