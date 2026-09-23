# 📊 Customer Satisfaction Study – Flipkart Online Shopping

A responsive academic research website developed to study **customer satisfaction among Flipkart online shoppers**.

The project presents the research objectives, methodology, satisfaction factors, survey questionnaire, findings, and conclusion in an interactive and user-friendly web interface.

> **Academic Research Project**
> A Study on Customer Satisfaction Among Flipkart Online Shopping

---

## 🌐 Project Overview

This project is an interactive research website designed to understand different factors that influence customer satisfaction while shopping online through Flipkart.

The study focuses on areas such as:

* Product quality
* Pricing and offers
* Delivery speed and reliability
* Customer service
* Website usability
* Return and refund processes
* Overall shopping experience
* Customer recommendation intent

The website also includes an online questionnaire through which participants can submit their responses for academic research purposes.

---

## ✨ Features

### 🏠 Interactive Landing Page

* Modern responsive design
* Academic research-focused layout
* Flipkart-inspired blue color scheme
* Hero section with project introduction
* Call-to-action buttons

### 📚 Research Information

The website provides detailed information about:

* About the Study
* Research Focus Areas
* Objectives
* Research Methodology
* Study Significance
* Research Limitations

### 📝 Online Survey

Users can participate in the customer satisfaction survey by providing:

* Full Name
* Age Group
* Gender
* Occupation
* Shopping Frequency
* Overall Satisfaction
* Product Quality Satisfaction
* Delivery Satisfaction
* Pricing Satisfaction
* Customer Service Satisfaction
* Return & Refund Satisfaction
* Recommendation Intent
* Additional Comments

The satisfaction questions use a **1–5 rating scale**.

### 📈 Research Findings

The website presents research findings through visual statistics and satisfaction indicators, including:

* Overall customer satisfaction
* Product quality satisfaction
* Delivery satisfaction
* Pricing satisfaction
* Customer service satisfaction
* Preferred shopping categories
* Repeat shoppers
* Post-purchase satisfaction
* Recommendation rate
* Average rating

### 📱 Responsive Design

The website is optimized for:

* 💻 Desktop
* 📱 Mobile
* 📟 Tablet

Responsive CSS media queries are included to adapt the layout to different screen sizes.

---

## 🎯 Objectives of the Study

The main objectives of the research are:

1. **Measure Customer Satisfaction**
   Understand and quantify the overall satisfaction level of Flipkart customers.

2. **Identify Key Factors**
   Identify the major factors influencing customer satisfaction.

3. **Understand Customer Preferences**
   Study preferences related to products, pricing, delivery, and services.

4. **Evaluate Shopping Experience**
   Understand how customers perceive their overall Flipkart shopping experience.

5. **Identify Areas for Improvement**
   Determine areas where customers expect improvements.

The objectives are implemented directly within the research website.

---

## 🔬 Research Methodology

| Parameter        | Description          |
| ---------------- | -------------------- |
| Research Type    | Descriptive Research |
| Data Collection  | Primary Survey       |
| Collection Tool  | Questionnaire        |
| Sampling Method  | Convenience Sampling |
| Study Population | Flipkart Shoppers    |
| Analysis Method  | Descriptive Analysis |

The methodology section of the website defines the study as descriptive research using a primary questionnaire-based survey and convenience sampling.

---

## 📊 Key Findings

The website currently presents the following research results:

| Metric                        | Result |
| ----------------------------- | -----: |
| Overall Satisfaction          |    86% |
| Product Quality Satisfaction  |    82% |
| Delivery Satisfaction         |    74% |
| Pricing Satisfaction          |    78% |
| Customer Service Satisfaction |    81% |
| Repeat Shoppers               |    72% |
| Post-Purchase Satisfaction    |  83.5% |
| Recommendation Rate           |  79.2% |
| Average Rating                |  4.3/5 |

The displayed findings also identify electronics and clothing as prominent shopping categories in the presented research data.

> **Note:** These figures are the values currently displayed in the project website. They should be treated as project/demo research results unless supported by the project's underlying survey dataset.

---

## 🛠️ Technologies Used

* **HTML5** – Website structure
* **CSS3** – Styling and responsive design
* **JavaScript** – Interactivity and form handling
* **Google Apps Script** – Survey response submission
* **Google Sheets / Apps Script backend** – Intended destination for submitted survey data

