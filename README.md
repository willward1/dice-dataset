# 🎲 DICE 2.0 Training Dataset

Automatically generated dataset from [realdice.org](https://realdice.org)

## 🔒 Security

This repository is **protected**:
- ✅ Read-only for public
- ✅ Only authorized tokens can write
- ✅ No public PRs or issues

## 📊 Structure

```
correct/      # Images where model prediction was correct
incorrect/    # Images where model prediction was wrong (needs relabeling)
metadata/     # JSON files with prediction details
```

## 🤖 How It's Built

1. Users roll dice on realdice.org
2. AI model makes prediction with confidence score
3. Community votes if prediction is correct/incorrect
4. Images automatically saved here via Netlify Functions

## 📈 Current Stats

- Total votes: 0
- Correct predictions: 0
- Incorrect predictions: 0
- Model accuracy: 0%

## 🎯 Purpose

Building a crowdsourced dataset for training DICE 2.0:
- Real-world dice images in various lighting conditions
- Community-validated labels
- Continuous improvement through voting feedback

## 🔐 Access

- **Public viewing**: Anyone can see and download the dataset
- **Writing**: Only authorized via Netlify Functions + GitHub token
- **No direct commits**: Protected from spam and unauthorized changes