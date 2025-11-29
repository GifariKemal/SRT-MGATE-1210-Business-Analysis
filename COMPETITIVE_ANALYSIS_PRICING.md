# SRT-MGATE-1210 Competitive Analysis & Pricing Strategy (UPDATED)

**Document Version:** 2.1 | **Date:** November 29, 2025  
**Prepared by:** SURIOTA R&D Team

---

## Executive Summary

Dokumen ini berisi analisis kompetitif lengkap untuk **SRT-MGATE-1210 Industrial IoT Gateway** dengan informasi terbaru berdasarkan official product datasheet, termasuk fitur **PoE (Power over Ethernet)** dan **2 varian produk**.

---

## 1. Product Variants

### 1.1 Standard Version (SRT-MGATE-1210)

| Specification | Value |
|---------------|-------|
| Network Port | RJ45 Ethernet 10/100 Mbps |
| Power Supply | Screw Terminal 12~48 VDC |
| PoE Support | ❌ Tidak ada |
| Target | Indoor/controlled environments |
| **MSRP** | **Rp 4.500.000 - 5.500.000** |

### 1.2 PoE Version (SRT-MGATE-1210-POE)

| Specification | Value |
|---------------|-------|
| Network Port | RJ45 Ethernet 10/100 Mbps + **PoE** |
| Power Supply | Screw Terminal 12~48 VDC **ATAU** PoE |
| PoE Standard | **IEEE 802.3af/at** (9W PD) |
| PoE Voltage | 36 ~ 57 VDC |
| Target | Outdoor/industrial/remote area |
| **MSRP** | **Rp 5.500.000 - 6.500.000** |

---

## 2. Complete Technical Specifications

### 2.1 Hardware

| Component | Specification |
|-----------|---------------|
| **Main CPU** | ESP32-S3-WROOM-1 (Dual-core 240MHz, 512KB SRAM, 8MB PSRAM) |
| **WiFi** | 2.4 GHz, 802.11 b/g/n, **WPA3-PSK**, Station/AP/AP+Station |
| **Bluetooth** | BLE 5.0, range up to 50m (LoS) |
| **RTC** | Real-Time Clock high accuracy |

### 2.2 Interface

| Interface | Specification |
|-----------|---------------|
| **Ethernet** | 1x RJ45 10/100 Mbps dengan **Magnetic Isolation** |
| **Modbus RTU** | 2x **Isolated RS-485** (2kV), up to 32 devices/port |
| **Modbus TCP/IP** | Port 502, up to 32 TCP clients |
| **USB** | 1x Type-C (Debug/Firmware) |
| **LED Indicators** | 8x LED |
| **Button** | 1x Config Button |

### 2.3 Power Specification

| Parameter | Standard Version | PoE Version |
|-----------|------------------|-------------|
| **DC Input** | 12V-48V DC | 12V-48V DC |
| **PoE** | ❌ | IEEE 802.3af (9W, 36-57V DC) |
| **Redundancy** | ❌ | ✅ Auto-switch dual power |

### 2.4 Environmental & Certifications

| Parameter | Specification |
|-----------|---------------|
| **Operating Temp** | -40°C to +75°C |
| **Storage Temp** | -40°C to +85°C |
| **Humidity** | 10~95% RH (non-condensing) |
| **EMC** | EN 55032 |
| **EMI** | FCC Part 15 |
| **EMS** | IEC 61000-4-2/4/5 |
| **Safety** | UL 60950-1, UL/cUL 62368-1, RoHS |

---

## 3. Competitive Landscape (15 Competitors)

### 3.1 Competitor Price Comparison

