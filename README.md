# CricketStatsPCAInference  
Created by **Jason Abi Chebli**  
© 2025 Jason Abi Chebli. All rights reserved.

## Description  
<div style="text-align: justify;">This project investigates batting and bowling performance in England Women’s T20 cricket through Principal Component Analysis (PCA), bootstrapping, and permutation testing. Using data from the <code>cricketdata</code> package, the project reduces dimensionality, visualises player clustering and variable contributions, and statistically tests key relationships using resampling-based inference techniques.</div>

## Demo  
You can explore the analysis conducted [here](https://jabichebli.github.io/CricketStatsPCAInference/report/index.html).

## Dataset  
- File: `engwt20.csv`  
- Region: England  
- Format: Player-season level summary  
- Statistics: Batting, bowling, and performance metrics across international T20 matches  

## Objectives  
- Select and prepare appropriate variables for PCA  
- Apply and interpret Principal Component Analysis (PCA)  
- Visualise PCA with scree plots and biplots  
- Identify which statistics contribute most to PC1 and PC2 using bootstrapping  
- Test correlations between batting and bowling performance using permutation tests  
- Provide concise interpretations with numerical and graphical summaries  

## Key Methods  
- Dimensionality Reduction: PCA using scaled numerical features  
- Bootstrapping: Resample PCA loadings to assess variable influence on PC1 & PC2  
- Permutation Testing:  
  - `RunsScored` vs `HighScore`  
  - `RunsScored` vs `RunsConceeded`  
- Visualisation: Scree plot, biplot, violin plots, correlation histograms  

## Files  
>[CricketStatsPCAInference.qmd](CricketStatsPCAInference.qmd) — Quarto file containing full analysis, PCA, bootstrap, and permutation testing  
>[index.html](report/index.html) — Rendered output for easy viewing  
>[engwt20.csv](engwt20.csv) — Dataset containing England Women’s T20 cricket statistics  

## Visual Highlights  
- Scree plot of explained variance  
- Biplot illustrating player clustering and variable directions  
- Bootstrapped loadings distributions for PC1 and PC2  
- Permutation-based null distributions and observed test statistics  
- Interpretation of key player performances via principal components  

## Feedback  
If you have questions, suggestions, or feedback on this analysis, feel free to [contact me](https://jabichebli.github.io/jabichebli/contact/). Your input is welcome and appreciated.
