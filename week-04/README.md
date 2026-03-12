# Week 04: The Management Layer (WordPress & Security)

## 🎯 Objective
Today we pivot from manual coding to **Website Management**. You will launch a live WordPress site for "Erasmus Brew," secure it against hackers, and optimize it for search engines (SEO).

---

## 🛠 Task 1: Free Hosting Setup (Pantheon)
We use Pantheon because it provides a professional "Sandbox" environment that allows us to use advanced plugins for free.

1.  Go to [Pantheon.io](https://pantheon.io/) and click **"Start Free"**.
2.  Register using your University email or Google account.
3.  Click **"Create New Site"** -> **"WordPress"**.
4.  Once the "Dashboard" loads, click **"Visit Development Site"** to finish the WordPress installation.

---

## 🎨 Task 2: Drag & Drop Design (Home Page)
Instead of coding, we will use the **Gutenberg** (Block) editor to recreate your landing page.

1.  Go to **Pages** -> **Add New**. Title it "Home".
2.  Use the **"+"** button to add "Blocks":
    - **Cover Block:** For your Hero Image.
    - **Heading Block:** For "Erasmus Brew".
    - **List Block:** For your Menu items.
3.  **Crucial Step:** Go to **Settings** -> **Reading** and set "Your homepage displays" to **A static page** (Select "Home").

---

## 🛡️ Task 3: Security & "The Bouncer"
Websites are attacked every minute. We will use two specific tools to protect our shop.

1.  **Wordfence Security:** Install and activate. This is your firewall.
2.  **WPS Hide Login:** - Install and go to Settings -> WPS Hide Login.
    - Change your login URL from `wp-admin` to something unique (e.g., `/coffee-gate` or `/secret-entrance`). 
    - **Write this URL down!** You will need it to log back in.

---

## 🔍 Task 4: SEO with RankMath
We use **RankMath** because it is faster and has more free features than Yoast.

1.  Install and activate **RankMath SEO**.
2.  Open your "Home" page editor.
3.  On the right sidebar, click the RankMath score button.
4.  **Edit Snippet:** Add a "SEO Description" that makes people want to click your link on Google.
5.  **Social Tab:** Upload a "Social Image." This is the image that will appear when you share your link on WhatsApp, X, or Facebook.

---

## 🏠 Homework: Expanding the Brew
To practice your management skills, you must add two additional pages to your site before next week.

1.  **Create "Contact Us" Page:** Include a heading, a paragraph with a fake address, and a "Buttons" block.
2.  **Create "Gallery" or "Our Story" Page:** Use the **Gallery Block** to upload at least 3 images of coffee/cafe culture.
3.  **Update the Menu:** Go to **Appearance** -> **Menus** (or use the Site Editor) to ensure these new pages appear in your website's navigation bar so users can find them!

---

## 🏁 Expected Results
Your `/week-04/` folder on GitHub should contain:
```text
/week-04/
  └── site-links.txt
```

The site-links.txt file must contain:

1. Your public website URL (e.g., dev-erasmus-brew.pantheonsite.io).

2. Your secret login URL (The one you created in Task 3).

---

## 📝 Submission
1. Create the site-links.txt file in GitHub Codespaces.
2. Go to the Source Control tab.
3. Commit message: Setup WordPress site with Security and SEO.
4. Commit and Sync Changes.