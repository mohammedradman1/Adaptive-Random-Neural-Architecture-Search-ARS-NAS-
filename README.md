# Adaptive Random Neural Architecture Search (ARS-NAS):-
**Adaptive Random Neural Architecture Search (ARS-NAS)** is a novel approach for efficiently exploring deep neural network architectures. It **adapts sampling probabilities** based on previous trial performance, striking a balance between **exploration** and **exploitation** to achieve competitive accuracy with reduced search cost.

📄 **Publication:** [IEEE ICICS 2025 – ARS-NAS](https://ieeexplore.ieee.org/abstract/document/11073105)  
🗂 **Code:** Includes experiments for **CIFAR-10**, **MNIST**, and **Fashion-MNIST**.

---

# 🧭 Overview:-
**Neural Architecture Search (NAS)** automates model design but often suffers from **high computational cost**.  
**ARS-NAS** improves efficiency by:  
- 🔄 **Dynamically adapting** the search space probabilities  
- 📊 **Using feedback** from intermediate evaluations  
- 🚫 **Reducing redundant** model trials  

We compare ⚡ **ARS-NAS** against:  
- 📋 **Grid Search**  
- 🎲 **Random Search**  

---

# 📦 Dataset:-
Experiments were conducted on:  
- 🖼 **CIFAR-10** — 60,000 32×32 RGB images, 10 classes  
- ✍️ **MNIST** — 70,000 28×28 grayscale digit images, 10 classes  
- 👕 **Fashion-MNIST** — 70,000 28×28 grayscale fashion item images, 10 classes

---
# ✨ Key Features:-
- 🚀 **Adaptive Search** that balances exploration and exploitation
- 📊 **Multi-dataset evaluation** (CIFAR-10, MNIST, Fashion-MNIST)
- ⏱ **Reduced computational cost** compared to grid/random search
- 📈 **Reproducible experiments** with shared code and configs

--- 
# 🛠 Preliminary Requirements:-
- 🐍 Python **3.10+**
- 📦 Install dependencies:
```bash
pip install numpy pandas scikit-learn torch torchvision matplotlib
```

---
# ▶️ How to Run:-
Open the desired notebook:
```bash
jupyter notebook "ARS-NAS for CIFAR-10.ipynb"
```

# 📚 Citation:-
If you use ARS-NAS, please cite:
```bibtex
@INPROCEEDINGS{11073105,
  author={AL-Matari, Mohammed R. and Mustafa, Ahmad M.},
  booktitle={2025 16th International Conference on Information and Communication Systems (ICICS)}, 
  title={Adaptive Random Neural Architecture Search}, 
  year={2025},
  volume={},
  number={},
  pages={1-6},
  keywords={Adaptation models;Accuracy;Neurons;Computer architecture;Search problems;Natural language processing;Neural architecture search;Reliability;Optimization;Biological neural networks;Deep Learning;Optimization;Automated Search;Search Space;Network Structure;Performance},
  doi={10.1109/ICICS65354.2025.11073105}}
```


---

## **# 📬 Contact:-**  
**LinkedIn:** [linkedin.com/in/mrm1](https://www.linkedin.com/in/mrm1/)  
