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
│   ├── page3/                                   # About Us page
│   │   ├── v1-baseline.md                       # About Us - Baseline (Score 6.5)
│   │   └── v2-enhanced.md                       # About Us - Enhanced (Score 7.5)
│   │
│   └── page4/                                   # Vision & Mission page
│       ├── v1-baseline.md                       # Vision & Mission - Baseline (Score 6.0)
│       └── v2-enhanced.md                       # Vision & Mission - Enhanced (Score 8.2)
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

### Page 3 - About Us (company-profile/page3/)

Two versions available for Company Profile Page 3:

| Version | File | Score | Description |
|---------|------|:-----:|-------------|
| V1 Baseline | `v1-baseline.md` | 6.5/10 | Professional baseline with CIPTA values |
| V2 Enhanced | `v2-enhanced.md` | 7.5/10 | + Bold hook + Market data ($2.7B) |

**Key Differences:**
- V2 adds bold contrarian opening hook
- V2 includes validated market size ($2.7B from Statista)
- Both use same professional company description
- Both align with CIPTA core values

---

### Page 4 - Vision & Mission (company-profile/page4/)

Two versions available for Company Profile Page 4:

| Version | File | Score | Description |
|---------|------|:-----:|-------------|
| V1 Baseline | `v1-baseline.md` | 6.0/10 | Current version analysis |
| V2 Enhanced | `v2-enhanced.md` | 8.2/10 | Improved Vision (9 words) + Enhanced Mission |

**Key Issues (V1):**
- Vision too long (32 words vs max 20)
- "And also" grammatically awkward
- Multiple concepts in one sentence
- Missing beneficiary focus in Mission

**Key Improvements (V2):**
- Vision shortened to 9 words: "Empowering Indonesian industries to thrive in the connected era."
- Mission includes explicit beneficiaries
- CIPTA values linked in Mission point 5
- Specific sectors mentioned (Industrial, Energy, Logistics, Maritime)

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
- Page 3 must align with CIPTA core values
- Market data validated: $2.7B from Statista (Industrial IoT Indonesia 2025)
- No Trust Signals or Testimonials in current versions
- Description should be professional, not dramatic

### Company Profile - Page 4 (Vision & Mission)
- Vision statement should be max 20 words (best practice: 5-14 words)
- Mission should answer: What you do + Who benefits + How
- Value taglines (Integrity, Precision, Adaptation) remain unchanged
- Enhanced vision: "Empowering Indonesian industries to thrive in the connected era."
- Focus sectors: Industrial, Energy, Logistics, Maritime

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
