# Data Flow Diagram (DFD) – Airbnb Clone Backend

## 📘 Overview
The Data Flow Diagram (DFD) illustrates how data moves through the Airbnb backend system.  
It maps the flow between entities (users, hosts, admin) and core backend processes (authentication, booking, payment).

---

## ⚙️ Key Processes
1. **User Registration/Login**
   - Input: Email, password, name.
   - Process: Validate, hash password, save to database.
   - Output: Access token, confirmation message.

2. **Property Booking**
   - Input: Property ID, dates, user ID.
   - Process: Check availability, create booking record.
   - Output: Booking confirmation.

3. **Payment Handling**
   - Input: Booking ID, payment details.
   - Process: Validate payment, update status.
   - Output: Payment receipt and confirmation.

---

## 📊 File Overview
| File | Description |
|------|--------------|
| `data-flow.drawio` | Editable DFD diagram |
| `data-flow.png` | Exported image file |
| `README.md` | Documentation file |

---

## 🧠 Notes
- Data sources and destinations include: Users, Properties, Bookings, and Payments.
- The DFD demonstrates backend logic and database interactions clearly.
