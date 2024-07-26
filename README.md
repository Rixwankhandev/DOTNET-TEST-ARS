# PROD-CAT-DN-TEST
E-Commerce Product Catalog Management System

# E-Commerce Product Catalog
This project involves developing a straightforward E-Commerce Product Catalog that allows users to view, search, and filter products. The application should be built using .NET Core and follow the MVC architecture. Data access will be handled through ADO.NET, with JavaScript and AJAX used for asynchronous operations, and partial views employed to dynamically load specific sections of the web pages.

# Product Catalog Features

**Listing View:**
The listing page should enable users to filter products based on Name, Price, and Category (Brakes, Engine, Suspension). Ensure the design is mobile-responsive and incorporates pagination. When a filter is applied, the product listing should be updated using partial views.

![listing-page](https://github.com/user-attachments/assets/778d2a1d-f099-4543-a229-a6d7a757b73e)

**View Popup:**
Users can click on the View icon in the Listing View to open a popup displaying detailed product information. Each product will have multiple images, which should be presented in a carousel/slider format.

![prod-view](https://github.com/user-attachments/assets/154f96fb-10dd-4520-bdbf-3fb8d5bdfdf2)


**Edit Popup:**
Clicking the Edit icon will open a popup (as shown in the provided image) where users can update all product properties except the SKU, which remains fixed. After a successful update, the Listing View should be refreshed upon clicking OK.

![edit-view](https://github.com/user-attachments/assets/b6855e3d-d92d-4248-865f-bffa8d817bdd)


**Delete Popup:**
Clicking the Delete icon will open a confirmation alert for deleting the product. Upon confirmation, the product will be deleted, and a success alert will be displayed. The Listing View should be refreshed based on the success response upon clicking OK.

![delete-view](https://github.com/user-attachments/assets/8c5115f7-9e75-4e24-b204-4f7788d3e66d)


# Backend Service:
1: Develop a backend service using .NET Core.
2: Implement data access using ADO.NET to interact with a SQL Server database.

# Frontend:
1: Utilize the MVC pattern to create the frontend.
2: Incorporate JavaScript with AJAX for asynchronous operations, Callbacks.
3: Use partial views to dynamically load specific parts of the web pages.
4: Implement functionality to asynchronously load product data, search for products, and filter products using AJAX.

**Code Quality Considerations:**
> Ensure the code is clean, well-documented, and follows best practices.
> Utilize meaningful variable and method names.
> Apply appropriate error handling and validation.
> Adhere to SOLID principles in your design.

**Here's the Figma Design Link:** https://www.figma.com/design/0fJR9ehv6SlhME3qlqZAM3/Assignment?node-id=1-2&t=of06mLnZrD9cKAqK-4

