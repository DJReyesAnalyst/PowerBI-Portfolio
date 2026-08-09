# Project 06: Bulk Distance Calculator 🐍📍

![Distance Calculator Dashboard Showcase](Project-06-Bulk-Distance-Calculator/Bulk-Distance-Calculator.jpg)

A Python desktop application developed to automate road-distance and travel-time calculations between multiple origin and destination sites.

## 📄 Business Problem

In telecom and field operations, planners may need to estimate travel distance between hundreds of sites. Manually checking routes one by one in a map application is slow and difficult to scale.

This application automates the process by allowing the user to upload an Excel file containing origin and destination coordinates, query a routing API, and generate an output file with calculated road distance and estimated travel time.

## 🎯 Objective

Create a simple desktop tool that can:

1. Browse and select an Excel input file.
2. Read origin and destination site information and GPS coordinates.
3. Send coordinate pairs to a routing API.
4. Retrieve real road-route distance.
5. Calculate estimated travel time using a standard planning speed of **50 km/h**.
6. Generate an Excel output containing the original information plus the calculated results.

## 📥 Input Data

The application expects the following columns:

| Column | Description |
|---|---|
| Origin | Origin site name |
| Origin Lat | Origin latitude |
| Origin Long | Origin longitude |
| Destination | Destination site name |
| Destination Lat | Destination latitude |
| Destination Long | Destination longitude |

## 📤 Output Data

The output retains the input columns and adds:

| Column | Description |
|---|---|
| Distance in KM | Real road-route distance returned by the routing service |
| Travel Time | Estimated travel time based on 50 km/h |

### Travel Time Formula

**Travel Time (hours) = Distance (KM) ÷ 50**

## 🛠 Technology Stack

- **Python**
- **Tkinter** — desktop graphical user interface
- **Pandas** — Excel/data processing
- **OpenRouteService / routing API** — road-route distance calculation
- **Requests / API integration**
- **Microsoft Excel** — input and output data format
- **VS Code** — development environment

## 🔄 Application Workflow

```text
Excel Input
    ↓
Browse Excel File
    ↓
Read Origin/Destination Coordinates
    ↓
Send Coordinates to Routing API
    ↓
Get Real Road Distance
    ↓
Calculate Travel Time @ 50 km/h
    ↓
Add Results to Dataset
    ↓
Export Excel Output
```

## 📊 Example Use Case

The tool can be used for telecom field operations, dispatch planning, site clustering, logistics, preventive maintenance planning, and other activities where travel distance between locations is required.

For example:

```text
Origin: Site A
Destination: Site B

Coordinates → Routing API → 28.61 KM

Travel Time = 28.61 / 50
            = 0.57 hours
```

## 🚀 Key Features

- Excel file selection through a desktop GUI
- Bulk processing of multiple site pairs
- Real road-route distance instead of straight-line distance
- Batch API processing
- Retry handling for temporary API failures
- Progress percentage display
- Processed record counter
- Success and failed record counters
- Current batch indicator
- Excel output generation

## 🖥 Application Screenshot

The application provides a simple interface showing the selected Excel file, processing progress, success/failure counts, and current batch.

**Screenshot:** The working application screenshot is maintained with the portfolio project materials and can be added to this folder when the repository project assets are uploaded.

## 🤖 AI-Assisted Development

This project also demonstrates my approach to **AI-assisted application development**.

I am still developing my Python programming skills, but I was able to turn an operational requirement into a working desktop application by:

- Defining the business requirement and expected workflow
- Designing the input/output structure
- Writing detailed prompts and requirements for AI-assisted coding
- Testing the generated Python code in VS Code
- Troubleshooting API, batch-processing, and connectivity issues
- Improving the GUI based on actual testing results
- Validating the output against expected road-distance results

The important skill demonstrated here is not only writing Python code, but **translating a real operational problem into a functional automation solution and iterating on it through testing and troubleshooting**.

## 📚 What I Learned

- Python desktop application development
- Working with Excel files using Pandas
- API integration
- Working with latitude/longitude coordinates
- Route and distance calculation
- Batch processing
- Error handling and retry logic
- GUI progress tracking
- Debugging network/API issues
- Using AI effectively as a development assistant

## 🔮 Future Improvements

Potential future enhancements include:

- Configurable travel speed instead of a fixed 50 km/h
- Multiple routing profiles
- Improved failed-record recovery
- API usage monitoring
- Downloadable processing logs
- Map visualization of routes
- Support for additional input file formats
- Packaging and distribution as a standalone Windows application

---

**Project Type:** Python Automation / Desktop Application  
**Domain:** Telecom / Field Operations / Logistics  
**Development Environment:** VS Code  
**Status:** Working Prototype / Continuously Improving
