# Monte Carlo Simulation and Sensitivity Analysis for Financial Risk Management

![image](https://github.com/user-attachments/assets/2baaf5f4-824d-458d-9d26-65fab90f50f0) ![image](https://github.com/user-attachments/assets/3d55a11b-7ea9-4736-be56-05f5fd16dde8)



## Overview
This project applies Monte Carlo Simulation and Sensitivity Analysis to financial risk management using Excel. The Monte Carlo method is used to generate random data based on different price assumptions (pessimistic, most likely, and optimistic) to analyze financial risk. Sensitivity Analysis is also performed to assess the impact of various factors on financial outcomes.

## Features
- **Monte Carlo Simulation:** Generates random data based on pessimistic, most likely, and optimistic price scenarios to model risk.
- **Sensitivity Analysis:** Evaluates how changes in key input variables affect financial risk and outcomes.
- **Data Visualization:** Graphical representation of risk distributions and sensitivity results using Excel charts.
- **Excel Implementation:** Uses Excel formulas and VBA for simulation and analysis.

## Installation
To use this project:

1. Download the Excel file from the repository.
2. Open the file in Microsoft Excel (2016 or later recommended).
3. Enable macros if using the VBA version.

## Usage
### Running Monte Carlo Simulation
1. Open the Excel file.
2. Input pessimistic, most likely, and optimistic price values.
3. Click the **Run Simulation** button (if VBA macros are enabled) or use Excel functions to generate random values.
4. View the results in the probability distribution and summary statistics tables.

### Running Sensitivity Analysis
1. Identify key financial variables in the Excel sheet.
2. Modify these variables systematically to observe their impact.
3. Use Excel’s Data Table feature or built-in formulas to analyze sensitivity.
4. Visualize results using Excel charts and pivot tables.

## Methodology
### Monte Carlo Simulation
1. Define pessimistic, most likely, and optimistic price assumptions.
2. Use Excel’s `RAND()` or `RANDBETWEEN()` functions to generate random values following a probability distribution (e.g., triangular or normal distribution).
3. Simulate multiple iterations using Data Tables or VBA macros.
4. Visualize results using histograms and probability distributions.

### Sensitivity Analysis
1. Identify key financial variables.
2. Systematically vary these inputs using Excel’s scenario manager or Data Table feature.
3. Use sensitivity charts and correlation analysis to interpret the impact.

## Example Results
- Probability distribution of financial outcomes
- Risk quantification based on different price assumptions
- Sensitivity analysis plots showing the effect of variable changes

## Dependencies
- Microsoft Excel 2016 or later
- VBA (optional for automated simulations)

## Contributing
Contributions are welcome! Please submit a pull request or open an issue if you find any bugs or have suggestions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
Rahul Dasari - dasarirahulpatel.drp@gmail.com

## Acknowledgments
- Financial risk modeling concepts from various academic and industry sources.
- Excel’s powerful data analysis and visualization capabilities.

