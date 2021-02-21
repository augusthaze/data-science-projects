## Outline
1. Prepare data
- Open files, look into data
- Calculate recovery feature by hand, check rougher.output.recovery feature
- Analyze features not available in the test set
- Data preprocessing
2. Analyze data
- Concentrations of metals at different stages of purification
- Feed particle size distributions in training and test sets
- Total concentrations of all substances at different stages
3. Build model
- Write function to calculate final sMAPE value
- Train models, evaluate using cross-validation
- Pick the best model, test using test sample
4. Conclusion

## Objective

Build a machine learning model for Zyfra to optimize production of gold and eliminate unprofitable parameters. Final model will predict the amount of gold recovered from gold ore.
