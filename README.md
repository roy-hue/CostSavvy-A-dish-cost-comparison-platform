Key Features

1. Dish Comparison System
Browse 400+ dishes across 7 cuisine categories (Italian, Mexican, Asian, American, Mediterranean, Indian, Other)
View restaurant prices, delivery fees, and homemade costs
Calculate potential savings with detailed breakdowns
See preparation time, difficulty level, and serving sizes
Filter by trending dishes, favorites, and categories

2. Monetization Model (Freemium)
Free Tier:
Limited to viewing 8 dishes
Basic cost comparison (view-only)
Manual shopping lists
7-day history access
Standard features
Premium ($19.99/month):
Unlimited dish visibility
AI meal plan generation
Unlimited history access
Export & automation capabilities
Advanced analytics
Multi-workspace support
Priority infrastructure routing
Add-ons (One-time or Monthly):
AI Meal Planner Pro ($9.99)
Real-Time Price Tracker ($4.99/mo)
Custom Recipe Generator ($7.99)
Smart Store Navigator ($5.99/mo)

3. Price Correction Feature ⭐ Just Implemented
Users can photo-submit price corrections
Requires $1+ difference to submit
Upload menu/receipt photos as evidence
Admin review and approval workflow
Automatic dish price updates upon approval
Track corrections by status (pending/approved/rejected)

4. Meal Planning
Weekly meal plan generation
Budget tracking with visual progress bars
Food waste reduction tips
Eco-impact calculations
Drag-and-drop meal organization
Premium: AI-powered meal plan generation

5. Shopping Lists
Auto-generated ingredient lists by dish
Organized by category (Produce, Dairy, Meat, etc.)
Estimated supermarket pricing
Optional ingredients marked
Export capabilities (Premium)

6. User Preferences
Save favorite dishes (5 max free, unlimited premium)
Set dietary restrictions
Weekly budget tracking
Location-based pricing (zip code)
Preferred supermarket chains

Technical Architecture

Authentication & Identity
Built-in Base44 authentication
Role-based access (admin/user)
Immutable CustomerIdentity entity
Stripe customer ID linking

Data Entities

1. Dish - Core dishes with pricing, difficulty, prep time
   
2. Ingredient - Linked ingredients with quantities and prices
   
3. Subscription - User tier, status, execution rights, capacity limits
   
4. CustomerIdentity - Immutable customer identity with Stripe linking
   
5. AddonPurchase - Individual addon purchases
    
6. UserPreference - User settings, favorites, dietary restrictions
    
7. MealPlan - Weekly meal schedules with cost tracking
    
8. PriceCorrection - User-submitted price corrections with photos

Payment Integration

Stripe checkout for subscriptions and add-ons
Webhook handling for payment events
Automatic subscription status updates
Revenue tracking and customer management

Admin Features

1. Price correction review dashboard

2. Approve/reject submissions with photos
   
3. Admin notes and audit trail
   
4. Automatic dish price updates

User Journey

1. Browse → View limited dishes (8 for free)

2. Compare → See detailed cost breakdowns

3. Report → Submit price corrections with photos

4. Plan → Create weekly meal plans

5. Shop → Generate ingredient shopping lists

6. Upgrade → Unlock premium features and add-ons

Growth Phases

Phase 1 (0-100 customers): Early access, testing

Phase 2 (100-1,000): Growth, feature expansion

Phase 3 (1,000+): Enterprise, partnerships

Monetization Triggers

Capacity constraints on free tier (8 dishes visible)
AI features locked behind premium
History depth limitations (7 days free vs unlimited premium)
Export and automation require premium
Usage-based feature gating

https://cost-savvy-475e32b2.base44.app
