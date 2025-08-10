# covid19
# COVID-19 Azure Data Factory Project

This project showcases a cloud-native data integration pipeline using Azure Data Factory (ADF), focused on ingesting, transforming, and preparing COVID-19 datasets for analytics and reporting.

## 🚀 Project Highlights

- Ingests public COVID-19 data from ECDC and Eurostat
- Automates data pipelines with ADF triggers and scheduling
- Configures datasets, linked services, and pipeline parameters
- Integrates with HDInsight and Power BI for downstream consumption
- Implements modular SQL and PySpark transformations

## 🛠️ Technologies Used

- **Azure Data Factory**
- **Azure Blob Storage**
- **Azure HDInsight**
- **Power BI**
- **Python & PySpark**
- **SQL**
- **Git & GitHub**

## 🔄 Copy Activity Flow

This diagram illustrates the source-to-sink flow using Azure Data Factory's Copy Activity.

![Copy Activity Diagram](docs/copy-activity-diagram.png)

## 📁 Repository Structure
covid19-adf/
    ├── cicd/ 
    ├── config/ 
    ├── ecdc_data/
    ├── eurostat_data/
    ├── hdinsight_scripts/ 
    ├── lookup_data/ 
    ├── power_bi_reports/ 
    ├── processed/ 
    ├── pyspark_notebooks/ 
    ├── raw/ 
    ├── sql_scripts/ 
    ├── LICENSE 
    └── README.md


## 👨‍💻 About the Developer

Cloud Data Engineer with hands-on experience in designing scalable data pipelines, orchestrating cloud-native workflows, and delivering analytics-ready datasets using Azure technologies.

## 📫 Contact

Connect via [LinkedIn](https://www.linkedin.com/in/ragulgowthamp) or explore more projects on [GitHub](https://github.com/ragul-gowthamps).

## 📄 License

This project is licensed under the MIT License.