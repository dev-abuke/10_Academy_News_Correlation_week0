# Welcome to Week-0 Task-1 of 10 Academy's intensive training program!

## Overview

This project is centered around the effective use of Git and GitHub for version control, the establishment of a Python-based environment, and the execution of continuous integration and continuous deployment (CI/CD) strategies. It also emphasizes the application of key performance indicators (KPIs) great for the setup of the development environment and associated skills. Additionally, the project incorporates the CRISP-DM framework for strategic project planning, and undertakes exploratory data analysis (EDA) and statistical reasoning.


## Table of Contents

- [Project Title](#Welcome-to-Week-0-Task-1-of-10-Academy's-intensive-training-program!)
  - [Overview](#overview)
  - [Goals to Achieve](#goals-to-achieve)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Branches](#branches)
    - [Commits](#commits)
    - [Code Organization](#code-organization)
    - [Notebooks](#notebooks)
        - [Day 1 Analysis](#day-1-analysis)
    - [Analysis Results](#analysis-results)
        - [Top and Bottom 10 Users](#top-and-bottom-users)
            - [By Reply Count](#Reply-Count)
            - [By Mention Count](#Mention-Count)
            - [By Message Count](#Message-Count)
        - [Top 10 Messages](#top-messages)
            - [By Reply Count](#Replies)
            - [By Mention Count](#Reactions)
            - [By Message Count](#Mentions)
        - [Channel Analysis](#channel-analysis)
        - [Time Analysis](#time-analysis)
  - [Contributing](#contributing)
  - [License](#license)

## Goals to Achieve

- **Dev Environment Setup:** Set up the Python environment, Git version control, and CI/CD.
- **Relevant Skills Demonstration:** Showcase proficiency in the CRISP-DM framework, data understanding, EDA techniques, and statistical thinking.
- **Project Planning - EDA & Stats:** Effectively plan and execute the project using the CRISP-DM framework, perform EDA, and create actionable insights from statistical analyses. Demonstrates Stats understanding by using suitable statistical distributions and plots to provide evidence to actionable insights gained from EDA.

## Installation

To get started with the project, follow these installation steps:

1. **Python Environment:**
    ```bash
    python -m venv your_env_name
    ```

    Replace `your_env_name` with the desired name for your environment.
    
    **Activate the environment:**

    - On Windows:

    ```bash
    .\your_env_name\scripts\activate
    ```

    - On macOS/Linux:

    ```bash
    source your_env_name/bin/activate
    ```

2. **Clone this package**
    To install the `network_analysis` package, follow these steps:

    1. Clone the repository:
        ```bash
        git clone https://github.com/dev-abuke/10_Academy_News_Correlation_week0.git
        ```
    2. Navigate to the project directory:
        ```bash
        cd 10_Academy_News_Correlation_week0
        ```
    
    3. Install the required dependencies:
        ```bash
        pip install -r requirements.txt
        ```


3. **Continuous Integration:**
    - CI/CD configurations are already set up. Refer to the CI/CD documentation for additional details.

## Usage

### Branches

In this repository, the branches are organized as follows:

- **main:** The main branch, initially forked from [https://github.com/10xac/week0_starter_network_analysis](https://github.com/10xac/week0_starter_network_analysis).

- **task-1:** The current branch for Day 1 analysis. 

  ```bash
  git checkout -b task-1
    ```


### Code Organization

Restructured the code by moving functions into `/src/loader.py` and `/src/utils.py`. In the analysis notebooks, used the `NewsDataLoader` from `/src/loader.py` and functions from `/src/utils.py` for data loading needs.

## Notebooks
### Day 1 Analysis
`/notebooks/EDA.ipynb`

## Contributing
Contributions are welcome! Before contributing, please review our contribution guidelines.

##  License
This project is licensed under the MIT License.