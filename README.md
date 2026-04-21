# Smart Waste Management System
                             
## Project Overview

The **Smart Waste Management System** is a software platform designed for **ECO Tirana** to improve how waste is collected and managed in the city of Tirana, Albania.

The system centralizes waste operations: **bin monitoring, collection scheduling, route optimization, fleet tracking, recycling management, and citizen reporting**.

It replaces manual and fragmented processes such as phone calls, paper schedules, and fixed routes with a single dashboard for administrators, managers, drivers, field operators, and citizens.

Even without real sensors, the system **simulates bin data** (fill levels, status, maintenance) to demonstrate how a fully connected system would work. This provides a **proof-of-concept** for ECO Tirana and prepares the system for future IoT sensor integration.

---

## Problem Statement

Tirana faces several challenges in urban waste management:

* Overflowing bins: High-traffic areas fill faster than fixed schedules can handle.
* Wasted resources: Trucks visit empty bins unnecessarily, wasting fuel and labor.
* No real-time visibility: Managers cannot see which bins are full or which trucks are active.
* Inefficient routing: Predetermined routes do not account for actual bin status or traffic.
* Untracked citizen complaints: Reports via phone are slow and difficult to follow.
* Poor recycling compliance: Contamination reduces recycling quality.
* Slow reporting: Manual reports are time-consuming and error-prone.

### Proposed Solution

A digital platform that combines bin data, fleet operations, scheduling, and citizen feedback to:

* Reduce unnecessary trips and fuel usage
* Respond to citizen complaints faster
* Provide clear, data-driven reports to the municipality
* Prepare for future integration of IoT sensors

---

## Main Modules and Features

### Bin Monitoring Module

* Real-time simulated fill levels and bin status (normal, full, damaged)
* Map visualization with color-coded bins
* Alerts when bins exceed thresholds
* Optional AI image analysis to estimate fill levels or detect contamination

### Route Optimization Module

* Generates efficient routes prioritizing full bins
* Considers truck capacity, zones, and shift duration
* Drivers receive step-by-step navigation

### Fleet Management Module

* Tracks trucks, driver assignments, maintenance, and fuel usage
* Displays simulated real-time truck locations and status

### Collection Scheduling Module

* Plans dynamic schedules based on bin fill levels and fleet availability
* Calendar view with manual overrides

### Recycling Management Module

* Tracks recycling bins and contamination alerts
* Calculates recycling rates

### Citizen Reporting Module

* Citizens submit issues with location, photo, and description
* Automatic assignment to managers or field operators
* Status tracking for each report

### Reporting and Analytics Module

* Dashboards with KPIs (bins collected, fleet usage, recycling rates)
* Trend charts and zone comparisons
* Exportable reports (PDF / CSV)

---

## How It Helps ECO Tirana

### Efficiency

Optimized routes reduce unnecessary trips and fuel consumption.

### Visibility

Managers gain real-time insight into bins, trucks, and schedules.

### Accountability

All collections, maintenance activities, and reports are logged.

### Sustainability

Improved recycling management and reduced emissions.

### Scalability

The platform works with simulated data today and is ready for real IoT sensors in the future.

---

## Documentation

Additional project documentation:

* [Stakeholders](docs/stakeholders.md)
* System Architecture *(to be added)*

