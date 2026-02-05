#Riksmaten_UPF

This repository contains analytic scripts used to characterize the intake of Ultra-processed food in the Swedish national dietary surveys Riksmaten, stratified by adults (Vuxna), adolescents (Ungdom) and young children (Småbarn).

##Repository structure

-`scripts/`
Quarto (.qmd) scripts for data processing and analysis.

-`data/`
Placeholder directory. Raw data are sensitive and not included in this repository.

-`output/`
Generated tables and figures (not tracked in version control).

##Data availability

The raw dietary intake data for Riksmaten Vuxna and Riksmaten Ungdom is available via the Swedish Food Authority's webside. Data for Riksmaten Young Children may be made available by the data owner upon reasonable request.

The file `data/Food_items.xlsx`is included and contains non-sensitive classification information used by the scripts. 

##License
This project is licensed under the MIT License.

##How to run the code

1. Open the R project (`Riksmaten_UPF.Rproj`) in RStudio.
2. Run the scripts in the `scripts/`directory in the intended order.
3. Outputs will be written to the òutput/`directory.

##Notes
All file paths are relative to the project root to ensure portability. 
