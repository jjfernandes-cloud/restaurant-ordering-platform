# restaurant-ordering-platform

This project is aimed to bridge the online gap betwen customer and vendor. 
Its main purpose is to allow customers to reach the vendor electronically, allowing them to view the menue, place orders and receive updates on the their order.
Futhermore, this project will also allow said vendor to view order, respond to them accordingly and track analytics. It will also have features such as accessed rights later on.

**Accessed right tiers and abilities:**
_Customers_
CAN: View menu, create an account, place orders, track order status, view order history, update personal profile (add contact details)
CANNOT: View other customers, edit menu listings, access restaurant dashboard
_Staff_
CAN: View incoming orders, update order status(Pending/Confirmed/Preparing/Ready/Completed/Cancelled), view customer order details, mark items as unavailable, view customer contact details
CANNOT: Change prices, delete orders, manage users, view financial reports/analytics
_Manager_
CAN: Execute all actions that staff can with the addition of: adding/editing menu items, adding/editing categories, vieing financial reports/analytics, managing promotions, viewing all orders and order histories
CANNOT: Create other managers, change owner account settings
_Admin_
CAN: Execute all actions that a manager can with the addition of: creating/disabling staff accounts, reset user passwords, configure restaurant settings, manage system-wide options
CANNOT: Transfer ownership, delete owner account
_Owner_
CAN:Create/remove admins, access financial reports, view audit logs, configure business settings, transfer ownership, access backups
CANNOT: Ultimately has full control.

**Planned Technology Stack**
_Backend_
Python
Django
_Database_
PostgreSQL
_Frontend_
HTML
CSS
JavaScript
_Deployment_
Render

The big question: WHY?
This project started as a way to gain more experience with full stack development while also building something that could make a lasting impact on my community. 
My aim is to treat this project like a real client project and follow proper procedures, development stages and document the entire process.
