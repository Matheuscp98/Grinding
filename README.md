# ⚙️ Tabular Dataset for Analysis of an Industrial Cylindrical Plunge Grinding Process

**DOI:** [10.5281/zenodo.17873859](https://doi.org/10.5281/zenodo.17873859)

---

## 📝 Description

This repository contains **tabular datasets** generated from an **industrial cylindrical plunge grinding process** used in the **manufacturing of piston rings**.

The dataset was produced through a **Response Surface Methodology (RSM)** design that defined the controlled levels of:

- **Cutting speed**
- **Depth of cut**
- **Feed rate**

A total of **30 experiments** were carried out under **real shop-floor conditions**.  
Each experiment was combined with **four noise configurations**, arising from two external factors:

- **Mandrel type**
- **Ring position** within the production package

For every configuration, **ten repeated dimensional measurements** were collected using the factory’s standard inspection fixture, resulting in **three dimensional output variables**:

- `T1`
- `T2`
- `T3`

All data are stored in [**Griding**](griding.csv), the main dataset of this repository.

The dataset is intended for:

- **Statistical Analysis**
- **Robust Parameter Design**
- **Response Surface Modeling (RSM)**
- **Sensitivity Analysis**
- **Process Optimization**
- **Machine Learning (ML)** applications in manufacturing

> **Note:** The main focus of this repository is the dataset itself.

---

## 📚 Publications

This dataset is part of the research study:

- *Manuscript currently under peer review*

---

## 🛠️ How to Use

1. Clone or download this repository.
2. Open [**Griding**](griding.csv) using:
   - Python (pandas)
   - R
   - MATLAB
   - Excel
   - Google Sheets
3. Use the dataset to analyze:
   - Machining input parameters
   - Noise factors
   - Repeated measurements
   - Dimensional responses (T1, T2, T3)
4. Apply statistical or ML models according to your research objectives.

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| [**README**](README.md) | Documentation of dataset purpose, structure, and usage. |
| [**Griding**](griding.csv) | Main dataset containing machining parameters, noise factors, repeated measurements, and dimensional outputs (T1, T2, T3). |

---

## 📊 Variables

### **Controlled Machining Parameters**
- `Vc` — Cutting speed (m/min)
- `ap` — Depth of cut (mm)
- `fr` — Feed rate (mm/min)

### **Noise Factors**
- `Mandrel` — Mandrel configuration (categorical)
- `Pos` — Ring position inside production package (categorical)

### **Repeated Measurements**
- `M1` to `M10` — Ten repeated dimensional readings per experimental + noise condition

### **Dimensional Output Variables**
- `T1` — Dimensional response 1 (µm)
- `T2` — Dimensional response 2 (µm)
- `T3` — Dimensional response 3 (µm)


## 📜 License

This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).  
See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

<a href="mailto:matheusc_pereira@hotmail.com">
  <img src="https://i.ibb.co/k6Ddn36k/email.png" alt="E-mail" height="60"/>
</a>
<a href="https://www.linkedin.com/in/matheuscostapereira/">
  <img src="https://i.ibb.co/Kx4rZxdr/linkedin.png" alt="LinkedIn" height="60"/>
</a>
<a href="https://scholar.google.com.br/citations?user=1iDBIzYAAAAJ&hl=en-us">
  <img src="https://i.ibb.co/SwsRKK1t/scholar.png" alt="Google Scholar" height="60"/>
</a>
<a href="https://lattes.cnpq.br/7025666927284220">
  <img src="https://i.ibb.co/1fMjS38j/lattes.png" alt="Lattes" height="60"/>
</a>

---

> _Feel free to open issues or PRs, or reach out for collaboration or questions!_
