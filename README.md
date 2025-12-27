# SURIOTA Business Analysis

**Business Analysis Repository for PT Surya Inovasi Prioritas (SURIOTA)**

---

## Overview

This repository contains comprehensive business analysis documentation for **SURIOTA**, covering:

- **Company Profile** - About Us page recommendations and scoring
- **Products** - Business analysis for SURIOTA hardware products
- **Services** - (Coming soon) Analysis for service offerings

---

## Company Information

**PT Surya Inovasi Prioritas (SURIOTA)** is a technology-based company specializing in Industrial IoT Services and System Integration, headquartered in Batam, Riau Islands, Indonesia.

### Core Values (CIPTA)

| Value | Description |
|-------|-------------|
| **C**ommitted | Committed outcomes |
| **I**ntegrity | Integrity in innovation |
| **P**recision | Precision in execution |
| **T**rust | Trust through reliability |
| **A**daptive | Adaptive growth |

### Key Metrics

| Metric | Value |
|--------|-------|
| Established | 2023 |
| Projects Delivered | 55+ |
| Team Members | 25+ |
| Products Developed | 6+ |
| Market Size (Indonesia IIoT) | $2.7 billion (2025) |

---

## Repository Structure

```
SURIOTA-Business-Analysis/
├── README.md                                    # This file
├── CLAUDE.md                                    # AI context file
│
├── company-profile/                             # Company Profile documentation
│   ├── MARKET_RESEARCH_FINDINGS.md              # Market research data
│   │
│   ├── page3/                                   # About Us page
│   │   ├── v1-baseline.md                       # Baseline (Score 6.5)
│   │   ├── v2-enhanced.md                       # Enhanced (Score 7.5)
│   │   └── v3-final.md                          # Final Bilingual (Score 8.5)
│   │
│   ├── page4/                                   # Vision & Mission page
│   │   ├── v1-baseline.md                       # Baseline (Score 6.0)
│   │   ├── v2-enhanced.md                       # Enhanced (Score 8.2)
│   │   └── v3-final.md                          # Final Bilingual (Score 8.5)
│   │
│   └── page5/                                   # Services page
│       └── v1-services.md                       # Final Bilingual (Score 8.5)
│
├── products/                                    # Product business analysis
│   └── SRT-MGATE-1210/                          # Modbus Gateway
│       ├── BUSINESS_ANALYSIS.md                 # Main business document
│       ├── FAQ_TEMPLATE.md                      # FAQ template
│       └── ROASTING_AND_RESPONSE.md             # Objection handling
│
├── data/                                        # Supporting data files
│   └── SRT-MGATE-1210/                          # Product data
│       ├── BOM_MODBUS Gateway IoT BD_HR.xlsx
│       ├── export_project_20251211_065536.xls
│       └── Kalkulasi Bg Ilham.jpeg
│
└── .claude/                                     # Claude Code config
    └── settings.local.json
```

---

## Company Profile

### Market Research

Comprehensive market research compiled in `MARKET_RESEARCH_FINDINGS.md` covering:
- Indonesia IIoT Market ($2.7B, 15% CAGR)
- Digital Economy Overview ($130B by 2025)
- Startup Ecosystem Challenges (funding collapse, governance issues)
- Batam Strategic Advantages (FTZ, Singapore proximity)
- Southeast Asia Expansion Opportunities (26% CAGR Asia Pacific)

### Page 3 - About Us

| Version | File | Score | Key Features |
|---------|------|:-----:|--------------|
| V1 Baseline | `page3/v1-baseline.md` | 6.5/10 | CIPTA values, basic metrics |
| V2 Enhanced | `page3/v2-enhanced.md` | 7.5/10 | + Bold hook + Market data |
| **V3 Final** | `page3/v3-final.md` | **8.5/10** | **Bilingual EN/ID, Innovation-focused** |

### Page 4 - Vision & Mission

| Version | File | Score | Key Features |
|---------|------|:-----:|--------------|
| V1 Baseline | `page4/v1-baseline.md` | 6.0/10 | Current analysis (32 words) |
| V2 Enhanced | `page4/v2-enhanced.md` | 8.2/10 | 9-word vision (Indonesia-focused) |
| **V3 Final** | `page4/v3-final.md` | **8.5/10** | **Bilingual EN/ID, Global vision** |

**Recommended Vision (V3):**
> "Transforming industries through smart, connected solutions."

### Page 5 - Services

| Version | File | Score | Key Features |
|---------|------|:-----:|--------------|
| **V1 Final** | `page5/v1-services.md` | **8.5/10** | **Bilingual EN/ID, 6 service categories** |

**Services:** System Integration, Predictive Maintenance, Remote Monitoring, Asset Tracking, Energy Management, Consulting

---

## Products

### SRT-MGATE-1210 - Industrial Modbus Gateway

| Model | Description | Price (IDR) | Price (USD) | Margin |
|-------|-------------|-------------|-------------|:------:|
| SRT-MGATE-1210 | Standard - 2xRS485, ETH, WiFi, BLE | Rp 2,700,000 | ~$169 | 40% |
| SRT-MGATE-1210-POE | PoE - 2xRS485, ETH+PoE, WiFi, BLE | Rp 3,100,000 | ~$194 | 41% |

#### Key Features

- **Dual RS-485** with ESD protection
- **WiFi** 2.4GHz with auto-failover
- **BLE 5.0** mobile configuration
- **RTC** DS3231 with battery backup
- **9 LED Indicators** for monitoring
- **MQTT Output** JSON to any cloud
- **Industrial Grade** -40C to +75C

#### Unique Selling Proposition

**SURIOTA is the ONLY Modbus-to-MQTT gateway in Indonesia with:**
- WiFi Built-in with Auto Failover
- BLE Mobile Configuration (5 minutes setup)
- RTC with Battery Backup
- 9 LED Status Indicators
- Local Indonesia Support

#### Competitor Comparison

| Brand | Model | Price | vs SURIOTA |
|-------|-------|-------|------------|
| USR-IOT | N720-ETH | Rp 3,500,000 | SURIOTA **23% cheaper** |
| BLIIoT | BL100 | Rp 3,373,000 | SURIOTA **20% cheaper** |
| ICP DAS | tGW-725 | Rp 3,450,000 | SURIOTA **22% cheaper** |
| Moxa | AIG-101-T | Rp 8,956,000 | SURIOTA **70% cheaper** |

---

## Supplier Program

SURIOTA offers supplier/distributor partnership with MAP policy:

| Tier | Min Order | Discount | Non-PoE Price | PoE Price |
|------|-----------|----------|---------------|-----------|
| Tier 1 | 5 unit | 20% | Rp 2,160,000 | Rp 2,480,000 |
| **Tier 2** | 10 unit | **25%** | **Rp 2,025,000** | **Rp 2,325,000** |
| Tier 3 | 25 unit | 30% | Rp 1,890,000 | Rp 2,170,000 |

Contact sales@suriota.com for supplier registration.

---

## Contact

**PT Surya Inovasi Prioritas (SURIOTA)**

| | |
|---------|-------------------|
| Website | www.suriota.com |
| Email | sales@suriota.com |
| Phone | +62 858-3567-2476 |

---

## Related Repositories

- [GatewaySuriotaPOC](https://github.com/GifariKemal/GatewaySuriotaPOC) - Firmware source code
- [GatewaySuriotaOTA](https://github.com/GifariKemal/GatewaySuriotaOTA) - OTA releases

---

## License

This documentation is proprietary to PT Surya Inovasi Prioritas. All rights reserved.

---

_Last Updated: December 27, 2025_
