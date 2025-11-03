# 🖼️ Image Compression using SVD (Singular Value Decomposition)

This project applies **Singular Value Decomposition (SVD)** to compress grayscale images by approximating them with low-rank matrices. By keeping only the top *k* singular values, the image can be reconstructed with significantly less data while preserving most of the visual quality.

The project includes:
- Conversion of images to grayscale matrices using OpenCV  
- SVD-based rank-*k* reconstruction using NumPy  
- Storage comparison – original vs. compressed (`k(m + n + 1)` entries)  
- Examples at **100-rank (~14.6% data)** and **3% storage reconstruction (k ≈ 21)**  
- Side-by-side visualization using Matplotlib

---

## Tech Stack

- **Python**, **NumPy**, **OpenCV**, **Matplotlib**
- Linear Algebra concepts: **Matrix Factorization, SVD, Rank-k Approximation**
