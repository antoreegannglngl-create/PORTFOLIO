ARINTLSUPPORT WEBSITE STARTER
=============================

FILES
- index.html: responsive homepage and service content
- styles.css: dark navy and blue design
- script.js: mobile navigation, WhatsApp link, inquiry form demo, preset-response chatbot, local homepage editor

PREVIEW LOCALLY
1. Extract the ZIP file.
2. Open index.html in Chrome, Edge, or Firefox.

BEFORE PUBLISHING
1. Edit script.js and replace CONFIG.whatsappNumber with your WhatsApp number in international format, digits only (example format: 9715XXXXXXXX).
2. Replace CONFIG.email with your actual business email.
3. Change ADMIN_PASSWORD from CHANGE-THIS-PASSWORD. This password is only a demo gate, not secure website authentication.
4. Replace portfolio concept cards with real projects and approved case studies.
5. The inquiry form currently opens the visitor's default email app using mailto. It does not automatically store or send inquiries. Connect a secure form backend/service before launch.
6. The chatbot uses preset answers; it is not connected to a live AI model. For a real AI chatbot, connect a backend to your AI provider. Never put secret API keys in browser JavaScript.
7. The homepage editor is available by visiting index.html?admin=1, but saves changes only in that browser's local storage. For a shared admin panel, use a secure CMS/backend with authentication and database storage.
8. Upload index.html, styles.css, and script.js to your hosting account's web root (often public_html, www, or httpdocs). Configure HTTPS/SSL with your host.
9. Test contact links and mobile display before launch. Add privacy and other legal pages as appropriate for your business.

This is a front-end starter, not a production CMS/backend. No form submissions are collected by this package.
