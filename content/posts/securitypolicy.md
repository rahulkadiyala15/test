---
title: "Security Policy"
date: 2023-03-02T15:54:31+10:00
draft: true
---

Emergent Coding Security Policy

# Overview

This document explains the Emergent Coding Security team's process for handling issues reported and what to expect in return.

## Reporting a Security Bug

All security bugs in the EC distribution should be reported by email to [security@codevalley.org](). This mail is delivered to the EC Security team.

## Tracks

Depending on the nature of your issue, it will be categorized by the EC security team as an issue in the PUBLIC, PRIVATE, or URGENT track. All security issues will be issued CVE numbers.

## URGENT

URGENT track issues are a threat to the EC ecosystem's integrity, or are being actively exploited in the wild leading to severe damage. There are no recent examples, but they would include remote code execution in net/http, or practical key recovery in crypto/tls.

URGENT track issues are fixed in private, and **trigger an immediate dedicated security release**, possibly with no pre-announcement.

## Comments on This Policy

If you have any suggestions to improve this policy, please [file an issue]() for discussion.