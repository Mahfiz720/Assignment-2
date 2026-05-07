# Flower Shop

এটি একটি ফ্লাওয়ার শপ (Flower Shop) এর রেসপনসিভ ওয়েব পেজ, যা অ্যাসাইনমেন্ট ২ হিসেবে তৈরি করা হয়েছে।

## প্রজেক্টের বিস্তারিত বিবরণ (Project Details)

এই রিপোজিটরির সম্পূর্ণ কোড বিশ্লেষণ করে নিচে প্রজেক্টটিতে ব্যবহৃত প্রযুক্তি ও উপাদানগুলোর বিস্তারিত বিবরণ দেওয়া হলো:

### ১. মূল প্রযুক্তি (Core Technologies)
* **HTML5:** ওয়েবসাইটের মূল স্ট্রাকচার তৈরি করতে HTML5 এর ব্যবহার করা হয়েছে। কোডটিকে গুছিয়ে লেখার জন্য সিমেন্টিক ট্যাগ যেমন `<header>`, `<nav>`, `<main>`, `<section>`, এবং `<footer>` ব্যবহার করা হয়েছে।
* **CSS3:** ওয়েবসাইটটির ডিজাইন এবং স্টাইলিং এর জন্য এক্সটার্নাল CSS (`styles.css`) ব্যবহার করা হয়েছে।

### ২. লেআউট সিস্টেম (Layout Systems)
* **Flexbox (ফ্লেক্সবক্স):** নেভিগেশন বার, কার্ডের ভিতরের উপাদান, এবং ফুটার সাজানোর জন্য `display: flex` এর প্রচুর ব্যবহার করা হয়েছে। এটি উপাদানগুলোকে সুন্দরভাবে অ্যালাইন এবং স্পেস করতে সাহায্য করেছে।
* **CSS Grid (সিএসএস গ্রিড):** প্রোডাক্ট কার্ডগুলোকে এবং লেটেস্ট ডিলসের কার্ডগুলোকে গ্রিড আকারে সাজানোর জন্য `display: grid` ব্যবহার করা হয়েছে। যেমন, প্রোডাক্ট সেকশনে `grid-template-columns: repeat(4, 1fr);` ব্যবহার করে ৪টি কলাম তৈরি করা হয়েছে।

### ৩. টাইপোগ্রাফি এবং ফন্ট (Typography and Fonts)
প্রজেক্টটিতে **Google Fonts** থেকে দুটি ফন্ট ইম্পোর্ট করা হয়েছে:
* **Noto Serif:** হেডিং এবং টাইটেলগুলোর জন্য (যেমন: `heading-primary`, `product-title`, `store-title`) ব্যবহার করা হয়েছে যাতে একটি প্রিমিয়াম লুক পাওয়া যায়।
* **Inter:** প্যারাগ্রাফ, ডেসক্রিপশন এবং বাটনগুলোর জন্য ব্যবহার করা হয়েছে, যা পড়তে অনেক সহজ।

### ৪. আইকন (Icons)
* **FontAwesome:** নেভিগেশন বারের শপিং কার্ট আইকনটির (`<i class="fa-solid fa-cart-arrow-down"></i>`) জন্য FontAwesome এর CDN ব্যবহার করা হয়েছে।
* এছাড়া ফুটারে সোশ্যাল মিডিয়ার লিংকগুলোর জন্য কাস্টম ইমেজ আইকন (যেমন: Facebook, Twitter, LinkedIn, YouTube) ব্যবহার করা হয়েছে।

### ৫. রেসপনসিভ ডিজাইন (Responsive Design)
* মোবাইল এবং ছোট স্ক্রিনের ডিভাইসের জন্য CSS এ **Media Queries** (`@media screen and (max-width: 576px)`) ব্যবহার করা হয়েছে।
* ছোট স্ক্রিনে নেভিগেশন লিঙ্কগুলো হাইড করা হয়েছে, লেআউটের দিক (flex-direction) পরিবর্তন করে কলাম-ভিত্তিক করা হয়েছে এবং গ্রিড কলামের সংখ্যা কমিয়ে আনা হয়েছে, যাতে সব সাইজের ডিভাইসে ওয়েবসাইটটি ঠিকমতো দেখা যায়।

### ৬. অন্যান্য বৈশিষ্ট্য (Other Features)
* **ইমেজ এবং অ্যাসেটস:** প্রজেক্টটিতে বিভিন্ন সেকশনে লোকাল ফোল্ডার (`assets/`) থেকে ইমেজ ব্যবহার করা হয়েছে। ব্যাকগ্রাউন্ড ইমেজ হিসেবেও কিছু অ্যাসেট ব্যবহার করা হয়েছে (যেমন: ফর্ম সেকশন)।
* **ফর্ম:** নিউজলেটার সাবস্ক্রাইব করার জন্য একটি সিম্পল HTML ফর্ম (`<form>`) ব্যবহার করা হয়েছে।

## Links

* [GitHub Repository](https://github.com/Mahfiz720/Assignment-2)
* [GitHub Live Demo](https://mahfiz720.github.io/Assignment-2/)
* [Vercel Live Demo](https://assignment-2-rho-self.vercel.app/)

## File Tree

```
.
├── assets
│   ├── deal-ana.png
│   ├── deal-bloom.png
│   ├── deal-zabo.png
│   ├── flower-store.png
│   ├── hero-flower.png
│   ├── icon-facebook.png
│   ├── icon-linkedin.png
│   ├── icon-twitter.png
│   ├── icon-youtube.png
│   ├── logo.png
│   ├── news-letter-bg.png
│   ├── sample-flower-image.png
│   └── trusted-badge.png
├── flower-market.fig
├── index.html
├── readme.md
└── styles.css
```
