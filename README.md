# Intraocular Pressure (IOP) Data Analyzer

A Python-based tool to upload, analyze, and visualize intraocular pressure (IOP) measurements over time.  
This project is designed to help healthcare professionals, researchers, and students easily detect trends in eye pressure data, which can be useful in glaucoma management and patient monitoring.

---

## Features
- **CSV Upload**: Import your own IOP dataset for analysis.
- **Summary Statistics**: Automatically calculates mean, median, min, and max IOP.
- **Trend Visualization**: Generates line plots to show pressure changes over time.
- **Glaucoma Risk Highlight**: Flags potential high IOP values (>21 mmHg) in the dataset.
- **Customizable**: Modify thresholds, labels, and styles to suit your needs.

---

## Example Use Case
A glaucoma clinic can use this tool to:
- Track each patient’s IOP history over multiple visits.
- Identify abnormal spikes in pressure.
- Export and share plots for electronic medical records.

---

## How It Works
1. The script prompts you to upload your IOP CSV file.
2. Data is read into a Pandas DataFrame.
3. The program calculates summary statistics.
4. A plot is generated showing changes in IOP over time, highlighting risky values.

---

## Sample Dataset Format
| Date       | Eye  | IOP  |
|------------|------|------|
| 2025-01-10 | OD   | 18   |
| 2025-02-15 | OS   | 22   |
| 2025-03-20 | OD   | 20   |

**Notes**:
- **Date**: Format `YYYY-MM-DD`
- **Eye**: OD (right) or OS (left)
- **IOP**: Pressure in mmHg

---

## Installation & Requirements
**Python Libraries Used**:
- pandas
- matplotlib

Install with:
```bash
pip install pandas matplotlib
```

---

## Usage
1. Run the Python script.
2. When prompted, upload your CSV file.
3. View the printed summary statistics.
4. The IOP trend plot will automatically appear.

---

## Example Output
- **Summary Statistics**: Mean, min, max, and median IOP
- **Line Plot**: Shows IOP changes over time, with high readings in red

---

## Author
**David Amagyei-Antwi**  
Graduate Student in Biotechnology | Optometrist | Aspiring Vision Science Researcher

---

## License
This project is open-source and available under the MIT License.

