# 🎂 Bal Mukunda's Bakery Website

A modern, responsive website for Bal Mukunda's Bakery featuring an interactive cake menu, gallery, and customer feedback system.

## ✨ Features

### 🏠 **Home Page (index.html)**
- **Interactive Cake Menu**: Expandable categories with cake details
- **Weight Selection**: Dropdown to choose between 0.5 kg and 1 kg options
- **Dynamic Pricing**: Automatic price updates based on weight selection
- **WhatsApp Integration**: Direct "Select" button for each cake with pre-filled order messages
- **Responsive Design**: Mobile-friendly layout with smooth animations
- **Highlights Section**: Key selling points and product features
- **Navigation**: Easy access to Gallery and Feedback pages

### 🖼️ **Gallery Page (pages/gallery.html)**
- **Dynamic Image Loading**: Automatically loads all cake images from `images/gallery/` directory
- **Masonry Grid Layout**: Pinterest-style responsive grid (4 columns on desktop)
- **Image Popup Modal**: Click any image to view in full size
- **Image Titles**: Automatic title generation from filenames
- **Responsive Design**: Adapts to different screen sizes

### 💬 **Feedback Page (pages/feedback.html)**
- **Customer Reviews**: Displays customer feedback images
- **Masonry Grid**: Pinterest-style layout with random image ordering
- **Load More Functionality**: Progressive loading for better performance
- **Responsive Design**: Mobile-optimized layout

## 🏗️ Project Structure

```
site test/
├── index.html                 # Main homepage with cake menu
├── css/
│   ├── main.css              # Main styles for homepage
│   ├── gallery.css           # Gallery page styles
│   └── feedback.css          # Feedback page styles
├── js/
│   ├── main.js               # Main functionality and cake data
│   ├── gallery.js            # Gallery functionality
│   └── feedback.js           # Feedback page functionality
├── images/
│   ├── bgfirst.jpg           # Background image
│   ├── logofirst.png         # Bakery logo
│   ├── flute-icon.png        # Category icon
│   ├── weight.png            # Weight icon
│   ├── gps.png               # Location icon
│   ├── gallery/              # Cake gallery images
│   │   ├── Almond Cake.jpg
│   │   ├── Apple Cinnamon Cake.jpg
│   │   └── ... (50+ images)
│   └── feedbacks/            # Customer feedback images
│       ├── feedback (1).jpg
│       ├── feedback (2).jpg
│       └── ... (53 images)
└── pages/
    ├── gallery.html          # Cake gallery page
    └── feedback.html         # Customer feedback page
```

## 🎯 Key Functionality

### **Cake Menu System**
- **Categories**: Organized cake categories with expandable sections
- **Weight Options**: 0.5 kg and 1 kg selections with automatic pricing
- **WhatsApp Integration**: Direct order placement via WhatsApp with pre-filled messages
- **Dynamic Content**: Menu generated from embedded JSON data

### **Image Management**
- **Gallery**: Automatic loading of all cake images
- **Feedback**: Customer review images with progressive loading
- **Modal Popups**: Large image viewing functionality
- **Responsive Grids**: Masonry layouts that adapt to screen size

### **User Experience**
- **Smooth Animations**: Hover effects and transitions
- **Mobile Responsive**: Optimized for all device sizes
- **Fast Loading**: Progressive image loading and lazy loading
- **Intuitive Navigation**: Clear paths between pages

## 🚀 Setup Instructions

### **Prerequisites**
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (for development)

### **Installation**
1. **Clone/Download** the project files
2. **Navigate** to the project directory
3. **Open** `index.html` in your browser

### **Development Setup**
For local development with live reload:
```bash
# Using Python (if installed)
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Using PHP (if installed)
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎨 Customization

### **Adding New Cakes**
Edit `js/main.js` and add new entries to the `cakeData` object:
```javascript
{
  "cakeName": "New Cake Name",
  "cakePrice": {
    "0.5 kg": "₹450",
    "1 kg": "₹900"
  },
  "category": "Category Name",
  "cakeDetails": "Cake description"
}
```

### **Adding Gallery Images**
1. Place new images in `images/gallery/` directory
2. Update `js/gallery.js` with new filenames
3. Images automatically appear in the gallery

### **Adding Feedback Images**
1. Place new images in `images/feedbacks/` directory
2. Update `js/feedback.js` with new filenames
3. Images automatically appear in the feedback section

### **Styling Changes**
- **Main styles**: Edit `css/main.css`
- **Gallery styles**: Edit `css/gallery.css`
- **Feedback styles**: Edit `css/feedback.css`

## 📱 Responsive Design

### **Breakpoints**
- **Desktop**: 4-column layouts
- **Tablet**: 3-column layouts
- **Mobile**: 2-column layouts
- **Small Mobile**: 1-column layouts

### **Features**
- **Flexible Grids**: Automatically adjust to screen size
- **Touch-Friendly**: Optimized for mobile interactions
- **Fast Loading**: Optimized images and progressive loading

## 🔧 Technical Details

### **Technologies Used**
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Dynamic functionality
- **Responsive Design**: Mobile-first approach

### **Browser Support**
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### **Performance Features**
- **Lazy Loading**: Images load as needed
- **Progressive Loading**: Content appears in batches
- **Optimized Images**: Appropriate sizing and formats
- **Minimal Dependencies**: No external libraries required

## 📞 Contact & Support

### **WhatsApp Integration**
- **Direct Ordering**: Click "Select" button on any cake
- **Pre-filled Messages**: Automatic order details
- **WhatsApp Number**: +91 8585900793

### **Location**
- **Base Location**: Sector-150, Noida
- **Delivery**: Available with distance-based charges

## 🎉 Special Features

### **Bakery Highlights**
- 🍯 Freshly-baked cakes for all occasions
- 🔥 Direct from Oven to your Home
- 🙏 Prayfully offered to Lord Krishna
- 🌾 Wheat flour base (No Maida)
- 🍯 Sulphurless sugar options

### **Add-on Options**
- **Jaggery, Desi Khand, Butter**: ₹50 extra per add-on
- **Desi Ghee (Patanjali)**: ₹75 extra
- **Custom Millet Options**: Available on request

## 📝 License

This project is created for Bal Mukunda's Bakery. All rights reserved.

---

**Made with ❤️ for delicious cakes and happy customers!** 🎂✨
