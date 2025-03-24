

# 🧬 Clifford Group Equivariant Neural Network Layers for Protein Structure Prediction 🧬

### 🌌 Northern Lights Deep Learning Conference 2024 - Tromsø, Norway 🇳🇴  

**Predicting Protein Structures with Geometric Deep Learning**  

## 🔬 Introduction
We introduce **Clifford Group Equivariant Neural Networks (CGENNs)** for **Protein Structure Prediction (PSP)**, leveraging the power of **Geometric Deep Learning** to enhance the accuracy and robustness of protein coordinate estimation. 

### 🔹 Why CGENNs for PSP? 🤖🧬
- **Proteins are 3D objects!** Conventional PSP methods flatten spatial relationships into machine learning features, losing crucial **geometric** information. 🌀
- **CGENNs understand rotations & translations!** They work in **Geometric Algebra G(3,0,0)**, ensuring predictions are **equivariant** to changes in the reference frame. 🔄
- **Better Generalization & Robustness!** Protein coordinates are **naturally independent** of orientation and position—CGENNs preserve this property. 🎯
- **Fewer Parameters, Higher Accuracy!** CGENNs improve **prediction accuracy by up to 2.1%**, outperforming linear layers while using **fewer trainable parameters**. 📈✨
- **Interpretable Outputs!** All inputs, outputs, weights, and biases exist within a **geometrically meaningful space**. 🔬🔍

---

## 📁 Supplementary Materials 

The folders with data "Output-ALL" (including orientational features) and "DISTANCES" (including distance maps) are available upon request to the authors.
The code can run also by commenting out the lines where you're reading data from those two folders. 

---

## 📖 Citation 📚
If you find this work useful, please cite:

```bibtex
@inproceedings{pepe2024clifford,
  title={Clifford group equivariant neural network layers for protein structure prediction},
  author={Pepe, Alberto and Buchholz, Sven and Lasenby, Joan},
  booktitle={Northern Lights Deep Learning Conference},
  pages={205--211},
  year={2024},
  organization={PMLR}
}
```

---

🔬 **CGENNs bring a a fresh approach to geometry-aware deep learning for protein structure prediction** 🧬
