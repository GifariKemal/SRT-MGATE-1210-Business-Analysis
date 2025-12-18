# Claude AI Context - SRT-MGATE-1210 Business Analysis

## Project Overview

This repository contains business analysis documentation for the **SRT-MGATE-1210** Industrial IoT Gateway series by **PT Surya Inovasi Prioritas (SURIOTA)**.

## Product Information

### SRT-MGATE-1210 Standard Version

- **Price**: Rp 2,700,000 (~$169 USD)
- **COGS**: Rp 1,630,000 (Fully Loaded Cost)
- **Gross Margin**: 40%
- **Features**: Dual RS-485 with ESD protection, WiFi WPA3, BLE 5.0, Ethernet 10/100, RTC with battery backup, 9 LED indicators

### SRT-MGATE-1210-POE Version

- **Price**: Rp 3,100,000 (~$194 USD)
- **COGS**: Rp 1,830,000 (Fully Loaded Cost)
- **Gross Margin**: 41%
- **Additional Feature**: IEEE 802.3af/at PoE support (9W, 36-57V) with auto-switch

## Key Technical Specifications

- **MCU**: ESP32-S3-WROOM-1 (Dual-core 240MHz, 8MB PSRAM)
- **RS-485**: 2 ports with ESD protection (TVS diodes), up to 32 devices/port
- **WiFi**: 2.4GHz 802.11 b/g/n, WPA3-PSK with auto-failover
- **Bluetooth**: BLE 5.0 for mobile configuration
- **Ethernet**: W5500 10/100 Mbps with magnetic isolation
- **RTC**: DS3231 with CR1220 battery backup
- **LED Indicators**: 9 LEDs (Status, Config, WiFi, NET, RS485 TX/RX, Power)
- **Protocol Input**: Modbus RTU (RS-485), Modbus TCP (WiFi/Ethernet)
- **Protocol Output**: MQTT + JSON format
- **Cloud Support**: AWS, Datacake, Grafana, ThingsBoard, SURGE, etc.
- **Power**: 12-48V DC (Standard), + PoE 36-57V (PoE version)
- **Operating Temp**: -40C to +75C (Industrial Grade)
- **Dimensions**: 110 x 90 x 58 mm
- **Warranty**: 1.5 Year
- **Certifications**: RoHS & CE, FCC (planned)

## Unique Selling Propositions (USP)

1. **BLE Mobile Configuration** - Setup via smartphone in 5 minutes (EXCLUSIVE)
2. **WiFi Auto Failover** - Automatic switch Ethernet to WiFi (EXCLUSIVE)
3. **RTC with Battery Backup** - Accurate timestamps even after power loss
4. **9 LED Status Indicators** - Complete system monitoring
5. **ESD Protection** - Industrial grade RS-485 protection
6. **PoE + DC Redundant Power** - Auto-switch dual power (PoE version)
7. **Local Indonesia Support** - Technical support in Bahasa Indonesia

## Competitor Positioning (Modbus-to-MQTT Gateway)

SURIOTA targets the **mid-range market** with premium features:

| Competitor | Model     | Price (Tokopedia) | vs SURIOTA                                   |
| ---------- | --------- | ----------------- | -------------------------------------------- |
| USR-IOT    | N720-ETH  | Rp 3,500,000      | SURIOTA **23% cheaper**, +WiFi +BLE          |
| USR-IOT    | N540 H7-4 | Rp 1,820,000      | SURIOTA +48%, justified: WiFi +BLE +RTC +ESD |
| BLIIoT     | BL100     | Rp 3,373,000      | SURIOTA **20% cheaper**, +BLE +RTC           |
| ICP DAS    | tGW-725   | Rp 3,450,000      | SURIOTA **22% cheaper**, +MQTT +WiFi +BLE    |
| Moxa       | AIG-101-T | Rp 8,956,000      | SURIOTA **70% cheaper**, +WiFi +BLE          |

**Key Insight**: SURIOTA is the ONLY Modbus-to-MQTT gateway in Indonesia with WiFi + BLE + RTC

## Financial Metrics

- **Exchange Rate**: 1 USD = Rp 16,648 (actual) / Rp 16,000 (rounded)
- **Break-even**: 82 units
- **Target Sales**: 100 units (Amortisasi basis, 2 tahun)

## Supplier/Distributor Strategy

### Distribution Model: Hybrid (Direct + Supplier + Project)

- **Direct Sales**: 40% (High-value customers, custom solutions)
- **Supplier Channel**: 40% (5 suppliers across regions)
- **Project/Tender**: 20% (Government, corporate tenders)

