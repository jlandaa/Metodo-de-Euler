# Euler Method for 1st Order ODEs

[![Vue](https://img.shields.io/badge/Vue.js-2.2.2-4fc08d?style=for-the-badge&logo=vue.js&logoColor=white)](https://vuejs.org/)
[![Math.js](https://img.shields.io/badge/Math.js-3.10.0-37474f?style=for-the-badge&logo=javascript&logoColor=white)](https://mathjs.org/)
[![D3.js](https://img.shields.io/badge/D3.js-v3-f9a03c?style=for-the-badge&logo=d3.js&logoColor=white)](https://d3js.org/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-3.3.7-563d7c?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/docs/3.3/)

This application is an interactive web-based tool designed to solve the simplest first-order ordinary differential equations (ODEs) using the **Euler Method**. It provides both a detailed data table and a dynamic graphical visualization of the numerical results.

## 🔗 Live Demo
Access the hosted application here:
[**https://jlandaa.github.io/Metodo-de-Euler/**](https://jlandaa.github.io/Metodo-de-Euler/)

---

## 📖 Description
The Euler method is a first-order numerical procedure for solving ordinary differential equations with a given initial value. This tool allows users to visualize how the step size ($h$) affects the approximation of the solution curve.

### Mathematical Foundation
The application calculates numerical approximations based on the following iterative formulas:

**Step in x**: $x_{n+1} = x_n + h$
**Approximation of y**: $y_{n+1} = y_n + h \cdot f(x_n, y_n)$



---

## 🛠 Usage Guide
Follow these steps to perform a calculation:

1.  **Input the Expression**: Enter the derivative function in the `f'(x,y)` field.
    **Syntax Note**: Use `*` as a multiplication operator between variables (e.g., `x*y`).
    The `*` symbol is not necessary for multiplication by a constant (e.g., `2x`).
2.  **Set Initial Values**: Provide the starting coordinates $x_0$ and $y_0$.
3.  **Define Step Size ($h$)**: Enter the interval value for each iteration.
4.  **Specify Iterations**: Enter the total number of steps to calculate.
5.  **Calculate and Plot**: Click **"Calcular y graficar"** to generate the results table and the D3.js visualization.

---

## 🧰 Libraries and Frameworks
The project utilizes the following libraries for performance and accuracy:

**Vue.js (v2.2.2)**: Manages UI reactivity and data binding.
**Math.js (v3.10.0)**: Used for parsing and evaluating mathematical expressions.
**Bootstrap (v3.3.7)**: Provides the responsive grid system and styling.
**D3.js (v3)**: Handles dynamic SVG graph generation.

---

## 🚀 Installation & Local Execution
Since this project fetches its dependencies via CDN, no complex environment setup or `npm install` is required.

### Local Setup
1.  **Clone the Repository**:
    ```bash
    git clone [https://github.com/jlandaa/Metodo-de-Euler.git](https://github.com/jlandaa/Metodo-de-Euler.git)
    ```
2.  **Verify Structure**: Ensure `style.css` is located inside a folder named `css/` relative to `index.html`.
3.  **Run**: Simply open `index.html` in any modern web browser.
   
## Application Preview
<img width="1919" height="979" alt="Ejemplo_Caso_Prueba" src="https://github.com/user-attachments/assets/baf5c4b2-d841-4a3c-926e-dafe0caeb3e8" />




