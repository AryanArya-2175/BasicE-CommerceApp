# BasicE-CommerceApp


 🛍️ Basic E-Commerce App – Project Report

 📌 Project Title:

Basic E-Commerce Desktop Application using Windows Forms and C#
 🧾 Objective:
🛠️ Technologies Used:

* **Language:** C#
* **Framework:** .NET (Windows Forms)
* **IDE:** Visual Studio 2022
* **GUI Framework:** Windows Forms Designer
🧩 Modules & Components:
1. **Product Catalog**

* Displays a list of available products with their prices.
* Implemented using a `ListBox` control (`lstProducts`).
* Products are stored in a `Dictionary<string, decimal>` for quick access.
2. **Cart System**

* Users can add selected products from the product list to a shopping cart.
* The selected items are displayed in a second `ListBox` (`lstCart`).
 3. **Total Calculation**

* Calculates the total price of all items in the cart.
* Displays the total using a `Label` (`lblTotal`).
* Safely accesses the dictionary to prevent errors (e.g., `KeyNotFoundException`).
 4. **Checkout**

* Provides a `Checkout` button that clears the cart and displays the total paid.
* Validates if the cart is empty before proceeding.

 💡 Features Implemented:

* ✅ GUI with product and cart lists.
* ✅ Dynamic product loading.
* ✅ Total price calculation.
* ✅ Safe dictionary access to prevent runtime errors.
* ✅ User feedback using message boxes.
* ✅ Clear separation of logic for maintainability.

 📷 Screenshot Highlights:

* Product list with items like “Apple - \$0.99”.
* Cart showing selected items.
* Live updating total label (`Total: $X.XX`).
* Message box confirming checkout or alerting if the cart is empty.

🛡️ Error Handling:

* Implemented checks using `products.ContainsKey(...)` to prevent runtime crashes when accessing dictionary entries.
* Handles missing or malformed selections gracefully.

 📈 Possible Enhancements:

* 🛒 Add quantity selection.
* 💳 Integrate payment gateway simulation.
* 📄 Add invoice generation.
* 🔎 Search/filter products.
* 🧾 Export cart summary as a text or PDF file.

