# Nearest-Neighbor-Search-Methods

This project explores and compares various algorithms for nearest neighbor search using the Adult Income dataset. The goal is to evaluate and benchmark different methods in terms of speed, accuracy, and suitability for different data types.

---

## 📌 Key Findings

* FAISS, HNSW, and Annoy offer scalable, fast approximate search options
* KDTree performs well on small datasets but scales poorly
* HNSW provides strong performance even on high-dimensional data

---

## 📚 Future Work

* Include more datasets to evaluate generalizability
* Evaluate recall\@k and precision\@k
* Add memory usage comparison
* Visualize performance using plots (e.g., seaborn barplots)

---

## 🧠 Author Notes

This project is intended as an educational comparison of nearest neighbor algorithms and trade-offs. It can serve as a starting point for further exploration into approximate nearest neighbor (ANN) methods and large-scale similarity search.

---

## 📎 Requirements

* Python 3.8+
* pandas, numpy, scikit-learn
* faiss-cpu / faiss-gpu
* annoy
* hnswlib
* matplotlib, seaborn (for visualization)

---

## 📂 File Structure

* `NearestNeighborSearchMethods.ipynb` — Main notebook with code and results
* `README.md` — This file