| No | Brand | Model | PoE | RS485 Ports | WiFi | BLE Config | Price (USD) | Price (IDR) |
|----|-------|-------|-----|-------------|------|------------|-------------|-------------|
| 1 | **Moxa** | MGate MB3180 | ❌ | 1 | ❌ | ❌ | $350-400 | Rp 5.6-6.4M |
| 2 | **Moxa** | MGate MB3280 | ❌ | 2 | ❌ | ❌ | $500-550 | Rp 8-8.8M |
| 3 | **Moxa** | MGate 5121 | ❌ | 1 | ❌ | ❌ | $800-850 | Rp 12.8-13.6M |
| 4 | **ICP DAS** | GW-7472 | ❌ | 2 | ❌ | ❌ | $189-250 | Rp 3-4M |
| 5 | **ICP DAS** | tGW-715 | ✅ | 1 | ❌ | ❌ | $200-280 | Rp 3.2-4.5M |
| 6 | **Advantech** | ECU-1051 | ❌ | 2 | ✅ | ❌ | $1,000-1,100 | Rp 16-17.6M |
| 7 | **Advantech** | WISE-4012E | ❌ | 1 | ✅ | ❌ | $450-550 | Rp 7.2-8.8M |
| 8 | **Wago** | 750-862 | ❌ | - | ❌ | ❌ | $736-961 | Rp 11.8-15.4M |
| 9 | **Red Lion** | DA10D | ✅ | 2 | ❌ | ❌ | $873-950 | Rp 14-15.2M |
| 10 | **Red Lion** | DA30D | ✅ | 2 | ❌ | ❌ | $1,200-1,400 | Rp 19.2-22.4M |
| 11 | **Siemens** | CloudConnect 7 | ❌ | 2 | ❌ | ❌ | $1,000-1,500 | Rp 16-24M |
| 12 | **Teltonika** | TRB245 | ❌ | 1 | ❌ | ❌ | $165-200 | Rp 2.6-3.2M |
| 13 | **Robustel** | R3000-4L | ❌ | 1 | ✅ | ❌ | $450-560 | Rp 7.2-9M |
| 14 | **USR-IOT** | N510-H7 | ❌ | 1 | ❌ | ❌ | $45-59 | Rp 720K-944K |
| 15 | **Waveshare** | RS485-ETH | ❌ | 1 | ❌ | ❌ | $20-35 | Rp 320-560K |
| | | | | | | | | |
| **→** | **SURIOTA** | **SRT-MGATE-1210** | ❌ | **2** | ✅ | ✅ | **$281-344** | **Rp 4.5-5.5M** |
| **→** | **SURIOTA** | **SRT-MGATE-1210-POE** | ✅ | **2** | ✅ | ✅ | **$344-406** | **Rp 5.5-6.5M** |

### 3.2 Feature Comparison Matrix

| Feature | SURIOTA | Moxa MB3180 | ICP DAS GW-7472 | Advantech WISE | Red Lion DA10D |
|---------|---------|-------------|-----------------|----------------|----------------|
| **Price** | Rp 4.5-6.5M | Rp 5.6-6.4M | Rp 3-4M | Rp 7-10M | Rp 14-15M |
| **PoE Support** | ✅ Optional | ❌ | ❌ | ✅ | ✅ |
| **Dual RS-485** | ✅ 2 ports | ❌ 1 port | ✅ 2 ports | ❌ 1 port | ✅ 2 ports |
| **RS-485 Isolation** | ✅ 2kV | ✅ 2kV | ✅ 2kV | ✅ | ✅ 2kV |
| **WiFi** | ✅ WPA3 | ❌ | ❌ | ✅ | ❌ |
| **BLE Config** | ✅ Mobile App | ❌ Web only | ❌ Web only | ❌ Web only | ❌ Web only |
| **Auto Failover** | ✅ ETH↔WiFi | ❌ | ❌ | ✅ | ❌ |
| **Redundant Power** | ✅ DC+PoE | ❌ | ❌ | ❌ | ✅ |
| **Temp Range** | -40~75°C | -40~75°C | -25~75°C | -25~70°C | -40~70°C |
| **Local Support** | ✅ Indonesia | ❌ Singapore | ❌ Taiwan | ❌ Taiwan | ❌ USA |

---

## 4. Unique Selling Proposition (USP)

