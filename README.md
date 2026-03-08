ARTAM PH Chatbot Integration

This repository contains the web front-end for ARTAM PH, a specialized e-commerce platform for handcrafted crochet and custom stationery. The project includes a live AI chatbot integration: ARTAM Assist - designed to enhance customer engagement and streamline inquiries.

---

Project Overview

ARTAM PH is a business offering unique, handmade items ranging from amigurumi and crochet bouquets to bespoke journals. This website serves as the primary digital storefront, featuring:

* Product Showcase: A dynamic catalog of latest products including milk cotton yarn, amigurumi, and stationery.
* Customer Reviews: Real-time feedback and testimonials from the community.
* Contact and Support: Integrated contact forms and social media links including Shopee, TikTok, Instagram, and Facebook.

---

Chatbot: ARTAM Assist

The website features an AI-powered chatbot powered by Chatling, configured to handle niche-specific queries regarding crochet materials, custom orders, and shop locations.

Key Features
* 24/7 Customer Support: Instant responses to common questions about product availability and pricing.
* Order Guidance: Helps users navigate through categories like Sanrio Amigurumi or Fiber Fillings.
* Quick Links: Direct access to Shopee and social media platforms.
* FAQ Support: Automated responses to frequently asked questions regarding shipping, payment methods (COD), and custom order lead times.
* Order Tracking: Seamless direction to Shopee and external platforms for real-time status updates on active purchases.
* Smart AI Chat Support: Utilizes natural language processing to understand specific crochet-related terminology and provide personalized crafting advice.

Technical Implementation
The chatbot is integrated via a lightweight JavaScript snippet located in the `<head>` of `index.html`:

```html
<script> window.chtlConfig = { chatbotId: "6327952384" } </script>
<script async data-id="6327952384" id="chtl-script" type="text/javascript" src="[https://chatling.ai/js/embed.js](https://chatling.ai/js/embed.js)"></script>
