# Data-Flow-Automation-with-Apache-NiFi
Mobile Sales Data Processing with Apache NiFi

This project demonstrates the use of **Apache NiFi** for building an end-to-end data pipeline to ingest, transform, and route **CSV-based mobile sales data**.

Project Highlights

-  **Data Source**: CSV file containing mobile sales transaction data  
- **Data Transformation**: Performed using the **ConvertRecord** processor with a **CSVReader** and **JSONRecordSetWriter**  
- **Schema Inference**: Automatic schema detection from CSV headers  
- **Use Case**: Converting structured sales data into a more consumable format (e.g., JSON) for further analysis  
- **Output**: Cleaned JSON files routed to the file system or downstream tools  

🔧 Key NiFi Processors Used

- `GetFile` – For reading source CSV files  
- `ConvertRecord` – To transform CSV to JSON using record-based schema-aware processors  
- `PutFile` – To save the transformed JSON output
