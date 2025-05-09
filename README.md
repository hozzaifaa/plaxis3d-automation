Here’s a full and polished `README.md` tailored to your PLAXIS 3D automation project, with all three tutorials (`00`, `01`, `02`) clearly indexed:

---

````markdown
# PLAXIS 3D Automation with Python 🏗️💻

This repository contains a collection of Jupyter notebooks for automating geotechnical modeling in **PLAXIS 3D** using Python scripting.  
It covers essential tasks like connecting to PLAXIS, setting project properties, defining boreholes, and generating soil layers programmatically.

---

## 📚 Tutorial Index

| Lesson | Notebook | Description |
|--------|----------|-------------|
| 00 | [`00_connect_to_plaxis3d.ipynb`](00_connect_to_plaxis3d.ipynb) | Connect to PLAXIS 3D Input using the scripting API |
| 01 | [`01_set_project_properties.ipynb`](01_set_project_properties.ipynb) | Set project title, company, units, and thermal parameters |
| 02 | [`02_define_boreholes_and_soil_layers.ipynb`](02_define_boreholes_and_soil_layers.ipynb) | Define boreholes, water head, and soil stratigraphy |

---

## 🔧 Requirements

To run the notebooks, ensure the following:

- **PLAXIS 3D** is installed and running
- The **Remote Scripting Server** in PLAXIS is enabled on `localhost:10000`
- A `.env` file is present with your connection settings (see below)
- Python packages: `plxscripting`, `python-dotenv`, `jupyter`

### 📦 Recommended `.env` file

```env
PLAXIS_HOST=localhost
PLAXIS_PORT=10000
PLAXIS_PASSWORD=your_plaxis_password
````

> Don’t commit your `.env` file — use `.env.example` instead.

---

## ▶️ Running the Notebooks

1. Open a terminal and activate the PLAXIS Python interpreter
2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
3. Open any notebook in this repo to explore, modify, and run the automation steps

---

## 📁 Folder Structure

```
plaxis3d-automation/
├── 00_connect_to_plaxis3d.ipynb
├── 01_set_project_properties.ipynb
├── 02_define_boreholes_and_soil_layers.ipynb
├── images/
│   ├── project-properties.png
│   ├── model-properties.png
│   └── modify-soil-layers.png
├── .env.example
├── requirements.txt
└── README.md
```

---

## 👨‍💻 Author

Geotechnical engineer 😊 focused on automation, PLAXIS scripting, and making engineering smarter with Python and machine learning.

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.

```
