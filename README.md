# BOGO Pricing Component

A responsive and interactive Buy-One-Get-One (BOGO) pricing component built with vanilla HTML, CSS, and JavaScript. This component allows users to select different unit quantities with dynamic pricing and customization options.

![BOGO Pricing Component](preview.png)

## Features

- Pure HTML, CSS, and JavaScript implementation (no external libraries)
- Interactive pricing options with expand/collapse functionality
- Size and color selection for multiple units
- Responsive design
- "Most Popular" option highlighting
- Dynamic discount badges
- Original price display with strikethrough
- Free delivery indicator
- Total price calculation
- "Add to Cart" functionality

## Live Demo

[View Live Demo](your-netlify-url-here)

## Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript
- Git installed on your machine
- A GitHub account
- A Netlify account (for deployment)

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/your-username/bogo-pricing-component.git
cd bogo-pricing-component
```

2. Open the project:
- Simply open the `index.html` file in your web browser
- Alternatively, use a local development server like Live Server in VS Code

### File Structure

```
bogo-pricing-component/
│
├── index.html          # Main HTML file
├── styles/
│   └── style.css      # CSS styles
├── scripts/
│   └── script.js      # JavaScript functionality
├── README.md          # Project documentation
└── preview.png        # Project preview image
```

## Deployment to Netlify

Follow these steps to deploy the project to Netlify:

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. Deploy to Netlify:
   - Log in to your Netlify account
   - Click "New site from Git"
   - Select your GitHub repository
   - Configure build settings:
     - Build Command: Leave empty (no build required)
     - Publish Directory: ./ (root directory)
   - Click "Deploy site"

3. Custom Domain (Optional):
   - Go to "Domain Settings" in your Netlify dashboard
   - Click "Add custom domain"
   - Follow the instructions to set up your domain

## Development Notes

- The component is built using vanilla JavaScript to maintain simplicity and avoid dependencies
- CSS is written with a mobile-first approach
- Interactive elements use event delegation for better performance
- The design follows the provided Figma specifications

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add YourFeature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Design inspired by the provided Figma template
- Powered by Pumper

## Support

For support, please open an issue in the GitHub repository or contact [your-email@example.com].
