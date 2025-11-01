# Moon-vhai - Solar System Calculator

A professional, responsive web application for calculating solar panel system requirements, battery capacity, and cost estimates.

## 🌟 Features

- **Professional Design**: Modern UI with gradient backgrounds and smooth animations
- **Comprehensive Calculator**: Calculates system size, panel count, battery capacity, and costs
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **PDF Export**: Generate and download professional PDF reports
- **User-Friendly**: Clear inputs, helpful tooltips, and instant results

## 🚀 Quick Start

### View Live Demo
Simply open `index.html` in your web browser, or deploy it using one of the methods in [DEPLOYMENT.md](DEPLOYMENT.md).

### Local Testing
```bash
# Clone the repository
git clone https://github.com/abukashem05/Moon-vhai.git
cd Moon-vhai

# Open index.html in your browser
# Or use a simple HTTP server:
python3 -m http.server 8080
# Then visit http://localhost:8080
```

## 📊 How to Use

1. **Enter Energy Consumption**:
   - Daily energy usage in kWh/day
   - Peak sun hours for your location (typically 4-6 hours)

2. **Configure System**:
   - Solar panel wattage (default: 300W)
   - System efficiency (default: 85%)

3. **Battery Storage**:
   - Number of backup days needed
   - Battery system voltage

4. **Cost Estimation**:
   - Cost per solar panel
   - Cost per kWh of battery storage

5. **Calculate**: Click "Calculate System" to see your results

6. **Export**: Download a PDF report of your calculations

## 🛠️ Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Vanilla JS for calculations
- **External Libraries**:
  - Font Awesome 6.4.0 (icons)
  - html2pdf.js 0.10.1 (PDF generation)

## 📱 Responsive Design

The calculator automatically adapts to different screen sizes:
- **Desktop**: Multi-column card layout
- **Tablet**: Optimized spacing and layout
- **Mobile**: Single-column, touch-friendly interface

## 🔒 Security

- Input validation for all fields
- Protection against division by zero
- XSS prevention using textContent
- Safe event handling

## 📄 License

This project is open source and available for personal and commercial use.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📞 Support

For deployment help, see [DEPLOYMENT.md](DEPLOYMENT.md)

---

**Made with ❤️ for sustainable energy solutions**
