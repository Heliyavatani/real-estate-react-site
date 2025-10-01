# Real Estate React Site

A modern, responsive real estate website built with React that replicates the functionality of popular property sites like Rightmove. This project was completed as coursework in late 2023 and demonstrates full-stack web development skills with a focus on property listings and user experience.

## 🌐 Live Demo

View the live application: [Live Deploy](https://68ddab2e2bf38640af0d17e3--cosmic-liger-379ba1.netlify.app)

## 📋 Project Overview

This React-based real estate platform provides users with an intuitive interface to browse, search, and view property listings. The application features a clean, modern design with responsive layouts optimized for both desktop and mobile devices.

### Key Features

- **Property Listings**: Browse through a comprehensive database of properties
- **Property Details**: Detailed property information including descriptions, images, and floor plans
- **Search & Filter**: Advanced filtering options for property type, price range, and location
- **Responsive Design**: Mobile-first approach ensuring optimal viewing on all devices
- **Interactive Maps**: Location-based property visualization
- **Image Galleries**: High-quality property photography with multiple viewing options

## 🏗️ Project Structure

```
real-estate-react-site/
├── index.html                 # Main HTML entry point
├── properties.json           # Property data and listings
├── asset-manifest.json       # Build asset manifest
├── images/                   # Property images and assets
│   ├── floorplan.jpg        # Sample floor plan
│   ├── prop1_1.jpg          # Property 1 images
│   ├── prop1_2.jpg
│   ├── prop1_3.jpg
│   ├── prop1_4.jpg
│   ├── prop2_1.jpg          # Property 2 images
│   ├── prop2_2.jpg
│   ├── prop2_3.jpg
│   ├── prop2_4.jpg
│   └── floorplan.jpg
└── static/                   # Built application assets
    ├── css/
    │   ├── main.e1a2c522.css
    │   └── main.e1a2c522.css.map
    └── js/
        ├── main.7c4ece1d.js
        ├── main.7c4ece1d.js.map
        ├── 787.e3b82e7f.chunk.js
        └── 787.e3b82e7f.chunk.js.map
```

## 🏠 Property Data

The application includes a comprehensive dataset of 8 properties with the following characteristics:

### Property Types
- **Houses**: 4 properties (3-4 bedrooms)
- **Flats**: 4 properties (1-3 bedrooms)

### Purchase Types
- **Sale**: 5 properties (prices ranging from £399,995 to £980,000)
- **Rent**: 3 properties (monthly rent from £1,200 to £2,500)

### Property Features
- **Bedrooms**: 1-4 bedrooms
- **Tenure**: Freehold and Leasehold options
- **Locations**: Various UK locations including Petts Wood, Orpington, and other areas
- **Images**: Multiple high-quality property photos per listing
- **Floor Plans**: Detailed property layouts
- **Descriptions**: Comprehensive property descriptions

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd real-estate-react-site
   ```

2. **Serve the application**
   
   Since this is a built React application, you can serve it using any static file server:

   **Using Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

   **Using Node.js (with http-server):**
   ```bash
   npm install -g http-server
   http-server -p 8000
   ```

   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

3. **Access the application**
   
   Open your browser and navigate to `http://localhost:8000`

## 🛠️ Technical Details

### Built With

- **React**: Frontend JavaScript library for building user interfaces
- **Create React App**: Development environment and build tooling
- **CSS3**: Modern styling with responsive design
- **JSON**: Data storage for property listings

### Build Information

- **Main Bundle**: `main.7c4ece1d.js`
- **CSS Bundle**: `main.e1a2c522.css`
- **Chunk Files**: Optimized code splitting for better performance
- **Source Maps**: Available for debugging and development

### Performance Features

- **Code Splitting**: Optimized JavaScript bundles
- **Asset Optimization**: Minified CSS and JavaScript
- **Image Optimization**: Compressed property images
- **Lazy Loading**: Efficient resource loading

## 📱 Responsive Design

The application is built with a mobile-first approach, ensuring optimal user experience across all devices:

- **Desktop**: Full-featured interface with advanced filtering
- **Tablet**: Touch-optimized navigation and property browsing
- **Mobile**: Streamlined interface for on-the-go property searching

## 🎨 User Interface

### Design Principles
- **Clean Layout**: Minimalist design focusing on property content
- **Intuitive Navigation**: Easy-to-use search and filtering
- **Visual Hierarchy**: Clear property information presentation
- **Accessibility**: WCAG compliant design patterns

### Key Components
- Property listing cards with images and key details
- Detailed property view with image galleries
- Search and filter interface
- Interactive maps for location visualization
- Floor plan integration

## 📊 Data Structure

The `properties.json` file contains structured property data with the following schema:

```json
{
  "properties": [
    {
      "id": "unique_property_id",
      "type": "House|Flat",
      "purchaseType": "Sale|Rent",
      "bedrooms": number,
      "price": number,
      "tenure": "Freehold|Leasehold",
      "description": "Detailed property description",
      "location": "Property address",
      "postcode": "UK postcode",
      "coordinates": {
        "lat": latitude,
        "lng": longitude
      },
      "picture": ["array_of_image_paths"],
      "floorPlan": "floor_plan_image_path",
      "url": "property_detail_url",
      "added": {
        "month": "Month",
        "day": day_number,
        "year": year_number
      }
    }
  ]
}
```

## 🔧 Development

### Project Status
This project was completed as coursework in late 2023 and represents a fully functional real estate website. The codebase demonstrates:

- React component architecture
- State management
- API integration patterns
- Responsive design implementation
- Performance optimization techniques

### Future Enhancements
Potential improvements for the application could include:

- User authentication and accounts
- Property favoriting and saved searches
- Advanced search filters
- Property comparison features
- Real-time property updates
- Integration with real estate APIs

## 📄 License

This project was created as educational coursework. Please respect the academic nature of this work.

## 👨‍💻 Author

Developed as coursework in late 2023, demonstrating proficiency in React development and modern web technologies.

## 🤝 Contributing

This is a coursework project. For educational purposes, feel free to explore the codebase and learn from the implementation patterns used.

---

**Note**: This is a demonstration project showcasing React development skills and should not be used for commercial real estate purposes without proper licensing and compliance with real estate regulations.
