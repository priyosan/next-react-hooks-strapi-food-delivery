
##Create a Food Ordering App with Strapi and Next.js 1/7
#Learn how to create a food ordering app with Strapi and Next.js using React Hooks.
Strapi
Strapi
Strapi

·
Follow

Published in
Strapi

·
9 min read
·
Jun 29, 2023
1







##Tutorial updated by Fredrick Emmanuel and Paul Bratslavsky

This tutorial will walk you through how to use Next.js to power your UI, complete using GraphQL, Stripe, Strapi, and Next to developing a full-stack application complete with the powerful Strapi (Headless CMS) powering the backend.

Get ready to develop an online food ordering app, more info on the tech stack here: Next.js, GraphQL, Stripe and Strapi! From sign up to order, you are going to let users discover restaurants, dishes and order meals.

Your app will be complete with user login, registration, authentication, image upload, restaurant creation, dish creation, cart functionality, and stripe order integration. The demo of the final result should make you hungry:

Note: The source code is available on GitHub for Frontend and Backend.

Screenshots of final product:

Strapi
Strapi is the most advanced open-source Node.js Headless Content Management System used to build scalable, secure, production-ready APIs quickly and efficiently saving developers countless hours of development. With its extensible plugin system, it provides an enormous set of built-in features: Admin Panel, Authentication & Permissions management, Content Management, API Generator, etc. Strapi is 100% open-source, which means:

Strapi is completely free.
You can host it on your servers, so you own the data.
It is entirely customizable and extensible, thanks to the plugin system.
Next.js
Next is a lightweight React framework to create server-rendered applications. Next.js will take care of the heavy lifting of the application build such as code splitting, HMR (hot module replacement) SSR (server-side rendering) and allow us to focus on writing the code, not our build config.

GraphQL
GraphQL is a query language also developed by Facebook to allow the front end of an application to easily query an application’s API. Each query requests only the data needed to be rendered by the current view. This allows the developer to craft a great user experience across multiple devices and screen sizes.

Stripe
Stripe is one payment processor for applications today. Stripe has developed the tools and SDKs to allow developers to craft and integrate secure, compliant payment processing into any app with ease.

Table of contents
🏗️ Setup (part 1) — Current
🏠 Restaurants (part 2)
🍔 Dishes (part 3)
🔐 Authentication (part 4)
🛒 Shopping Card (part 5)
💵 Order and Checkout (part 6)
🚀 Bonus: Deploy (part 7)
