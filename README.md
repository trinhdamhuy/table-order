# Table Order

**Table Order** is a cross-platform application designed to help users reserve tables at restaurants or eateries via web or Android devices. This application also supports restaurants by allowing them to manage table layouts, monitor reservations, and optimize service workflows effectively.

## Technology Stack

### Frontend Framework
- **Flutter 3.5.3**: Cross-platform UI framework for building natively compiled applications
- **Dart SDK**: Programming language optimized for building mobile, desktop, server, and web applications

### Backend & Cloud Services
- **Firebase Platform**: Comprehensive backend-as-a-service solution
  - **Firebase Authentication**: User authentication and authorization
  - **Cloud Firestore**: NoSQL cloud database for real-time data synchronization
  - **Firebase Realtime Database**: Real-time database for instant data updates
  - **Firebase Storage**: Cloud storage for images and media files
  - **Firebase Cloud Messaging**: Push notifications and messaging service

### Key Libraries & Packages
- **State Management**: Scoped Model for reactive state management
- **Location Services**: Geolocator, Geocoding, geoflutterfire_plus for location-based features
- **UI Components**: 
  - Carousel Slider for image galleries
  - Cached Network Image for optimized image loading
  - Responsive Builder for adaptive layouts
  - Font Awesome Flutter for iconography
- **Authentication**: Google Sign-In integration
- **QR Code**: QR Flutter for QR code generation and Mobile Scanner for scanning
- **Notifications**: Firebase Messaging with Flutter Local Notifications
- **Media**: Image Picker for photo selection
- **Internationalization**: Flutter Localizations with Intl package

### Architecture Pattern
- **MVC-like Architecture**: Model-View-Service separation
  - **Models**: Data structures for User, Restaurant, Reservation, Table, Floor, Review, Employee, Admin, Notification
  - **Views**: UI components organized by feature (Auth, Restaurant, Reservations, Owner, User, QR)
  - **Services**: Firebase service layer for business logic and data operations

## Project Scale

### Codebase Metrics
- **Total Dart Files**: 65+ files
- **Lines of Code**: ~2,255 lines in src directory
- **Main Modules**:
  - 9 Data Models
  - 8 Service Classes
  - 35+ View Components
  - Multiple Utility Classes

### Platform Support
- **Android**: Native Android application
- **Web**: Progressive Web App (PWA)
- **iOS**: iOS compatibility (infrastructure present)
- **Linux, macOS, Windows**: Desktop support infrastructure

### Feature Scope
- Multi-language support (English with i18n infrastructure)
- Real-time data synchronization
- Location-based restaurant search
- QR code generation and scanning
- Push notification system
- Image upload and management
- Responsive design for all screen sizes

## Features

### For Users
- **Search Restaurants**: Find restaurants based on location, cuisine, or preferences.
- **Table Reservation**: Book tables easily through the app.
- **Real-Time Notifications**: Receive updates on reservation status.
- **Payment Integration**: Pay securely within the app.

### For Restaurants
- **Table Layout Management**: Configure and manage table arrangements.
- **Real-Time Reservation Monitoring**: Track customer bookings instantly.
- **Analytics and Reporting**: Analyze customer booking habits to improve service.
- **Enhanced Service Workflow**: Optimize the process of serving customers.

## Team Roles & Development Process

### Project Roles
- **Full-Stack Flutter Developers**: Building cross-platform UI and integrating Firebase services
- **UI/UX Designers**: Creating intuitive interfaces for both customers and restaurant owners
- **Backend Architects**: Designing Firebase database structure and security rules
- **QA Engineers**: Testing across multiple platforms and devices
- **DevOps**: Managing deployment pipelines and Firebase configuration

### Development Methodology
- **Agile Development**: Iterative development with continuous integration
- **Version Control**: Git-based workflow with feature branching
- **Code Quality**: Flutter lints and analysis for maintaining code standards
- **Cross-Platform Testing**: Testing on Android, Web, and other platforms

## Development Results & Achievements

### Successfully Implemented Features

#### Customer-Facing Features
✅ **Restaurant Discovery**
- Location-based restaurant search using GPS coordinates
- Filter restaurants by cuisine, rating, and distance
- View detailed restaurant information with images

