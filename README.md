# 🌅 Solstice - Weather Analytics Dashboard

*Smarter insights for today's weather and tomorrow's climate.*

## 🏗️ Features

- **🎨 Dynamic Weather-Aware Backgrounds** - Backgrounds change based on weather conditions
- **📊 Interactive Dashboard** - Real-time weather analytics and visualizations
- **🗺️ Interactive Map** - Weather data visualization on maps
- **📈 Dynamic Charts** - Trend analysis with beautiful Chart.js graphs
- **🔐 Authentication Flow** - Secure login/signup with smooth animations
- **📤 Data Export** - Export weather data as CSV/PDF
- **🎯 Smart Recommendations** - Personalized weather insights and recommendations
- **📱 Responsive Design** - Works perfectly on desktop and mobile
- **⚡ Smooth Animations** - Powered by Framer Motion

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone and install dependencies:**
```bash
cd solistice
npm install
```

2. **Start development server:**
```bash
npm run dev
```

3. **Open your browser:**
Visit `http://localhost:3000` to see Solstice in action!

## 🎯 User Journey

1. **Home Page** - Beautiful landing with weather-aware animated backgrounds
2. **Authentication** - Optional login/signup for personalized experiences  
3. **Dashboard** - Comprehensive weather analytics with:
   - Interactive location search
   - Variable selection (Temperature, Humidity, Wind, Pressure)
   - Date range picker (1 day to 90 days)
   - Threshold configuration
   - Unit toggle (°C ↔ °F)
   - Interactive maps with weather markers
   - Dynamic charts showing trends
   - Smart summary box with probability insights
   - Export functionality

## 🛠️ Tech Stack

- **Frontend:** React 18 + Vite
- **Styling:** Tailwind CSS + Custom animations
- **Routing:** React Router v6
- **Animations:** Framer Motion
- **Charts:** Chart.js + React Chart.js 2
- **Maps:** Leaflet + React Leaflet
- **Notifications:** React Hot Toast
- **Export:** jsPDF + Papa Parse
- **HTTP:** Axios

## 🎨 Design System

- **Colors:** Sunrise-inspired palette (blues, yellows, oranges)
- **Typography:** Poppins font family
- **Animations:** Smooth transitions with cubic-bezier easing
- **Background Effects:** Dynamic weather-based animations
  - ☀️ Sunny: Golden gradients with sun rays
  - 🌧️ Rainy: Blue-grey with falling raindrops
  - ⛅ Cloudy: Soft gradients with moving clouds
  - 🌩️ Stormy: Dark tones with lightning effects
  - ❄️ Snowy: White-blue with snow particles
  - 💨 Windy: Light gradients with swaying motion

## 📦 Available Scripts

- `npm run dev` - Development server with hot reload
- `npm run build` - Production build
- `npm run preview` - Preview production build locally
- `npm run lint` - Code linting

## 🌐 Deployment

### Vercel (Recommended)
```bash
npm install -g vercel
vercel deploy
```

### Netlify
```bash
npm run build
# Upload dist/ folder to Netlify
```

### Traditional Hosting
```bash
npm run build
# Upload dist/ folder contents to your web server
```

## 🔧 Configuration

### Environment Variables (Optional)
Create a `.env.local` file:
```
VITE_VISUAL_CROSSING_API_KEY=your_visual_crossing_api_key
VITE_DEFAULT_LOCATION=your_default_city
```

### Visual Crossing Weather API Integration
1. Sign up for a Visual Crossing API key at [visualcrossing.com](https://www.visualcrossing.com/weather-api)
2. Replace `DEMO_KEY` in `WeatherContext.jsx` with your actual API key
3. Set your default location in the environment variables
4. The app will automatically fetch real weather data using Visual Crossing's Timeline Weather API

**Visual Crossing API Features:**
- ✅ Current weather conditions
- ✅ Historical weather data
- ✅ Hourly forecasts
- ✅ Detailed weather parameters (temperature, humidity, wind, pressure)
- ✅ Precipitation probability
- ✅ Cloud cover information

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Weather data inspiration from climate analytics platforms
- Design patterns from modern dashboard applications
- Icons from various emoji libraries
- Animation concepts from leading UI/UX trends

---

**Built with ❤️ for climate awareness and weather intelligence**
