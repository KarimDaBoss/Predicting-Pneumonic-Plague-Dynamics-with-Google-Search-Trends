<a name="readme-top"></a>

<!--
!!! IMPORTANT !!!
This README is an example of how you could professionally present your codebase. 
Writing documentation is a crucial part of your work as a professional software developer and cannot be ignored. 

You should modify this file to match your project and remove sections that don't apply.

REQUIRED SECTIONS:
- Table of Contents
- About the Project
  - Built With
  - Live Demo
- Getting Started
- Authors
- Future Features
- Contributing
- Show your support
- Acknowledgements
- License

OPTIONAL SECTIONS:
- FAQ

After you're finished please remove all the comments and instructions!

For more information on the importance of a professional README for your repositories: https://github.com/microverseinc/curriculum-transversal-skills/blob/main/documentation/articles/readme_best_practices.md
-->

<div align="center">

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 Predicting Pneumonic Plague Dynamics with Google Search Trends](#about-project)
    - This Python project combines weekly epidemiological case counts of pneumonic plague in Madagascar (Aug–Nov 2017) with Google Trends data for related search terms to explore how online interest tracks—and even predicts—disease spread ​. It uses pandas and numpy to clean and merge time series, matplotlib/seaborn for visualization, and scikit‑learn to build and evaluate both univariate and multivariate linear regression models based on search‑term volumes and lagged case data. Through correlation analyses, error‑metric comparisons, and reflective discussion on public‑health applications and ethical considerations, the work demonstrates the power—and the pitfalls—of digital surveillance in informing outbreak response.
  - [🛠 PYTHON](#built-with)
    - [Python 3.x
    - `pandas` – data manipulation and analysis
    - `numpy` – numerical operations
    - `matplotlib / seaborn` – data visualization
    - `scikit-learn` – regression modeling and metrics
    - Jupyter Notebook – exploratory analysis and reporting]
  - [Key Features](#key-features)
     - Time‑Series Integration & Visualization
          - Combines weekly pneumonic plague case counts with Google Trends search‑volume data and produces line plots to visualize outbreak dynamics alongside public interest.
     - Predictive Regression Modeling
          - Implements both univariate and multivariate linear regressions using (a) search‑term volumes and (b) lagged epidemiological case counts, then evaluates each model’s predictive power via correlation and mean absolute error metrics ​

     - Public‑Health Synthesis & Ethical Reflection
          - Interprets model results for practical decision‑making (e.g., early warning systems), discusses real‑world applications (media monitoring, outbreak response), and addresses ethical concerns around data privacy and representativeness 
- [💻 Getting Started](#getting-started)
    - To get a local copy up and running, follow these steps.
  - [Prerequisites](#prerequisites)
    - Python 3.x
    - Jupyter Notebook
    - Git
  - [Setup](#setup)
     - Clone this repository: `git clone https://github.com/Marlyn-Mayienga/[project-name].git`
  - [Install](#install)
     - Install dependencies: `pip install yfinance pandas numpy matplotlib scikit-learn seaborn`
  - [Usage](#usage)
     - Ensure the epidemiological data file and Google Trends CSVs are located in data/.
     - Launch Jupyter Notebook:
         - `jupyter notebook`
     - Open and run plague_outbreak_analysis.ipynb to reproduce:
          - Weekly case‐count plots
          - Search‐term time series and correlation analysis
          - Regression modeling and error metrics
          - Synthesis and public‐health reflections
- [👥 Authors](#authors)
   - 👤 **Marlyn Mayienga**

- GitHub: [@Marlyn_Mayienga](https://github.com/Marlyn_Mayienga)
- Twitter: [@Merl_Mayienga](https://twitter.com/M_ayienga)
- LinkedIn: [Marlyn_Mayienga](https://linkedin.com/in/Marlyn_Mayienga)
- [🔭 Future Features](#future-features)
    - Interactive dashboard (Plotly Dash or Streamlit) for real‑time monitoring
    - Incorporate additional search terms and languages
    - Extend to other disease outbreaks (e.g., COVID‑19, Marburg)
    - Evaluate non‑linear models (e.g., random forest, ARIMA)

- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)
   - This project is [MIT](./LICENSE) licensed.

_NOTE: we recommend using the [MIT license](https://choosealicense.com/licenses/mit/) - you can set it up quickly by [using templates available on GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). You can also use [any other license](https://choosealicense.com/licenses/) if you wish._

<p align="right">(<a href="#readme-top">back to top</a>)</p>
