# Stylish

**A Flutter-based fashion commerce app with customer, seller, and admin workflows.**

Stylish is a multi-role e-commerce app designed for product discovery, shopping, order management, and store administration.

## Features

### Customer features
- Product browsing with a clean home feed
- Search products by name
- Filter products by category
- View featured deals and highlighted items
- Open detailed product pages with images, pricing, and stock info
- Add products to wishlist
- Add products to cart
- Update cart quantities
- Remove products from cart
- View live cart totals
- Checkout and place orders
- Track order history
- Filter orders by status
- Cancel pending or processing orders
- View order details
- Rate and review products
- Update profile details
- Change profile image
- Add, edit, and manage delivery addresses
- Set a default address
- Toggle light/dark mode
- Receive local notifications for order updates
- Handle offline state gracefully

### Seller features
- Access a seller dashboard
- Manage products
- Add new products
- Edit existing product data
- Update product stock and pricing
- View orders for fulfillment
- Manage order updates and processing
- Maintain a product catalog for the storefront

### Admin features
- Access an admin dashboard
- Manage all products
- Add or update products
- View sales and store analytics
- Track inventory insights
- View all customer orders
- View order details and updates
- Manage users
- Change user roles between customer, seller, and admin
- Control admin-only workflows and access

## Roles and responsibilities

| Role | What they can do |
| --- | --- |
| **Customer** | Shop products, save favorites, add to cart, checkout, manage orders, review products, update profile, and manage addresses |
| **Seller** | Manage products, track inventory, and handle orders for selling operations |
| **Admin** | Full platform management including analytics, user roles, product control, and order oversight |

## Tech stack

- Flutter
- Dart
- Firebase Authentication
- Cloud Firestore
- Firebase Storage
- Riverpod
- GoRouter
- SharedPreferences
- Local notifications

## Summary

Stylish is a complete e-commerce application with customer shopping, seller management, and admin control features in one platform.

## Media gallery

Compact thumbnails are arranged four per row. Select any image to open it at full size. Screens follow their numbered flow within each role.

### Shared flow

| 1. Splash | 2. Onboarding | 3. Onboarding | 4. Onboarding |
| --- | --- | --- | --- |
| <a href="media/images/shared/1. splash screen.jpg"><img src="media/images/shared/1. splash screen.jpg" alt="Splash screen" width="150"></a> | <a href="media/images/shared/2. onboarding screen.jpg"><img src="media/images/shared/2. onboarding screen.jpg" alt="Onboarding 1" width="150"></a> | <a href="media/images/shared/3. onboarding screen.jpg"><img src="media/images/shared/3. onboarding screen.jpg" alt="Onboarding 2" width="150"></a> | <a href="media/images/shared/4. onboarding screen.jpg"><img src="media/images/shared/4. onboarding screen.jpg" alt="Onboarding 3" width="150"></a> |
| 5. Login | 6. Signup | 6.1 Signup and login | |
| <a href="media/images/shared/5. login screen.jpg"><img src="media/images/shared/5. login screen.jpg" alt="Login screen" width="150"></a> | <a href="media/images/shared/6. Signup screen.jpg"><img src="media/images/shared/6. Signup screen.jpg" alt="Signup screen" width="150"></a> | <a href="media/images/shared/6.1 signup-login screen.png"><img src="media/images/shared/6.1 signup-login screen.png" alt="Combined signup and login" width="150"></a> | |

### Client flow

