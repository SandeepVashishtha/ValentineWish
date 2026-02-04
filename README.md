# Valentine Wish

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat&logo=greensock&logoColor=white)
![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)

An animated, customizable Valentine's Day greeting webpage to send special wishes to your loved ones! This project features smooth animations, beautiful visuals, and is fully customizable to make your Valentine's Day message unique and memorable.

## Features

- **Beautiful Animations**: Smooth GSAP-powered animations that create a delightful user experience
- **Fully Customizable**: Easy customization through a simple JSON configuration file
- **Responsive Design**: Works seamlessly across different devices and screen sizes
- **Interactive Elements**: Engaging animations with floating balloons, hearts, and more
- **Personal Touch**: Add custom names, messages, and images
- **Replay Option**: Allow recipients to watch the animation again

## Preview

The animation sequence includes:
1. Personalized greeting with the recipient's name
2. Valentine's Day announcement
3. A thoughtful message progression
4. Special wishes with custom image
5. Floating balloons and hearts
6. Interactive replay option

## Getting Started

### Prerequisites

No special software or dependencies required! This is a simple static website that runs in any modern web browser.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SandeepVashishtha/ValentineWish.git
```

2. Navigate to the project directory:
```bash
cd ValentineWish
```

3. Open `index.html` in your web browser, or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js http-server (install with: npm install -g http-server)
http-server
```

4. Visit `http://localhost:8000` in your browser

## Customization

Customize the Valentine's wish by editing the `customize.json` file:

```json
{
  "name": "Your Loved One's Name",
  "greetingText": "Your greeting message here!",
  "wishText": "Your special Valentine's wish here!",
  "imagePath": "img/your-image.jpg"
}
```

### Configuration Options

- **name**: The recipient's name that appears in the greeting
- **greetingText**: A personalized greeting message
- **wishText**: Your main Valentine's Day wish/message
- **imagePath**: Path to a custom image (add your image to the `img/` folder)

### Adding Your Own Image

1. Add your image to the `img/` folder
2. Update the `imagePath` in `customize.json` to point to your image
3. Supported formats: JPG, PNG, SVG

## Project Structure

```
ValentineWish/
├── index.html          # Main HTML file
├── customize.json      # Customization configuration
├── script/
│   └── main.js        # Animation logic and data handling
├── style/
│   └── style.css      # Styling and layout
├── img/               # Images and SVG assets
│   ├── balloon.svg
│   ├── heart.svg
│   ├── happy.svg
│   ├── music-note.svg
│   ├── smiling.svg
│   ├── valentine.jpg
│   └── vector.jpg
└── README.md          # This file
```

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript (ES6)**: Logic and interactivity
- **GSAP (GreenSock Animation Platform)**: Professional-grade animations
- **Babel Standalone**: ES6+ JavaScript support

## Usage Tips

1. **Personalize it**: Make sure to update all fields in `customize.json` for a truly personal touch
2. **Test locally**: Preview the animation before sharing to ensure everything looks perfect
3. **Share the link**: Host it on GitHub Pages, Netlify, or Vercel for easy sharing
4. **Mobile-friendly**: The animation works great on mobile devices too!

## Deployment

### GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" section
3. Select the branch (usually `main` or `master`)
4. Click "Save"
5. Your site will be available at `https://yourusername.github.io/ValentineWish/`

### Netlify or Vercel

Simply drag and drop the project folder to [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/) for instant deployment.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- GSAP for the amazing animation library
- All the open-source contributors who make projects like this possible
- Special thanks to everyone celebrating love on Valentine's Day!

## Show Your Support

If you found this project helpful or used it to make someone's Valentine's Day special, please give it a star!

---

Made with love for Valentine's Day
