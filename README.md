# circular-acrophase-plot

This R script visualizes time-of-day data (acrophase) using circular statistics. It plots a 24-hour circular graph of hormone rhythms (e.g., cortisol) and calculates the circular mean and variance of the dataset.

Files Included
R Script: `circular_plot.R`
Example data: `example_hormone_acrophase_data.csv`
Example output file: `output_plot.jpeg`

How to Use

1. **Install required R packages:**

```r
install.packages(c("circular", "dplyr"))
```

2. **Run the script:**

```r
source("circular_plot.R")
```

3. **Customize parameters inside the script:**
- `columnParameter`: Selects the data column (e.g., 2)
- `myTitle`: Title of your plot
- `colGraph`: Point/arrow color
- `circMeanArrowBool`: Show/hide mean vector arrow (TRUE/FALSE)

---

## 📊 Output

The script generates:
- A circular plot showing individual data points
- Optional arrow indicating the **circular mean direction**
- A legend displaying mean and variance
- A summary statistics table (viewed in R)

---

## 📎 Example Use Case

This tool is useful in:
- Chronobiology studies
- Hormone or sleep rhythm analysis
- Visualization of phase-timed biological signals (e.g., gene expression peaks)

---

## 🔒 Contribution & Integrity

This repository is intended for **reproducible analysis and educational use**.  
Please do not modify the `main` branch directly.  
If you'd like to suggest improvements, feel free to submit a **pull request** or open an **issue**.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, share, and modify with attribution.

---

## 🌐 Related Resources

- [circular R package documentation](https://cran.r-project.org/web/packages/circular/index.html)
- [protocols.io version of this workflow](https://www.protocols.io/) *(link when ready)*

---

## 🙋‍♂️ Author

**Taha Yildirim**  
Simon Fraser University  
