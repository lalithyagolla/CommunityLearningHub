# CommunityLearningHub

https://vocal-conkies-6d59aa.netlify.app

l created a Community Learning Hub where users can discover educational content, interact with curated feeds, and earn credit points for engagement. The platform will focus on providing a seamless learning experience with social features to encourage community participation.

Core Features:

User authentication system with JWT tokens for secure access
Credit points economy for rewarding engagement and unlocking premium content
Social feed aggregator pulling from Twitter, Reddit, and LinkedIn APIs
Content interaction features (save, share, report)
User profile with points history and saved content
Admin/moderator dashboard for content moderation and user management
Responsive design optimized for all devices
Design Elements:

Vibrant color palette centered around orange (#FF7D00), green (#4CAF50), and yellow (#FFC107) with complementary neutral tones
Clean, intuitive interface with clear visual hierarchy and intentional white space
Subtle animations for feed interactions, credit point transactions, and navigation
Modern typography system with high readability and proper contrast ratios
Card-based content display with preview images, source attribution, and engagement options
8px spacing system with consistent alignment across all UI components
Mobile-first responsive layout with appropriate breakpoints for tablet and desktop views
I've created a comprehensive Community Learning Hub application with a focus on educational content discovery, user engagement, and credit point rewards. The platform features a clean and intuitive interface built with React, TypeScript, and Tailwind CSS, using the requested color scheme of orange, green, and yellow.

The application is organized using a modular component architecture that promotes maintainability and scalability. Each module has a specific responsibility, from authentication to feed management and admin capabilities, all connected through a centralized context system for state management.

The user interface provides a seamless experience across devices with responsive design principles and thoughtful animations for interactive elements. The implementation includes all core requirements including user authentication, credit points system, feed aggregation, and an admin panel with comprehensive reporting features

I've implemented a mock authentication system since we don't have a backend yet. The system includes:

Mock users with predefined credentials:

Regular user: john@example.com / password123
Admin user: admin@example.com / admin123
Token-based authentication using base64 encoded user data

Persistent login state using localStorage

Protected routes for authenticated users

Admin-only routes for admin users

You can now test the authentication by:

Registering a new account
Logging in with existing credentials
Accessing protected routes
Testing admin features with the admin account
The mock system maintains the same interface as a real backend would, making it easy to switch to a real API later

use Netlify for deployment since it's one of our supported providers.

Deploy to Community Learning Hub

netlify


Your site has been successfully deployed! You can view it at: https://vocal-conkies-6d59aa.netlify.app