✅ **Table Reservation System**
- Real-time table availability checking
- Interactive table selection with floor layout visualization
- Booking confirmation with QR code generation
- Reservation history and management

✅ **User Management**
- Email and Google OAuth authentication
- User profile management
- Reservation tracking and notifications

#### Restaurant Owner Features
✅ **Restaurant Management**
- Restaurant registration and profile setup
- Multiple restaurant location support
- Image gallery management

✅ **Table & Floor Management**
- Visual floor layout configuration
- Table arrangement and capacity settings
- Real-time table status monitoring

✅ **Reservation Management**
- View and manage incoming reservations
- QR code scanning for check-in verification
- Customer notification system

✅ **Analytics Dashboard**
- Reservation statistics and trends
- Customer review management
- Business insights and reporting

### Technical Achievements
- **Cross-Platform Deployment**: Successfully deployed on Android and Web platforms
- **Real-Time Synchronization**: Instant updates across all connected devices
- **Scalable Architecture**: Firebase infrastructure supporting concurrent users
- **Secure Authentication**: Email/password and OAuth authentication with Firebase Auth
- **Optimized Performance**: Cached images, lazy loading, and efficient state management
- **Responsive Design**: Adaptive UI for phones, tablets, and desktops

### Security Implementation
- **Data Encryption**: All sensitive data encrypted in transit and at rest
- **Authentication Security**: OAuth 2.0 and secure session management
- **Firebase Security Rules**: Fine-grained access control for database operations
- **Permission Management**: Proper Android/iOS permission handling
- **Secure Storage**: Firebase Storage with access control policies

## Objectives

1. **Multi-Platform Development**: Build a smooth, feature-complete application for both Android and web platforms.
2. **User Experience (UX/UI)**: Provide an intuitive and visually appealing interface to simplify the reservation process.
3. **Restaurant Management Tools**: Develop tools to help restaurants manage reservations, optimize workflows, and monitor table statuses.
4. **Security and Stability**: Ensure user data and payment information are secure while maintaining system reliability.
5. **Analytics and Insights**: Offer tools for restaurants to analyze customer behavior and make data-driven decisions.

## Expected Outcomes

- ✅ A fully functional cross-platform application that meets all core requirements.
- ✅ A user-friendly interface with smooth navigation and seamless interactions.
- ✅ Effective restaurant management tools to enhance operational efficiency.
- ✅ High-level security to protect user data and payment transactions.
- ✅ Increased business efficiency for restaurants through data-driven insights.

## Project Impact

### For Customers
- **Convenience**: Easy restaurant discovery and table reservation from anywhere
- **Time Savings**: No need to call or wait for reservation confirmations
- **Transparency**: Real-time availability and instant booking confirmation
- **Better Planning**: View restaurant details, reviews, and floor layouts before booking

### For Restaurants
- **Operational Efficiency**: Automated reservation management reduces manual work
- **Customer Insights**: Analytics help understand booking patterns and customer preferences
- **Revenue Optimization**: Better table utilization through visual management
- **Modern Technology**: QR code check-in and digital reservation system
- **Reduced No-Shows**: Notification system and booking confirmations

### Business Value
- **Market Expansion**: Restaurants can reach customers beyond traditional marketing
- **Data-Driven Decisions**: Analytics enable strategic business planning
- **Competitive Advantage**: Modern reservation system attracts tech-savvy customers
- **Cost Reduction**: Reduced phone handling and manual booking processes

## Usage

### For Customers
1. **Download & Setup**:
   - Download the Android app or visit the web application
   - Sign up using email or Google account
   
2. **Find Restaurants**:
   - Allow location access for nearby restaurants
   - Browse restaurants or search by name, cuisine, or location
   - View restaurant details, photos, and reviews
   
3. **Make a Reservation**:
   - Select desired date and time
   - View floor layout and choose preferred table
   - Confirm booking details
   - Receive confirmation with QR code
   
4. **Manage Reservations**:
   - View upcoming and past reservations
   - Receive notifications for booking updates
   - Present QR code at restaurant for check-in

