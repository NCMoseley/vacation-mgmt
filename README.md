# Vacation-MGMT

This repository is for an application similar in functionality to Airbnb and other vacation rental software. It is a full-stack app built with Next.js 13 App Router: React, Tailwind, Prisma, NextAuth and uses MongoDB as a data store. It is deployed on Vercel.

## Demo 

[Demo](https://vacation-mgmt.vercel.app/)

![Example](https://github.com/ncmoseley/vacation-mgmt/blob/main/public/images/vacations-mgmt-banner.png?raw=true)

## Features

- Features to enhance user experience
- Tailwind design for modern and responsive look
- Tailwind animations and effects for interactivity
- Fully responsive website for any device
- Authentication options: credential, Google, and Github
- Image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Calendars with react-date-range for simple date selection
- Booking/reservation system with guest and owner reservation cancellation options
- Property creation and deletion with pricing calculation
- Advanced search algorithm to filter properties by category, date range, map location, number of guests, rooms, and bathrooms
- Favorites system and shareable URL filters
- POST and DELETE routes in route handlers (app/api)
- Fetching data in server react components by directly accessing the database

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
