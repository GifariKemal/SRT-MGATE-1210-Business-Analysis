# Claude AI Context - SRT-MGATE-1210 Business Analysis

## Project Overview

This repository contains business analysis documentation for the **SRT-MGATE-1210** Industrial IoT Gateway series by **PT Surya Inovasi Prioritas (SURIOTA)**.

## Product Information

### SRT-MGATE-1210 Standard Version
- **Price**: Rp 5,000,000 ($312 USD)
- **COGS**: Rp 900,000 ($56.25 USD) @ 200 pcs
- **Gross Margin**: 82%
- **Features**: Dual RS-485 (2kV isolated), WiFi WPA3, BLE 5.0, Ethernet 10/100

### SRT-MGATE-1210-POE Version
- **Price**: Rp 6,000,000 ($375 USD)
- **COGS**: Rp 1,096,960 ($68.56 USD) @ 200 pcs
- **Gross Margin**: 81.7%
- **Additional Feature**: IEEE 802.3af/at PoE support (9W, 36-57V)

## Key Technical Specifications

- **MCU**: ESP32-S3-WROOM-1 (Dual-core 240MHz, 8MB PSRAM)
- **RS-485**: 2 ports, 2kV isolated, up to 32 devices/port
- **WiFi**: 2.4GHz 802.11 b/g/n, WPA3-PSK
- **Bluetooth**: BLE 5.0 for mobile configuration
- **Ethernet**: W5500 10/100 Mbps with magnetic isolation
- **Power**: 12-48V DC (Standard), + PoE 36-57V (PoE version)
- **Operating Temp**: -40°C to +75°C
- **Certifications**: FCC, CE, UL, RoHS

## Unique Selling Propositions (USP)

1. **BLE Mobile Configuration** - Setup via smartphone in 5 minutes
2. **PoE + DC Redundant Power** - Auto-switch dual power
3. **Triple Connectivity** - ETH + WiFi + BLE
4. **Auto Network Failover** - Ethernet ↔ WiFi automatic switch
5. **Local Indonesia Support** - Technical support in Bahasa Indonesia

## Competitor Positioning

SURIOTA targets the **mid-range market** with premium features:
- 30-50% cheaper than Moxa, Advantech, Red Lion
- More features than budget options (USR-IOT, Waveshare)
- Local support advantage vs imported brands

## Key Competitors

| Competitor | Model | Price Range | Notes |
|------------|-------|-------------|-------|
| Moxa | MGate MB3180/3280 | Rp 5.6-8.8M | No WiFi, No BLE |
| ICP DAS | GW-7472 | Rp 3-4M | No WiFi, No BLE |
| Red Lion | DA10D | Rp 14-15M | PoE, but 65% more expensive |
| Advantech | WISE-4012E | Rp 7-10M | WiFi, but no BLE |

## Financial Metrics (200 pcs production)

- **Total Investment**: Rp 270,760,000 (~$16,900)
- **Total Revenue**: Rp 1,080,000,000 (~$67,500)
- **Net Profit**: Rp 809,240,000 (~$50,600)
- **Break-even**: 60 units
- **ROI**: 299%
- **Payback Period**: 3-4 months

## Exchange Rate

**1 USD = Rp 16,000** (used throughout all calculations)

## File Structure

```
SRT-MGATE-1210-Business-Analysis/
├── README.md                          # Repository overview
├── CLAUDE.md                          # This context file
└── COMPETITIVE_ANALYSIS_PRICING.md    # Full analysis document
```

## Document Sections

The main analysis document contains:
1. Product Variants & Specifications
2. Competitive Landscape (15 competitors)
3. Feature Comparison Matrix
4. USP Breakdown
5. COGS Analysis (BOM + Manufacturing)
6. Pricing Strategy & Official Pricelist
7. Profit Analysis & ROI
8. Sales Talking Points

## Notes for AI Assistant

- SD Card/MicroSD feature has been **deferred** (not included in current version)
- DNV-GL Maritime certification has been **deferred** (not included)
- Focus on core features: BLE Config, PoE, WiFi Failover, Dual RS-485
- All prices shown in both USD and IDR
- Target market: Indonesia industrial sector

## Related Repositories

- `GatewaySuriotaPOC` - Main firmware source code
- `GatewaySuriotaOTA` - OTA firmware releases

## Contact

PT Surya Inovasi Prioritas (SURIOTA)
- Email: sales@suriota.com
- Website: www.suriota.com
