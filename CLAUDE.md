# Claude AI Context - SURIOTA Business Analysis

## Repository Overview

This repository contains business analysis documentation for **PT Surya Inovasi Prioritas (SURIOTA)**, covering:

1. **Company Profile** - About Us page recommendations and analysis
2. **Products** - Business analysis for SURIOTA hardware products
3. **Services** - (Coming soon) Analysis for SURIOTA service offerings

---

## Company Information

### About SURIOTA

PT Surya Inovasi Prioritas (SURIOTA) is a technology-based company specializing in Industrial IoT Services and System Integration, headquartered in Batam, Riau Islands, Indonesia.

**Core Values (CIPTA):**
- **C**ommitted outcomes
- **I**ntegrity in innovation
- **P**recision in execution
- **T**rust through reliability
- **A**daptive growth

**Market Context:**
- Indonesia Industrial IoT Market: **$2.7 billion** (2025, Statista)
- Focus sectors: Industrial, Energy, Logistics, Maritime

### Key Metrics
- Established: 2023
- Projects Delivered: 55+
- Team Members: 25+
- Products Developed: 6+

---

## File Structure

```
SURIOTA-Business-Analysis/
├── README.md                                    # Repository overview
├── CLAUDE.md                                    # This AI context file
│
├── company-profile/                             # Company Profile documentation
│   ├── MARKET_RESEARCH_FINDINGS.md              # Comprehensive market research
│   │
│   ├── page3/                                   # About Us page
│   │   ├── v1-baseline.md                       # Baseline (Score 6.5)
│   │   ├── v2-enhanced.md                       # Enhanced (Score 7.5)
│   │   └── v3-final.md                          # Final Bilingual EN/ID (Score 8.5)
│   │
│   ├── page4/                                   # Vision & Mission page
│   │   ├── v1-baseline.md                       # Baseline (Score 6.0)
│   │   ├── v2-enhanced.md                       # Enhanced (Score 8.2)
│   │   └── v3-final.md                          # Final Bilingual EN/ID (Score 8.5)
│   │
│   └── page5/                                   # Services page
│       └── v1-services.md                       # Final Bilingual EN/ID (Score 8.5)
│
├── products/                                    # Product business analysis
│   └── SRT-MGATE-1210/                          # Modbus Gateway product
│       ├── BUSINESS_ANALYSIS.md                 # Main business document (v6.1)
│       ├── FAQ_TEMPLATE.md                      # FAQ template (v1.1)
│       └── ROASTING_AND_RESPONSE.md             # Objection handling guide (v1.1)
│
├── data/                                        # Supporting data files
│   └── SRT-MGATE-1210/                          # Product-specific data
│       ├── BOM_MODBUS Gateway IoT BD_HR.xlsx    # Bill of Materials
│       ├── export_project_20251211_065536.xls   # LCSC BOM export
│       └── Kalkulasi Bg Ilham.jpeg              # Cost calculation reference
│
└── .claude/                                     # Claude Code configuration
    └── settings.local.json
```

---

## Company Profile Documentation

### Market Research (company-profile/MARKET_RESEARCH_FINDINGS.md)

Comprehensive research covering:
- Indonesia IIoT Market: $2.7B (2025), 15% CAGR
- Digital Economy: $130B by 2025
- Startup Ecosystem Challenges (eFishery/TaniHub scandals, 95% funding collapse)
- Batam Strategic Advantages (FTZ, Singapore proximity)
- Southeast Asia Expansion Opportunities (26% CAGR Asia Pacific)
- Industrial IoT Services Demand & Use Cases

---

### Page 3 - About Us (company-profile/page3/)

| Version | File | Score | Description |
|---------|------|:-----:|-------------|
| V1 Baseline | `v1-baseline.md` | 6.5/10 | Professional baseline with CIPTA values |
| V2 Enhanced | `v2-enhanced.md` | 7.5/10 | + Bold hook + Market data |
| **V3 Final** | `v3-final.md` | **8.5/10** | **Bilingual EN/ID, Innovation-focused, No geo limit** |

**V3 Key Changes:**
- Innovation-driven narrative (not market-driven)
- Emphasizes independence and self-funding
- No geographic limitations for expansion potential
- Governance as differentiator from scandal-prone startups
- Bilingual for team understanding

---

### Page 4 - Vision & Mission (company-profile/page4/)

| Version | File | Score | Description |
|---------|------|:-----:|-------------|
| V1 Baseline | `v1-baseline.md` | 6.0/10 | Current version analysis (32 words) |
| V2 Enhanced | `v2-enhanced.md` | 8.2/10 | 9-word vision (Indonesia-focused) |
| **V3 Final** | `v3-final.md` | **8.5/10** | **Bilingual EN/ID, Global 6-word vision** |

**V3 Vision (Recommended):**
> "Transforming industries through smart, connected solutions."

**V3 Key Changes:**
- Vision: 6 words, global scope, no geographic limitation
- Mission: 5 action verbs (DELIVER, ENABLE, BUILD, DEVELOP, UPHOLD)
- Integrity emphasized (differentiator from scandal-prone startups)
- Bilingual for team understanding

---

### Page 5 - Services (company-profile/page5/)

| Version | File | Score | Description |
|---------|------|:-----:|-------------|
| **V1 Final** | `v1-services.md` | **8.5/10** | **Bilingual EN/ID, 6 service categories** |

