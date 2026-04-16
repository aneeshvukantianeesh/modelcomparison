 #  Model Comparison Analysis

## Overview

This project evaluates two different approaches for generating professional emails:

* **Model A (Baseline Email Generator)**
* **Model B (Structured Email Generator)**

The goal is to determine which model produces higher quality outputs using custom evaluation metrics.

---

##  Objective

To compare two models using the same 10 test scenarios and evaluate their performance based on defined metrics.

---

##  Models

### Model A – Baseline

* Generates short and simple responses
* Minimal formatting
* Lacks professional structure

### Model B – Structured Generator

* Produces complete email format
* Includes subject, greeting, body, and closing
* Maintains professional tone

---

##  Evaluation Metrics

1. **Length Score**
   Measures response completeness and detail.

2. **Structure Score**
   Checks presence of key email components (Subject, Greeting, Closing).

3. **Clarity Score**
   Evaluates readability based on sentence structure.

---

##  Results

| Metric    | Model A  | Model B   |
| --------- | -------- | --------- |
| Length    | Low      | High      |
| Structure | Poor     | Excellent |
| Clarity   | Moderate | High      |

---

##  Visualization

The comparison graph (`model_comparison_graph.png`) shows a clear performance improvement of Model B over Model A.

---

## Conclusion

Model B significantly outperforms Model A across all metrics.
It is recommended for production usage due to:

* Better structure
* Higher clarity
* Professional formatting

---

##  How to Run

1. Open the Jupyter Notebook
2. Run all cells
3. Outputs generated:

   * CSV file
   * JSON file
   * Graph image

---

##  Outputs

* `final_model_comparison.csv`
* `final_model_comparison.json`
* `model_comparison_graph.png`

---
