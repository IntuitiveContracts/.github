# Coverage in a Click

Coverage in a Click is an application designed to provide a seamless and convenient experience for customers looking to purchase battery warranties for their vehicles. With easy VIN search functionality, multiple payment options, and efficient checkout processes, our application aims to ensure customer satisfaction and offer a reliable solution to avoid recurring battery replacement costs. Additionally, we provide an opportunity for individuals to become ambassadors and earn commissions by promoting our unique automotive product.
-----------------

## Table of Contents

- [Purpose](#purpose)
- [Technical Getting Started](#technical-getting-started)
- [Target Audience](#target-audience)
- [Requirements](#requirements)
- [Operational Processes](#operational-processes)
- [Code Documentations](#code-documentations)
- [Repositories](#repositories)

## Purpose
-----------------
The primary purpose of the Coverage in a Click application is to provide a good sale experience to the customer by buying a battery warranty. The customer can search for warranties with their VIN, and if their vehicle is supported, they can proceed to checkout and finish through different payment methods.

## Technical Getting Started

---

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Target Audience
-----------------
This application aims to fit two types of necessities: the vehicle owner who wants a better experience when replacing batteries and a businessperson who wants to sell products and earn a commission.

### User Persona

**Name:** John Doe  
**Age:** 35  
**Occupation:** Office Manager  
**Location:** California, USA  
**Vehicle:** 2019 Honda Accord  
**Goals:**
- Find a reliable and cost-effective solution to avoid recurring battery replacement costs
- Verify that his vehicle is eligible for a lifetime battery warranty
- Complete the purchase quickly and securely using a preferred payment method

### Ambassador Persona

**Name:** Jane Smith  
**Age:** 28  
**Occupation:** Car Blogger and YouTuber  
**Location:** Texas, USA  
**Goals:**
- Generate additional income by promoting a valuable and unique automotive product
- Register as an ambassador quickly and effortlessly
- Receive a unique affiliate link to share with her audience and track her commissions

## Requirements
-----------------
Based on the system documentation and other related documents, the following requirements have been identified:

**User**
- Provide a seamless and user-friendly UI to provide a good UX in the purchase journey.
- Provide an input to provide the VIN number and verify if the vehicle is supported for the available warranties.
- Have multiple payment method options.
- All purchase process will be online without any unnecessary human interactions.
- Receive purchase details and warranty contract via email.

**Ambassador**
- Offer discounts to customers through an ambassador program.
- Provide ambassador link generation.
- Provide an easy ambassador registration for product promotion.
- Provide metrics, such as the number of lifetime battery warranties sold, the percentage of revenue generated through affiliate marketing, or the customer satisfaction rate.

## Operational Processes
-----------------
### How do customers replace batteries?

**With Coverage in a Click**
Customers can replace batteries by simply clicking one of the following links:
- [Coverage in a Click - Lifetime vehicle coverage](https://www.coverageinaclick.com/)
- [Get Coverage in a Click - Fast and Easy Insurance Quotes](https://www.coverageinaclick.com/getCoverage)

By entering the Vehicle Identification Number (VIN), customers can proceed to a three-step checkout process, allowing them to enjoy a lifetime of battery coverage within one minute.

**Without Coverage in a Click**
Without Coverage in a Click, vehicle owners will rely on the limited coverage and warranties provided by the manufacturer. This may result in additional costs for recurrent and atypical battery repairs, as well as the need to visit specialized dealerships with poor customer service.

### How do the dealership and customers validate the coverage?

**With Coverage in a Click**
Dealerships can validate the coverage for any vehicle by accessing the battery coverage contract within the Coverage in a Click or LodeStar Re (Coverage Administrator)