### 4.1 Primary USP Statement

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                               ║
║   "SATU-SATUNYA INDUSTRIAL IoT GATEWAY DENGAN:"                              ║
║                                                                               ║
║   ✓ BLE Mobile Configuration (Setup via Smartphone)                          ║
║   ✓ PoE + DC Redundant Power (Varian PoE)                                    ║
║   ✓ Dual RS-485 + WiFi + Ethernet (Triple Connectivity)                      ║
║   ✓ Auto Network Failover (Ethernet ↔ WiFi)                                  ║
║   ✓ Local Indonesia Support                                                  ║
║                                                                               ║
║   DI HARGA MID-RANGE (Rp 4.5-6.5 Juta)                                       ║
║                                                                               ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.2 USP Breakdown by Feature

| USP Feature | Nilai Tambah | Kompetitor Terdekat |
|-------------|--------------|---------------------|
| **PoE Support (802.3af/at)** | Instalasi tanpa power adapter terpisah | Red Lion DA10D ($873) - 2x lebih mahal |
| **BLE Mobile Config** | Setup 5 menit via HP, tanpa laptop | Tidak ada kompetitor yang punya |
| **Redundant Power** | DC + PoE auto-switch | Enterprise only ($800+) |
| **2kV RS-485 Isolation** | Industrial grade protection | Standard di premium brands |
| **WPA3 WiFi Security** | Latest security standard | Jarang di gateway murah |

### 4.3 Competitive Advantages Summary

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    COMPETITIVE ADVANTAGES                                    │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  1. PRICE COMPETITIVENESS                                                   │
│     • 30-50% lebih murah dari Moxa, Advantech, Red Lion                    │
│     • Fitur setara premium dengan harga mid-range                          │
│                                                                              │
│  2. UNIQUE FEATURES                                                         │
│     • BLE Config - Satu-satunya gateway dengan mobile app config           │
│     • PoE Redundant - Rare di harga < $500                                 │
│     • Triple Connectivity - ETH + WiFi + BLE dalam satu device            │
│                                                                              │
│  3. LOCAL ADVANTAGE                                                         │
│     • Technical support Bahasa Indonesia                                    │
│     • Lead time 1-3 hari vs 2-8 minggu import                              │
│     • Spare parts & service lokal                                          │
│                                                                              │
│  4. CERTIFICATIONS                                                          │
│     • FCC, CE, UL - International standards                                │
│     • RoHS compliant                                                        │
│                                                                              │
│  5. INDUSTRIAL GRADE                                                        │
│     • -40°C to +75°C operating temp                                        │
│     • 2kV isolation RS-485                                                 │
│     • 10-95% humidity                                                       │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 5. Cost of Goods Sold (COGS) Analysis - UPDATED

### 5.1 BOM - Standard Version (Per Unit @ 200 pcs)

> **Exchange Rate:** 1 USD = Rp 16,000

| No | Component | Specification | Qty | Unit (USD) | Total (USD) | Total (IDR) |
|----|-----------|---------------|-----|------------|-------------|-------------|
| 1 | ESP32-S3-WROOM-1-N16R8 | 16MB Flash, 8MB PSRAM | 1 | $5.60 | $5.60 | Rp 89,600 |
| 2 | W5500 Module | Ethernet Controller | 1 | $3.20 | $3.20 | Rp 51,200 |
| 3 | MAX3485 IC | RS485 Transceiver (Isolated) | 2 | $0.85 | $1.70 | Rp 27,200 |
| 4 | Digital Isolator | 2kV Isolation | 2 | $1.20 | $2.40 | Rp 38,400 |
| 5 | DS3231 Module | RTC with TCXO | 1 | $1.80 | $1.80 | Rp 28,800 |
| 6 | DC-DC Converter | 12-48V to 3.3V/5V | 1 | $2.50 | $2.50 | Rp 40,000 |
| 7 | TVS Diodes | ESD/Surge Protection | 8 | $0.18 | $1.44 | Rp 23,040 |
| 8 | RJ45 Connector | Magnetic Isolation | 1 | $1.20 | $1.20 | Rp 19,200 |
| 9 | Terminal Block | Power + RS485 | 3 | $0.65 | $1.95 | Rp 31,200 |
| 10 | USB-C Connector | Power/Debug | 1 | $0.35 | $0.35 | Rp 5,600 |
| 11 | LED Indicators | 8x Status LED | 8 | $0.08 | $0.64 | Rp 10,240 |
| 12 | Push Button | Config button | 1 | $0.12 | $0.12 | Rp 1,920 |
| 13 | Passive Components | Caps, Resistors, etc. | Set | $1.50 | $1.50 | Rp 24,000 |
| 14 | PCB 4-Layer | FR4 Industrial Grade | 1 | $5.50 | $5.50 | Rp 88,000 |
| 15 | DIN Rail Enclosure | Industrial Plastic IP20 | 1 | $4.50 | $4.50 | Rp 72,000 |
| 16 | Label & Packaging | Branding + Box | 1 | $0.80 | $0.80 | Rp 12,800 |
| | **SUBTOTAL BOM (Standard)** | | | | **$35.20** | **Rp 563,200** |

