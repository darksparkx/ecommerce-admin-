# Full Stack E-Commerce Dashboard & CMS: Next.js 13 App Router, React, Tailwind, Prisma, MySQL

For DEMO, use [Stripe Testing Cards](https://stripe.com/docs/testing)

Key Features:

-   Shadcn UI used for the interface
-   Our admin dashboard serves as both CMS, Admin and API
-   You can control mulitple vendors / stores through this single CMS (For example you can have a "Shoe store" and a "Laptop store" and a "Suit store", and the CMS will generate API routes for all of those individually)
-   You can create, update and delete categories
-   You can create, update and delete products
-   You can upload multiple images for products, and change them whenever you want
-   You can create, update and delete filters such as "Color" and "Size", and then match them in the "Product" creation form
-   You can create, update and delete "Billboards" which are these big texts on top of the page. You can attach them to a single category, or use them standalone (The Admin generates API for all of those cases)
-   You can Search through all categories, products, sizes, colors, billboards with included pagination
-   You can control which products are "featured" so they show on the homepage
-   You can see your orders, sales, etc
-   You can see graphs of your revenue etc
-   Authentication is implimented using Clerk
-   Order creation
-   Stripe checkout
-   Stripe webhooks
-   MySQL + Prisma + PlanetScale
