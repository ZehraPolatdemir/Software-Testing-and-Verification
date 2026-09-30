# Week 1: Sauce Demo UI Automation & Performance Test

## 🎯 Objective
The goal of this assignment is to automate the checkout process on [Swag Labs (Sauce Demo)](https://www.saucedemo.com) and compare the performance of different user roles. The test validates whether the page load time stays within the acceptable 5-second limit[cite: 1].

## 🧪 Test Scenarios
1. **Functional Testing:** Automating the end-to-end checkout flow (Login > Add to Cart > Go to Cart > Checkout Info > Finish Order) using `standard_user`[cite: 1].
2. **Performance Testing:** Measuring the execution time for each step using `performance_glitch_user` and comparing it against the baseline[cite: 1].
3. **Verification (Assertion):** Verifying that the login process completes within 5 seconds[cite: 1].

## 📈 Results & Visualization
The script records the load times for each step and generates a comparison line chart using Matplotlib[cite: 1]. 

*(Add your Matplotlib graph screenshot here, e.g., `![Performance Graph](result_graph.png)`)*

## 🚀 How to Run
1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip3 install selenium matplotlib webdriver-manager