### 5.2 BOM - PoE Version (Per Unit @ 200 pcs)

| No | Additional Component | Specification | Qty | Unit (USD) | Total (USD) | Total (IDR) |
|----|---------------------|---------------|-----|------------|-------------|-------------|
| | Base BOM (Standard) | | | | $35.20 | Rp 563,200 |
| 17 | PoE PD Controller | IEEE 802.3af/at, 9W | 1 | $3.80 | $3.80 | Rp 60,800 |
| 18 | PoE Transformer | Isolation Transformer | 1 | $2.20 | $2.20 | Rp 35,200 |
| 19 | PoE Protection | TVS + Fuse | Set | $0.85 | $0.85 | Rp 13,600 |
| 20 | RJ45 PoE Connector | Magnetic + PoE | 1 | $1.80 | $1.80 | Rp 28,800 |
| | **SUBTOTAL BOM (PoE)** | | | | **$43.85** | **Rp 701,600** |

### 5.3 Manufacturing Cost (Per Unit @ 200 pcs)

| No | Cost Item | Standard (USD) | Standard (IDR) | PoE (USD) | PoE (IDR) |
|----|-----------|----------------|----------------|-----------|-----------|
| 1 | SMT Assembly | $4.00 | Rp 64,000 | $4.50 | Rp 72,000 |
| 2 | Manual Assembly | $1.80 | Rp 28,800 | $2.00 | Rp 32,000 |
| 3 | Testing & QC | $2.50 | Rp 40,000 | $3.00 | Rp 48,000 |
| 4 | Firmware Flashing | $0.50 | Rp 8,000 | $0.50 | Rp 8,000 |
| 5 | Burn-in Test | $1.00 | Rp 16,000 | $1.00 | Rp 16,000 |
| | **SUBTOTAL MFG** | **$9.80** | **Rp 156,800** | **$11.00** | **Rp 176,000** |

### 5.4 Total COGS Summary

