# 🌟 Google Reviews Carousel Widget

A modern, responsive, and interactive Google Reviews carousel widget built with pure HTML, CSS, and vanilla JavaScript. No dependencies, no backend required.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- 🎨 **Modern UI Design** - Clean, professional Google-style interface
- 📱 **Fully Responsive** - Perfect on desktop, tablet, and mobile
- 🎯 **Touch & Swipe Support** - Native swipe gestures on mobile devices
- 🖱️ **Drag-to-Scroll** - Mouse drag navigation on desktop
- ⚡ **Auto-Scroll** - Automatic carousel rotation with smart pause on interaction
- 🎭 **Smooth Animations** - Elegant transitions and hover effects
- 🚫 **Zero Dependencies** - Pure vanilla JavaScript, no libraries needed
- ♿ **User-Friendly** - Intuitive navigation with arrow buttons and progress dots
- 🔒 **No Backend Required** - 100% frontend solution

## 🚀 Demo

**[View Live Demo](https://RaynoxDevs.github.io/google-review-widget/index.html)**

## 📸 Screenshots

### Desktop View
<img src="screenshots/desktop.png" alt="Desktop View" width="800"/>

### Mobile View
<img src="screenshots/mobile.png" alt="Mobile View" width="300"/>

## 🛠️ Installation

### Option 1: Direct Download
```bash
# Clone the repository
git clone https://github.com/RaynoxDevs/google-reviews-widget.git

# Navigate to the directory
cd google-reviews-widget

# Open in browser
open index.html
```

### Option 2: Copy-Paste
Simply copy the entire HTML file content into your project.

## 📖 Usage

### Basic Integration

#### As iFrame (Recommended)
```html
<!-- Simple embed -->
<iframe 
  src="https://RaynoxDevs.github.io/google-reviews-widget/" 
  style="width: 100%; height: 400px; border: none; background: transparent; overflow: hidden;"
  title="Avis clients Google"
  loading="lazy">
</iframe>
```

#### Real-world Example
Here's how it's integrated on a real site:

```html
<section id="reviews" class="section reviews">
    <div class="container">
        <h2 class="section-title">Avis Clients</h2>
        <p class="section-subtitle">Découvrez les avis de nos clientes sur Google</p>
        
        <div class="reviews-embed">
            <iframe 
                src="avis.html" 
                style="width: 100%; height: 400px; border: none; background: transparent; overflow: hidden;"
                title="Avis clients Google"
                loading="lazy">
            </iframe>
        </div>
    </div>
</section>
```

### Customization

#### Adding Your Reviews
Edit the review cards in the HTML:

```html
<div class="review-card">
    <div class="review-header">
        <img src="your-avatar-url.jpg" alt="Name" class="review-avatar">
        <div class="review-info">
            <div class="review-author">Customer Name</div>
            <div class="review-meta">@username • 1 month ago</div>
        </div>
    </div>
    <div class="stars">
        <span class="star">★</span>
        <span class="star">★</span>
        <span class="star">★</span>
        <span class="star">★</span>
        <span class="star">★</span>
    </div>
    <div class="review-text">
        Your customer review text here...
    </div>
</div>
```

#### Styling
Customize colors and styles in the `<style>` section:

```css
/* Main colors */
.star { color: #fbbc04; }  /* Star color */
.review-card { background: white; }  /* Card background */
.progress-dot.active { background: #fbbc04; }  /* Active dot */
```

#### Auto-Scroll Timing
Adjust the carousel speed in the JavaScript:

```javascript
autoSlideInterval = setInterval(() => {
    slide(1);
}, 5000);  // Change 5000 to your desired milliseconds
```

## ⚙️ Configuration

| Feature | Default | Customizable |
|---------|---------|--------------|
| Auto-scroll interval | 5 seconds | ✅ |
| Pause on interaction | 15 seconds | ✅ |
| Cards per view (desktop) | 3 | ✅ |
| Cards per view (mobile) | 1 | ✅ |
| Swipe sensitivity | 50px | ✅ |

## 🎯 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | ✅ Latest |
| Firefox | ✅ Latest |
| Safari | ✅ Latest |
| Edge | ✅ Latest |
| Opera | ✅ Latest |

## 📱 Responsive Breakpoints

- **Desktop**: > 768px (3 cards visible)
- **Mobile**: ≤ 768px (1 card visible with progress dots)

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💡 Use Cases

- ✅ Business websites
- ✅ Landing pages
- ✅ E-commerce stores
- ✅ Portfolio sites
- ✅ Service provider pages
- ✅ Restaurant/Salon websites

## 🐛 Known Issues

None at the moment! If you find any bugs, please [open an issue](https://github.com/RaynoxDevs/google-review-widget/issues).

## 📬 Contact

- GitHub: [@RaynoxDevs](https://github.com/RaynoxDevs)
- Email: iam.raynox@gmail.com

## 🙏 Acknowledgments

- Inspired by Google Reviews interface
- Icons: Google Material Design
- Fonts: System fonts stack for optimal performance

---

<p align="center">Made by Raynox</p>
<p align="center">⭐ Star this repo if you find it useful!</p>