### Supplier Pricing (MAP Policy)

| Tier       | Min Order | Discount | Non-PoE Price    | PoE Price        |
| ---------- | --------- | -------- | ---------------- | ---------------- |
| Tier 1     | 5 unit    | 20%      | Rp 2,160,000     | Rp 2,480,000     |
| **Tier 2** | 10 unit   | **25%**  | **Rp 2,025,000** | **Rp 2,325,000** |
| Tier 3     | 25 unit   | 30%      | Rp 1,890,000     | Rp 2,170,000     |

### MAP (Minimum Advertised Price)

- **Non-PoE**: Rp 2,700,000 (sama dengan harga direct SURIOTA)
- **PoE**: Rp 3,100,000 (sama dengan harga direct SURIOTA)
- Supplier DILARANG menjual dibawah MAP

### Additional Distribution Costs

- Packaging: Rp 90,000/unit
- Shipping: Rp 40,000/unit (avg)
- Overhead: Rp 20,000/unit
- **Total**: Rp 150,000/unit

## File Structure

```
SRT-MGATE-1210-Business-Analysis/
├── README.md                                   # Repository overview
├── CLAUDE.md                                   # This context file
│
├── docs/                                       # Documentation folder
│   ├── SRT-MGATE-1210_BUSINESS_ANALYSIS.md     # Main business document (v6.1)
│   ├── FAQ_TEMPLATE.md                         # FAQ template (v1.1)
│   └── ROASTING_AND_RESPONSE.md                # Objection handling guide (v1.1)
│
├── data/                                       # Data files
│   ├── BOM_MODBUS Gateway IoT BD_HR.xlsx       # Bill of Materials
│   ├── export_project_20251211_065536.xls      # LCSC BOM export
│   └── Kalkulasi Bg Ilham.jpeg                 # Cost calculation reference
│
└── .claude/                                    # Claude Code configuration
    └── settings.local.json
```

## Documentation Files

### Main Document (docs/SRT-MGATE-1210_BUSINESS_ANALYSIS.md) - v6.1

1. Executive Summary & Pricing Recommendation
2. Product Specifications (Updated with RTC, 9 LED, ESD)
3. COGS Analysis (Updated with BOM LCSC data & R&D amortization)
4. Competitor Analysis (5 Modbus-to-MQTT competitors)
5. Feature Comparison Matrix
6. Pricing Strategy & Volume Discounts (Updated: Opsi B - Margin 40%)
7. USP Breakdown
8. Sales & Marketing Guide (16 scenarios)
9. Objection Handling
10. Brand Awareness Strategy
11. Financial Projections (Updated: 100 unit target, scenario analysis)
12. Supplier/Distributor Strategy (MAP policy & tier pricing)
13. Technical Specifications Appendix

### FAQ Template (docs/FAQ_TEMPLATE.md) - v1.1

- Standar format jawaban untuk customer
- Quick response card untuk WhatsApp/Chat
- FAQ tentang harga, garansi, fitur, supplier program

### Roasting & Response Guide (docs/ROASTING_AND_RESPONSE.md) - v1.1

- Panduan menghadapi kritik keras dari customer
- 8 kategori: Brand, Technical, Price, Support, Features, Business, Use Case, Supplier
- Quick reference card untuk one-liner responses

### Data Files (data/)

- **BOM_MODBUS Gateway IoT BD_HR.xlsx** - Bill of Materials dari LCSC
- **export_project_20251211_065536.xls** - Export BOM dengan pricing
- **Kalkulasi Bg Ilham.jpeg** - Reference gambar kalkulasi

## Notes for AI Assistant

- **2kV Isolation claim REMOVED** - Schematic shows MAX485ESA+T (non-isolated)
- **ESD Protection ADDED** - TVS diodes (SMCJ60CA-M3/9AT) on RS-485
- **RTC ADDED** - DS3231SN# with CR1220 battery backup
- **9 LED Indicators ADDED** - Status, Config, WiFi, NET, RS485 TX/RX
- SD Card/MicroSD feature has been **deferred** (not included)
- Focus on Modbus-to-MQTT gateway competitors only
- All prices shown in both USD and IDR
- Target market: Indonesia industrial sector

## Related Repositories

- `GatewaySuriotaPOC` - Main firmware source code
- `GatewaySuriotaOTA` - OTA firmware releases

## Contact

PT Surya Inovasi Prioritas (SURIOTA)

- Email: sales@suriota.com
- Website: www.suriota.com
- Phone: +62 858-3567-2476
