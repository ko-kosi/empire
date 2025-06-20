KnowEmpire Marketplace Documentation
1. Introduction
The KnowEmpire Marketplace is a peer-to-peer (P2P) platform designed to facilitate trustless trading of goods and services. Built with a focus on crypto-native experiences and integration with the Farcaster ecosystem, it aims to connect buyers and sellers securely, transparently, and efficiently. Users can earn $KNOW points through various interactions, including successful transactions daliy streaks and referral programs.
2. Key Features
For Sellers:
Seller Registration: Easy onboarding process to become a seller, specifying the type of items/services to sell (Goods, Digital, Services).

Product Listing: Post products/services with details such as name, description, price (in $KNOW), category, image, and location.

AI-Powered Content Generation:

Enhance Description: Utilize an integrated AI (Gemini 2.0 Flash) to generate more compelling and detailed product descriptions.

Generate Catchy Headlines: Get AI-suggested headlines for your products to improve visibility and appeal.

Product Management: View and (simulated) edit/delete your posted listings.

Notifications: Receive real-time notifications for new inquiries, successful purchases, and service agreements from buyers.

For Buyers:
Buyer Registration: Simple registration to start browsing and purchasing.

Product Browsing: Explore products and services listed by sellers, filtered by category (All, Goods, Digital, Services).

Buyer-Seller Interaction:

Goods: Initiate an order inquiry, specify quantity, and proceed to simulated payment.

Digital: Direct purchase with simulated payment and instant download access.

Services: Send a service request with preferred date/time and location details.

Notifications: Receive notifications regarding order inquiries, availability confirmations, and purchase receipts.

General Features:
Know Points System: Earn Know Points for daily logins and successful transactions.

Farcaster Wallet Integration (Simulated): Placeholder for future Farcaster wallet connection for decentralized interactions.

Referral System: Share the platform and earn commissions from referred users' earnings.

Theme Toggle: Switch between light and dark themes for personalized viewing.

Toast Notifications: Non-intrusive on-screen messages for user feedback (e.g., "Product posted successfully!").

3. User Roles
The marketplace supports two primary user roles:

Buyer: Focuses on browsing available products and services, initiating purchases, and receiving relevant notifications.

Seller: Focuses on listing products/services, managing their offerings, and responding to buyer inquiries and purchases.

A single email address can register as either a buyer or a seller. The system logs the last registered role and email to restore the dashboard experience upon returning.

4. How to Use
4.1. Registration
As a Buyer:

On the landing page, click "Register as Buyer".

Enter your email address and click "Register as Buyer".

The dashboard will load after a short countdown, defaulting to the "Browse Products" section.

As a Seller:

On the landing page, click "Register to Sell".

Fill in your email, select your selling category (Goods, Digital, or Services), provide a brief description, optionally add a portfolio link, and select your location.

Check the agreement checkbox and click "Register as Seller".

The dashboard will load, defaulting to the "My Listings" (Post) section.

4.2. Posting a Product (Seller Role)
Ensure you are logged in as a seller. The dashboard should show the "My Listings" section.

Click the + (Add) floating action button (FAB) at the bottom right.

Fill in the product details:

Image: Upload a product image (optional, but recommended).

Product Name: Enter the name of your product.

Description: Provide a detailed description. Use "✨ Enhance Description" to get AI assistance.

Price ($KNOW): Set the price in $KNOW tokens.

Category: Select "Goods", "Services", or "Digital".

If "Digital" is selected, specify "Digital Product Type" and upload a "Digital File".

Location: Specify your location.

Optionally, use "✨ Generate Catchy Headlines" to get AI suggestions for your product name. Click a suggestion to use it.

Click "Post Product". Your listing will appear in your "My Listings" and be visible to buyers.

4.3. Browsing and Purchasing (Buyer Role)
Ensure you are logged in as a buyer. The dashboard should show the "Browse Products" section.

Use the category tabs (All, Goods, Services, Digital) to filter listings.

Click on any product card to view its details in a modal.

To Purchase/Interact:

Goods: Click "Buy Now" on the product card or within the detail modal. In the subsequent modal, adjust quantity and click "Proceed to Pay". Confirm payment to complete the simulated transaction.

Digital: Click "Buy Now" or "Chat Seller". In the modal, click "Buy" to complete the simulated payment. A "Download Product" button will appear.

Services: Click "Chat Seller". In the modal, specify preferred date/time and location, then click "Agree & Send Request". This sends a service request notification to the seller.

4.4. Managing Notifications
Click on the "Notifications" button in the bottom navigation bar (or from the "Menu" if in other sections).

Your notification list will display. Unread notifications are highlighted.

Click on a notification to mark it as read.

For certain notifications (e.g., Goods Order Inquiry for sellers, Goods Availability Confirmed for buyers), action buttons will appear to facilitate the next step in the transaction.

5. Technical Overview
The KnowEmpire Marketplace is a client-side application implemented using standard web technologies:

HTML5: Structures the content of the web pages.

CSS3: Styles the application, ensuring a responsive and visually appealing user interface with a modern design and dark theme support.

JavaScript (ES6+): Handles all application logic, user interactions, data management, and dynamic content rendering.

Local Storage: Used for persistent storage of user session data (email, role), posted products, and user-specific notifications. This simulates database persistence for demonstration purposes.

Gemini API (Simulated): Integration with Google's Gemini 2.0 Flash model is simulated for AI features like enhancing product descriptions and generating headlines. Actual API calls are made but the API key is handled by the Canvas environment.

Simulated Transactions: Payments and product delivery are simulated client-side, demonstrating the workflow without actual blockchain interaction or real money.

No External Frameworks: The application is built using vanilla JavaScript to minimize dependencies and demonstrate core web development concepts.

6. Future Enhancements
Blockchain Integration: Implement actual smart contracts for decentralized escrow and $KNOW token transactions.

Real-time Chat: Integrate a real-time messaging system for direct buyer-seller communication beyond notifications.

User Profiles: Enhance user profiles with reputation systems, transaction history, and customizable avatars.

Advanced Search & Filters: Implement more robust search capabilities and filtering options for products.

Dispute Resolution: Develop a mechanism for resolving disputes between buyers and sellers.

Payment Gateway Integration: Connect with real crypto payment gateways for $KNOW token payments.

User Authentication: Implement a more secure authentication system (e.g., Firebase Auth, Web3 wallet-based login).

Seller Analytics: Provide sellers with insights into their product performance and sales.

Referral Tracking: Fully implement tracking and payout mechanisms for the referral system.

End of Documentation
