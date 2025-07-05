---

````markdown
# Liquefaction LPI and LSN Calculator

This project provides a standalone desktop application for calculating **Liquefaction Potential Index (LPI)** and **Liquefaction Severity Number (LSN)** based on geotechnical data such as SPT, CPT, and site-specific parameters.

It is designed for geotechnical engineers, researchers, and students to streamline the assessment of soil liquefaction potential in seismic-prone regions. The app is built with **PyQt6** and packaged as an executable for easy deployment.

---

## 🛠️ Features

- Interactive GUI for entering or importing borehole data
- Automatic computation of:
  - Cyclic Stress Ratio (CSR)
  - Cyclic Resistance Ratio (CRR)
  - Factor of Safety (FS)
  - Liquefaction Potential Index (LPI)
  - Liquefaction Severity Number (LSN)
- Exportable results in CSV or Excel format
- Supports unit conversion and error handling

---

## 📷 Screenshot

![App Screenshot](./assets/screenshot.png)

---

## 🚀 Installation

You can either clone and run the script manually, or download the standalone `.exe` file from the [Releases](../../releases) page (Windows only).

### Running from source:

```bash
git clone https://github.com/your-username/liquefaction-lpi-lsn.git
cd liquefaction-lpi-lsn
pip install -r requirements.txt
python main.py
````

---

## 📂 Directory Structure

```
.
├── main.py
├── ui/
│   └── liquefaction_gui.ui
├── modules/
│   └── lpi_calculations.py
├── assets/
│   └── screenshot.png
├── requirements.txt
└── README.md
```

---

## 🧪 Example Input Parameters

* SPT N-values
* Depth (m)
* Groundwater Table (GWT)
* PGA (Peak Ground Acceleration)
* Fines Content (%)
* Unit Weight (kN/m³)

---

## 👥 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:

   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:

   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## 📜 License

This project is licensed under the **Creative Commons Zero v1.0 Universal (CC0-1.0)** license.
Feel free to use, modify, and distribute the code without restriction. See [LICENSE](./LICENSE) for more.

---

## 🙏 Acknowledgments

Special thanks to the geotechnical engineering and data science communities for their contributions to soil behavior research, liquefaction assessment methods, and machine learning innovations in civil engineering.

---

## 📬 Contact

For questions, feedback, or contributions, contact: **[rhudwill@gmail.com](mailto:rhudwill@gmail.com)**

```

---
