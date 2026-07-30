# Nike Ireland Supply Chain and Customer Retention Analytics

## Project Overview

This project proposes a Business Intelligence and CRM solution designed to help Nike Ireland improve supply-chain visibility, delivery performance, inventory management and customer satisfaction.

The solution combines Power BI dashboards with a HubSpot CRM workflow to transform operational insights into automated customer-service actions.

## Business Problem

The analysis identified operational challenges related to:

- Late deliveries
- Product stockouts
- Supplier performance
- Long customer-support resolution times
- Low customer satisfaction
- Limited visibility across supply-chain and customer-service processes

## Business Objectives

- Reduce late deliveries.
- Improve product availability.
- Monitor supplier performance.
- Improve customer-support response times.
- Increase customer satisfaction.
- Enable proactive and data-driven decision-making.

## Technology Stack

- Power BI
- Power Query
- DAX
- HubSpot CRM
- Relational Data Modelling
- Excel / CSV data sources

## Dashboard Solution

The project contains three Power BI dashboards:

### Executive Dashboard

Provides a strategic view of:

- Total sales
- Late-delivery rate
- Stockout rate
- Customer satisfaction
- Delivery volumes
- Return reasons

### Supply Chain Dashboard

Analyses:

- Supplier performance
- Inventory availability
- Shipment delays
- Product stock pressure
- Supplier rankings

### Customer Experience Dashboard

Monitors:

- Customer tickets
- Resolution time
- CSAT
- Ticket categories
- Returns
- Regional customer-service trends

## Data Model

The analytical model includes dimension tables for:

- Customers
- Products
- Stores
- Suppliers

Fact tables include:

- Orders
- Shipments
- Inventory
- Customer tickets
- Returns
- Supplier scorecards

## CRM Automation

A HubSpot workflow was designed for late-delivery complaints.

When a ticket is classified as `Late Delivery`, the workflow:

1. Changes its status to `Under Investigation`.
2. Assigns it to a customer-service agent.
3. Sends an internal notification.
4. Prioritises the issue for follow-up.

## Key Findings

The initial analysis identified:

- Late-delivery rate of approximately 26%.
- Stockout rate of approximately 21%.
- Customer satisfaction score of approximately 5.02 out of 10.
- Average customer-support resolution time of approximately 56 hours.
- Supplier performance differences contributing to operational delays.

## Future Work

- Add predictive models for delivery delays.
- Develop customer churn prediction.
- Implement demand forecasting.
- Connect dashboards to real-time operational data.
- Expand CRM automation.
