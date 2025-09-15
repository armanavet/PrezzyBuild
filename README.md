# Paper Tear WebGL Template with Loading Screen

This WebGL template includes a beautiful loading screen that covers the background until Unity loads completely.

## Features

### Loading Screen
- **Full-screen overlay** that prevents website background from showing during Unity load
- **Animated progress bar** with real-time percentage updates
- **Smooth transitions** with fade-out animation when Unity is ready
- **Responsive design** that works on both desktop and mobile devices
- **Contextual loading messages** that change based on progress:
  - 0-30%: "Initializing..."
  - 30-70%: "Loading assets..."
  - 70-95%: "Almost ready..."
  - 95-100%: "Starting experience..."

### Visual Elements
- **Gradient background** matching your game's theme
- **Animated spinner** with smooth rotation
- **Floating elements** with subtle animations
- **Typography** with gradient text effects
- **Loading tips** to engage users during wait time

### Technical Features
- **Progress tracking** via Unity's loading callback
- **Error handling** with user-friendly error messages
- **Smooth fade transition** (0.5s) when hiding loading screen
- **Mobile optimization** with responsive breakpoints
- **Transparent Unity canvas** once loaded

## How It Works

1. **Initial Load**: Loading screen appears immediately when page loads
2. **Progress Updates**: Unity's loading progress is displayed in real-time
3. **Completion**: Loading screen fades out smoothly when Unity is ready
4. **Error Handling**: Shows error message if Unity fails to load

## Customization

### Changing the Title
Edit the loading title in the HTML:
```html
<h1 class="loading-title">Your Game Title</h1>
```

### Modifying Colors
Update the gradient in the CSS:
```css
#loading-screen {
  background: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);
}
```

### Adding Custom Tips
Modify the loading tips section:
```html
<div class="loading-tips">
  <p>💡 <strong>Your Tip:</strong> Your custom tip text</p>
</div>
```

## Browser Compatibility

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Lightweight CSS animations using `transform` and `opacity`
- Hardware-accelerated transitions
- Minimal JavaScript overhead
- Optimized for fast loading on all devices