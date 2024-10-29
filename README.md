# 🏗️ Llava-Powered Image and OCR Querying in Construction 🖼️🔍

Welcome to the **Llava-Powered Image and OCR Querying** repository! This project demonstrates how the **Llava Large Language Model (LLM)**, a multimodal visual assistant, can be leveraged to analyze images and perform OCR tasks within a construction context. Built with `torch`, `llava-torch`, and `transformers`, this model empowers users to query images, extract structured information, and support various construction applications—from safety inspections to documentation.

---

## 📑 Table of Contents
1. [📋 Project Overview](#-Project-Overview)
2. [✨ Key Features](#-Key-Features)
3. [🔧 Installation & Setup](#-installation--setup)
4. [🛠️ Usage Guide](#-usage-guide)
5. [🏗️ Construction Use Cases](#-construction-use-cases)
6. [🚀 Future Enhancements](#-future-enhancements)
7. [🙏 Acknowledgments](#-acknowledgments)
8. [🔗 General Links & Resources](#-general-links--resources)

---

## 📋 Project Overview

This project provides a hands-on example of how **Llava LLM** can support the construction industry by allowing users to:
- **Decipher Images:** Identify and interpret elements in site photos, enhancing safety and compliance monitoring.
- **Extract Text with OCR:** Convert text from construction documents into digital text for streamlined data management.
- **Analyze Visual Data Contextually:** Leverage Llava’s capabilities to understand and classify objects and contexts within an image, improving project insights and decision-making.

With detailed explanations and code, this project aims to bridge AI capabilities with practical applications in construction.

---

## ✨ Key Features

- **🖼️ Image Analysis**: Utilize Llava’s multimodal capacity to query images directly, extracting contextual insights.
- **📝 Optical Character Recognition (OCR)**: Turn construction documents and images into actionable, digitized text.
- **🚧 Construction-Oriented Use Cases**: Tailored examples to illustrate Llava’s application in safety, documentation, and project management.
- **📦 Streamlined Setup**: Deploy with a requirements file and Jupyter Notebook to get started immediately.
  
---

## 🔧 Installation & Setup

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/YourUsername/Construction_Llava_Visual_Assistant.git
    cd Construction_Llava_Visual_Assistant
    ```

2. **Set Up Environment**:
    - **Python 3.11** is recommended.
    - A **Linux** distribution is mandatory. Llava torch library doesnot work on Windows or MacOS.
    - Create and activate a virtual environment:
      ```bash
      python -m venv llava_env
      source llava_env/bin/activate  # On Windows, use `llava_env\Scripts\activate`
      ```

3. **Install Requirements**:
    ```bash
    pip install -r requirements.txt
    ```
    **Required Libraries**: `torch`, `llava-torch`, `transformers`, `accelerate`, `bitsandbytes`, `PIL`, `glob`, `requests`.

---

## 🛠️ Usage Guide

### 1️⃣ Run the Jupyter Notebook

The primary project is encapsulated in a Jupyter Notebook:
- **Llava chat model.ipynb**: Load this notebook to access step-by-step guidance on querying images and using OCR in Llava.

### 2️⃣ Query Images and Documents
1. **Choose an Image**: Load an image relevant to construction, such as site inspections or design blueprints.
2. **Enter a Prompt**: Use natural language queries like “Describe safety equipment in this image” or “Extract text from this document” to engage the Llava model.

### 3️⃣ Receive and Interpret Results
- **Image Contextual Analysis**: Llava will describe or classify the image based on your query.
- **OCR Extraction**: Receive digitized text for construction documents, facilitating seamless documentation and compliance.

---

## 🏗️ Construction Use Cases

Explore these practical applications of Llava in the construction industry:
- **Safety Compliance Checks**: Query site images to ensure safety gear is used and potential hazards are addressed.
- **Project Documentation**: Convert construction plans and written site notes into digital format for easy access and tracking.
- **Inventory & Resource Management**: Identify equipment and materials from images, improving inventory accuracy and allocation.
- **Inspection Reports**: Analyze site images for structural integrity, identifying any defects or areas needing repair.

---

## 🚀 Future Enhancements

- **Enhanced Multimodal Analysis**: Expand Llava’s use cases to include more intricate construction scenarios.
- **Database Integration**: Connect OCR outputs with construction project management tools for better data integration.
- **Automated Reporting**: Generate comprehensive safety and inspection reports from queried images.

---

## 🙏 Acknowledgments

Special thanks to **Venelin Valkov** for providing educational resources on large language models that contributed to this project’s development.

---

## 🔗 General Links & Resources

- **Our Website**: [APC Mastery Path](https://www.apcmasterypath.co.uk)
- **LinkedIn**: [Personal](https://www.linkedin.com/in/mohamed-ashour-0727/) | [APC Mastery Path](https://www.linkedin.com/company/apc-mastery-path)