```
┌──────────────────────────────────────────────────────────────────────────────────────┐
│                         COGS CALCULATION @ 200 PCS                                    │
│                         (Exchange Rate: 1 USD = Rp 16,000)                           │
├──────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                       │
│  ╔════════════════════════════════════════════════════════════════════════════════╗  │
│  ║                 STANDARD VERSION (SRT-MGATE-1210)                              ║  │
│  ╠════════════════════════════════════════════════════════════════════════════════╣  │
│  ║  Cost Component              │    USD        │      IDR                        ║  │
│  ║  ─────────────────────────────────────────────────────────────────────────     ║  │
│  ║  Bill of Materials (BOM)     │    $35.20     │      Rp 563,200                 ║  │
│  ║  Manufacturing Cost          │    $9.80      │      Rp 156,800                 ║  │
│  ║  ─────────────────────────────────────────────────────────────────────────     ║  │
│  ║  Direct Cost per Unit        │    $45.00     │      Rp 720,000                 ║  │
│  ║                              │               │                                 ║  │
│  ║  Overhead (15%)              │    $6.75      │      Rp 108,000                 ║  │
│  ║  Shipping & Handling (5%)    │    $2.25      │      Rp 36,000                  ║  │
│  ║  Contingency (5%)            │    $2.25      │      Rp 36,000                  ║  │
│  ║  ─────────────────────────────────────────────────────────────────────────     ║  │
│  ║  TOTAL COGS PER UNIT         │    $56.25     │      Rp 900,000                 ║  │
│  ║  TOTAL COGS FOR 200 PCS      │    $11,250    │      Rp 180,000,000             ║  │
│  ╚════════════════════════════════════════════════════════════════════════════════╝  │
│                                                                                       │
│  ╔════════════════════════════════════════════════════════════════════════════════╗  │
│  ║                 PoE VERSION (SRT-MGATE-1210-POE)                               ║  │
│  ╠════════════════════════════════════════════════════════════════════════════════╣  │
│  ║  Cost Component              │    USD        │      IDR                        ║  │
│  ║  ─────────────────────────────────────────────────────────────────────────     ║  │
│  ║  Bill of Materials (BOM)     │    $43.85     │      Rp 701,600                 ║  │
│  ║  Manufacturing Cost          │    $11.00     │      Rp 176,000                 ║  │
│  ║  ─────────────────────────────────────────────────────────────────────────     ║  │
│  ║  Direct Cost per Unit        │    $54.85     │      Rp 877,600                 ║  │
│  ║                              │               │                                 ║  │
│  ║  Overhead (15%)              │    $8.23      │      Rp 131,680                 ║  │
│  ║  Shipping & Handling (5%)    │    $2.74      │      Rp 43,840                  ║  │
│  ║  Contingency (5%)            │    $2.74      │      Rp 43,840                  ║  │
│  ║  ─────────────────────────────────────────────────────────────────────────     ║  │
│  ║  TOTAL COGS PER UNIT         │    $68.56     │      Rp 1,096,960               ║  │
│  ║  TOTAL COGS FOR 200 PCS      │    $13,712    │      Rp 219,392,000             ║  │
│  ╚════════════════════════════════════════════════════════════════════════════════╝  │
│                                                                                       │
└──────────────────────────────────────────────────────────────────────────────────────┘
```

### 5.5 COGS by Production Volume

| Volume | Standard (USD) | Standard (IDR) | PoE (USD) | PoE (IDR) |
|--------|----------------|----------------|-----------|-----------|
| 50 pcs | $68.00 | Rp 1,088,000 | $82.70 | Rp 1,323,200 |
| 100 pcs | $61.90 | Rp 990,400 | $75.60 | Rp 1,209,600 |
| **200 pcs** | **$56.25** | **Rp 900,000** | **$68.56** | **Rp 1,096,960** |
| 500 pcs | $49.00 | Rp 784,000 | $59.80 | Rp 956,800 |
| 1000 pcs | $43.70 | Rp 699,200 | $53.30 | Rp 852,800 |

---

## 6. Pricing Strategy & Official Pricelist

### 6.1 Pricing Methodology

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    PRICING STRATEGY FRAMEWORK                                │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  TARGET GROSS MARGIN: 75-80%                                                │
│                                                                              │
│  STANDARD VERSION:                                                          │
│  • COGS: $56.25 (Rp 900,000)                                               │
│  • Target Margin: 80%                                                       │
│  • Floor Price: $281 (Rp 4,500,000)                                        │
│  • MSRP: Rp 4,500,000 - 5,500,000 (avg Rp 5,000,000)                       │
│  • Gross Margin: 82%                                                        │
│                                                                              │
│  PoE VERSION:                                                               │
│  • COGS: $68.56 (Rp 1,097,000)                                             │
│  • Target Margin: 80%                                                       │
│  • Floor Price: $343 (Rp 5,485,000)                                        │
│  • MSRP: Rp 5,500,000 - 6,500,000 (avg Rp 6,000,000)                       │
│  • Gross Margin: 82%                                                        │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 6.2 Official Pricelist

---

# PRICELIST SRT-MGATE-1210 SERIES
## Suriota Modbus Gateway IIoT

