# Snort Ruleset Guide

Snort uses rule-based logic to detect threats.

- Rule format: `alert tcp any any -> any 80 (msg:"Example"; sid:1000001;)`
- Customize rules in `/etc/snort/rules/local.rules`
