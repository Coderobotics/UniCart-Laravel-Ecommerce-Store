# UniCart Laravel Ecommerce Store

UniCart is a self-hosted e-commerce and retail management system sold as complete source code on Coderobotics. It is built with Laravel 12, Livewire 3, Alpine.js, Tailwind CSS v4 and MySQL/MariaDB, and combines an online storefront, an offline-first POS system and a full back office in one application. The storefront supports product variants, digital downloads, bundles, multi-currency pricing and checkout with Razorpay, Stripe, PayPal and cash on delivery. The POS runs in the browser as a PWA, keeps selling without an internet connection and syncs sales automatically when the connection returns. The back office covers inventory, purchasing, suppliers, expenses, coupons, gift cards, loyalty points, reviews, staff roles with two-factor sign-in, and backups. For Indian businesses, it produces GST invoices, credit notes and GSTR-1/GSTR-3B reports; other countries use a generic tax engine. UniCart suits retail shops that sell both online and in-store, as well as developers and agencies who want a modern Laravel e-commerce codebase. It is sold for a one-time payment with no encryption or domain limits, and includes one year of free updates and email support.

<img src="https://www.coderobotics.com/frontend/assets/icon/unicart-laravel-ecommerce-online-store.jpg">

Most small retailers end up paying for three or four separate tools: a website builder for online sales, a POS app for the counter, a spreadsheet for stock and an accountant’s tool for tax returns. None of them share data. Stock drifts, prices don’t match and month-end reports take days. UniCart replaces all of them with one self-hosted system. The storefront, the till, inventory, purchasing, marketing and accounting reports all work from the same database.

What You Get
 
Storefront

Home page you can edit, product listings with filters, full-text search and a slide-out cart
Product types: simple, with variants (size, colour), digital downloads with licence keys, and bundles
Customer accounts with addresses, wishlist, order tracking, downloads and data export
Prices shown in the shopper’s currency, with optional fixed prices per currency
Installable as an app (PWA), with sitemap, schema.org structured data and browser push notifications for order updates
Layouts ready for right-to-left (RTL) languages
Checkout & Orders

One-page checkout with Razorpay, Stripe, PayPal and cash on delivery
Shipping zones, stock reserved when an order is placed, and unpaid orders cancelled automatically
GST invoices and credit notes as PDFs, with gap-free numbering for each financial year
Shipments with tracking, refunds, returns and digital delivery
Staff can create manual orders and email the customer a payment link
Offline-First POS (Point of Sale)

Browser-based till that keeps selling with no internet connection and syncs automatically when the connection returns
Terminal pairing and cashier PIN sign-in
Barcode scanning with a USB scanner or the device camera
Line and cart discounts, with a manager PIN required above set limits
Cash, card and UPI payments, GST receipts, held sales and returns at the till
Shifts with cash in/out and X/Z reports
Catalogue & Inventory

Media library with automatic WebP images, categories, brands, attributes and size charts
CSV import and export, a stock ledger for every movement, stocktakes and barcode label printing
Low-stock alerts by email
Purchasing & Expenses

Suppliers, purchase orders and goods receipts (full or partial)
Average or last cost price updated automatically on each goods receipt
Supplier payments and balances, and expenses with receipt uploads
Marketing

Coupons, automatic discounts (sales, buy X get Y) and customer group pricing
Gift cards, loyalty points and abandoned-cart emails
Reviews with photos and moderation, verified-buyer badges, and product Q&A
CMS pages, blog and scheduled banners
Reports & Tax

Dashboard, sales reports, profit & loss, stock valuation and stock movements
GST working papers for GSTR-1 (B2B, B2CL, B2CS, exports, credit notes, HSN, documents) and GSTR-3B, with CSV export
Generic tax engine for non-GST countries: tax rates by country, state or postcode, including compound rates
Payment reconciliation, plus customer and offer reports
Administration & Security

Staff roles with detailed permissions (Super Admin, Store Manager, Catalogue Editor, Fulfilment, Accountant, Cashier)
Two-factor sign-in for staff, with recovery codes
Full audit log, nightly backups with restore steps, and security headers
Email and SMS templates you can edit, with live preview. SMS works with Twilio or any HTTP API provider (MSG91, Textlocal, Fast2SMS, Exotel and similar)
Web installer: set up in four steps from the browser

Why This Tool?
 
Running online and in-store sales on separate systems means stock that doesn’t match, duplicate data entry and tax reports you have to put together by hand. UniCart puts every channel in one place, on your own server.

One stock, one price list. Online orders and till sales draw from the same inventory.
The POS works offline. Sales are never lost when the connection drops; they sync automatically later.
GST built in. CGST/SGST/IGST split, cess, exports under LUT, and invoices and credit notes that match your returns.
Self-hosted, no monthly fees. Your data stays on your server, with no per-order commission and no SaaS subscription.
Complete, tested source code. Covered by automated unit, feature, end-to-end, accessibility (WCAG 2.1 AA) and performance tests.

Perfect For
 
Retail shops that sell online and in-store
Clothing, electronics, grocery and gift stores
Indian businesses that need GST-compliant invoices and return reports
Sellers of digital products, software licence keys and gift cards
Agencies and freelancers building e-commerce sites for clients
Developers who want a modern Laravel + Livewire e-commerce codebase to extend

Tech Stack
 
Laravel 12 (PHP 8.2+)
Livewire 3
Alpine.js
Tailwind CSS v4
MySQL 8 / MariaDB 10.11+
PWA with service worker and IndexedDB (offline POS)
PHPUnit and Puppeteer (automated tests)
Payment gateways: Razorpay, Stripe, PayPal

Prerequisites
 
PHP 8.2 or higher with these extensions: bcmath, ctype, fileinfo, gd, intl, mbstring, openssl, pdo_mysql, tokenizer, xml, zip
MySQL 8 or MariaDB 10.11+
Composer 2
Node.js 20+ (for building front-end assets)
A cron job (or Task Scheduler) running every minute, for emails, SMS, exchange rates and backups
HTTPS for live use (needed for the PWA, push notifications and payment webhooks)

More details and download link:
https://www.coderobotics.com/product/unicart-laravel-ecommerce-store

