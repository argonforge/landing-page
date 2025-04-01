# E-Book Landing Page

A modern, responsive landing page for your e-book built with Go and Gin. This landing page features a clean design, optimized for conversions, and works great on all devices.

## Features

- Modern, responsive design using Tailwind CSS
- Clean and professional layout
- Optimized for conversions
- Mobile-friendly
- Smooth scrolling and animations
- Custom styling with CSS
- Easy to customize

## Prerequisites

- Go 1.21 or later
- Git

## Getting Started

1. Clone the repository:
```bash
git clone <your-repo-url>
cd landing-page
```

2. Install dependencies:
```bash
go mod download
```

3. Run the application:
```bash
go run main.go
```

4. Open your browser and navigate to:
```
http://localhost:8080
```

## Customization

You can customize the following in `main.go`:
- E-book title
- Price
- Port number (default: 8080)

To modify the content, edit the following files:
- `templates/index.html` - Main landing page content
- `static/css/style.css` - Custom styling
- `main.go` - Application configuration

## Project Structure

```
landing-page/
├── main.go           # Main application file
├── go.mod           # Go module file
├── templates/       # HTML templates
│   └── index.html   # Main landing page template
└── static/         # Static files
    └── css/        # CSS files
        └── style.css # Custom styles
```

## Sections

The landing page includes:
- Hero section with compelling headline
- Features section highlighting key benefits
- Pricing section with clear call-to-action
- Final CTA section
- Footer with social links

## Development

To make changes to the landing page:
1. Edit the HTML template in `templates/index.html`
2. Modify styles in `static/css/style.css`
3. Update configuration in `main.go`
4. Restart the server to see changes

## License

MIT License - feel free to use this template for your own projects!