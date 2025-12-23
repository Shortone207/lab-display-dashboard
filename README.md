# Lab Display Dashboard

A simple web-based dashboard for displaying key laboratory information on a large screen. This project contains two pre-generated HTML pages designed for easy visibility in the test hall environment.

## Purpose

This dashboard provides a centralized display for:
- **Training Overview**: A summary of available training sessions and resources
- **Risk Assessment Overview**: A list of risk assessments with links to detailed documents

The pages are designed to be displayed on large screens in the laboratory test hall, making important information easily accessible to all staff members.

## Project Structure

```
lab-display-dashboard/
├── assets/
│   ├── css/         # Stylesheets for the HTML pages
│   ├── js/          # JavaScript files for interactive features
│   └── images/      # Images, icons, and other visual assets
├── training-overview.html    # (Pre-generated) Training sessions page
├── risk-assessment.html      # (Pre-generated) Risk assessments page
├── README.md                 # This file
└── .gitignore               # Git ignore rules
```

## Usage

### Viewing the Dashboard

1. Clone or download this repository to your local machine or web server
2. Open the HTML files in a web browser:
   - `training-overview.html` - For training information
   - `risk-assessment.html` - For risk assessment information
3. For best results, display the pages on a large screen or TV in your test hall

### Customization

To customize the dashboard for your laboratory:

1. **CSS Files**: Place your stylesheets in the `assets/css/` directory
   - Modify colors, fonts, and layout to match your organization's branding
   - Ensure text is large enough to be read from a distance

2. **JavaScript Files**: Add any interactive features in the `assets/js/` directory
   - Auto-refresh timers to keep content up-to-date
   - Dynamic content loading from external sources
   - Interactive filters or search functionality

3. **Images**: Store logos, icons, and visual assets in the `assets/images/` directory
   - Use appropriate image formats (PNG for logos, JPEG for photos)
   - Optimize images for web display to ensure fast loading

### Deployment

#### Local Network (Recommended)
1. Host the files on a local web server (Apache, Nginx, or simple HTTP server)
2. Access the dashboard via the server's IP address on your network
3. Set up a dedicated display device (monitor/TV) to show the dashboard

#### File-based Display
1. Simply open the HTML files directly in a web browser
2. Use browser's full-screen mode (F11) for optimal display
3. Set the browser to open automatically on system startup

#### Auto-refresh Setup
Consider adding a browser extension or JavaScript timer to automatically refresh the pages periodically to ensure the most up-to-date information is displayed.

## Browser Compatibility

The dashboard is designed to work with modern web browsers:
- Chrome/Chromium
- Firefox
- Edge
- Safari

## Contributing

To add or modify content:
1. Update the HTML files with your laboratory-specific information
2. Add supporting CSS and JavaScript files to the appropriate `assets/` subdirectories
3. Test the changes on your display device before deploying
4. Commit and push changes to the repository

## Support

For issues or questions about this dashboard, please refer to your organization's IT support or the repository maintainer.

