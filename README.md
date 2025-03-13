# Computational Statistics Course Repository

## 📚 Project Overview
This repository contains practice exercises and simulations from the **Computational Statistics** course. Each notebook demonstrates key statistical methods through practical examples, visualizations, and step-by-step implementations. The focus is on understanding fundamental statistical concepts and computational techniques through simulations and sampling methods.

---

## 📁 Topics Covered

1. **Central Limit Theorem**
   - Demonstrates the concept of the **Central Limit Theorem (CLT)** using simulations.
   - Visualizes how sample means approximate a normal distribution, regardless of the original population distribution.

2. **Inverse Transformation Method**
   - Explains the method for generating random variables from any distribution using the **inverse of the cumulative distribution function (CDF)**.
   - Includes simulations for distributions like exponential and uniform.

3. **Acceptance-Rejection Method**
   - Implements the **acceptance-rejection method** for generating samples from complex distributions.
   - Visualizes the acceptance and rejection regions using Python.

4. **Monte Carlo Integration and Importance Sampling**
   - Demonstrates **Monte Carlo integration** techniques for estimating integrals.
   - Explores **importance sampling** for variance reduction.

5. **Markov Chain Monte Carlo (MCMC), Gibbs Sampler, and Metropolis-Hastings (MH)**
   - Provides an in-depth understanding of **MCMC** techniques.
   - Implements **Gibbs Sampling** and **Metropolis-Hastings** algorithms.
   - Visualizes convergence and distribution of samples.

6. **Bootstrap, Jackknife, and Expectation-Maximization (EM)**
   - Introduces **resampling techniques** like bootstrap and jackknife for estimating variance and bias.
   - Demonstrates the **EM algorithm** for parameter estimation.

---

## 📂 Repository Structure

```
Computational-Statistics/
│
├── README.md                     # Overview of the repository
├── LICENSE                       # Open-source license (MIT)
│
├── notebooks/                    # Jupyter Notebooks for each topic
│   ├── 01_Central_Limit_Theorem.ipynb
│   ├── 02_Inverse_Transformation_Method.ipynb
│   ├── 03_Acceptance_Rejection_Method.ipynb
│   ├── 04_Monte_Carlo_Integration.ipynb
│   ├── 05_MCMC_Gibbs_Sampler_MH.ipynb
│   └── 06_Bootstrap_Jackknife_EM.ipynb
│
├── reports/                      # Summary report for all topics (optional)
│   └── Final_Summary_Report.pdf
│
└── scripts/                      # Python scripts for reusable code (optional)
    └── sampling_methods.py
```

---

## ⚙️ How to Run the Notebooks

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/Computational-Statistics.git
cd Computational-Statistics
```

2. **Create a Virtual Environment (Optional)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Required Packages**
*(No specific requirements, but ensure Python 3.x and libraries like `numpy`, `scipy`, and `matplotlib` are installed)*
```bash
pip install numpy scipy matplotlib seaborn
```

4. **Run the Notebooks**
Open the notebooks using Jupyter Lab or Jupyter Notebook:
```bash
jupyter notebook
```

---

## ✅ Key Learning Highlights
- Hands-on understanding of **sampling techniques** and their statistical significance.
- Visualization of key statistical concepts for better interpretation.
- Practical implementations of **MCMC algorithms**, **resampling techniques**, and **Monte Carlo methods**.
- Code-focused approach to bridge theoretical understanding with real-world applications.

---

## 📄 License
This repository is licensed under the **MIT License** - feel free to use, share, and contribute!

---

## 🤝 Contributing
Contributions are welcome! If you have suggestions or additional implementations, feel free to fork this repository and submit a pull request.

---

> 📢 **Note**: This repository is part of a learning exercise in computational statistics. For any feedback, feel free to reach out!

---

Happy Learning! 🚀
