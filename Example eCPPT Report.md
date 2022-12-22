---
title: "eCPPT Report Sample"
author: ["First and Last Name", "Email Address Here"]
date: "2020-07-25"
subject: "Markdown"
keywords: [Markdown, Example]
subtitle: "eCPPT Exam Report"
lang: "en"
titlepage: true
titlepage-color: "1E90FF"
titlepage-text-color: "FFFAFA"
titlepage-rule-color: "FFFAFA"
titlepage-rule-height: 2
book: true
classoption: oneside
code-block-font-size: \scriptsize
---

\pagebreak

# Title of the Report

**EVERYTHING IN THIS REPORT IS MY RECOMMENDATION. MODIFY TO YOUR LIKING!**

## Introduction

This section wants you to introduce information about the penetration test and what you will be doing to the network.

## Objective

A quick 2-3 sentences about the objective about the penetration test. What is the goal of this penetration test.

# Executive Summary

The executive summary should be brief and straight to the point. This is given to people who are not so technical, so do not give too much technical information. Just list the IP address range and what significant vulnerabilities you found.

## Scoping and Time Limitations

Tell the reader your scope. What was the final agreement before the penetration test started.

## Recommendations

Give overall recommendations about the vulnerabilities you found. Do not go into too much detail, remember this is still the Executive Summary. Brief and easy to understand recommendation. 2-3 sentences should be enough.

\pagebreak

# Findings

Describe in 2-3 sentences what the reader will see in this section. Below is an example of a "finding".

## 127.0.0.1 (Host Machine Name)

|Open Ports|Service|Version|
| :---: | :---: | :---: |
|22|SSH|OpenSSH v6.0|
|80|HTTP|Nginx/1.14.0 |

### TF-01: Name of Vulnerability

|     |     |
| --- | ---------- |
| Description | Brief description of what you found, and what an attacker could do. | 
| CVSS v3.1 Vector | Get CVSS v3.1 vector from https://cvss.js.org/#CVSS:3.1 |
| Overall Risk | Put down the overall risk from the Severity Score Vector from the website mentioned above. |
| Gain Access | Yes/No |
| Level of Privilege | Did you obtain User, System, or N/A |
| References | References of the attack and remediation techniques. |

#### Evidence

Screenshot of the issue (most likely shows the end result of the attack).

#### Reproduce Steps

Reproduce steps of the attack from start to finish. Be sure to supply descriptive information about what is going on with a screenshot attacked to each step.

Example:

1. First, we ran `command` on the victim machine.

\<screenshot of the command being run>

2. Then we exploited the machine by using an exploit from somewhere. Put where you got the exploit in the References section.

\<screenshot of exploit being run>

#### Remediation 

Do not be definite when remediating. Be sure to recommend some fixes or patches needed.

\pagebreak

# Appendices

## Appendix A: Buffer Overflow Script

Provide your BoF script here. Be sure to link this section to your Buffer Overflow finding so the reader can easily click on see the script. (Put the script in the code block below).

```python
```

\pagebreak

# Table of  Vulnerabilities Exploited

One of the requirements is to have a table at the bottom of your report. Fill out the table as you do the exam so you do not miss anything important.
| Host (IP) | Open Ports | Services | Obtained Access? | Vulnerabilities Exploited |
|:---------:|:----------:|:--------:|:----------------:|:-------------------------:|
|           |            |          |                  |                           |