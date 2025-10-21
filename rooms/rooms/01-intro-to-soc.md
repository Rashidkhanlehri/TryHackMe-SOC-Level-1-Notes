# 01 - Intro to SOC
**Room URL:** https://tryhackme.com/room/intro-to-soc  
**Topic:** SOC fundamentals  
**Difficulty:** Beginner  
**Date:** 2025-10-21  
**Author:** Muhammad Rashid

---

## Objective
Understand basic SOC roles, SIEM purpose, and common log sources.

## Setup
- Use TryHackMe AttackBox or local VM.
- No target IP required (theory room).

## Walkthrough
1. **SOC overview**
   - Notes: SOC monitors alerts, performs triage, escalates incidents.
2. **SIEM basics**
   - Key points:
     - Log collection (endpoints, network, cloud)
     - Event correlation and retention
3. **Basic triage**
   - Steps:
     - Identify source IP, timestamp, event ID
     - Prioritize high-severity alerts

## Commands / Examples
```bash
# Example to view Linux auth logs
sudo tail -n 200 /var/log/auth.log
# Grep for failed logins
sudo grep "Failed password" /var/log/auth.log
```

## Notes / Takeaways
- SIEM = central log aggregator + correlation engine.
- Triage should include context: user, host, time, and related alerts.

## References
- TryHackMe Room page

