# circular-acrophase-plot

This R script visualizes time-of-day data (acrophase) using circular statistics. It plots a 24-hour circular graph of hormone rhythms (e.g., cortisol) and calculates the circular mean and variance of the dataset.

Files Included
R Script: `circular_plot.R`
Example data: `example_hormone_acrophase_data.csv`
Example output file: `output_plot.jpeg`

How to Use

1. Install required R packages:

```r
install.packages(c("circular", "dplyr"))
```

2. Run the script

3. Customize parameters inside the script

4. Export the created graph
---

Output

The script generates:
- A circular plot showing individual data points
- Optional arrow indicating the **circular mean direction**
- An optional legend displaying mean and variance
- An optional summary statistics table (viewed in R)

---

Contribution & Integrity

This repository is intended for reproducible analysis and educational use.  
Please do not modify the `main` branch directly.  
If you would like to suggest improvements, feel free to submit a pull request or open an issue.


Related Resources

- [circular R package documentation]([https://cran.r-project.org/web/packages/circular/](https://cran.r-project.org/web/packages/circular/circular.pdf) 
- [protocols.io version of this workflow](https://www.protocols.io/) 


Author

Taha Yildirim
M.A Candidate, Cognitive & Neural Sciences (CNS) | Psychology
Lab Coordinator | Translational Neuroscience Lab 
Simon Fraser University
8888 University Dr., Burnaby, B.C. V5A 1S6
