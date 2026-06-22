# SAP Flight Management Analytics App
### SAP BTP ABAP Environment | CDS Views | OData V4 | Fiori Elements

## Overview

This project demonstrates the development of an SAP Fiori Elements application using Core Data Services (CDS) Views on SAP BTP ABAP Environment.

The application provides an interactive flight management dashboard that allows users to browse, search, and filter airline flight information through a modern SAP Fiori interface.

The project showcases practical ABAP Cloud development concepts including:

- CDS View Modeling
- Metadata Extensions
- OData V4 Service Exposure
- Service Binding
- Fiori Elements UI Generation
- SAP BTP ABAP Development Tools (ADT)

---

## Project Objective

The goal of this project is to build a lightweight analytical application capable of:

- Viewing airline flight information
- Filtering flight records dynamically
- Exposing business data through OData services
- Generating a Fiori Elements application with minimal UI coding

---

## Technologies Used

| Technology | Purpose |
|------------|----------|
| SAP BTP ABAP Environment | Development Platform |
| Eclipse ADT | ABAP Development |
| ABAP Cloud | Backend Development |
| CDS Views | Data Modeling |
| OData V4 | Service Exposure |
| Fiori Elements | User Interface |
| SAP HANA Cloud | Data Storage |

---

## Architecture

Flight Data Table
        |
        v
CDS Root View Entity
        |
        v
Metadata Extension
        |
        v
Service Definition
        |
        v
Service Binding (OData V4)
        |
        v
Fiori Elements Application

---

## Features

### Flight Data Visualization

Display airline information including:

- Airline ID
- Flight Number
- Flight Date
- Flight Price
- Currency
- Plane Type
- Created By
- Created On
- Changed By
- Changed On

---

### Advanced Filtering

Users can filter records using:

- Airline ID
- Flight Number
- Flight Date
- Flight Price
- Plane Type
- Created By
- Created On
- Changed By
- Changed On

---

### Responsive SAP Fiori Interface

The application automatically generates a modern SAP Fiori UI using CDS annotations and OData services.

---

## Sample Screens

### Main Flight List Report

Displays all available flight records.

![Main Screen](images/main-screen.png)

---

### Airline Filter Example

Filter records by Airline ID.

Example:

Airline ID = JL

Returns all Japan Airlines flight records.

![Airline Filter](images/filter-airline.png)

---

### Flight Date Filter Example

Filter flights for a specific date.

Example:

Flight Date = 09-Jan-2027

![Date Filter](images/filter-date.png)

---

### Plane Type Filter Example

Filter flights by aircraft model.

Example:

Plane Type = A380-800

![Plane Filter](images/filter-plane.png)

---

## SAP Objects Created

### CDS View

```abap
define root view entity ...
```

### Metadata Extension

```abap
@UI.lineItem
@UI.selectionField
```

### Service Definition

```abap
define service ...
```

### Service Binding

```abap
OData V4
```

---

## Business Scenario

Airline companies manage thousands of flight records daily.

This application enables:

- Flight data exploration
- Quick searching
- Aircraft analysis
- Airline-specific filtering
- Operational reporting

through a clean SAP Fiori user experience.

---

## Learning Outcomes

This project helped me gain hands-on experience in:

- SAP BTP ABAP Environment
- ABAP Cloud Development
- CDS View Modeling
- OData V4 Services
- Fiori Elements Development
- Service Definitions
- Service Bindings
- SAP Eclipse ADT

---

## Future Enhancements

Planned improvements include:

- RAP Business Object Implementation
- Create / Update / Delete Operations
- Analytical CDS Views
- KPI Tiles
- Charts and Dashboards
- Authorization Control
- Custom Actions

---

## Author

Luthuful Haq

SAP ABAP Developer (Learning)

GitHub:
https://github.com/Luthufulhaq

LinkedIn:
https://linkedin.com/in/luthufulhaq
