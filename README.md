# Securio — Open AQI Dataset
### Adevair Technologies | UNICEF Climate & Health 2026

## What This Is
Real-world hyperlocal air quality data collected by Securio — 
an intelligent wearable that senses, filters, and maps air 
quality at street level. Data is contributed openly to UNICEF 
under a framework validated with the Cambridge Institute for 
Sustainability Leadership.

## Dataset Summary
| Parameter | Value |
|---|---|
| Total sensor readings | 100,000+ across 3 cities |
| Scientific dataset | 21,963 readings — 7 days, 10 locations |
| Cities covered | Bengaluru, Pune, Delhi |
| Sensor consistency | R²=0.956 (PM2.5 vs AQI) |
| Peak AQI recorded | 631 (Hazardous) |
| Peak PM2.5 recorded | 552 µg/m³ — 36× WHO guideline |
| WHO exceedance rate | 58.9% of all readings |
| Mean PM2.5 | 48.5 µg/m³ — 3.2× WHO annual guideline |
| Sampling frequency | Every 3 seconds |

## Files
- `Securio_AQI_7Day_Report.csv` — 21,963 reading 
  scientific dataset, April 14–21 2026, 10 locations
- `Securio_Journey_Pins_2026-04-24.csv` — Landmark 
  commute validation: AQI 64→235 in 24 minutes, 78 data 
  pins. City app showed Moderate throughout.
- `Securio_Journey_Pins_2026-05-14.csv` — May 2026 
  corridor data, ongoing collection
- `Friday_24th.csv` — Full day dataset, April 24 2026

## Key Finding
A child commuting to school in Bengaluru was exposed to 
AQI swinging from 64 (Good) to 235 (Very Unhealthy) in a 
single 24-minute journey — exposure that no existing fixed 
monitoring infrastructure captured.

## Data Structure (Journey Pins)
Each journey CSV contains:
`Pin# | Timestamp | Type | AQI | Min AQI | Max AQI | 
PM1 | PM2.5 | PM10 | CO | Location | Latitude | Longitude`

## Licence
CC0 1.0 Universal — no rights reserved. 
Freely usable by UNICEF and partners for climate-health 
policy and research.

## About Securio
Securio combines 5 simultaneous layers in one wearable:
- PM1/PM2.5/PM10 sensing
- Carbon monoxide detection  
- Posture AI (TinyML on-device)
- AURA Core active filtration
- Hands-free SOS

TRL-7 validated | Patent filings covering 135+ countries | 
August 2026 launch

**Adevair Technologies Private Limited**  
DPIIT Recognition: DIPP172103  
Contact: kachi.shailesh@adevair.com  
Website: www.adevair.com
