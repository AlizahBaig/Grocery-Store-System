# Grocery-Store-System
The C code simulates a basic grocery store system. It manages different products across sections like fruits, vegetables, meats, etc. Users select a section to shop from, input quantities of desired items, and receive a receipt. The code handles user inputs, tracks purchased quantities, updates stock, and generates a detailed receipt with product names, prices, quantities, and total amounts spent. Opportunities exist to refine error handling, optimize iterations, and improve output formatting for better user experience.

### Code Report

#### Overview:
The provided C code simulates a simple grocery store system. It manages different types of products and allows users to select items from various sections, make purchases, and generates a receipt.

#### Structure & Functionality:
- **Struct Product:**
  - Represents a product with fields for name, price, quantity, section, and total purchased quantity.
- **printProducts Function:**
  - Displays products based on the selected section, showing name, price, available quantity, and section.
- **Main Function:**
  - Initializes an array of products across different sections.
  - Prompts users to select a section to shop from and allows them to input their choices.
  - Manages shopping, calculates totals, updates quantities, and generates a receipt.

#### Key Points:
- **Input Handling:**
  - Accepts user inputs for section selection and quantities while handling invalid inputs.
- **Shopping & Quantities:**
  - Allows users to purchase items by specifying quantities and updates the total purchased quantity and available quantity.
- **Receipt Generation:**
  - Generates a receipt displaying purchased products with their quantities, prices, and total amounts.

#### Recommendations:
- **Error Handling:**
  - Enhance error handling for various inputs to provide more user-friendly messages and prevent unexpected behavior.
- **Optimization:**
  - Consider improving the loop iterations to stop once a section's products are exhausted instead of looping through the entire product list.
- **Formatting & Readability:**
  - Enhance the formatting of output messages and align columns in the receipt for better readability.

#### Conclusion:
The code effectively models a grocery store system, enabling section-wise shopping, purchase quantity tracking, and generating a detailed receipt. However, it can be further refined by enhancing error handling, optimizing iteration processes, and improving output formatting.

#### Contributors:
Alizah Baig CT-021
Neha Salman CT-022
Fatimah Sajid CT-013
