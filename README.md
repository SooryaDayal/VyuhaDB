# VyuhaDB: An open-source repository for structured Indic-language scam signatures to empower AI-driven fraud detection in India. #AIforAll #AIKosh #TeamAbhaya

**Team:** Abhaya  
**Theme:** AI for Social Impact / Data Readiness  
**Focus:** Protecting Senior Citizens and MSMEs from Cyber-Fraud

--- 

## Project Overview
**VyuhaDB** is an automated open-source pipeline and repository designed to bridge the "AI-Readiness Gap" in Indian cybersecurity. We transform unstructured fraud alerts and news reports into a structured "Signature Library" of scam scripts in regional languages (Malayalam, Hindi, and English).

Inspired by the strategic defensive formations of ancient India, **VyuhaDB** organizes chaotic data into a machine-readable defense shield for the national AI ecosystem.

## The Problem
India loses thousands of crores annually to localized "Social Engineering" scams. Global AI safety tools fail because they lack high-quality, structured datasets of **Indic-language scam scripts** (Manglish/Hinglish).

## The Solution
VyuhaDB extracts the "Linguistic DNA" of scams.
1. **Automated Ingestion:** Scrapes raw data from official portals (NCRP, Sanchar Saathi).
2. **Indic Parser:** Uses Bhashini APIs to standardize regional scam scripts.
3. **Signature Registry:** Provides a JSON/CSV library of scam patterns for developers to build "Safe-Dialers" and fraud-blockers.

## Data Schema (Vyuha-Signature)
The repository provides signatures in a standardized format:

```json
{
  "scam_type": "Digital Arrest",
  "language": "Malayalam-English",
  "psychological_trigger": "Fear/Authority",
  "script_snippet": "CBI office ninnu vilikkunnu... Aadhaar illegal activity undu...",
  "risk_level": "High"
}
