# SRT-MGATE-1210 Business Analysis

**Competitive Analysis, Pricing Strategy, and Sales Guide for SRT-MGATE-1210 Industrial IoT Gateway**

---

## Overview

This repository contains comprehensive business analysis documentation for the **SRT-MGATE-1210** series Industrial IoT Gateway, developed by **PT Surya Inovasi Prioritas (SURIOTA)**.

### Product Variants

| Model                  | Description                                | MSRP (IDR)   | MSRP (USD) | Margin |
| ---------------------- | ------------------------------------------ | ------------ | ---------- | ------ |
| **SRT-MGATE-1210**     | Standard Version - 2xRS485, ETH, WiFi, BLE | Rp 2,700,000 | ~$169      | 40%    |
| **SRT-MGATE-1210-POE** | PoE Version - 2xRS485, ETH+PoE, WiFi, BLE  | Rp 3,100,000 | ~$194      | 41%    |

---

## Key Features

| Feature              | Description                         |
| -------------------- | ----------------------------------- |
| **Dual RS-485**      | 2 ports with ESD protection         |
| **WiFi**             | 2.4GHz with auto-failover           |
| **BLE 5.0**          | Mobile configuration via smartphone |
| **RTC**              | DS3231 with battery backup          |
| **LED Indicators**   | 9 LEDs for complete monitoring      |
| **MQTT Output**      | JSON format to any cloud platform   |
| **Industrial Grade** | -40C to +75C operating temp         |

---

## Unique Selling Proposition (USP)

**SURIOTA is the ONLY Modbus-to-MQTT gateway in Indonesia with:**

- WiFi Built-in with Auto Failover
- BLE Mobile Configuration (setup in 5 minutes)
- RTC with Battery Backup
- 9 LED Status Indicators
- Local Indonesia Support

---

## Competitor Comparison

| Brand   | Model     | Price (Tokopedia) | vs SURIOTA              |
| ------- | --------- | ----------------- | ----------------------- |
| USR-IOT | N720-ETH  | Rp 3,500,000      | SURIOTA **23% cheaper** |
| BLIIoT  | BL100     | Rp 3,373,000      | SURIOTA **20% cheaper** |
| ICP DAS | tGW-725   | Rp 3,450,000      | SURIOTA **22% cheaper** |
| Moxa    | AIG-101-T | Rp 8,956,000      | SURIOTA **70% cheaper** |

---

## Repository Structure

```
SRT-MGATE-1210-Business-Analysis/
├── README.md                           # This file - repository overview
├── CLAUDE.md                           # AI assistant context file
│
├── docs/                               # Documentation
│   ├── SRT-MGATE-1210_BUSINESS_ANALYSIS.md   # Main business document (v6.1)
│   ├── FAQ_TEMPLATE.md                       # FAQ template (v1.1)
│   └── ROASTING_AND_RESPONSE.md              # Objection handling guide (v1.1)
│
├── data/                               # Data files
│   ├── BOM_MODBUS Gateway IoT BD_HR.xlsx     # Bill of Materials
│   ├── export_project_20251211_065536.xls    # LCSC BOM export
│   └── Kalkulasi Bg Ilham.jpeg               # Cost calculation reference
│
└── .claude/                            # Claude Code configuration
    └── settings.local.json
```

---

## Documentation Contents

The main analysis document (`docs/SRT-MGATE-1210_BUSINESS_ANALYSIS.md`) includes:

1. **Executive Summary** - Pricing recommendation & key metrics
2. **Product Specifications** - Complete technical specs
3. **COGS Analysis** - Actual production cost breakdown with BOM data
4. **Competitor Analysis** - 5 Modbus-to-MQTT gateway competitors
5. **Feature Comparison Matrix** - Side-by-side comparison
6. **Pricing Strategy** - Volume discounts & 3 pricing options analysis
7. **USP Breakdown** - Unique selling points explained
8. **Sales Guide** - 16 customer scenario scripts
9. **Objection Handling** - Common objections & responses
10. **Brand Awareness Strategy** - Marketing roadmap
11. **Financial Projections** - Revenue & profit analysis (100 unit target)
12. **Supplier/Distributor Strategy** - MAP policy & tier pricing
13. **Technical Appendix** - Specifications & glossary

### Additional Documents

| Document                        | Description                                       |
| ------------------------------- | ------------------------------------------------- |
| `docs/FAQ_TEMPLATE.md`          | Template FAQ dengan format standar untuk customer |
| `docs/ROASTING_AND_RESPONSE.md` | Panduan handle kritik keras dari pelanggan        |

---

## Supplier Program

SURIOTA offers supplier/distributor partnership with MAP (Minimum Advertised Price) policy:

| Tier       | Min Order | Discount | Non-PoE Price    | PoE Price        |
| ---------- | --------- | -------- | ---------------- | ---------------- |
| Tier 1     | 5 unit    | 20%      | Rp 2,160,000     | Rp 2,480,000     |
| **Tier 2** | 10 unit   | **25%**  | **Rp 2,025,000** | **Rp 2,325,000** |
| Tier 3     | 25 unit   | 30%      | Rp 1,890,000     | Rp 2,170,000     |

Contact sales@suriota.com for supplier registration.

---

## Exchange Rate

All calculations use: **1 USD = Rp 16,648** (actual) / **Rp 16,000** (rounded)

---

## Contact

**PT Surya Inovasi Prioritas (SURIOTA)**

|         |                   |
| ------- | ----------------- |
| Website | www.suriota.com   |
| Email   | sales@suriota.com |
| Phone   | +62 858-3567-2476 |

---

## Related Repositories

- [GatewaySuriotaPOC](https://github.com/GifariKemal/GatewaySuriotaPOC) - Main firmware source code
- [GatewaySuriotaOTA](https://github.com/GifariKemal/GatewaySuriotaOTA) - OTA firmware releases

---

## License

This documentation is proprietary to PT Surya Inovasi Prioritas. All rights reserved.

---

_Document Version: 6.1 | Last Updated: December 18, 2025_
