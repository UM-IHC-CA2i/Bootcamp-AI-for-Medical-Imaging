# Bootcamp: AI for Medical Imaging

Starter notebooks and data for the **Research Track** of the AI-Ready Radiology Curriculum.

## Repository structure

```
data/
  radiology_ai_findings.csv    — Dataset of 60 radiology studies
lesson-notebooks/
  Research_Module_1.ipynb      — Python basics and data exploration
  Research_Module_2.ipynb      — Evaluation metrics, ROC curves, subgroup analysis
  Research_Module_3.ipynb      — Machine learning and image processing
  Research_Module_4.ipynb      — Advanced image AI and NLP
  Research_Module_5.ipynb      — Mini research project
README.md
```

## Getting started

1. **Fork** this repository (click the "Fork" button in the top right)
2. Open the notebook in Google Colab:
   - Go to [colab.research.google.com](https://colab.research.google.com)
   - Click **Open notebook**
   - Select the **GitHub** tab
   - Paste your fork URL (e.g., `https://github.com/YOUR-USERNAME/Bootcamp-AI-for-Medical-Imaging`)
   - Click the notebook you want to open (e.g., `lesson-notebooks/Research_Module_1.ipynb`)
3. In the notebook, replace `YOUR-USERNAME` with your GitHub username in the data loading cell
4. Follow the instructions in the notebook

## How to submit your work

After completing each module:
1. In Colab, go to **File > Download > Download .ipynb**
2. Go to your fork on GitHub (e.g., `https://github.com/YOUR-USERNAME/Bootcamp-AI-for-Medical-Imaging`)
3. Click the **Code** tab
4. Click **Add file > Upload files**
5. Drag and drop your downloaded `.ipynb` file
6. Type a commit message (e.g., `Completed Research Module 1`)
7. Make sure "Commit directly to the main branch" is selected
8. Click **Commit changes**

After all modules are complete:
1. On your fork's main page, click **Contribute**
2. Click **Open pull request**
3. Add a title and click **Create pull request**

To withdraw your submission, close the pull request from the same page.

## Dataset description

`data/radiology_ai_findings.csv` contains 60 anonymized radiology studies across 4 imaging modalities (CR, CT, MR, US) and 7 body regions. Each study records whether an AI tool flagged a finding, the AI's confidence score, and whether a radiologist confirmed the finding.

This data is synthetic and designed for educational purposes.
