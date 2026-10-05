# Customer behavior analysis, campaign effectiveness, and data-driven decision-making

This dataset, curated by Kevin Hillstrom, is a foundational resource for **Uplift Modeling**, **Causal Inference**, and **Customer Analytics**. It provides a clear view into a direct marketing campaign where a random subset of customers was targeted with different e-mail campaigns, making it ideal for testing treatment effects.

## 📊 Dataset Overview

The data tracks customer behavior after a specific e-mail marketing campaign. It includes demographic, behavioral, and transactional history, allowing for sophisticated segmentation and churn/conversion analysis.

### Column Dictionary

| Column Name | Description |
| :--- | :--- |
| `recency` | Months since the customer's last purchase. |
| `history` | Total monetary value of purchases made by the customer in the past. |
| `history_segment` | Customer categorization based on previous spending behavior (e.g., Low, Medium, High). |
| `mens` | Binary indicator: Did the customer purchase men's merchandise in the past? |
| `womens` | Binary indicator: Did the customer purchase women's merchandise in the past? |
| `zip_code` | Categorical classification of the customer's residence area (Urban, Suburban, Rural). |
| `newbie` | Binary indicator: Is the customer a "newbie" (new to the brand) or an existing customer? |
| `channel` | The primary channel used for previous purchases (Web, Phone, Multichannel). |
| `segment` | The specific campaign treatment the customer received (Mens E-mail, Womens E-mail, No E-mail). |
| `visit` | Binary indicator: Did the customer visit the website after the campaign? |
| `conversion` | Binary indicator: Did the customer make a purchase after the campaign? |
| `spend` | The total amount spent by the customer after the campaign. |

---

## 🔗 Credits
*   **Original Source:** [Kevin Hillstrom / MineThatData](https://www.kaggle.com/datasets/bofulee/kevin-hillstrom-minethatdata-e-mailanalytics)
*   **Context:** This is a classic dataset for marketing analytics and causal inference research.

