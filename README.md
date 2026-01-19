# iot-indoor-air-quality-platform
End-to-end Indoor Air Quality (IAQ) IoT platform architecture covering device onboarding, secure telemetry ingestion, time-series data modeling, AQI analytics, and real-time dashboards for smart buildings. Designed for scalable AQMS systems handling high-frequency sensor data.

# Indoor Air Quality IoT Platform – Architecture

## Overview
This repository presents the architecture of an Indoor Air Quality (IAQ) monitoring
platform designed for smart buildings. The system supports real-time sensor data
ingestion, AQI analytics, and long-term environmental data storage.

## Problem Statement
Indoor environments require continuous monitoring of air quality parameters
(PM2.5, PM10, CO₂, TVOC, Temperature, Humidity) to ensure occupant health
and regulatory compliance.

## Architecture Overview
Indoor IAQ Device  
→ Secure Device API  
→ Telemetry Ingestion Service  
→ Time-Series Database  
→ AQI Analytics Engine  
→ Real-Time Dashboard & Alerts

## Key Architecture Capabilities
- Device onboarding using QR / Serial identity
- High-frequency telemetry ingestion (5-min intervals)
- Time-series optimized data modeling
- Configurable AQI standards (USA, UAE, India)
- Scalable design for large device fleets

## Technology Stack
- Backend: Java / .NET
- Database: PostgreSQL + TimescaleDB
- Frontend: React
- Protocols: HTTPS / MQTT (conceptual)

## Non-Functional Requirements
- Scalability
- Fault tolerance
- Data accuracy
- Observability

 
