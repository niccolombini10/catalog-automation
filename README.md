# 📦 E-commerce Catalog Automation

### Python • pandas • Data Cleaning • Supplier Integration • Feed Generation

This project demonstrates a professional end-to-end automation workflow for managing a large e-commerce catalog (70,000+ products).
It includes data cleaning, supplier file integration, attribute normalization, and the generation of CSV/XLSX feeds for platforms like Shopify (Matrixify), Google Merchant Center, and Kelkoo.

---

## 🚀 Features

* **Automatic catalog updates** using Python and pandas
* **Data cleaning & normalization** across multiple supplier formats
* **Merge & reconciliation** of product attributes, variants, and prices
* **Feed generation** for external platforms (Google, Kelkoo, custom exports)
* **Logging system** for debugging and daily cronjob monitoring
* **Modular structure** to easily plug in new suppliers and workflows
* **Extensible pipeline** for future data analysis tasks

---

## 🧱 Project Structure

```
catalog-automation/
│
├── src/
│   ├── cleaner.py        # Data cleaning utilities
│   ├── merger.py         # Supplier merge logic
│   ├── feed_generator.py # Google/Merchant/Kelkoo outputs
│   ├── utils.py          # Shared functions
│   └── main.py           # Entry point of the pipeline
│
├── samples/
│   ├── supplier_sample.xlsx
│   ├── catalog_sample.csv
│   └── output_sample.csv
│
└── README.md
```

---

## 🛠 Technologies

* **Python 3.x**
* **pandas**
* **openpyxl**
* **logging**
* **cron (Linux)**
* **Shopify Matrixify (export/import formats)**

---

## 📝 Example Workflow

1. Load supplier files
2. Normalize column names
3. Clean missing or inconsistent values
4. Merge suppliers with the master catalog
5. Apply business logic (pricing, availability, tags…)
6. Export final feed for Shopify / Google / Kelkoo
7. Log execution via cronjob

---

## 📈 Future Improvements

* Data validation using Pydantic
* Supplier-specific mappers
* SQL database integration
* Dashboard for monitoring catalog changes

---

## 👤 Author

**Niccolò Colombini**
CTO & E-commerce Technical Specialist
