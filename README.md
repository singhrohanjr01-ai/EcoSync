# EcoSync
# IoT Energy Consumption Tracker Dashboard

A modern, responsive web dashboard for monitoring and forecasting solar energy utilization using AI-driven analytics. Built as a 4th-year Computer Science Engineering minor project.

## 🚀 Features

### 1. **Navigation Panel**
- Sidebar with logo and navigation links to all sections
- Top navbar with page title, dark/light mode toggle, and user avatar
- Responsive design that adapts to different screen sizes

### 2. **Main Dashboard (Home)**
- Real-time energy consumption and generation display
- Solar energy generation status with live updates
- Battery/storage level indicators
- Summary cards showing energy statistics (today/week/month)
- Interactive charts displaying last 12 hours trends
- System notifications and alerts

### 3. **Real-Time Monitoring**
- Live energy flow visualization updating every 2 seconds
- Interactive charts with time range filters (1hr, 24hr, 7 days)
- Area charts showing consumption vs generation
- Real-time device status monitoring
- Connection status for all IoT devices

### 4. **AI Forecasting**
- 24-hour and 7-day energy generation forecasts
- Weather impact predictions (temperature, solar radiation)
- AI model confidence metrics
- Optimization recommendations based on forecast data
- Interactive forecast charts with multiple data series

### 5. **Historical Data**
- Interactive graphs with customizable date ranges
- Multiple chart types (line, bar)
- Data export functionality (CSV)
- Comprehensive statistics summary
- Detailed data table view

### 6. **Settings**
- IoT device management (connect/disconnect)
- Alert threshold configuration
- Dark/light theme selection
- Notification preferences
- Data refresh rate settings
- System information display

## 🛠️ Technology Stack

- **Framework**: React 18.3 with TypeScript
- **Routing**: React Router 7.13
- **Styling**: Tailwind CSS 4.1 (modern utility-first CSS)
- **Charts**: Recharts 2.15 (React charting library)
- **Icons**: Lucide React (modern icon library)
- **State Management**: React Context API
- **Build Tool**: Vite 6.3

## 📁 Project Structure

```
/src
  /app
    /components
      /layout
        - Sidebar.tsx          # Navigation sidebar
        - Navbar.tsx           # Top navigation bar
        - Layout.tsx           # Main layout wrapper
      /dashboard
        - StatCard.tsx         # Reusable statistics card
    /contexts
      - ThemeContext.tsx       # Dark/light theme context
    /data
      - mockData.ts            # Simulated IoT sensor data
    /pages
      - Dashboard.tsx          # Main dashboard page
      - RealTimeMonitoring.tsx # Live monitoring page
      - Forecasting.tsx        # AI forecasting page
      - HistoricalData.tsx     # Historical analysis page
      - Settings.tsx           # Settings page
    - routes.tsx               # Route configuration
    - App.tsx                  # Root component
  /styles
    - theme.css                # Design tokens and dark mode
    - index.css                # Global styles
    - tailwind.css             # Tailwind imports
```

## 🎨 Design Principles

- **Modern UI**: Clean, card-based design with smooth transitions
- **Responsive**: Fully responsive layout for mobile, tablet, and desktop
- **Accessibility**: Semantic HTML and ARIA labels
- **Dark Mode**: Complete dark mode support with theme toggle
- **Performance**: Optimized rendering with React best practices

## 📊 Data Simulation

The dashboard uses realistic mock data to simulate:
- IoT sensor readings (energy consumption, solar generation, battery levels)
- AI model forecasts (weather patterns, predicted generation)
- Device status and connectivity
- Historical energy data with realistic daily patterns

### Key Data Patterns:
- **Solar Generation**: Peaks at noon (11 AM - 2 PM), zero at night
- **Consumption**: Higher during day (6 AM - 10 PM), lower at night
- **Battery**: Charges during high solar generation, discharges at night
- **Forecasts**: Weather-dependent predictions with confidence scores

## 🔧 Configuration

### Alert Thresholds
Configure in Settings page:
- Maximum Consumption (default: 5000 W)
- Minimum Battery Level (default: 20%)
- Low Solar Generation (default: 500 W)
- High Temperature Alert (default: 35°C)

### Data Refresh Rate
- Real-time updates: Every 2-3 seconds
- Configurable in Settings page
- Options: 2s, 5s, 10s, 30s, or manual

### Theme
- Auto-saves theme preference to localStorage
- Toggle between light and dark mode
- System-wide theme application

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔐 Future Enhancements

Potential additions for production deployment:

1. **Authentication**: User login/registration system
2. **Real IoT Integration**: Connect to actual sensors via MQTT/WebSocket
3. **Backend API**: Node.js/Express server for data persistence
4. **Database**: MongoDB/PostgreSQL for historical data storage
5. **Real AI Model**: TensorFlow.js or Python ML backend
6. **Advanced Analytics**: More detailed insights and predictions
7. **Multi-location Support**: Manage multiple sites
8. **Mobile App**: React Native companion app
9. **Email/SMS Alerts**: Automated notification system
10. **PDF Reports**: Automated report generation

## 👥 Credits

**Project Type**: 4th Year Computer Science Engineering Minor Project

**Technologies Used**:
- React.js for component-based UI
- Tailwind CSS for modern styling
- Recharts for data visualization
- React Router for navigation
- TypeScript for type safety

## 📄 License

This project is created for educational purposes as part of a CSE major project.

## 🎓 Academic Context

This dashboard demonstrates:
- Full-stack web development skills
- IoT system integration concepts
- Data visualization techniques
- AI/ML integration patterns
- Modern responsive design
- State management in React
- Routing and navigation
- Dark mode implementation


