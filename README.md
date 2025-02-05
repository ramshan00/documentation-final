#  6-Days Journey of Building an Online Marketplace

Welcome to the documentation of my exciting 6-day journey of creating an **Online Marketplace** from scratch! This file outlines the daily progress, challenges, and achievements of this project.


## **Day 1: Laying the Foundation**

### Accomplishments:

1. **Marketplace Type Chosen:** General E-Commerce.

   - **Purpose:** Provide a platform for users to browse and purchase a wide range of products conveniently.

2. **Business Goals Defined:**

   - **Problem Solved:** Bridging the gap between users and high-quality, affordable products.
   - **Target Audience:** Online shoppers looking for a seamless experience.
   - **Key Features:** Speed, affordability, and a user-friendly interface.

3. **Data Schema Created:**

   - Entities:
     - **Products:** ID, Name, Price, Image.
     - **Orders:** Order ID, Customer Info, Order Details, Status.
   - Relationships diagrammed to ensure a solid database structure.


## **Day 2: Technical Planning**

### Accomplishments:

1. **System Architecture:**

   - Created a diagram showcasing interactions between the frontend, Sanity CMS, and APIs.
   - Defined the roles of each component for clarity.

2. **User Workflows:**

   - Outlined key workflows, such as browsing products, adding to cart, and placing orders.

3. **API Endpoints:**

   - Designed and documented key endpoints:
     - `/products` (GET) - Fetch all product details.

4. **Sanity CMS Schema:**

   - Example schema for products:
     ```js
     export default {
       name: 'product',
       type: 'document',
       fields: [
         { name: 'name', type: 'string', title: 'Product Name' },
         { name: 'price', type: 'number', title: 'Price' },
         { name: 'image', type: 'image', title: 'Product Image' }
       ]
     };
     ```


## **Day 3: API Integration and Data Migration**

### Accomplishments:

1. **API Integration:**

   - Successfully integrated APIs to fetch product data dynamically.

2. **Schema Adjustments:**

   - Refined database schema for better data representation.

3. **Migration Steps:**

   - Migrated initial data into Sanity CMS.
   - Ensured data consistency and validated fields.

4. **Best Practices Followed:**

   - Utilized `.env` files for API keys.
   - Modularized code and documented every step.

5. **Testing:**

   - Verified API responses using Thunderclient.
   - Logged discrepancies for future fixes.


## **Day 4: Building Dynamic Frontend Components**

### Accomplishments:

1. **Dynamic Product Listing:**

   - Fetched products from Sanity CMS and displayed them dynamically.

2. **Product Detail Pages:**

   - Implemented dynamic routes for viewing individual products.

3. **Search and Filters:**

   - Added a stateful search bar and dynamic category filters.


4. **Cart Functionality:**

   - Built a cart system for adding, updating, and removing products.

5. **Styling:**

   - Leveraged Tailwind CSS for a clean and responsive UI.



## **Day 5: Testing and Quality Assurance**

### Accomplishments:

1. **Functional Testing:**

   - Verified all core features, including cart operations, product listing and product details.

2. **Error Handling:**

   - Tested error responses and implemented user-friendly messages for API failures.

3. **Performance Optimization:**

   - Optimized images and implemented lazy loading.

4. **Cross-Browser Testing:**

   - Ensured compatibility across Chrome, Edge.

5. **Security Testing:**

   - Validated inputs and secured all communication via HTTPS.

6. **Documentation:**

   - Documented testing results and noted areas for improvement.

---

## **Day 6: Deployment and Staging Setup**

### Accomplishments:

1. **Hosting on Vercel:**

   - Deployed the project with smooth integration for Next.js.

2. **Environment Variables:**

   - Configured sensitive data securely.

3. **Staging Deployment:**

   - Validated the staging environment to ensure readiness for production.

4. **Performance Checks:**

   - Conducted Lighthouse tests to optimize performance further.





### Conclusion:

This 6-day journey has been a great learning experience, from foundational planning to deployment. Each step brought valuable insights into creating a scalable and user-friendly marketplace. Looking forward to the next phases of this project!



