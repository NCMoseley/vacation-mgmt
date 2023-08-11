# Vacation-MGMT

This repository is for an application similar in functionality to Airbnb and other vacation rental software. It is a full-stack app built with Next.js 13 App Router: React, Tailwind, Prisma, NextAuth 2023 and uses MongoDB as a data store. It is deployed on Vercel.

## Features

- Tailwind design
- Tailwind animations and effects
- Full responsiveness
- Credential authentication
- Google authentication
- Github authentication
- Image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Calendars with react-date-range
- Page loading state
- Page empty state
- Booking / Reservation system
- Guest reservation cancellation
- Owner reservation cancellation
- Creation and deletion of properties
- Pricing calculation
- Advanced search algorithm by category, date range, map location, number of guests, rooms and bathrooms
    - For example we will filter out properties that have a reservation in your desired date range to travel
- Favorites system
- Shareable URL filters
    - Lets say you select a category, location and date range, you will be able to share URL with a logged out friend in another browser and they will see the same results
- How to write POST and DELETE routes in route handlers (app/api)
- How to fetch data in server react components by directly accessing database (WITHOUT API! like Magic!)
- How to handle files like error.tsx and loading.tsx which are new Next 13 templting files to unify loading and error handling
- How to handle relations between Server and Child components!

## Demo 

[Demo](https://vacation-mgmt-rcitk5ufh-ncmoseley.vercel.app/)

### Prerequisites

**Node version 14.x**
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Inspired by the following repositories

- [Antonio Erdeljac](https://github.com/AntonioErdeljac/next13-airbnb-clone/tree/master)
