# Amazon-Invoice-Generator
A lightweight, fully client-side tool that allows Amazon sellers to generate professional PDF invoices from their order data—without needing a backend.

This tool simulates Amazon Selling Partner API responses by accepting exported JSON files and turns them into styled invoices based on a customizable HTML template. It’s perfect for demos, internal use, or as a frontend proof of concept for future integration with Amazon’s official APIs.

Tech Stack:

<img src ="https://github.com/super-fz/Social-Media-Dashboard/assets/122122054/2fdb809d-7c0c-4d10-9e37-8c753f58418f" height = "55">
<img src ="https://github.com/user-attachments/assets/32481355-9279-4606-b121-6feb83043fc3" height = "55">
<img src ="https://github.com/super-fz/Social-Media-Dashboard/assets/122122054/f744032c-55b2-460e-b068-254829613310" height = "55">
<img src ="https://github.com/user-attachments/assets/ae8cdd74-e946-4bf0-ad22-427aadb22915" height = "55">
<img src ="https://github.com/user-attachments/assets/2d50d9eb-7455-4f7f-9322-4604b241ca92" height = "55">



<img src ="https://github.com/user-attachments/assets/72c8f42d-3830-4e1a-895e-16b4f9d65246">


Amazon Selling Partner API (SP-API) includes:

•Orders API v0: Retrieve order information.

•Vendor Invoices API v1: Manage invoice generation and submission.

To connect this tool directly with SP-API, a secure backend is required to handle:


•OAuth2 authentication

•Access tokens

•API calls with credentials

This project demonstrates the frontend component only. Full integration can be added via a backend using the SP-API documentation.

Improvements required:


•Backend integration for real-time data fetching

•Custom invoice branding and templates

•Batch PDF download

•Localization support
