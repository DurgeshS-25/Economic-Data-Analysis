# Economic Data Analysis with Python Using Pandas

## Overview
This project focuses on analyzing economic data using Python and the Pandas library. It uses data fetched from the Federal Reserve Economic Data (FRED) API to perform insightful analysis and create visualizations. This guide will walk you through the setup and usage of this project.

---

## Prerequisites

### **1. API Key**
To access data from the FRED API, you need to obtain an API key. Follow these steps to get your API key:
- Visit the [FRED API Documentation](https://fred.stlouisfed.org/docs/api/fred/).
- Register for a free account and generate an API key.
- Save the API key securely, as you'll need it to run the project.

### **2. Install Python and Anaconda**
Ensure you have the following installed on your system:
- **Python (version 3.12.7 or compatible)**.
- **Anaconda** (recommended for managing environments).

---

## Installation and Setup

Follow these steps to set up the project:

```bash
# Step 1: Clone the repository or download the project files
git clone <repository_url>

# Step 2: Navigate to the project directory
cd Economic_Data_Analysis

# Step 3: Create a Conda environment (recommended)
conda create --name economic_analysis python=3.12.7

# Step 4: Activate the environment
conda activate economic_analysis

# Step 5: Install dependencies
pip install -r requirements.txt

# Step 6: Create a `.env` file in the project directory
# Add your FRED API key in the following format:
API_Key=your_api_key_here

# Step 7: Deactivate the environment (when you're done)
conda deactivate
