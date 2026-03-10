# Smart-Waste-Management-System
 
- Project Overview

The Smart Waste Management System is a software platform designed for ECO Tirana to improve how waste is collected and managed in the city of Tirana, Albania.
The system centralizes waste operations: bin monitoring, collection scheduling, route optimization, fleet tracking, recycling management, and citizen reporting. It replaces manual and fragmented processes (phone calls, paper schedules, fixed routes) with a single, easy-to-use dashboard for administrators, managers, drivers, field operators, and citizens.
Even without real sensors, the system simulates bin data (fill levels, status, maintenance) to show how a fully connected system would work. This provides a realistic proof-of-concept for ECO Tirana and lays the groundwork for future IoT sensor deployment.

- Problem Statement

Tirana faces challenges in urban waste management:

Overflowing bins: High-traffic areas fill faster than fixed schedules can handle.

Wasted resources: Trucks visit empty bins unnecessarily, wasting fuel and labor.

No real-time visibility: Managers cannot see which bins are full or which trucks are active.

Inefficient routing: Predetermined routes do not account for actual bin status or traffic.

Untracked citizen complaints: Reports via phone are slow and hard to follow.

Poor recycling compliance: Contamination reduces recycling quality.

Slow reporting: Manual reports are time-consuming and error-prone.

Solution: A digital platform that combines bin data, fleet operations, scheduling, and citizen feedback to:

Reduce unnecessary trips and fuel usage.

Respond to citizen complaints faster.

Provide clear, data-backed reports to the municipality.

Prepare for future integration of real sensors.

- Stakeholders

Primary Users (Actors):

Admin: Manages users, roles, and system configuration.

Waste Management Manager: Monitors operations, approves schedules, views analytics.

Truck Driver: Receives routes, marks bins collected, reports issues.

Field Operator: Maintains bins, logs maintenance, updates bin status.

Citizen (optional): Reports full bins, illegal dumping, or damage.

Secondary Stakeholders:

ECO Tirana Management: Oversees operations, service quality, and costs.

Municipality of Tirana: Receives reports and ensures compliance with regulations.

Development Team: Builds and maintains the system.

Environmental Agencies: Monitor recycling and environmental impact.

- Main Modules and Features

Bin Monitoring Module

Real-time simulated fill levels, status (normal, full, damaged).

Map visualization with color-coded bins.

Alerts when bins exceed thresholds.

Optional AI image analysis for photos to estimate fill level or detect contamination.

Route Optimization Module

Generates efficient routes prioritizing full bins.

Considers truck capacity, zones, and shift duration.

Drivers see step-by-step navigation.

Fleet Management Module

Tracks trucks, driver assignments, maintenance, and fuel.

Real-time (simulated) truck locations and status.

Collection Scheduling Module

Plans dynamic schedules based on bin fill levels and fleet availability.

Calendar view and manual overrides.

Recycling Management Module

Tracks recycling bins, contamination alerts, and recycling rates.

Citizen Reporting Module

Citizens submit issues via location, photo, and description.

Reports assigned automatically to managers or field operators.

Status tracking for each report.

Reporting and Analytics Module

Dashboards with KPIs: bins collected, fill levels, fleet usage, recycling rates.

Trend charts, zone comparisons, and exportable reports (PDF/CSV).

- Functional Requirements

Display real-time simulated bin fill levels and status.

Generate optimized collection routes.

Assign drivers to trucks and routes; notify them of changes.

Allow citizens to submit reports with location, photo, and description.

Track the status of citizen reports from submission to resolution.

Monitor fleet status and maintenance schedules.

Track recycling bins and detect contamination.

Send alerts for bins exceeding thresholds.

Generate dashboards and exportable reports.

Provide mobile-friendly view for drivers.

- Non-Functional Requirements

System should be available during operational hours (06:00–22:00).

Pages and dashboard load quickly (<2 seconds).

Support 100+ concurrent users without slowdowns.

Secure: encrypted data, role-based access, authentication via JWT/OAuth.

Responsive UI for mobile and desktop.

Scalable to thousands of bins.

Keep audit logs of actions.

Process simulated sensor updates quickly (<5 seconds).

- How It Helps ECO Tirana

Efficiency: Reduce unnecessary trips, optimize routes, faster response to issues.

Visibility: Real-time dashboard for bins, trucks, and schedules.

Accountability: Logs all collections, maintenance, and reports.

Sustainability: Better recycling, fewer emissions.

Scalability: Works now with simulated data; ready for real sensors in the future.
