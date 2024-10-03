# :moneybag: Tip & Consumption Calculator

This project is a Tip & Consumption Calculator that allows users to easily manage and calculate the total cost of an order, including tips. The app is built with React and TypeScript, using Vite for fast development and Tailwind CSS for styling. The project focuses on improving performance by optimizing component rendering.

## :star2: Features
- *Add Order:* Add individual orders with their corresponding prices.
- *Delete Order:* Remove any order from the list.
- *Calculate Tip:* Automatically calculate tips based on predefined percentages (10%, 20%, and 50%).
- *Calculate Subtotal:* Get the total of all added orders before applying the tip.
- *Calculate Total:* Calculate the final total, including both the tip and the subtotal.
- *Save Order:* Save the current order to preserve it for future reference.

## :pushpin: Technologies Used
- *React (with TypeScript)* for building the user interface.
- *Vite* as the build tool for faster and more optimized development.
- *Tailwind CSS* for modern, responsive styling.

## :ok_hand: Performance Optimization

To enhance performance, I implemented:

- *Custom Hooks:* Encapsulated logic into reusable hooks to make the code more maintainable.
- *Memoization (useMemo):* Reduced unnecessary re-renders by using useMemo for expensive calculations, improving app responsiveness.
- *Efficient Component Rendering:* Optimized the rendering process of some components to reduce re-renders and improve the overall user experience.

## :globe_with_meridians: Site
**Site:** https://tipcalculator-sac.netlify.app/

## 🚀 Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/Tip-Calculator.git
```
### 2. Navigate to the project folder
```bash
cd tip-calculator
```
### 3. Install dependencies
```bash
npm install
```
### 4. Start the application
```bash
npm run dev
```
### 5. Build the application
```bash
npm run build
```