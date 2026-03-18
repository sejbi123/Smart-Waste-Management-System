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

## Functional Requirements

The system must:

* Display simulated real-time bin fill levels and status
* Generate optimized waste collection routes
* Assign drivers to trucks and routes
* Allow citizens to submit reports with location and photos
* Track the status of citizen reports
* Monitor fleet status and maintenance schedules
* Track recycling bins and detect contamination
* Send alerts when bins exceed thresholds
* Generate dashboards and exportable reports
* Provide a mobile-friendly interface for drivers

---

## Non-Functional Requirements

* System availability during operational hours (06:00 – 22:00)
* Fast loading dashboards (< 2 seconds)
* Support 100+ concurrent users
* Secure authentication and role-based access control
* Responsive UI for mobile and desktop
* Scalable architecture supporting thousands of bins
* Maintain audit logs of system actions
* Simulated sensor updates processed within 5 seconds

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
### User Cards

 Name: System Administrator  
Role: Platform Owner / Supervisor  

Goals:
- Monitor entire waste management system  
- Analyze reports and KPIs  
- Ensure system efficiency  

Tasks:
- View dashboards  
- Manage users and roles  
- Generate reports  

Pain Points:
- Lack of real-time data  
- Manual reporting  

Needs:
- Clear dashboards  
- Reliable system performance

  Name: Operations Manager  
Role: Planning & Monitoring  

Goals:
- Optimize routes and schedules  
- Reduce operational costs  

Tasks:
- Assign routes to drivers  
- Monitor bins and fleet  
- Adjust schedules  

Pain Points:
- Inefficient routes  
- No visibility of bin status  

Needs:
- Real-time updates  
- Smart route suggestions
  Name: Driver  
Role: Waste Collection  

Goals:
- Complete routes efficiently  
- Avoid delays  

Tasks:
- Follow assigned routes  
- Collect waste  
- Deliver to facility  

Pain Points:
- Unclear routes  
- Traffic or delays  

Needs:
- Mobile-friendly interface  
- Step-by-step navigation

  Name: Field Worker  
Role: Bin Maintenance  

Goals:
- Fix damaged or overflowing bins  

Tasks:
- Repair bins  
- Respond to issues  

Pain Points:
- Delayed reports  
- Lack of task tracking  

Needs:
- Clear task assignments  
- Location-based alerts
  Name: Facility Worker  
Role: Waste Processing  

Goals:
- Manage waste unloading  
- Track waste types and quantities  

Tasks:
- Register truck arrival  
- Log waste data  
- Report contamination  

Pain Points:
- Manual logging  
- Lack of tracking system  

Needs:
- Simple interface  
- Fast data entry
  Name: Citizen  
Role: Service User  

Goals:
- Report issues quickly  
- Live in a clean environment  

Tasks:
- Submit complaints  
- Track report status  

Pain Points:
- Slow response  
- No feedback  

Needs:
- Easy reporting system  
- Status updates  

## Documentation

Additional project documentation:

* [Stakeholders](docs/stakeholders.md)
* ![Stakeholder Onion Diagram]
<a href="onion.dia2.png">
  <img src="onion.diagram.png" width="600"/>
</a>

* System Architecture *(to be added)*

