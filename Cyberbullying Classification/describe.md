# Cyberbullying Text Classification Project

## 🌐 Project Overview
As social media becomes ubiquitous across all age groups, cyberbullying has emerged as a critical societal issue with severe psychological impacts.
This project tackles cyberbullying detection through machine learning, analyzing over **47,000 labeled tweets** to identify different types of online harassment.

## 🗂 Dataset Information
### Content
- **Source:** Twitter (tweets)
- **Size:** 47,000+ samples
- **Balance:** ~8,000 samples per class
- **Classes:**
  - `Age`-based bullying
  - `Ethnicity`-based bullying
  - `Gender`-based bullying
  - `Religion`-based bullying
  - `Other` cyberbullying
  - `Not cyberbullying`

### Format
- CSV file containing:
  - Text content
  - Cyberbullying category
 
## ⚠️ Content Warning
The dataset contains **sensitive material** - tweets either describing bullying events or containing offensive content. Please:
- Review only what you're comfortable with

## 🛠️ Technical Implementation
### Approaches
1. **Traditional ML** (MultinomialNB)
2. **Deep Learning** (LSTMs, Conv1D)
3. **Pretrained Models** (SBERT, Google USE)

### Evaluation Metrics
- Accuracy
