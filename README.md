# YouTube Clone

A responsive YouTube clone built with HTML and CSS that replicates the core design and layout of YouTube's homepage.

## 🎯 Project Overview

This project is a frontend implementation of YouTube's homepage interface, featuring a responsive design that works across different screen sizes. It includes the main navigation header, sidebar navigation, and a grid layout of video thumbnails with video information.

## ✨ Features

- **Responsive Design**: Fully responsive layout that adapts to desktop, tablet, and mobile devices
- **YouTube-like Interface**: Replicates YouTube's homepage design with header, sidebar, and video grid
- **Interactive Elements**: Hover effects on buttons and navigation items
- **Video Thumbnails**: Display video images with duration overlay
- **Video Information**: Shows video titles, channel names, view counts, and upload times
- **Search Functionality**: Search bar with microphone icon
- **Navigation Sidebar**: Home, Subscriptions, Explore, and Library sections

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: 
  - Flexbox and Grid layouts
  - Media queries for responsive design
  - Custom properties and modern CSS features
  - Hover effects and transitions

## 📁 Project Structure

```
YOUTUBE/
├── code/
│   ├── index.html          # Main HTML file
│   └── youtube.css         # Stylesheet
├── icons/                  # SVG and PNG icons
│   ├── hamburger-menu.svg
│   ├── youtube-logo.svg
│   ├── search.svg
│   ├── microphone.png
│   ├── upload.svg
│   ├── notifications.svg
│   ├── home.svg
│   ├── subscriptions.svg
│   ├── explore.svg
│   ├── library.svg
│   └── photo_2025-06-22_16-03-29.jpg
├── images/                 # Video thumbnail images
│   ├── channels4_profile (1).jpg
│   ├── channels4_profile (2).jpg
│   ├── channels4_profile.jpg
│   ├── FTI96c3mGG0-HD.jpg
│   ├── FWAdfuPpLOc-HD.jpg
│   ├── hXYiAUlQ5Yk-HD.jpg
│   ├── KBH-TVZfvh8-HD.jpg
│   ├── R8pI5pNkynQ-HD.jpg
│   └── Tybr3D5ZksQ-HD.jpg
└── screenshots/            # Project screenshots
    └── Screenshot 2025-07-06 153605.png
```

## 🚀 Installation & Usage

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/youtube-clone.git
   cd youtube-clone
   ```

2. **Open the project**
   - Navigate to the `YOUTUBE/code/` directory
   - Open `index.html` in your web browser
   - Or use a local server for better development experience

3. **Using a local server (optional)**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the application**
   - Open your browser and go to `http://localhost:8000/YOUTUBE/code/`

## 📱 Responsive Design

The application is fully responsive and includes breakpoints for:

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile Large**: 600px - 767px
- **Mobile Medium**: 480px - 599px
- **Mobile Small**: 360px - 479px

## 🎨 Key Features Implementation

### Header Section
- Fixed header with YouTube logo, search bar, and user controls
- Responsive search bar with microphone icon
- Upload, notifications, and profile icons

### Sidebar Navigation
- Fixed sidebar with navigation icons
- Home, Subscriptions, Explore, and Library sections
- Hover effects for better user interaction

### Video Grid
- CSS Grid layout for video thumbnails
- Video duration overlay on thumbnails
- Channel logos and video information
- Responsive grid that adapts to screen size

## 🔧 Customization

### Adding New Videos
To add new videos, duplicate the video structure in `index.html`:

```html
<div class="video1">
    <div class="videoimage">
        <img src="/YOUTUBE/images/your-image.jpg" height="180px">
        <div class="videotime">10:30</div>
    </div>
    <div class="videoinfo">
        <div class="channellogo">
            <img src="/YOUTUBE/images/channel-logo.jpg" height="40px">
        </div>
        <div class="videodetails">
            <p class="videotitle">Your Video Title</p>
            <p class="channelname">Channel Name</p>
            <p class="viewcount">1M views • 2 days ago</p>
        </div>
    </div>
</div>
```

### Styling Modifications
- Edit `youtube.css` to customize colors, fonts, and layout
- Modify media queries to adjust responsive breakpoints
- Update hover effects and transitions

## 📸 Screenshots

The project includes screenshots in the `screenshots/` directory showing the application in action.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Santosh Reddy**
- GitHub: [@SaiSantoshReddy744](https://github.com/SaiSantoshReddy744)

## 🙏 Acknowledgments

- YouTube for the design inspiration
- Icons from various sources (SVG icons)
- Sample images for demonstration purposes

## 📞 Contact

If you have any questions or suggestions, feel free to reach out:
- Email: saisantoshreddy999@gmail.com
- GitHub: [@SaiSantoshReddy744](https://github.com/SaiSantoshReddy744)

---

⭐ If you found this project helpful, please give it a star! 
