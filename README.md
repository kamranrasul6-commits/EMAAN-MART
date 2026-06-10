# Emaan Mart - E-Commerce Website

A modern, professional, mobile-responsive e-commerce website for **Emaan Mart**, an online shopping store based in Pakistan.

## 🌟 Features

### Core Features
- ✅ **Responsive Design** - Works perfectly on mobile, tablet, and desktop devices
- ✅ **Shopping Cart** - Add/remove products, update quantities
- ✅ **Wishlist** - Save favorite items for later
- ✅ **Product Search** - Find products by name and category
- ✅ **Product Filtering** - Filter by category, price range, and ratings
- ✅ **Product Sorting** - Sort by price, rating, newest, and alphabetically
- ✅ **Checkout System** - Complete checkout with customer information and shipping details
- ✅ **Multiple Payment Methods** - COD, Bank Transfer, JazzCash/EasyPaisa

### Pages Included
1. **Homepage (index.html)** - Hero section, featured products, categories, testimonials, newsletter
2. **Shop (shop.html)** - Product listing with filters and sorting
3. **Categories (categories.html)** - Browse products by category
4. **Product Details** - Quick view and detailed information
5. **Shopping Cart (cart.html)** - Review and manage cart items
6. **Checkout (checkout.html)** - Complete purchase with address and payment options
7. **Wishlist (wishlist.html)** - Saved favorite items
8. **About (about.html)** - Company information and team
9. **Contact (contact.html)** - Contact form and support information
10. **FAQ (faq.html)** - Frequently asked questions with searchable interface
11. **Order Tracking (order-tracking.html)** - Track order status and delivery

## 📁 Project Structure

```
Emaan Mart/
├── index.html                 # Homepage
├── shop.html                  # Product listing
├── cart.html                  # Shopping cart
├── checkout.html              # Checkout page
├── categories.html            # Categories page
├── wishlist.html              # Wishlist page
├── about.html                 # About Us page
├── contact.html               # Contact Us page
├── faq.html                   # FAQ page
├── order-tracking.html        # Order tracking
├── assets/
│   ├── css/
│   │   └── style.css          # Custom styles
│   └── js/
│       ├── products.js        # Product data (30+ products)
│       └── script.js          # Main JavaScript functionality
└── README.md                  # This file
```

## 🎨 Design & Colors

- **Primary Color**: Green (#22c55e)
- **Primary Dark**: Dark Green (#16a34a)
- **Secondary Color**: White with light green background (#f0fdf4)
- **Typography**: System fonts for optimal performance
- **Layout**: Mobile-first responsive design

## 💻 Technologies Used

- **HTML5** - Semantic markup with SEO meta tags
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript (Vanilla)** - No dependencies needed
- **Font Awesome** - Icon library (via CDN)
- **localStorage API** - Client-side data persistence

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs completely on the client side

### Installation

1. Extract the project folder to your desired location
2. Open `index.html` in your web browser
3. Start shopping!

### Running Locally

You can run this locally in multiple ways:

**Option 1: Direct File Access**
- Simply open `index.html` with your browser

**Option 2: Using Python (if installed)**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Option 3: Using Node.js (with http-server)**
```bash
npx http-server
```

**Option 4: Using VS Code Live Server Extension**
- Install "Live Server" extension in VS Code
- Right-click on index.html and select "Open with Live Server"

## 📦 Product Categories

1. **Electronics** - Laptops, phones, tablets, webcams
2. **Mobile Accessories** - Chargers, cables, cases, screen protectors
3. **Fashion** - T-shirts, jeans, formal shirts, sweaters
4. **Home & Kitchen** - Kitchenware, furniture, bedsheets
5. **Beauty & Personal Care** - Skincare, makeup, haircare
6. **Grocery** - Spices, rice, flour, cooking oil
7. **Islamic Products** - Supporting Pakistani heritage

## 🛍️ Shopping Features

### Product Management
- **30+ Sample Products** - Realistic product data with images, prices, ratings
- **Quick View** - Quick product preview
- **Add to Cart** - Add products with quantity management
- **Add to Wishlist** - Save favorites for later
- **Product Ratings** - User ratings and review counts

### Cart Features
- **Quantity Management** - Increase/decrease product quantities
- **Cart Persistence** - Cart saved in localStorage
- **Cart Summary** - View subtotal, tax, and total
- **Promo Codes** - Support for discount codes (Try: SAVE10)

### Checkout
- **Customer Information** - Full name, email, phone
- **Shipping Address** - Complete address form
- **Payment Options** - Multiple payment methods
- **Order Summary** - Review items before purchase
- **Order Confirmation** - Order ID generation and confirmation

## 🔧 Configuration

### Tailwind CSS
The project uses Tailwind CSS via CDN. For production, consider:
1. Installing Tailwind locally
2. Building optimized CSS
3. Removing unused styles

### Customization
- **Colors**: Edit Tailwind config in HTML files or create custom CSS
- **Products**: Modify `assets/js/products.js` to add/edit products
- **Contact Info**: Update phone number (+92-335-6267708) throughout pages
- **Company Info**: Edit company details in footer and about page

## 📱 Responsive Breakpoints

- **Mobile**: 320px - 640px
- **Tablet**: 641px - 1024px
- **Desktop**: 1025px and above

## 🔐 Security Notes

- All data is stored locally in the browser
- No server-side processing
- No real payment processing (demo only)
- Customer information is for demo purposes
- Suitable for development and learning

## 📊 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Key Functionality

### Cart Management
```javascript
// Add to cart
addToCart(productId)

// Remove from cart
removeFromCart(productId)

// Update quantity
updateQuantity(productId, quantity)

// Get cart total
getCartTotal()
```

### Wishlist Management
```javascript
// Toggle wishlist
toggleWishlist(productId)

// Check if in wishlist
isInWishlist(productId)
```

### Filtering & Sorting
```javascript
// Filter by category
filterByCategory(category)

// Filter by price
filterByPrice(minPrice, maxPrice)

// Sort products
sortProducts(sortBy)
```

## 📞 Contact Information

- **Phone**: +92-335-6267708
- **Country**: Pakistan
- **Currency**: PKR (Pakistani Rupees)
- **WhatsApp**: Available via floating button

## 🎓 Educational Value

This project is perfect for:
- Learning HTML5 semantic markup
- Understanding modern CSS with Tailwind
- JavaScript DOM manipulation and event handling
- Working with localStorage for data persistence
- Building responsive e-commerce interfaces
- Understanding e-commerce workflow

## 📝 Sample Data

The project includes 30+ sample products with:
- Realistic product names and prices
- Product categories
- Discount percentages
- Star ratings (4.3-4.8)
- Review counts
- Stock availability
- Product images (placeholder URLs)

## 🚀 Future Enhancements

Potential features to add:
- User authentication and accounts
- Real payment gateway integration
- Product reviews and ratings system
- Admin dashboard
- Inventory management
- Email notifications
- SMS order tracking
- Multiple language support
- Advanced search with filters
- Related products section

## 📄 License

This project is free to use for educational and commercial purposes.

## 👨‍💼 About Emaan Mart

Emaan Mart is committed to providing quality products across Pakistan at competitive prices with reliable customer service. Our mission is to make online shopping accessible to everyone with a seamless, trustworthy experience.

---

**Built with ❤️ for the Pakistani e-commerce market**

Last Updated: November 2024
