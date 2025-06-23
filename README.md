# 🌲 Prim's Algorithm MST Visualizer

[![Streamlit Cloud](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-streamlit-cloud-link)

## 🚀 Live Demo
[https://your-streamlit-cloud-link](https://your-streamlit-cloud-link)

---

## 📖 Project Purpose
This project is an interactive web application to visualize **Prim's Algorithm** for finding the Minimum Spanning Tree (MST) of a weighted undirected graph. Built with Python and Streamlit, it allows users to:
- Create and edit graphs interactively
- Watch step-by-step or animated construction of the MST
- See real-time edge selection and MST cost updates

## 🌟 What is Prim's Algorithm?
Prim's Algorithm is a greedy algorithm that finds a minimum spanning tree for a weighted undirected graph. It starts from an arbitrary node and grows the MST by always choosing the minimum-weight edge that connects a visited node to an unvisited node.

**Applications:** Network design, circuit design, clustering, etc.

---

## 🖼️ Screenshots

| Graph Creation | Step-by-Step Visualization |
|---------------|--------------------------|
| ![Graph Creation](assets/graph_creation.png) | ![Step Visualization](assets/step_visualization.png) |

*Replace with your own screenshots or GIFs!*

---

## ⏱️ Complexity
- **Time Complexity:** O(E log V) using a min-heap (priority queue)
- **Space Complexity:** O(V + E) for storing the graph and heap

Where V = number of vertices, E = number of edges.

---

## 🧱 Project Structure
```
.
├── app.py              # Main Streamlit app
├── algorithm.py        # Prim's algorithm implementation
├── utils.py            # Helper functions
├── test_algorithm.py   # Unit tests
├── requirements.txt    # Dependencies
├── README.md           # This file
└── data/               # (Optional) Sample graphs
```

---

## 🛠️ How to Run Locally
1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/prims-alg-visualizer.git
   cd prims-alg-visualizer
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the app:**
   ```bash
   streamlit run app.py
   ```
4. **Run tests:**
   ```bash
   pytest test_algorithm.py
   ```

---

## ☁️ Deploy on Streamlit Cloud
1. Push your code to GitHub
2. Go to [Streamlit Cloud](https://streamlit.io/cloud)
3. Connect your repo and deploy!

---

## 📚 References
- [CLRS: Introduction to Algorithms](https://mitpress.mit.edu/9780262046305/introduction-to-algorithms/)
- [Visualgo: MST](https://visualgo.net/en/mst)
- [NetworkX Documentation](https://networkx.org/)
- [Streamlit Documentation](https://docs.streamlit.io/)

---

## 👨‍💻 Author
Your Name ([GitHub](https://github.com/yourusername)) 