**Effective Date:** December 1, 2025  
**Currency:** IDR (1 USD = Rp 16,000)

---

### Product Pricing

| Product Code | Description | MSRP (IDR) | MSRP (USD) |
|--------------|-------------|------------|------------|
| **SRT-MGATE-1210** | Standard Version - 2xRS485, ETH, WiFi, BLE | **Rp 5.000.000** | **$312** |
| **SRT-MGATE-1210-POE** | PoE Version - 2xRS485, ETH+PoE, WiFi, BLE | **Rp 6.000.000** | **$375** |

### Volume Discount - Standard Version

| Quantity | Unit Price (IDR) | Discount | Unit Price (USD) |
|----------|------------------|----------|------------------|
| 1-4 pcs | Rp 5.000.000 | 0% | $312 |
| 5-9 pcs | Rp 4.750.000 | 5% | $297 |
| 10-24 pcs | Rp 4.500.000 | 10% | $281 |
| 25-49 pcs | Rp 4.250.000 | 15% | $266 |
| 50-99 pcs | Rp 4.000.000 | 20% | $250 |
| 100+ pcs | Rp 3.750.000 | 25% | $234 |

### Volume Discount - PoE Version

| Quantity | Unit Price (IDR) | Discount | Unit Price (USD) |
|----------|------------------|----------|------------------|
| 1-4 pcs | Rp 6.000.000 | 0% | $375 |
| 5-9 pcs | Rp 5.700.000 | 5% | $356 |
| 10-24 pcs | Rp 5.400.000 | 10% | $337 |
| 25-49 pcs | Rp 5.100.000 | 15% | $319 |
| 50-99 pcs | Rp 4.800.000 | 20% | $300 |
| 100+ pcs | Rp 4.500.000 | 25% | $281 |

### Distributor/OEM Pricing

| Tier | Min. Order | Standard Price | PoE Price | Reseller Margin |
|------|------------|----------------|-----------|-----------------|
| Bronze | 25 pcs | Rp 3.500.000 | Rp 4.200.000 | 30% |
| Silver | 50 pcs | Rp 3.250.000 | Rp 3.900.000 | 35% |
| Gold | 100 pcs | Rp 3.000.000 | Rp 3.600.000 | 40% |
| OEM | 200+ pcs | Rp 2.500.000 | Rp 3.000.000 | Negotiable |

### Accessories & Add-ons

| Product Code | Description | Price (IDR) |
|--------------|-------------|-------------|
| SRT-PWR-24V2A | 24V 2A Industrial Power Adapter | Rp 250.000 |
| SRT-PWR-48V1A | 48V 1A Industrial Power Adapter | Rp 350.000 |
| SRT-ANT-2.4G | External 2.4GHz Antenna (SMA) | Rp 150.000 |
| SRT-DIN-KIT | DIN Rail Mounting Kit (spare) | Rp 100.000 |
| SRT-CAB-RS485 | RS485 Cable 2m (Shielded, Twisted Pair) | Rp 180.000 |
| SRT-EXT-WTY | Extended Warranty (+2 Years) | Rp 750.000 |

### Service Packages

| Package | Description | Price (IDR) |
|---------|-------------|-------------|
| SRT-SVC-INSTALL | On-site Installation & Commissioning | Rp 1.500.000/site |
| SRT-SVC-TRAINING | Technical Training (1 day, max 5 pax) | Rp 3.000.000/session |
| SRT-SVC-ANNUAL | Annual Maintenance Contract | Rp 500.000/unit/year |

---

### 6.3 Pricing Justification vs Competitors

| Comparison | Analysis |
|------------|----------|
| **vs Moxa MB3180 (Rp 5.6-6.4M)** | Harga sama, tapi SURIOTA punya WiFi + BLE yang Moxa tidak punya |
| **vs Moxa MB3280 2-port (Rp 8-8.8M)** | 40% lebih murah untuk fitur 2-port yang sama |
| **vs ICP DAS GW-7472 (Rp 3-4M)** | 25-50% lebih mahal, tapi punya WiFi, BLE, PoE option |
| **vs Red Lion DA10D (Rp 14-15M)** | **65% lebih murah** dengan fitur comparable + BLE |
| **vs Advantech WISE (Rp 7-10M)** | 40% lebih murah dengan fitur serupa + BLE config |

