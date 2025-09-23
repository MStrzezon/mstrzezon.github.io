---
layout: default
title: JPK Generator - File Format Converter
permalink: /projects/jpk-generator/
---

# 📄 JPK Generator (XLSX/CSV to XML)

**Status**: ✅ Completed  
**Language**: Java  
**Type**: Data Conversion Tool

---

## 📋 Overview

A specialized Java application for converting Excel (.xlsx) and CSV files into JPK XML format - the standardized format required for Polish tax reporting to government authorities. The tool demonstrates practical application of Java technologies for business process automation.

---

## 🎯 Key Features

### 📊 **Multi-Format Input Support**
- **Excel Files (.xlsx)**: Direct processing of Excel spreadsheets
- **CSV Files**: Support for comma-separated value format
- **Automated Detection**: Smart format recognition and processing

### 🔄 **XML Generation**
- **JPK Standard**: Compliant with Polish Ministry of Finance specifications
- **JAXB Integration**: Object-to-XML marshalling using Java standards
- **Schema Validation**: Ensures output meets government requirements

### ⚙️ **Data Processing**
- **Invoice Processing**: Handles invoice data extraction and transformation
- **Tax Calculations**: Automatic VAT and tax amount processing
- **Data Validation**: Input validation and error handling

---

## 🛠️ Technical Architecture

### **Project Structure**
```
generator_jpk/
├── main/           # Application entry point
├── utils/          # Core processing utilities
├── javadoc/        # Complete API documentation
└── test files/     # Sample input files
```

### **Core Components**

#### **Input Processing**
```java
// File readers for different formats
Read.readXLSX(pathToFile)  // Excel file processing
Read.readCSV(pathToFile)   // CSV file processing
```

#### **Data Model**
```java
// JAXB-annotated classes for XML structure
@XmlRootElement(name="tns:JPK")
public class JPK {
    // Invoice data containers
    // Tax calculation elements
    // Person and company information
}
```

#### **Output Generation**
```java
// XML marshalling
Write.marshal(jpk, outputFileName);
```

---

## 📊 Data Flow

### **1. Input Analysis**
```java
// Automatic format detection
if (args[0].endsWith(".csv")) {
    jpk = Read.readCSV(args[0]);
} else if (args[0].endsWith(".xlsx")) {
    jpk = Read.readXLSX(args[0]);
}
```

### **2. Data Transformation**
```java
// Convert business data to JPK format
- Invoice header information
- Line item details with tax calculations
- Customer and supplier data
- Compliance metadata
```

### **3. XML Generation**
```java
// JAXB marshalling to XML
- Schema-compliant output
- Formatted XML structure
- Government-ready file format
```

---

## 🚀 Usage

### **Command Line Interface**
```bash
# For CSV input
java -jar Generator.jar input.csv output.xml

# For Excel input  
java -jar Generator.jar input.xlsx output.xml
```

### **Build Process**
```bash
# Maven build
mvn clean install

# Creates executable JAR with dependencies
# Target: Generator.jar
```

---

## 🔧 Technical Implementation

### **JAXB XML Binding**
```java
@XmlRootElement(name="tns:JPK")
@XmlAccessorType(XmlAccessType.FIELD)
public class JPK {
    @XmlElement(name="tns:Naglowek")
    private Header header;
    
    @XmlElement(name="tns:Faktura")
    private List<Invoice> invoices;
}
```

### **Data Processing**
```java
// Money amount conversion
private static BigDecimal moneyToBigDecimal(String s) {
    // Handles "3 600 zł" -> 3600.00
    // Currency symbol removal
    // Decimal precision handling
}
```

### **File I/O Operations**
```java
// Excel processing with Apache POI
XSSFWorkbook workbook = new XSSFWorkbook(file);
XSSFSheet sheet = workbook.getSheetAt(0);

// CSV processing with Apache Commons CSV
CSVParser.parse(in, CSVFormat.TDF);
```

---

## 📈 Business Impact

### **Problem Solved**
- **Manual Reporting**: Eliminated manual XML creation for tax reports
- **Error Reduction**: Automated data transformation reduces human errors
- **Compliance**: Ensures proper JPK format for government submissions

### **Use Cases**
- **Accounting Firms**: Batch processing of client tax data
- **Small Businesses**: Converting Excel invoices to JPK format
- **Tax Preparation**: Government reporting automation

---

## 🧪 Quality Assurance

### **Testing Framework**
```java
// JUnit test coverage
@Test
public void testXLSXReading() { /* ... */ }

@Test  
public void testCSVProcessing() { /* ... */ }

@Test
public void testXMLGeneration() { /* ... */ }
```

### **Documentation**
- **Javadoc**: Complete API documentation
- **Usage Guide**: Command-line instructions
- **Format Specs**: JPK standard compliance details

---

## 🔗 Links

- **[GitHub Repository](https://github.com/mstrzezon/generator_jpk)** - Source code and documentation
- **[Javadoc Documentation](https://github.com/mstrzezon/generator_jpk/tree/main/javadoc)** - API reference

---

## 🏷️ Technologies Used

<div class="tech-showcase">
  <div class="tech-category">
    <h4>Core Technologies</h4>
    <ul>
      <li>Java SE 17</li>
      <li>JAXB (XML Binding)</li>
      <li>Maven Build System</li>
      <li>Apache Commons CSV</li>
    </ul>
  </div>
  
  <div class="tech-category">
    <h4>File Processing</h4>
    <ul>
      <li>Apache POI (Excel)</li>
      <li>CSV Parsing</li>
      <li>XML Generation</li>
      <li>Data Validation</li>
    </ul>
  </div>
  
  <div class="tech-category">
    <h4>Standards & Compliance</h4>
    <ul>
      <li>JPK Schema</li>
      <li>Polish Tax Standards</li>
      <li>XML Schema Validation</li>
      <li>Government Compliance</li>
    </ul>
  </div>
</div>

---

*This project demonstrates practical business application development with emphasis on data conversion, government compliance standards, and enterprise-grade Java development practices.*