**Services Offered:**
1. System Integration - PLC/SCADA to Cloud, Modbus to MQTT
2. Predictive Maintenance - Vibration/temperature monitoring, alerting
3. Remote Monitoring & Control - Cloud dashboards, mobile apps
4. Asset Tracking & Management - GPS, utilization analytics
5. Energy Management - Power monitoring, carbon footprint
6. Consulting & Implementation - Assessment, POC, training

**Industries Served:** Manufacturing, Energy, Logistics, Maritime, Oil & Gas, Building Management

---

## Product: SRT-MGATE-1210 (products/SRT-MGATE-1210/)

### Product Overview

Industrial Modbus-to-MQTT Gateway with advanced connectivity features.

### Pricing

| Version | Price | COGS | Gross Margin |
|---------|-------|------|:------------:|
| Standard | Rp 2,700,000 (~$169) | Rp 1,630,000 | 40% |
| PoE | Rp 3,100,000 (~$194) | Rp 1,830,000 | 41% |

### Key Technical Specifications

- **MCU**: ESP32-S3-WROOM-1 (Dual-core 240MHz, 8MB PSRAM)
- **RS-485**: 2 ports with ESD protection (TVS diodes)
- **WiFi**: 2.4GHz 802.11 b/g/n, WPA3-PSK with auto-failover
- **Bluetooth**: BLE 5.0 for mobile configuration
- **Ethernet**: W5500 10/100 Mbps with magnetic isolation
- **RTC**: DS3231 with CR1220 battery backup
- **LED Indicators**: 9 LEDs (Status, Config, WiFi, NET, RS485 TX/RX, Power)
- **Protocol**: Modbus RTU/TCP to MQTT + JSON
- **Cloud Support**: AWS, Datacake, Grafana, ThingsBoard, SURGE
- **Power**: 12-48V DC (Standard), + PoE 36-57V (PoE version)
- **Operating Temp**: -40C to +75C (Industrial Grade)
- **Certifications**: RoHS & CE

### Unique Selling Propositions (USP)

1. **BLE Mobile Configuration** - Setup via smartphone in 5 minutes (EXCLUSIVE)
2. **WiFi Auto Failover** - Automatic switch Ethernet to WiFi (EXCLUSIVE)
3. **RTC with Battery Backup** - Accurate timestamps even after power loss
4. **9 LED Status Indicators** - Complete system monitoring
5. **ESD Protection** - Industrial grade RS-485 protection
6. **PoE + DC Redundant Power** - Auto-switch dual power (PoE version)
7. **Local Indonesia Support** - Technical support in Bahasa Indonesia

### Competitor Positioning

SURIOTA targets the **mid-range market** with premium features:

| Competitor | Model | Price | vs SURIOTA |
|------------|-------|-------|------------|
| USR-IOT | N720-ETH | Rp 3,500,000 | SURIOTA **23% cheaper**, +WiFi +BLE |
| BLIIoT | BL100 | Rp 3,373,000 | SURIOTA **20% cheaper**, +BLE +RTC |
| ICP DAS | tGW-725 | Rp 3,450,000 | SURIOTA **22% cheaper**, +MQTT +WiFi +BLE |
| Moxa | AIG-101-T | Rp 8,956,000 | SURIOTA **70% cheaper**, +WiFi +BLE |

**Key Insight**: SURIOTA is the ONLY Modbus-to-MQTT gateway in Indonesia with WiFi + BLE + RTC

### Documentation Files

| File | Description |
|------|-------------|
| `BUSINESS_ANALYSIS.md` | Complete business analysis (pricing, COGS, strategy) |
| `FAQ_TEMPLATE.md` | Standard FAQ responses for customers |
| `ROASTING_AND_RESPONSE.md` | Objection handling guide |

---

## Notes for AI Assistant

### Company Profile - Page 3 (About Us)
- V3 Final is the recommended version (bilingual EN/ID)
- Innovation-focused narrative, NOT market-driven
- Emphasizes independence and self-funding as differentiators
- No geographic limitations - allows for regional expansion
- CIPTA core values maintained

### Company Profile - Page 4 (Vision & Mission)
- V3 Final is the recommended version (bilingual EN/ID)
- Vision: "Transforming industries through smart, connected solutions." (6 words, global)
- NO "Indonesia" in vision - company is independent, self-funded, aspires to regional presence
- Mission uses 5 strong action verbs: DELIVER, ENABLE, BUILD, DEVELOP, UPHOLD
- Integrity emphasized as differentiator from scandal-prone Indonesian startups
- Value taglines remain: Integrity, Precision, Adaptation

### Company Profile - Page 5 (Services)
- V1 Final is the recommended version (bilingual EN/ID)
- 6 service categories aligned with market research findings
- Services match IIoT industry demand (predictive maintenance 50%+, etc.)
- Industries: Manufacturing, Energy, Logistics, Maritime, Oil & Gas, Building Management
- Protocol alignment: MQTT (55% industry usage), Modbus (core competency)

### Product (SRT-MGATE-1210)
- **2kV Isolation claim REMOVED** - Schematic shows MAX485ESA+T (non-isolated)
- **ESD Protection ADDED** - TVS diodes (SMCJ60CA-M3/9AT) on RS-485
- **RTC ADDED** - DS3231SN# with CR1220 battery backup
- SD Card/MicroSD feature has been **deferred**
- Focus on Modbus-to-MQTT gateway competitors only
- All prices in both USD and IDR

---

## Related Repositories

- `GatewaySuriotaPOC` - Main firmware source code
- `GatewaySuriotaOTA` - OTA firmware releases

---

## Contact

**PT Surya Inovasi Prioritas (SURIOTA)**

- Email: sales@suriota.com
- Website: www.suriota.com
- Phone: +62 858-3567-2476
