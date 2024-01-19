# E-SHOP Documentation

## UNIVERSITY OF RWANDA
**NYARUGENGE CAMPUS**
**ICT/CSE**
**MODULE: SOFTWARE DESIGN AND DEVELOPMENT**

### PROJECT PARTNERS:
- [AMIZERO SIFA  221011109]()
- [UWIMANA LIBERTHA 221006043](https://github.com/liberee1)

### DATE: JANUARY 19, 2024

### PROJECT NAME: E-SHOP

---

## TABLE OF CONTENTS
- [PURPOSE](#purpose)
- [SCOPE](#scope)
- [OVERVIEW](#document-overview)
- [REFERENCES](#references)
- [TABLE OF FIGURES](#table-of-figures)
- [LIST OF ABBREVIATIONS](#list-of-abbreviations)
- [Chapter 1. Introduction](#chapter-1-introduction)
  - [1.1 Historical background of the case study](#11-historical-background-of-the-case-study)
  - [1.2 Problem Statement](#12-problem-statement)
  - [1.3 Objectives of my project](#13-objectives-of-my-project)
- [Chapter 2. System analysis and design](#chapter-2-system-analysis-and-design)
  - [2.1 System analysis](#21-system-analysis)
    - [2.1.1 Functional requirement of project](#211-functional-requirement-of-project)
    - [2.1.2 Intended users of project](#212-intended-users-of-project)
  - [2.2 System design](#22-system-design)
    - [2.2.1 Database design with ERD and relationship](#221-database-design-with-erd-and-relationship)
- [Chapter 4. Implementation](#chapter-4-implementation)
  - [4.1 All screenshots with captions and discussion](#41-all-screenshots-with-captions-and-discussion)
  - [4.2 Recommendation: Link for project](#42-recommendation-link-for-project)
  - [4.3 CONCLUSION](#43-conclusion)

## PURPOSE
The E-Shop platform is developed with the overarching purpose of creating a versatile and efficient online marketplace that facilitates seamless transactions between buyers and sellers.

## SCOPE
The E-Shop platform encompasses a comprehensive set of features and functionalities designed to create a robust and user-friendly online shopping experience.

## DOCUMENT OVERVIEW
This document describes the structure of the E-SHOP, including high-level components, their interactions, physical arrangement, design decisions, and detailed information on the system.

## REFERENCES
Refer to the project partners and any external resources used in the development of the E-Shop platform.

## TABLE OF FIGURES
Include figures that illustrate the E-Shop platform, such as screenshots, diagrams, or charts.

## LIST OF ABBREVIATIONS
Provide a list of abbreviations used throughout the document.

---

## Chapter 1. Introduction

### 1.1 Historical background of the case study:
The historical background traces the evolution of online shopping and e-commerce, providing context for the development of the E-Shop platform.

### 1.2 Problem Statement:
Users faced a fragmented and inconsistent experience while navigating various online shopping platforms. The lack of a unified design and user interface across devices resulted in confusion and hindered user engagement.

### 1.3 Objectives of my project:
The E-Shop focused on fostering user engagement by introducing features like wishlists and integrating social media logins, aiming to create a more interactive shopping experience.

---

## Chapter 2. System analysis and design

### 2.1 System analysis:

#### 2.1.1 Functional requirement of project:
Define specific features and capabilities that the E-Shop platform must possess to meet the needs of users and administrators.

#### 2.1.2 Intended users of project:
- Shoppers
- Reviewers
- Administrators
- General users
- Wishlist creators
- System partners

### 2.2 System design:

#### 2.2.1 Database design with ERD and relationship:
Include detailed information about the database design using Entity-Relationship Diagrams (ERD) and relationships.

---

## Chapter 4. Implementation

### 4.1 All screenshots with captions and discussion
Explore various screenshots showcasing different aspects of the E-Shop platform with relevant captions and discussions.

### 4.2 Recommendation: Link for project
Include a link or information on where to access the E-Shop project.

### 4.3 CONCLUSION
Summarize the development journey, emphasizing the collaboration, planning, design, and implementation that went into creating the E-Shop platform.

---

## Features:
- PWA (Progressive Web App)
- Responsive Layout
- Shopping Cart, Wishlist, Product Reviews
- Coupons & Discounts
- Product attributes: cost price, promotion price, stock, size...
- Blog: category, tag, content, web page 
- Module/Extension: Shipping, payment, discount, ...
- Upload manager: banner, images,..
- SEO support: customer URL b
- Newsletter management
- Contact forms with real-time notification (Laravel Pusher)
- Related Products, Recommendations
- Product search form
- Laravel Socialite implement(Facebook, Google & twitter) & Customer login
- Payment integration(Paypal)
- Order Tracking system
- Multi-level comment system
and many more...

### Admin:
- Admin roles, permission
- Product manager
- Media manager using unisharp laravel file manager
- Banner manager
- Order management
- Category management
- Brand management
- Shipping Management
- Review Management
- Blog, Category & Tag manager
- User Management
- Coupon Management
- System config: email setting, info shop, maintain status,...
- Line Chart & Pie chart ...
- Generate order in pdf form...
- Real-time message & notification
- Profile Settings
and many more...

### User Dashboard:
- Order management
- Review Management
- Comment Management
- Profile Settings

## Set up:

1. Clone the repo and cd into it
2. In your terminal `composer install`
3. Rename or copy `.env.example` file to `.env`
4. `php artisan key:generate`
5. Set your database credentials in your `.env` file
6. Set your Braintree credentials in your `.env` file if you want to use PayPal
7. Import db file(`database/e-shop.sql`) into your database (`mysql,sql`)
8. `npm install`
9. `npm run watch`
10. Run command[laravel file manager]:-  `php artisan storage:link`
11. Edit `.env` file: remove APP_URL
12. `php artisan serve` or use virtual host
13. Visit `localhost:8000` in your browser
14. Visit `/admin` if you want to access the admin panel. Admin Email/Password: `admin@gmail.com`/`1111`. User Email/Password: `user@gmail.com`/`1111`

**Thank You so much for your time !!!**

## Screenshots:

![screencapture-e-shop-loc-admin-2020-08-15-15_47_37](https://user-images.githubusercontent.com/29488275/90719413-13b82200-e2d4-11ea-8ca0-f0e
