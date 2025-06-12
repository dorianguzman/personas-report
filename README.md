# Personas AI Agent - Performance Report Generator

This directory contains a comprehensive tool for generating professional performance reports from Twitter/X analytics CSV data, styled with Personas branding.

## 🚀 All-in-One Report Generator

### **Report Generator** (`report_generator.html`)
The single, unified interface for generating all report types:
- Upload Twitter/X CSV analytics data
- Enter campaign information
- Manually input click data (Twitter doesn't export this)
- Generate multiple report formats:
  - Interactive web report (HTML)
  - Data export (CSV)
  - Summary report (TXT)
  - Instructions for PDF generation

### Key Features:
- 📊 Real-time preview with Chart.js visualizations
- 🎨 Personas brand styling throughout
- 📈 Automatic metrics calculation (CTR, growth rates, benchmarks)
- 💾 Multiple export formats from one interface
- 🔄 No installation required - runs in browser

## 🛠️ Usage

### Quick Start:
```bash
# Open the report generator
open report_generator.html
```

### Step-by-Step Process:
1. **Upload CSV**: Export data from Twitter/X Analytics and upload
2. **Enter Campaign Info**: Add campaign name and client/region
3. **Input Click Data**: Manually enter clicks for each date
4. **Preview Metrics**: See real-time calculations and charts
5. **Generate Reports**: Create all report formats with one click

### Generated Outputs:
- **Web Report**: Interactive HTML with charts and metrics
- **Data Export**: CSV with impressions, clicks, and CTR calculations
- **Summary**: Text report with key insights and performance metrics
- **PDF Instructions**: Python script reference for professional PDFs

## 📁 Project Structure

### Core Generator
- `report_generator.html` - All-in-one report generation interface

### Python Scripts (for advanced users)
- `generate_report_from_csv.py` - Generate PDF reports from CSV
- `generate_pdf_report.py` - Sample PDF generation script
- `generate_web_report.py` - Update existing web reports
- `requirements.txt` - Python dependencies

### Sample Reports
- `index.html` - Example interactive web report (Africa case study)

### Assets
- `assets/` - Personas brand fonts and styling resources

## 🎨 Design System

The reports follow the Personas brand guidelines:
- Primary Green: `#c4fb01`
- Primary Cyan: `#00bcd4`
- Dark background: `#0a0a0a`
- Youth font for headings
- Geologica font for body text

## 📊 Key Metrics Tracked

- **Total Impressions** with growth rate
- **Total Clicks** with peak performance
- **Average CTR** compared to industry benchmark (0.05%)
- **Campaign Duration** in days
- **Daily Performance** charts and trends

## 📝 Data Requirements

### Twitter/X Analytics Export
Export your data from Twitter/X:
1. Go to Account → Analytics
2. Export as CSV
3. Upload to the generator

### Manual Click Entry
Since Twitter doesn't export click data, you'll need to:
1. Check each post's engagement metrics
2. Enter clicks for each date in the generator
3. CTR will be calculated automatically

## 🔗 Learn More

Visit [www.qstarlabs.ai](https://www.qstarlabs.ai) to deploy AI agents for your performance marketing campaigns.

---

*This report showcases the power of autonomous AI agents in performance marketing, demonstrating real results from live campaigns.*