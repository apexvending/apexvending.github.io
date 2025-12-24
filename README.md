# Apex Vending Solutions Website

## Setup Instructions

### Files Included
1. `index.html` - Homepage
2. `products.html` - Products showcase page
3. `contact.html` - Contact form page

### How to Add Your Images

#### 1. For the Homepage Montage
- Save your montage image (the one showing all the vending machine features) as `montage.png`
- Place it in the same folder as your HTML files
- In `index.html`, the image is referenced on line ~475 as `montage-placeholder.png`
- Simply rename your image to match, or update the filename in the code

#### 2. For the Logo (Optional)
- You can add your logo to the navigation by replacing the text "APEX" with an image
- Save your logo as `logo.png`
- Update the navigation code to use: `<img src="logo.png" alt="Apex Vending" style="height: 40px;">`

#### 3. For Product Images
- In `products.html`, there are 12 product placeholders (currently showing emoji icons)
- Save your 12 product images with descriptive names like:
  - `product-1.jpg`, `product-2.jpg`, etc.
- Replace the placeholder emoji sections with actual images:
  ```html
  <div class="product-image">
      <img src="product-1.jpg" alt="Product Name">
  </div>
  ```
- Update the product names and categories accordingly

### Contact Form
The contact form is configured to send emails to: **chris@apexvending.biz**

When users submit the form, it will:
1. Open their default email client
2. Pre-fill the recipient (chris@apexvending.biz)
3. Include all form data in the email body

### Design Features
- **Futuristic black/dark theme** with cyan accents
- **Fully responsive** - works on desktop, tablet, and mobile
- **Smooth animations** on scroll
- **Modern typography** using Orbitron (headings) and Inter (body)
- **Professional gradient effects** and hover states

### File Structure
```
your-website/
│
├── index.html          (Homepage)
├── products.html       (Products page)
├── contact.html        (Contact page)
├── montage.png        (Your montage image - add this)
├── logo.png           (Optional - your logo)
└── images/            (Optional - folder for product images)
    ├── product-1.jpg
    ├── product-2.jpg
    └── ...
```

### Testing Locally
1. Put all HTML files in one folder
2. Add your images to the same folder (or in an 'images' subfolder)
3. Open `index.html` in any web browser
4. Navigate between pages using the top menu

### Customization Tips
- **Colors**: All colors are defined in CSS variables at the top of each file
- **Text**: Update any text content directly in the HTML
- **Products**: When you have your 12 actual products, replace the emoji placeholders with real images and update names/categories

### Next Steps
1. Add your montage image
2. Add your 12 product images and update names
3. Test the site locally
4. Upload to your web hosting service

Need help? The site is ready to go - just add your images and you're set!