### For Restaurants
1. **Restaurant Setup**:
   - Register restaurant with details and images
   - Configure floor layouts and table arrangements
   - Set operating hours and capacity
   
2. **Manage Operations**:
   - Monitor real-time reservation dashboard
   - View table status and occupancy
   - Scan customer QR codes for check-in
   
3. **Customer Engagement**:
   - Respond to customer reviews
   - Send notifications for special events
   - Track customer preferences
   
4. **Business Analytics**:
   - Review booking statistics and trends
   - Analyze peak hours and popular tables
   - Generate reports for business planning

## Technical Requirements

### For Development
- Flutter SDK 3.5.3 or higher
- Dart SDK compatible with Flutter version
- Firebase project with necessary services enabled
- Android Studio / Xcode (for mobile development)
- VS Code or IntelliJ IDEA (recommended IDEs)

### For Users
- **Android**: Android 5.0 (Lollipop) or higher
- **Web**: Modern web browser (Chrome, Firefox, Safari, Edge)
- **iOS**: iOS 12.0 or higher (if deploying to iOS)
- Internet connection for real-time features
- Location services enabled (optional, for nearby search)

## Installation & Setup

### Developer Setup
```bash
# Clone the repository
git clone https://github.com/trinhdamhuy/table-order.git
cd table-order

# Install dependencies
flutter pub get

# Configure Firebase
# 1. Create a Firebase project at console.firebase.google.com
# 2. Add Android/iOS/Web apps to your Firebase project
# 3. Download and place configuration files:
#    - google-services.json (Android)
#    - GoogleService-Info.plist (iOS)
#    - Update firebase_options.dart (Web)

# Run the application
flutter run
```

### Build for Production
```bash
# Build for Android
flutter build apk --release

# Build for Web
flutter build web --release

# Build for iOS
flutter build ios --release
```

## Security

### Data Protection
- **End-to-End Encryption**: All data transmission encrypted using HTTPS/TLS
- **Firebase Security Rules**: Granular access control for database and storage
- **Authentication**: Secure user authentication with Firebase Auth
- **Session Management**: Automatic session timeout and secure token handling
- **Data Validation**: Input sanitization and validation on client and server

### Privacy
- **User Consent**: Explicit permission requests for location and notifications
- **Data Minimization**: Collect only necessary user information
- **GDPR Compliant**: User data rights and privacy protection
- **Secure Storage**: Encrypted storage of sensitive user data

### Security Best Practices
- Regular dependency updates to patch vulnerabilities
- Code analysis with Flutter lints
- Firebase security rules testing
- Secure API key management
- No hardcoded credentials in source code

## Future Enhancements

### Planned Features
- [ ] **Payment Integration**: In-app payment processing for deposits
- [ ] **Advanced Analytics**: Machine learning for demand prediction
- [ ] **Multi-Language Support**: Additional languages beyond English
- [ ] **Loyalty Programs**: Reward system for frequent customers
- [ ] **Social Features**: Share experiences and recommendations
- [ ] **Table Splitting**: Split bills and reservations among groups
- [ ] **Waitlist Management**: Queue system for walk-in customers
- [ ] **Menu Integration**: Browse menus and pre-order food
- [ ] **Rating System**: Enhanced review system with photo uploads
- [ ] **Chat Support**: In-app messaging between customers and restaurants

### Technical Improvements
- [ ] Offline mode with data synchronization
- [ ] Progressive Web App (PWA) enhancements
- [ ] Performance optimization for low-end devices
- [ ] Automated testing suite expansion
- [ ] CI/CD pipeline implementation
- [ ] iOS App Store deployment
- [ ] Desktop applications for Windows, macOS, Linux

## Contributing

Contributions are welcome! Please follow these guidelines:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the terms specified in the LICENSE file.

## Contact & Support

For questions, issues, or suggestions:
- **Repository**: [github.com/trinhdamhuy/table-order](https://github.com/trinhdamhuy/table-order)
- **Issues**: Submit via GitHub Issues
- **Documentation**: See this README and inline code documentation

## Acknowledgments

- Flutter team for the amazing cross-platform framework
- Firebase for comprehensive backend services
- Open source community for the excellent packages used in this project