The project is implemented as a single HTML webpage containing the HTML structure, CSS styling, and JavaScript functionality. The survey submission code sends collected responses to a configured Google Apps Script endpoint.

---

## 📂 Project Structure

```text
customer-satisfaction-flipkart/
│
├── index.html
└── README.md
```

If you later separate the code into multiple files, you can use:

```text
customer-satisfaction-flipkart/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   └── images/
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the Project

Navigate into the project folder:

```bash
cd YOUR-REPOSITORY
```

### 3. Run the Website

Since the project is built with HTML, CSS, and JavaScript, you can open:

```text
index.html
```

directly in your web browser.

For development, you can also use **VS Code Live Server**.

---

## 📝 Survey Data Submission

The survey form performs client-side validation before submitting responses.

Required information includes:

* Name
* Age
* Gender
* Occupation
* Shopping frequency
* Satisfaction ratings

The JavaScript code prepares the survey response and sends it to a configured Google Apps Script endpoint.

### ⚠️ Important

If you publish this repository publicly, **do not expose private API keys, credentials, tokens, or sensitive backend URLs** in your source code.

The current project contains a Google Apps Script endpoint directly in the JavaScript. For a production project, consider moving configuration into a safer deployment setup.

---

## 📋 Survey Rating Scale

The project uses a 5-point satisfaction scale:

| Rating | Meaning                      |
| -----: | ---------------------------- |
|      1 | Very Dissatisfied / Very Low |
|      2 | Dissatisfied / Low           |
|      3 | Neutral                      |
|      4 | Satisfied / High             |
|      5 | Very Satisfied / Very High   |

The survey includes ratings for overall satisfaction, product quality, delivery, pricing, customer service, returns/refunds, and recommendation intent.

---

## 📱 Responsive Interface

The interface includes responsive layouts for smaller screens.

On mobile devices:

* Navigation changes to a mobile menu
* Content sections become single-column
* Buttons expand to available width
* Survey fields adapt to screen size
* Charts and tables become responsive
* Footer content stacks vertically

---

## 🔍 Research Focus Areas

The research evaluates the following major areas:

### 🎁 Product Quality

Whether products meet the descriptions, images, specifications, and customer expectations.

### 💰 Pricing & Offers

The influence of pricing, discounts, deals, and perceived value.

### 🚚 Delivery Experience

Delivery speed, reliability, tracking, packaging, and on-time delivery.

### 💬 Customer Service

Customer support accessibility and service quality.

### 🖥️ Website Experience

Navigation, search, product information, and checkout experience.

### ↩️ Returns & Refunds

The simplicity and transparency of return and refund procedures.

These areas are incorporated throughout the website's research and survey sections.

---

## ⚠️ Research Limitations

The project identifies several limitations:

* Convenience sampling may not represent the entire Flipkart customer population.
* Responses reflect participant opinions and experiences at the time of the survey.
* The displayed results depend on the available survey responses.
* The findings should therefore be interpreted within the scope of the study.

---

## 🎓 Academic Purpose

This project is intended for **educational and academic research purposes**.

It demonstrates how a web-based interface can be used to:

* Present a research study
* Collect questionnaire responses
* Organize customer satisfaction factors
* Display research findings
* Communicate conclusions interactively

---

## 🔮 Future Improvements

Possible improvements include:

* [ ] Add a dedicated backend/database
* [ ] Add authentication for researchers
* [ ] Add an admin dashboard
* [ ] Export survey responses to CSV/Excel
* [ ] Add dynamic charts based on real survey responses
* [ ] Add statistical analysis
* [ ] Add demographic analysis
* [ ] Add data visualization using Chart.js
* [ ] Separate HTML, CSS, and JavaScript files
* [ ] Add automated deployment with GitHub Pages
* [ ] Improve accessibility
* [ ] Add dark mode

---

## 👨‍💻 Author

**Your Name**

GitHub: `https://github.com/YOUR-USERNAME`

---

## 📄 License

This project is created for **academic and educational purposes**.

The project is not affiliated with or officially endorsed by Flipkart.

---

## ⭐ Support

If you find this project useful for learning or academic research, consider giving the repository a ⭐ on GitHub.
