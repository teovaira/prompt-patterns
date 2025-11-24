# Exercise 1: Summarization Pattern

## Objective
Create a reusable prompt for text summarization.

## Weak Prompt
"Summarize this text."

## Refined Pattern
"Summarize the following text in 3 bullet points, focusing on the main arguments and ignoring examples."

## Test Input 1: News Article
**Text**: "Climate scientists have released a new report showing that global temperatures have risen by 1.2 degrees Celsius since pre-industrial times. The report, published in Nature Climate Change, analyzed data from weather stations worldwide. For instance, temperatures in Arctic regions have increased by 3 degrees. The researchers warn that without immediate action, we could see catastrophic changes in weather patterns. Examples include more frequent hurricanes and extended droughts in agricultural regions."

**Output with refined pattern**:
• Global temperatures have increased by 1.2 degrees Celsius since pre-industrial times according to new climate research
• Scientists warn that without immediate action, catastrophic weather pattern changes are inevitable
• The study analyzed worldwide weather station data and was published in Nature Climate Change journal

## Test Input 2: Technical Blog
**Text**: "Machine learning models require careful preprocessing of data to achieve optimal performance. Data cleaning involves removing duplicates, handling missing values, and normalizing features. For example, in a customer dataset, you might remove duplicate email addresses and fill missing age values with median values. Feature scaling ensures all variables contribute equally to model training. Techniques like StandardScaler in Python can normalize data to have zero mean and unit variance."

**Output with refined pattern**:
• Machine learning models need careful data preprocessing to perform optimally
• Data cleaning includes removing duplicates, handling missing values, and normalizing features
• Feature scaling ensures all variables contribute equally during model training

## Analysis
The refined pattern improved clarity by specifying exact output format (3 bullet points), focusing scope (main arguments), and excluding unnecessary details (examples). This makes outputs more consistent and useful across different text types.