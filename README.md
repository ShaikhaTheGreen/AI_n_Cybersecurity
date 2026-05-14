
# AI and Cybersecurity Repository

Welcome to the **AI and Cybersecurity** repository! This project explores the intersection of artificial intelligence and cybersecurity through practical examples, simulations, and analyses. By following these steps, you can run the provided examples using Google Colab.

---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Prerequisites](#prerequisites)
3. [Getting Started](#getting-started)
4. [Running the Examples in Google Colab](#running-the-examples-in-google-colab)
5. [Folder Structure](#folder-structure)
6. [Contributing](#contributing)
7. [License](#license)

---

## About the Project

This repository demonstrates how AI models can enhance cybersecurity efforts, including:

- Phishing detection
- Network anomaly detection
- Real-time threat monitoring

The examples utilize Jupyter notebooks and Python scripts with preprocessed datasets to showcase these applications.

---

## Prerequisites

To follow along, you need:

1. A Google account to access [Google Colab](https://colab.research.google.com/).
2. Basic familiarity with Python and machine learning concepts.
3. An internet connection to download datasets and run cloud-based notebooks.

---

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ShaikhaTheGreen/AI_n_Cybersecurity.git
   ```

2. **Explore the Content**:
   Open any of the `.ipynb` files at the repository root to browse the notebooks. Supporting CSV data lives in [`datasets/`](datasets/).

---

## Running the Examples in Google Colab

You can run all the examples on Google Colab without needing to set up a local Python environment. Follow these steps:

### Step 1: Open the Notebook in Google Colab

1. From the repository root, click any `.ipynb` file you wish to run:
   - [`Phishing_Detection_Simulation.ipynb`](Phishing_Detection_Simulation.ipynb)
   - [`Network_Traffic_for_Anomaly_Detection.ipynb`](Network_Traffic_for_Anomaly_Detection.ipynb)
   - [`Real_Time_Network_Threat_Detection.ipynb`](Real_Time_Network_Threat_Detection.ipynb)
2. In the GitHub preview, click the **"Open in Colab"** button at the top (or copy the notebook URL and open it directly in [Google Colab](https://colab.research.google.com/)).

### Step 2: Connect to Google Colab Runtime

1. Click **"Connect"** in the top-right corner of the Colab interface to connect to a free GPU/CPU runtime.
2. Verify that the runtime is active by checking the status indicator.

### Step 3: Install Dependencies

Each notebook installs its own dependencies in the first cell using `!pip install` — typically `pandas`, `scikit-learn`, `numpy`, and `matplotlib`. Just run the first cell.

### Step 4: Download Datasets

Datasets are hosted in the `datasets` folder. Use the `wget` or `gdown` command to download them into your Colab environment. Example:
```python
!wget https://raw.githubusercontent.com/ShaikhaTheGreen/AI_n_Cybersecurity/main/datasets/network_traffic.csv
```

### Step 5: Execute the Code

Run each cell in the notebook sequentially to:

- Preprocess the data.
- Train AI models.
- Visualize the results.

### Step 6: Save Your Work

Save the notebook and results back to your Google Drive or local machine as needed.

---

## Folder Structure

```plaintext
AI_n_Cybersecurity/
├── Phishing_Detection_Simulation.ipynb         # Logistic regression on labeled emails
├── Network_Traffic_for_Anomaly_Detection.ipynb # Anomaly detection on flow records
├── Real_Time_Network_Threat_Detection.ipynb    # Streaming threat detection demo
├── datasets/                                   # CSV datasets for the notebooks above
│   ├── emails_dataset.csv
│   ├── network_traffic.csv
│   └── real_time_traffic.csv
├── README.md
├── LICENSE
├── CONTRIBUTING.md
└── CODE_OF_CONDUCT.md
```

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author

**Dr. Shaikhah Alkhadhr** — Assistant Professor, Department of Information Science, Kuwait University. Ph.D. in Computer Science and Engineering, Penn State (2023). Research at the intersection of AI safety, AI for cybersecurity, and scientific machine learning.

- Personal site: <https://shaikhathegreen.github.io>
- KU faculty page: <https://www.ku.edu.kw/user/2227>
- ORCID: [0000-0001-5938-2953](https://orcid.org/0000-0001-5938-2953)
- More work: [HybridGuard](https://github.com/ShaikhaTheGreen/HybridGuard) · [Device-Anatomy](https://github.com/ShaikhaTheGreen/Device-Anatomy)