| 7. Home | 8. Home | 10. Search | 16. Tracking |
| --- | --- | --- | --- |
| <a href="media/images/client/7. client home page 1.jpg"><img src="media/images/client/7. client home page 1.jpg" alt="Client home 1" width="150"></a> | <a href="media/images/client/8 client home page 2.jpg"><img src="media/images/client/8 client home page 2.jpg" alt="Client home 2" width="150"></a> | <a href="media/images/client/10. client search product.jpg"><img src="media/images/client/10. client search product.jpg" alt="Client search products" width="150"></a> | <a href="media/images/client/16. client order tracking.jpg"><img src="media/images/client/16. client order tracking.jpg" alt="Client order tracking" width="150"></a> |
| 17. Order history | 18. Profile | 19. Addresses | 20. Checkout |
| <a href="media/images/client/17. client order history with filters.jpg"><img src="media/images/client/17. client order history with filters.jpg" alt="Client order history" width="150"></a> | <a href="media/images/client/18. client profile edit.jpg"><img src="media/images/client/18. client profile edit.jpg" alt="Client profile" width="150"></a> | <a href="media/images/client/19. client add new address or upgrade address.jpg"><img src="media/images/client/19. client add new address or upgrade address.jpg" alt="Client addresses" width="150"></a> | <a href="media/images/client/20. client product checkout.jpg"><img src="media/images/client/20. client product checkout.jpg" alt="Client checkout" width="150"></a> |
| 21.1 Tracking filter | 21.2 Tracking filter | 22. Review | 26. Home dark mode |
| <a href="media/images/client/21.1 client order tracing with order status filter.jpg"><img src="media/images/client/21.1 client order tracing with order status filter.jpg" alt="Order tracking status filter 1" width="150"></a> | <a href="media/images/client/21.2 client order tracking with order status filter.jpg"><img src="media/images/client/21.2 client order tracking with order status filter.jpg" alt="Order tracking status filter 2" width="150"></a> | <a href="media/images/client/22. review product.jpg"><img src="media/images/client/22. review product.jpg" alt="Review product" width="150"></a> | <a href="media/images/client/26. Client HomeScreen DarkMode.jpeg"><img src="media/images/client/26. Client HomeScreen DarkMode.jpeg" alt="Client home dark mode" width="150"></a> |
| 27. Cart | 28. Reviews | 29. Orders | 29.1 Expanded order |
| <a href="media/images/client/27. Client MyCart.jpeg"><img src="media/images/client/27. Client MyCart.jpeg" alt="Client cart" width="150"></a> | <a href="media/images/client/28. Client View Product Reviews.jpeg"><img src="media/images/client/28. Client View Product Reviews.jpeg" alt="Product reviews" width="150"></a> | <a href="media/images/client/29. Client MyOrders DarkMode.jpeg"><img src="media/images/client/29. Client MyOrders DarkMode.jpeg" alt="Client orders" width="150"></a> | <a href="media/images/client/29.1 Client MyOrders Expand DarkMode.jpeg"><img src="media/images/client/29.1 Client MyOrders Expand DarkMode.jpeg" alt="Expanded client order" width="150"></a> |
| 30. Wishlist | 33. Deal of the day | 34. Reviewed history | |
| <a href="media/images/client/30. Client Wishlist DarkMode.jpeg"><img src="media/images/client/30. Client Wishlist DarkMode.jpeg" alt="Client wishlist" width="150"></a> | <a href="media/images/client/33. Client DealOfTheDay.jpeg"><img src="media/images/client/33. Client DealOfTheDay.jpeg" alt="Deal of the day" width="150"></a> | <a href="media/images/client/34. OrderHistory(marked as Reviewed).jpeg"><img src="media/images/client/34. OrderHistory(marked as Reviewed).jpeg" alt="Reviewed order history" width="150"></a> | |

### Seller flow

| 31. Dashboard | 32. Dashboard with filtering | | |
| --- | --- | --- | --- |
| <a href="media/images/seller/31. Seller DashBoard.jpeg"><img src="media/images/seller/31. Seller DashBoard.jpeg" alt="Seller dashboard" width="150"></a> | <a href="media/images/seller/32. Seller Dashboard with filtering.jpeg"><img src="media/images/seller/32. Seller Dashboard with filtering.jpeg" alt="Seller dashboard with filtering" width="150"></a> | | |

### Admin flow

| 9. Search | 11. Product list | 12. Analytics | 13. Order history |
| --- | --- | --- | --- |
| <a href="media/images/admin/9. admin search product.jpg"><img src="media/images/admin/9. admin search product.jpg" alt="Admin search" width="150"></a> | <a href="media/images/admin/11. admin product list screen.jpg"><img src="media/images/admin/11. admin product list screen.jpg" alt="Admin product list" width="150"></a> | <a href="media/images/admin/12. admin analytics.jpg"><img src="media/images/admin/12. admin analytics.jpg" alt="Admin analytics" width="150"></a> | <a href="media/images/admin/13. order history.jpg"><img src="media/images/admin/13. order history.jpg" alt="Admin order history" width="150"></a> |
| 14. Filter products | 15. Add product | 23. Export sales | 24. Order tracking |
| <a href="media/images/admin/14. admin filter products.jpg"><img src="media/images/admin/14. admin filter products.jpg" alt="Admin product filters" width="150"></a> | <a href="media/images/admin/15. admin add product.jpg"><img src="media/images/admin/15. admin add product.jpg" alt="Admin add product" width="150"></a> | <a href="media/images/admin/23. Export Sales history.jpg"><img src="media/images/admin/23. Export Sales history.jpg" alt="Export sales history" width="150"></a> | <a href="media/images/admin/24. Admin Order Tracking.jpeg"><img src="media/images/admin/24. Admin Order Tracking.jpeg" alt="Admin order tracking" width="150"></a> |
| 24.1 Analytics filter | 24.2 Analytics filter | 25. Order history | 35. Status update |
| <a href="media/images/admin/24.1 Admin analytics with filtering.jpeg"><img src="media/images/admin/24.1 Admin analytics with filtering.jpeg" alt="Admin analytics filter view 1" width="150"></a> | <a href="media/images/admin/24.2 Admin analytics with filtering.jpeg"><img src="media/images/admin/24.2 Admin analytics with filtering.jpeg" alt="Admin analytics filter view 2" width="150"></a> | <a href="media/images/admin/25. Admin order history.jpeg"><img src="media/images/admin/25. Admin order history.jpeg" alt="Admin order history" width="150"></a> | <a href="media/images/admin/35. Admin Order Status Update.jpeg"><img src="media/images/admin/35. Admin Order Status Update.jpeg" alt="Admin order status update" width="150"></a> |

## Video previews

- [App preview](https://vimeo.com/1239048270)
- [Product checkout](https://vimeo.com/1239048243)
- [Admin add product](https://vimeo.com/1239048210)
- [Seller and admin workflows](https://vimeo.com/1239047997)
