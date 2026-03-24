# Bangladesh Weather & Air Pollution Dataset

A cleaned version of the [Bangladesh-District-Level-Weather-Pollution-DataSet](https://github.com/Albab-Hasan/Bangladesh-District-Level-Weather-Pollution-DataSet) ready for use.

## Overview

- **Records**: 14,208 (64 districts × 222 days)
- **File**: `master.csv`
- **Coverage**: All 8 administrative divisions and 64 districts of Bangladesh
- **Temporal resolution**: Daily
- **Period**: August 10, 2025 – March 19, 2026
- **No missing data**: Complete observations for every district on every date

## Columns

| Column | Description |
|--------|-------------|
| `date` | Observation date (YYYY-MM-DD) |
| `district` | District name |
| `division` | Administrative division |
| `lat` | Latitude |
| `lon` | Longitude |
| `temp_c` | Temperature (°C) |
| `humidity` | Relative humidity (%) |
| `wind_speed` | Wind speed |
| `clouds` | Cloud coverage (%) |
| `aqi` | Air Quality Index |
| `pm2_5` | PM2.5 concentration (µg/m³) |
| `o3` | Ozone concentration |
| `no2` | Nitrogen dioxide concentration |
| `so2` | Sulfur dioxide concentration |
| `co` | Carbon monoxide concentration |

## Administrative Divisions

| Division | Districts |
|----------|-----------|
| Barishal | Barguna, Barishal, Bhola, Jhalokathi, Patuakhali, Pirojpur |
| Chattogram | Bandarban, Brahmanbaria, Chandpur, Chattogram, Cox's Bazar, Cumilla, Feni, Khagrachhari, Lakshmipur, Noakhali, Rangamati |
| Dhaka | Dhaka, Faridpur, Gazipur, Gopalganj, Kishoreganj, Madaripur, Manikganj, Munshiganj, Narayanganj, Narsingdi, Rajbari, Shariatpur, Tangail |
| Khulna | Bagerhat, Chuadanga, Jashore, Jhenaidah, Khulna, Kushtia, Magura, Meherpur, Narail, Satkhira |
| Mymensingh | Jamalpur, Mymensingh, Netrokona, Sherpur |
| Rajshahi | Bogura, Chapai Nawabganj, Joypurhat, Naogaon, Natore, Pabna, Rajshahi, Sirajganj |
| Rangpur | Dinajpur, Gaibandha, Kurigram, Lalmonirhat, Nilphamari, Rangpur, Thakurgaon |
| Sylhet | Habiganj, Moulvibazar, Sunamganj, Sylhet |

## Sample Data

```
date,district,division,lat,lon,temp_c,humidity,wind_speed,clouds,aqi,pm2_5,o3,no2,so2,co
2025-08-10,Bagerhat,Khulna,22.655478,89.794181,30.96,68,4.05,100,1,1.45,40.24,0.13,0.17,98.42
```

## Potential Use Cases

- Weather and air quality correlation analysis
- Regional pollution comparisons across divisions
- Seasonal trend analysis (monsoon to dry season transition)
- Geospatial mapping of pollution hotspots
- Time-series forecasting of AQI and pollutant levels