### 6.4 Why This Price is Justified

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    VALUE PROPOSITION @ Rp 5-6 JUTA                          │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  WHAT CUSTOMER GETS:                                                        │
│  ═══════════════════                                                        │
│  ✓ 2x Isolated RS-485 ports (2kV) .......... Worth Rp 1.5M (vs 1-port)    │
│  ✓ WiFi 2.4GHz WPA3 + Auto Failover ........ Worth Rp 1.0M (add-on)       │
│  ✓ BLE 5.0 Mobile Configuration ............ Worth Rp 800K (unique)       │
│  ✓ PoE IEEE 802.3af/at (PoE version) ....... Worth Rp 1.0M (add-on)       │
│  ✓ Industrial Temp -40~75°C ................ Worth Rp 300K (premium)      │
│  ✓ Local Indonesia Support ................. Worth Rp 500K (service)      │
│  ─────────────────────────────────────────────────────────────────────────  │
│  TOTAL VALUE                                   Rp 5.1M+ (Conservative)     │
│                                                                              │
│  SELLING PRICE (Standard)                      Rp 5.0M                      │
│  CUSTOMER SAVINGS                              Rp 100K+ (value match)      │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 7. Profit Analysis - UPDATED

### 7.1 Unit Economics

| Metric | Standard Version | PoE Version |
|--------|------------------|-------------|
| **Selling Price (MSRP)** | Rp 5.000.000 ($312) | Rp 6.000.000 ($375) |
| **COGS** | Rp 900.000 ($56) | Rp 1.097.000 ($69) |
| **Gross Profit** | Rp 4.100.000 ($256) | Rp 4.903.000 ($306) |
| **Gross Margin** | **82.0%** | **81.7%** |
| Marketing & Sales (15%) | Rp 750.000 | Rp 900.000 |
| R&D Amortization (10%) | Rp 500.000 | Rp 600.000 |
| Overhead (10%) | Rp 500.000 | Rp 600.000 |
| **Net Profit per Unit** | **Rp 2.341.000** | **Rp 2.794.000** |
| **Net Margin** | **46.8%** | **46.6%** |

### 7.2 Break-Even & ROI (Mixed 200 pcs: 120 Standard + 80 PoE)

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    BREAK-EVEN & ROI ANALYSIS                                 │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  INITIAL INVESTMENT:                                                        │
│    Standard COGS (120 pcs)       : Rp 108.000.000                          │
│    PoE COGS (80 pcs)             : Rp 87.760.000                           │
│    Tooling & Setup               : Rp 25.000.000                           │
│    Certification (CE/FCC/UL)     : Rp 50.000.000                           │
│    ──────────────────────────────────────────────                          │
│    TOTAL INVESTMENT              : Rp 270.760.000 (~$16,900)               │
│                                                                              │
│  REVENUE (if all sold at MSRP):                                            │
│    Standard (120 pcs × Rp 5.0M)  : Rp 600.000.000                          │
│    PoE (80 pcs × Rp 6.0M)        : Rp 480.000.000                          │
│    ──────────────────────────────────────────────                          │
│    TOTAL REVENUE                 : Rp 1.080.000.000                        │
│                                                                              │
│  GROSS PROFIT:                                                              │
│    Revenue - COGS                : Rp 884.240.000                          │
│    Less Fixed Costs              : Rp 75.000.000                           │
│    ──────────────────────────────────────────────                          │
│    NET PROFIT                    : Rp 809.240.000 (~$50,600)               │
│                                                                              │
│  ═══════════════════════════════════════════════════════════════════════   │
│  BREAK-EVEN UNITS                : 60 units (mixed)                        │
│  ROI                             : 299%                                    │
│  PAYBACK PERIOD                  : 3-4 months                              │
│  ═══════════════════════════════════════════════════════════════════════   │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 8. Sales Talking Points

