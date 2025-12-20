---
layout: project
type: project
image: img/rainbow-recipes/Rainbow-Recipes-Square-Guest-Landing.PNG
title: "Rainbow Recipes"
# All dates must be YYYY-MM-DD format!
date: 2025-12-10
published: true
labels:
  - Software Engineering
  - Full-Stack
  - Next.js
  - PostgreSQL
  - Team Project
summary: "A full-stack recipe-sharing platform built for UH students with role-based access, filtering, and vendor support."
---

## Project Overview
Rainbow Recipes is a full-stack web application created as the final project for ICS 314 (Software Engineering I). The goal of the project was to make a platform that students can share and browse recipes, view vendors, apply filters, sort items, and manage personalized content, like favorites and uploaded recipes. The application uses Next.js, TypeScript, Prisma, PostgreSQL, and NextAuth. Industry-style workflow was also followed, such as issue-driven project management, branching, and pull requests.

As a team, we designed the system to allow multiple user types (regular users, vendors, and admins) while keeping the interface clean and easy to use. The application was deployed with Vercel and initially used Neon for PostgreSQL hosting. As the project grew and exceeded the provider’s network usage limits, the team migrated to Supabase-hosted PostgreSQL. The database supported core application data, like user accounts, recipes, vendors, images, tags, and user-generated content such as favorites and reviews.

## My Role

I contributed to both the UI and functionality of the application. My tasks focused on the creation of pages, refining user experience, and building the search, filter, and sorting tools that make the app easier to navigate. Some of my main contributions included:
- Creating the Landing Page, Navbar, and About Page
- Implementing the Navbar categories component
- Refactoring the Favorites and My Recipes pages to use a shared RecipeList component
- Adding sort options to the Recipes page (e.g., cost low-to-high)
- Updating the Sign In page styling to match the rest of the app
- Implementing add/edit/delete features for dietary and appliance tags in the Admin page
- Linking each recipe’s author to an individual profile page
- Adding filter and sort tools to Vendor pages and My Store
- Implementing the search bar for vendor browsing
- Uploading Batch #3 of recipe entries
- Expanding the ingredient filters to include ingredient categories

These features helped improve the navigation, readability, and consistency of the application while giving users more ways to browse and manage recipes.

## Application Flow
Users begin on the guest landing page, where they can browse recipes or explore vendors without signing in. Guest users can search, filter, and sort recipes and view recipe details such as cost, prep time, and favorite counts. Signed-in users gain access to additional features such as saving favorites, publishing recipes, and accessing a customized navigation experience. Vendors can also be explored through an interactive map that displays store locations. Vendors manage their storefronts and inventory through dedicated pages, while administrators manage users, tags, and other application data through an admin dashboard.

<img src="/img/rainbow-recipes/rainbow-recipes-guest-landing.png" alt="Guest landing page" style="max-width:100%; height:auto; display:block; margin: 1.5em auto;">

<img src="/img/rainbow-recipes/rainbow-recipes-guest-recipes-page.png" alt="Recipes browsing page" style="max-width:100%; height:auto; display:block; margin: 1.5em auto;">

<img src="/img/rainbow-recipes/rainbow-recipes-vendor-map.png" alt="Vendor map view" style="max-width:100%; height:auto; display:block; margin: 1.5em auto;">

<img src="/img/rainbow-recipes/rainbow-recipes-vendor-mystore-page.png" alt="Vendor store management page" style="max-width:100%; height:auto; display:block; margin: 1.5em auto;">

<img src="/img/rainbow-recipes/rainbow-recipes-admin-dashboard.png" alt="Admin dashboard" style="max-width:100%; height:auto; display:block; margin: 1.5em auto;">

## Lessons Learned

Working on Rainbow Recipes taught me a large amount about real, team-based software engineering. I became more familiar with frameworks like Next.js and Prisma, and learned how much smoother development is when components are made reusable across the application. Implementing search, filter, and sorting logic also helped me think through data flow between the UI and database.

This project also taught me how to work as a team in software development. GitHub issues, branches, and pull requests made it much easier to be organized and to avoid conflicts. 
