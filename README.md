# Transparent WebGL Template

This template ensures that your Unity WebGL build has a fully transparent background, allowing the website content behind it to be visible.

## Key Features

1. **Transparent Canvas**: The Unity canvas background is set to transparent
2. **Transparent HTML Elements**: All HTML elements have transparent backgrounds
3. **Full Viewport Coverage**: The Unity content covers the full viewport
4. **Responsive Design**: Works on both desktop and mobile devices

## How It Works

- The CSS sets `background: transparent !important` on all relevant elements
- The Unity canvas is positioned to cover the full viewport
- Camera clear flags are set to "Depth Only" to prevent background clearing
- Project settings enable framebuffer alpha preservation

## Usage

1. Build your Unity project for WebGL
2. The build will automatically use this template
3. Embed the built files in your website
4. The Unity content will appear transparent over your website background

## Customization

You can modify the `index.html` and `style.css` files to customize the appearance while maintaining transparency.

