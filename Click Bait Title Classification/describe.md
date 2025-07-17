# Clickbait Detection NLP Model

## 📰 Project Overview
This repository contains an NLP model for detecting clickbait headlines in online news media, implementing techniques from the seminal paper:  
**["Stop Clickbait: Detecting and Preventing Clickbait in Online News Media"](https://arxiv.org/pdf/1610.09786)**  
*by Chakraborty et al. (2016)*

## 🗃️ Dataset Composition
### Non-Clickbait Sources
- **18,513** Wikinews articles (from Newsreader project)
- Headlines extracted as genuine news examples

### Clickbait Sources
- **8,069** articles crawled from known clickbait domains:
  - `BuzzFeed` 
  - `Upworthy`
  - `ViralNova`
  - `Scoopwhoop`
  - `ViralStories`
- Collected during September 2015

### Technical Approaches
- Deep Learning (LSTMs,GRU)
- Google USE for transfer learning 
