# Intern Dashboard

A modern, full-stack intern dashboard application built with Node.js, Express, and vanilla JavaScript. This application provides a comprehensive platform for interns to track their donations, manage referral codes, view rewards, and compete on leaderboards.

## 🚀 Features

### Frontend
- **Modern UI/UX**: Beautiful, responsive design with smooth animations
- **Login/Signup System**: Dummy authentication with form validation
- **Dashboard**: Real-time stats, referral codes, and activity tracking
- **Rewards System**: Interactive rewards/unlockables with progress tracking
- **Leaderboard**: Competitive ranking system with podium display
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile

### Backend
- **RESTful API**: Clean API endpoints for data management
- **Dummy Data**: Comprehensive mock data for demonstration
- **Error Handling**: Graceful fallbacks and error management
- **CORS Support**: Cross-origin resource sharing enabled

## 📋 Requirements

- Node.js (v14 or higher)
- npm or yarn package manager

## 🛠️ Installation

1. **Clone or navigate to the project directory**
   ```bash
   cd E:\intern-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Access the application**
   - Open your browser and navigate to `http://localhost:3000`
   - Login page: `http://localhost:3000/login`
   - Dashboard: `http://localhost:3000/dashboard`
   - Leaderboard: `http://localhost:3000/leaderboard`

## 📁 Project Structure

```
intern-dashboard/
├── package.json          # Project dependencies and scripts
├── server.js            # Express server and API endpoints
├── README.md           # Project documentation
└── public/             # Frontend files
    ├── login.html      # Login/signup page
    ├── dashboard.html  # Main dashboard
    ├── leaderboard.html # Leaderboard page
    ├── styles.css      # Main stylesheet
    ├── login.js        # Login page functionality
    ├── dashboard.js    # Dashboard functionality
    └── leaderboard.js  # Leaderboard functionality
```

## 🔧 API Endpoints

### User Data
- `GET /api/user` - Get current user information
- `GET /api/dashboard` - Get complete dashboard data

### Rewards
- `GET /api/rewards` - Get available rewards and unlock status

### Leaderboard
- `GET /api/leaderboard` - Get leaderboard rankings

## 🎨 Features Overview

### Dashboard
- **User Profile**: Display intern name, email, and profile picture
- **Statistics Cards**: Total donations, referrals, rank, and rewards count
- **Referral System**: Unique referral code with copy functionality
- **Rewards Grid**: Interactive rewards with unlock/locked states
- **Activity Feed**: Recent activity timeline

### Leaderboard
- **Podium Display**: Top 3 performers with visual ranking
- **Full Rankings Table**: Complete list with detailed stats
- **Filter Options**: All time, monthly, and weekly views
- **User Details**: Click to view detailed user information

### Login System
- **Form Validation**: Client-side validation with error messages
- **Smooth Transitions**: Animated form switching
- **Notification System**: Success/error feedback
- **Responsive Design**: Works on all device sizes

## 🎯 Key Features

### Referral System
- Unique referral codes for each intern
- One-click copy to clipboard functionality
- Referral statistics tracking
- Visual feedback for successful copies

### Rewards System
- Multiple reward tiers (Coffee Voucher, CEO Lunch, etc.)
- Progress tracking for locked rewards
- Interactive reward cards with detailed modals
- Visual indicators for unlocked/locked states

### Leaderboard Competition
- Real-time ranking updates
- Podium display for top performers
- Detailed user statistics
- Filterable views (All time, Month, Week)

## 🎨 Design Features

### Modern UI Elements
- Gradient backgrounds and smooth animations
- Card-based layout with hover effects
- Consistent color scheme (Purple/Indigo theme)
- Font Awesome icons throughout
- Responsive grid layouts

### Interactive Elements
- Hover effects on cards and buttons
- Loading states and spinners
- Modal dialogs for detailed information
- Toast notifications for user feedback
- Smooth page transitions

## 🔒 Security Features

- CORS enabled for cross-origin requests
- Input validation on all forms
- XSS protection through proper escaping
- Secure headers and error handling

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full-featured experience with sidebar navigation
- **Tablet**: Adapted layout with touch-friendly elements
- **Mobile**: Stacked layout with mobile-optimized navigation

## 🚀 Performance Features

- Optimized CSS with efficient selectors
- Lazy loading for images and content
- Minimal JavaScript bundle size
- Efficient DOM manipulation
- Fallback data for offline functionality

## 🛠️ Development

### Running in Development Mode
```bash
npm run dev
```

### Building for Production
```bash
npm start
```

### API Testing
You can test the API endpoints using:
- **Postman**: Import the endpoints and test with dummy data
- **Browser**: Navigate directly to `/api/user`, `/api/rewards`, etc.
- **cURL**: Command line testing of endpoints

## 📊 Dummy Data

The application includes comprehensive dummy data:
- **User**: Alex Johnson with referral code "alex2025"
- **Donations**: $1,250 total raised
- **Rank**: #3 on leaderboard
- **Rewards**: 2 unlocked, 2 locked
- **Leaderboard**: 10 interns with varying performance

## 🎯 Future Enhancements

- **Database Integration**: MySQL/PostgreSQL for persistent data
- **Authentication**: Real user authentication system
- **Real-time Updates**: WebSocket integration for live data
- **Admin Panel**: Management interface for administrators
- **Analytics**: Detailed reporting and analytics
- **Mobile App**: React Native or Flutter mobile application

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support or questions:
- Check the documentation above
- Review the code comments
- Test the API endpoints
- Ensure all dependencies are installed

---

**Built with ❤️ using Node.js, Express, and vanilla JavaScript** 