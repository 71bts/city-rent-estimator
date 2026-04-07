# City Rent & Living Cost Estimator

A comprehensive web application that helps students, job seekers, and working professionals estimate total living costs in different areas using AI-powered insights and machine learning.

## 🌟 Features

### ✅ Implemented

1. **Dashboard Overview**
   - Real-time statistics on rent, properties, and costs
   - Cost breakdown visualization (Rent, Food, Utilities, Commute)
   - Top recommended areas with NFS (Nearby Facilities Score)
   - AI-powered rent predictions

2. **Area Comparison**
   - Compare up to 4 areas simultaneously
   - Detailed cost breakdown tables
   - Nearby Facilities Score (NFS) for each area
   - Safety scores and facility availability
   - Visual cost comparison charts

3. **Property Listings**
   - Browse rental properties with filters
   - ML-based rent prediction (Fair/Overpriced detection)
   - Amenities and furnishing details
   - Compatibility scoring for each property

4. **AI Chat Assistant**
   - Personalized area recommendations
   - Budget-aware suggestions
   - Location and commute considerations
   - Safety-first approach

5. **Rent Split Calculator**
   - Game Theory implementation (Shapley Value)
   - Fair distribution based on room size and facilities
   - Comparison with equal split
   - Handles attached bathrooms and balconies

6. **Roommate Compatibility Matcher**
   - AI-powered matching algorithm
   - Considers budget, food type, cleanliness, work style, sleep schedule
   - Compatibility percentage for each potential roommate
   - Detailed preference comparison

## 🚀 Getting Started

### Installation

```bash
# Navigate to project directory
cd "H:\Sarvesh Training\city-rent-estimator"

# Install dependencies
npm install

# Run development server
npm run dev
```

### Open in Browser

Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
city-rent-estimator/
├── app/
│   ├── layout.tsx          # Root layout
│   ├── page.tsx            # Main dashboard
│   ├── page.module.css     # Dashboard styles
│   └── globals.css         # Global styles & design system
├── components/
│   ├── Sidebar.tsx         # Navigation sidebar
│   └── Dashboard/
│       ├── Overview.tsx        # Dashboard overview
│       ├── AreaComparison.tsx  # Area comparison tool
│       ├── Properties.tsx      # Property listings
│       ├── AIChat.tsx          # AI assistant
│       ├── RentSplit.tsx       # Rent calculator
│       └── RoommateFinder.tsx  # Roommate matcher
└── package.json
```

## 🎨 Design Features

- **Premium Dark Theme** with glassmorphism effects
- **Modern Gradients** for visual appeal
- **Smooth Animations** for enhanced UX
- **Fully Responsive** design for all devices
- **Inter Font** from Google Fonts

## 🔧 Technologies Used

- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe development
- **CSS Modules** - Scoped styling
- **React Hooks** - State management

## 📊 Key Algorithms

### Rent Prediction
Uses property features (area, type, amenities) to predict fair rent prices

### Shapley Value (Game Theory)
Ensures fair rent distribution among roommates based on:
- Room size (Small/Medium/Large)
- Attached bathroom availability
- Balcony access

### Compatibility Matching
Weights: Budget (25%), Food (20%), Cleanliness (20%), Work Style (20%), Sleep (15%)

## 🔮 Future Enhancements

- Backend API integration
- Real web scraping implementation
- ML model training and deployment
- User authentication
- Save preferences and properties
- City-to-city comparison
- Travel time heatmap
- Women safety scores
- Property booking integration

## 📝 Notes

- Currently uses mock data for demonstration
- Real web scraping requires API partnerships
- AI chat needs API key integration (OpenAI/Gemini)
- ML models need training data and deployment

## 🎯 Target Users

- Students relocating for education
- Job seekers moving for work
- Working professionals
- People looking for flatmates

## 💡 How to Use

1. **Select Your City** from the dropdown
2. **Explore Dashboard** to see overview statistics
3. **Compare Areas** to find affordable locations
4. **Browse Properties** with AI predictions
5. **Chat with AI** for recommendations
6. **Calculate Rent Split** fairly using game theory
7. **Find Roommates** with compatibility matching

---

Built with ❤️ for smart living decisions
