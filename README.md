# Advanced Statistics Project

**MSc Data Science Coursework**  
*University of the West of England | Spring 2025*

## What This Project Is About

This was my final assessment for the Advanced Statistics module of my MSc in Data Science. The goal was to dive deep into both supervised and unsupervised learning methods, apply them to a real dataset, and write up the findings in academic style.

**[→ See the complete analysis and results here](./report.pdf)**

It was actually my first time working extensively with R (the module required it), and I really enjoyed the challenge of transferring my Python skills to a new language while tackling the subject matter.

## What I Built

### The Analysis Pipeline
- **Data preprocessing and cleaning** - Getting messy real-world data into shape
- **Exploratory data analysis** - Understanding what we're working with
- **Multiple modeling approaches** - Comparing different statistical methods
- **Validation and comparison** - Making sure the results actually mean something

### Methods I Implemented
- **Logistic Regression** with feature selection
- **Random Forest** with hyperparameter tuning and regularization
- **Support Vector Machines** with hyperparameter/kernel tuning
- **Hierarchical Clustering** to attempt to find natural groupings
- **Model-Based Clustering** using Gaussian mixtures
- **Bootstrap Sampling** for robust confidence intervals
- **Factor Analysis and PCA** for dimensionality reduction

## Repository Structure

The project is split into separate Quarto documents for the initial exploration of each problem. Then, the final solutions are implemented in the report quarto file for presentation

```
├── report.pdf                      # Final submitted report
├── report.qmd                      # Main report source
├── Data(2).csv                     # Raw dataset
├── data_clean.csv                  # Cleaned dataset
├── bootstrap_data.csv              # oversampled dataset produced using bootstrapping
├── preprocessing.qmd             
├── eda.qmd                      
├── logistic_regression.qmd      
├── random_forest.qmd            
├── svm.qmd                      
├── agg_hierarchical_clustering.qmd 
├── model_based_clustering.qmd   
├── bootstrap.qmd                
└── ...                             # files like the cached report results and figures, references and citation info                     
```

## What I Learned

This project really pushed me to think systematically about statistical analysis - not just throwing algorithms at data, but understanding and justifying when and why to use different approaches. The requirement to write everything up as a formal academic report also taught me a lot about communicating statistical findings clearly - quarto is definitly a tool i'm going to be using more in future.

I thought the R requirement would be really challenging because I would be learning a new programming language while alongside implementing the theoretical statistics, but I was able to transfer my programming fundementals from my experience with python, and ended up enjoying the extra layer of challenge.

## Technical Details

- **Language**: R with RStudio
- **Documentation**: Quarto for reproducible analysis
- **Key Libraries**: tidyverse, caret, randomForest, e1071, cluster
- **Output**: Academic-style report with full methodology and results

## Running the Code

Each `.qmd` file can be run independently, though main `report.qmd` pulls everything together into the final document and contains all the code needed to produce the final analysis and can be run without the other files. Some of the notebooks do contain extra exploration that lead to choices that were made with the direction of the project. 

To run the code, you will need R installed, and to render the final report you will need quarto installed. 

---

*Part of my MSc Data Science portfolio at University of the West of England*