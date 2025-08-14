# 🍽️ CanteenHub - Campus Dining Management System

A modern, comprehensive canteen management system designed for educational institutions. Built with Next.js, TypeScript, and Tailwind CSS, providing a seamless dining experience for students, staff, and administrators.

## ✨ Features

### 👥 Multi-Role User System
- **Students**: Order meals, track orders, manage dining experience
- **Staff**: Priority ordering with special menu access
- **Admin**: Complete system management with analytics

### 🛒 Advanced Ordering System
- **Cart-based ordering** with real-time updates
- **Category filtering** (Breakfast, Lunch, Snacks, Beverages)
- **Search functionality** across menu items
- **Pickup time selection** (15, 30, 45, 60 minutes)
- **Live order tracking** with status updates

### 💳 Multiple Payment Methods
- **Online Payment** integration
- **Cash payment** option
- **Token-based system** with auto-generated token numbers
- **Secure transaction** handling

### 📊 Admin Dashboard
- **Menu Management**: Add, edit, delete menu items
- **Order Management**: Real-time order status updates
- **Sales Reports**: Daily, weekly, monthly analytics
- **Popular Items**: Track most ordered items
- **User Management**: Monitor active users

### 🎨 Modern UI/UX
- **Colorful and visually appealing** design
- **Responsive layout** for all devices
- **Smooth animations** and transitions
- **Intuitive navigation** with clean interface
- **Real-time notifications** and feedback

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Canteen_Management_System
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📱 Usage Guide

### For Students & Staff

1. **Choose Your Role**
   - Select Student, Staff, or Admin on the homepage
   - Each role has specific features and benefits

2. **Authentication**
   - Login with your credentials
   - New users can register with role-specific information
   - Demo credentials: `demo@example.com` / `demo123`

3. **Ordering Process**
   - Browse menu by categories or search items
   - Add items to cart with quantity control
   - Select pickup time and payment method
   - Place order and receive token number
   - Track order status in real-time

4. **Order Management**
   - View order history
   - Check order status (Preparing, Ready, Completed)
   - Access token numbers for pickup

### For Administrators

1. **Dashboard Overview**
   - View key metrics (orders, revenue, menu items, users)
   - Monitor recent orders and their status
   - Access quick actions for order management

2. **Menu Management**
   - Add new menu items with details
   - Edit existing items (name, description, price, category)
   - Delete items from menu
   - Set availability status

3. **Order Management**
   - View all incoming orders
   - Update order status (Pending → Preparing → Ready → Completed)
   - Track payment methods and token numbers
   - Manage pickup times

4. **Reports & Analytics**
   - Sales overview (daily, weekly, monthly)
   - Popular items analysis
   - Revenue tracking
   - User activity monitoring

## 🛠️ Technical Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS with custom design system
- **Icons**: Lucide React
- **Notifications**: React Hot Toast
- **State Management**: React Hooks, Zustand
- **Charts**: Recharts (for analytics)
- **Date Handling**: date-fns

## 🎨 Design System

### Color Palette
- **Primary**: Orange gradient (#ed7a1a to #de5f0f)
- **Secondary**: Blue gradient (#0ea5e9 to #0284c7)
- **Accent**: Purple gradient (#d946ef to #c026d3)
- **Success**: Green (#22c55e)
- **Warning**: Yellow (#f59e0b)

### Components
- **Cards**: Clean, shadowed containers
- **Buttons**: Gradient-filled with hover effects
- **Inputs**: Focused with ring effects
- **Modals**: Overlay-based with smooth transitions

## 📁 Project Structure

```
Canteen_Management_System/
├── app/
│   ├── globals.css          # Global styles and Tailwind config
│   ├── layout.tsx           # Root layout with providers
│   ├── page.tsx             # Landing page with role selection
│   ├── auth/
│   │   └── page.tsx         # Authentication page
│   ├── dashboard/
│   │   └── page.tsx         # User dashboard (students/staff)
│   └── admin/
│       └── page.tsx         # Admin dashboard
├── package.json             # Dependencies and scripts
├── tailwind.config.js       # Tailwind configuration
├── tsconfig.json           # TypeScript configuration
└── README.md              # Project documentation
```

## 🔧 Configuration

### Environment Variables
Create a `.env.local` file for environment-specific settings:

```env
# Database (if implementing backend)
DATABASE_URL=your_database_url

# Payment Gateway (if implementing real payments)
STRIPE_PUBLIC_KEY=your_stripe_key
STRIPE_SECRET_KEY=your_stripe_secret

# Authentication (if implementing real auth)
JWT_SECRET=your_jwt_secret
```

### Customization
- **Colors**: Modify `tailwind.config.js` for brand colors
- **Menu Items**: Update sample data in dashboard components
- **Categories**: Add/remove categories in the menu filter
- **Payment Methods**: Extend payment options in checkout

## 🚀 Deployment

### Vercel (Recommended)
1. Push code to GitHub
2. Connect repository to Vercel
3. Deploy automatically

### Other Platforms
- **Netlify**: Build command: `npm run build`
- **Railway**: Supports Node.js applications
- **Heroku**: Add buildpack for Node.js

## 🔮 Future Enhancements

- [ ] **Real-time Chat**: Customer support integration
- [ ] **Mobile App**: React Native companion app
- [ ] **Payment Gateway**: Stripe/PayPal integration
- [ ] **Inventory Management**: Stock tracking system
- [ ] **Loyalty Program**: Points and rewards system
- [ ] **Dietary Preferences**: Allergen and preference tracking
- [ ] **QR Code Orders**: Quick ordering via QR codes
- [ ] **Analytics Dashboard**: Advanced reporting features

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Next.js Team** for the amazing framework
- **Tailwind CSS** for the utility-first CSS framework
- **Lucide** for the beautiful icons
- **React Hot Toast** for the notification system

---

**Made with ❤️ for better campus dining experiences**

For support or questions, please open an issue in the repository. 