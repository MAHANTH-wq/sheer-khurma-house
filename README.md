# Sheer Khurma House - Restaurant Website

A beautiful, responsive static website for Sheer Khurma House restaurant, showcasing traditional desserts with an elegant design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern Animations**: Smooth scroll effects and elegant transitions
- **Sections Include**:
  - Hero section with call-to-action
  - About section with restaurant history
  - Menu section showcasing desserts with prices
  - Customer reviews section
  - Order section with Swiggy and Zomato integration
  - Footer with contact information

## Setup Instructions

1. **Download the folder** containing all files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`

2. **Open the website**:
   - Simply double-click on `index.html` to open it in your default browser
   - Or right-click on `index.html` and select "Open with" to choose a specific browser

3. **Customize the order buttons**:
   - Open `script.js` in a text editor
   - Find the `orderSwiggy()` and `orderZomato()` functions
   - Replace the placeholder URLs with your actual restaurant links:
     ```javascript
     function orderSwiggy() {
         const swiggyUrl = 'YOUR_SWIGGY_RESTAURANT_URL';
         window.open(swiggyUrl, '_blank');
     }

     function orderZomato() {
         const zomatoUrl = 'YOUR_ZOMATO_RESTAURANT_URL';
         window.open(zomatoUrl, '_blank');
     }
     ```

4. **Add your restaurant images** (optional):
   - Replace the placeholder elements in the HTML with actual images
   - Add images to a folder called `images/` in the same directory
   - Update the image paths in `index.html`

## Customization

### Colors
Edit the CSS variables in `styles.css` to change the color scheme:
```css
:root {
    --primary-color: #8B6F47;
    --accent-color: #D4AF37;
    /* ... other colors */
}
```

### Content
- Edit the text content directly in `index.html`
- Update menu items, prices, and descriptions
- Modify the about section to reflect your restaurant's story
- Update contact information in the footer

### Fonts
The website uses:
- **Cormorant Garamond** for headings (elegant serif)
- **Nunito** for body text (clean sans-serif)

These are loaded from Google Fonts and can be changed in the `<head>` section of `index.html`.

## File Structure

```
sheer-khurma-house/
│
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive functionality
└── README.md           # This file
```

## Browser Compatibility

Works on all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Tips for Best Results

1. **Add Real Images**: Replace the placeholder elements with high-quality photos of your food
2. **Update Links**: Add your actual Swiggy and Zomato restaurant URLs
3. **Test on Mobile**: Check how it looks on your phone to ensure responsiveness
4. **Customize Content**: Make the story and reviews authentic to your restaurant

## Support

For any questions or customizations, feel free to modify the code as needed. The code is well-commented to help you understand each section.

Enjoy your new restaurant website! 🌙
