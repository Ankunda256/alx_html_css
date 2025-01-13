# Headphones Website

Welcome to the **Headphones Website** repository! This project showcases a responsive and visually appealing landing page for a headphones brand. The website is designed to provide users with an immersive experience, highlighting the brand's features, results, and contact options.

## Features

- **Fully Responsive Design:**
  - Adapts seamlessly to different screen sizes, switching to a mobile-friendly layout when the screen width is 480px or less.
- **Hover Interactions:**
  - Links change color to `#FF6565` on hover and active states.
  - Buttons have an opacity of `0.9` on hover and active states.
- **Content Width:**
  - The content has a maximum width of `1000px`, centered for an elegant and clean appearance.
- **Modern Design:**
  - Gradient backgrounds, clean typography, and a professional layout to enhance user experience.

## Technologies Used

- **HTML5**: Markup structure for the page.
- **CSS3**: Styling and responsive design.
- **Media Queries**: For handling mobile responsiveness.

## Project Structure

```
headphones-website/
├── index.html        # Main HTML file
├── styles.css        # CSS file for styling
├── images/           # Folder for all image assets
└── README.md         # Project documentation
```

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Ankunda256/alx_html_css-1
   ```

2. Navigate to the project directory:
   ```bash
   cd headphones-website
   ```

3. Open the `index.html` file in your preferred browser:
   ```bash
   open index.html
   ```

## Responsive Design

The website includes a responsive design implemented through CSS media queries:

```css
@media (max-width: 480px) {
    body {
        font-size: 14px;
    }

    header h1 {
        font-size: 1.8rem;
    }

    .icons {
        flex-direction: column;
        gap: 10px;
    }
}
```

## Interactions

- **Links Hover/Active:**
  ```css
  a:hover, a:active {
     