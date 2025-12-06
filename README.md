
# 📦 Product Delivery Management System (PDMS)

A robust, full-stack web application designed to streamline the interaction between Dealers, Customers, and Delivery Personnel. This system facilitates product management, order processing, and delivery tracking in a unified platform.

## 🛠️ Tech Stack

**Frontend:**
* **React (Vite):** Fast and modern UI library.
* **Tailwind CSS:** For responsive and clean styling.
* **Axios:** For handling HTTP requests.
* **React Router:** For seamless navigation.

**Backend:**
* **Node.js & Express.js:** Server-side runtime and framework.
* **JWT (JSON Web Tokens):** For secure, stateless authentication.
* **Bcrypt.js:** For password hashing security.
* **Multer:** For handling product image uploads.

**Database:**
* **MySQL:** Relational database for storing users, products, and orders.


---

## ✨ Features by Role

### 🧑‍💼 Dealer (Seller)
* **Dashboard:** View business statistics (Total Products, Pending Orders, Completed Deliveries).
* **Product Management:** Add, Edit, and Delete products.
* **Image Upload:** Upload product images directly from the local device.
* **Order Fulfillment:** View incoming customer orders and assign them to available Delivery Personnel.

### 🛍️ Customer (Buyer)
* **Browse Products:** View a catalog of products from all dealers.
* **Shopping Cart:** Add items to a cart and manage quantities.
* **Checkout:** Place orders securely.
* **Order History:** View past orders and their status (Pending, Shipped, Delivered).

### 🚚 Delivery Personnel
* **Assignment View:** See orders assigned specifically to them.
* **Status Updates:** Update delivery status (e.g., "Out for Delivery", "Delivered") which reflects in real-time for the Dealer and Customer.
* **Availability:** System tracks availability to ensure only free personnel are assigned tasks.

---

## 🗄️ Database Schema

The project uses a relational MySQL database with the following key tables:
* `Customers`, `Dealers`, `DeliveryPersonnel` (Users)
* `Products` (Inventory)
* `Orders` & `OrderDetails` (Transactional data)
* `Deliveries` (Logistics tracking)

---

## 📸 Screenshots

### 1. Landing & Login Page

<img width="1298" height="590" alt="Screenshot 2025-12-06 201142" src="https://github.com/user-attachments/assets/462d7afa-69bf-499f-9097-bc7bd4274f15" />
<img width="1290" height="581" alt="image" src="https://github.com/user-attachments/assets/f3a90675-4346-4417-bfec-7bc5d7feda70" />


### 2. Customer Dashboard (Product Catalog)
<img width="1132" height="509" alt="image" src="https://github.com/user-attachments/assets/3358a9f8-8830-48c3-9b06-3e2aa4caa4e5" />
<img width="1132" height="501" alt="image" src="https://github.com/user-attachments/assets/e89a87d4-0e1c-4f33-af2f-c729b1808631" />



### 3. Shopping Cart
<img width="1141" height="516" alt="image" src="https://github.com/user-attachments/assets/45b3005d-464b-4481-ad99-69a957d21bc0" />


### 4. Dealer Dashboard
<img width="956" height="438" alt="image" src="https://github.com/user-attachments/assets/567bd7d4-f55d-454e-ad50-afaaa00f16ee" />


### 5. Order Assignment (Dealer View)
<img width="1130" height="516" alt="image" src="https://github.com/user-attachments/assets/0375b442-46dc-4bfa-beb0-e4d51a50a8c4" />
<img width="958" height="437" alt="image" src="https://github.com/user-attachments/assets/a59706da-c587-471f-968c-02302cb49b5e" />


### 6. Delivery Personnel Dashboard
<img width="957" height="438" alt="image" src="https://github.com/user-attachments/assets/39ea25a9-6ba5-463c-83ea-bc5285dc5624" />


---