### 8.1 Elevator Pitch (30 seconds)

> "SRT-MGATE-1210 adalah industrial IoT gateway **buatan Indonesia** yang punya fitur **premium** dengan harga **mid-range**. Ini **satu-satunya** gateway yang bisa di-setup via **smartphone dalam 5 menit**, punya **PoE** untuk instalasi mudah, dan **WiFi failover** otomatis. Harga **40-65% lebih murah** dari Moxa dan Red Lion, tapi fitur **lebih lengkap**. Plus, support teknis **lokal Indonesia**."

### 8.2 Key Selling Points (For Sales Team)

| Situation | Talking Point |
|-----------|---------------|
| **"Kenapa bukan Moxa?"** | "Moxa MB3180 tidak punya WiFi atau BLE. Harga sama, fitur kami lebih lengkap." |
| **"Terlalu mahal"** | "Kalau dibandingkan Red Lion DA10D yang punya PoE, kami 65% lebih murah. ICP DAS memang lebih murah tapi tidak punya WiFi dan BLE." |
| **"Brand belum terkenal"** | "Kami sudah dipakai di PT Astra Daihatsu, Pertamina, dan PAL Indonesia. Plus, support teknis lokal dalam Bahasa Indonesia." |
| **"Butuh PoE"** | "Kami punya versi PoE (Rp 6 juta). Kompetitor dengan PoE mulai dari Rp 14 juta (Red Lion)." |
| **"Setup ribet"** | "Demo: setup dalam 5 menit via smartphone. Tidak perlu laptop atau IP configuration awal." |
| **"Perlu WiFi failover"** | "Ada auto failover WiFi ↔ Ethernet. Kalau Ethernet putus, otomatis switch ke WiFi." |

### 8.3 Feature Demo Script

```
5-MINUTE DEMO SCRIPT:
═════════════════════

1. [0:00-0:30] UNBOXING
   "Ini gateway kami, sudah siap pakai. Colok power 12-48V."

2. [0:30-1:30] BLE CONNECTION
   "Download app Suriota Config di HP. Nyalakan Bluetooth."
   "Scan... klik device... connected dalam 10 detik."

3. [1:30-3:00] CONFIGURATION
   "Setup WiFi network... done."
   "Setup Modbus device: slave ID 1, baud 9600... done."
   "Setup MQTT broker: broker.hivemq.com... done."

4. [3:00-4:00] VERIFICATION
   "Lihat LED: Power hijau, Network biru, RS485 kuning berkedip."
   "Data sudah mengalir ke cloud."

5. [4:00-5:00] ADVANCED FEATURES
   "Auto failover WiFi kalau Ethernet putus."
   "PoE version bisa power via Ethernet."
   "Industrial grade: -40°C sampai +75°C."

DONE! Setup selesai dalam 5 menit tanpa laptop.
```

---

## 9. Appendix

### A. Competitor Price Sources

| Brand | Source | Date Verified |
|-------|--------|---------------|
| Moxa | moxa.com, moxastore.com | Nov 2025 |
| ICP DAS | icpdas-usa.com | Nov 2025 |
| Advantech | buy.advantech.com | Nov 2025 |
| Red Lion | process-tech.com, rs-online | Nov 2025 |
| USR-IOT | shop.usriot.com | Nov 2025 |

### B. Exchange Rate

| Currency | Rate (Nov 2025) |
|----------|-----------------|
| 1 USD | Rp 16,000 |

### C. Document History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2025-11-29 | SURIOTA R&D | Initial release |
| 2.0 | 2025-11-29 | SURIOTA R&D | Added PoE version, updated specs from datasheet |
| 2.1 | 2025-11-29 | SURIOTA R&D | Removed MicroSD and DNV-GL maritime references (deferred features) |

---

**PT Surya Inovasi Prioritas (SURIOTA)**  
R&D Team - Industrial IoT Solutions

**Contact:** sales@suriota.com | www.suriota.com | +62 858-3567-2476
