# Codynex Technologies

**Transform Your Business with Digital Excellence**

We create stunning websites, powerful software solutions, and innovative digital experiences that help your business grow and succeed.

![Codynex](public/logo.png)

## 🚀 About Us

Codynex Technologies is a leading web development and software solutions company specializing in creating modern, high-performance websites and custom software applications. With **10+ completed projects**, **10+ happy clients**, and **3+ years of experience**, we deliver cutting-edge digital solutions tailored to your business needs.

### Our Stats
- ✅ **10+** Projects Completed
- ✅ **10+** Happy Clients  
- ✅ **3+** Years Experience
- ✅ **24/7** Support Available

## 💼 Our Services

### Core IT Services 💡

#### 🌐 Website Design & Development
Professional website development tailored to your business needs
- Static Websites
- Dynamic Websites
- Business / Portfolio Websites
- Corporate Websites
- Single Page Websites
- *Best for small businesses & startups*

#### 🛒 E-Commerce Website Development
Complete online store solutions to grow your business
- Online Store Setup
- Product & Category Management
- Payment Gateway Integration
- Order & Customer Management
- Mobile-friendly E-commerce

#### 💻 Web Application Development
Custom web applications built with modern technologies
- Custom Web Applications
- Admin Dashboards
- CRM / ERP Web Systems
- Booking & Management Systems
- Laravel / PHP Based Applications
- React / Node Based Applications

#### 📱 Mobile App Development
Native Android applications for your business
- Android Applications
- Business Apps
- POS Mobile Apps

### Business Software Solutions 🏢

#### 🧾 POS Billing Software ⭐ (Our Flagship Product)
Complete point of sale solution for your business
- POS for Retail & Shops
- Barcode Scanning & Printing
- Inventory Management
- GST Billing
- Offline & Online Support

#### 🧠 Custom Software Development
Tailored software solutions for your unique requirements
- Business Process Automation
- Custom Tools for Offices
- Reporting & Analytics Systems
- Internal Management Software

### Digital Presence & Growth 📈

#### 🔍 SEO Setup & Website Optimization
Boost your online visibility and reach more customers
- Basic SEO Setup
- Google Search Console
- Google Analytics
- Performance Optimization

#### 📍 Google My Business (GMB) Setup
Get found locally with proper Google Business setup
- Business Profile Creation
- Location & Map Setup
- Local Visibility Support

### Support & Maintenance 🛠️

#### 🔧 Website Maintenance & Support
Keep your website running smoothly and securely
- Content Updates
- Bug Fixes
- Security Updates
- Performance Monitoring
- Annual Maintenance (AMC)

#### ☁️ Domain, Hosting & Email Setup
Complete web infrastructure setup and management
- Domain Registration
- Web Hosting Setup
- Business Email
- SSL & Security Setup

## 💰 Pricing Plans

- **Single Page Website**: ₹3,999 (Renewal: ₹2,000/year)
- **Standard Website**: ₹8,999 (Renewal: ₹3,000/year) ⭐ Most Popular
- **E-Commerce Website**: ₹14,999 (Renewal: ₹6,000/year)
- **Custom Application**: Custom pricing based on requirements

### Additional Services
- **Custom Mobile App Development**: Starting from ₹39,999
- **Logo Creation**: ₹2,500
- **Contact Card Creation**: ₹1,000

## 📞 Contact Us

Get in touch with us for your next project:

- 📧 **Email**: [support@codynextech.com](mailto:support@codynextech.com)
- 📱 **Phone**: [+91 93450 21613](tel:+919345021613)
- 💬 **WhatsApp**: [Chat with us](https://wa.me/9345021613)
- 📷 **Instagram**: [@codynex.tech](https://www.instagram.com/codynex.tech/)

---

## 🌟 Website Features

### Public Website
- **Home Page** - Hero section, services preview, POS showcase, portfolio, testimonials
- **Services Page** - All services with category filtering
- **Portfolio Page** - Project showcase with filtering
- **Pricing Page** - Pricing plans with features
- **Blog Page** - Articles with SEO optimization
- **Contact Page** - Form with validation and submission
- **POS Product Page** - Dedicated showcase for POS software

### Admin Panel (`/admin`)
- **Dashboard** - Overview stats and quick actions
- **Blogs Management** - Full CRUD with publishing
- **Services Management** - Add, edit, delete services
- **Portfolio Management** - Manage projects
- **Pricing Management** - Update pricing plans
- **Reviews Management** - Customer testimonials
- **Contacts** - View form submissions
- **Settings** - Contact info and social links

### Technical Features
- ⚡ Fast loading with Vite
- 🎨 Modern UI with Tailwind CSS
- 🌙 Dark theme with purple accents
- ✨ Smooth animations with Framer Motion
- 📱 Fully responsive design
- 🔍 SEO optimized pages
- 🔐 Secure authentication with Supabase
- 📊 Real-time data with Supabase

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- npm or yarn
- Supabase account
- Vercel account (for deployment)

### Installation

1. **Clone/Download the project**
   ```bash
   cd codynex-website
   npm install
   ```

2. **Set up Supabase**
   - Create a new project at [supabase.com](https://supabase.com)
   - Go to SQL Editor and run the migration from `supabase/migrations/001_initial_schema.sql`
   - Enable Email Auth in Authentication settings
   - Create an admin user in Authentication > Users

3. **Configure Environment**
   ```bash
   cp .env.example .env
   ```
   Edit `.env` with your Supabase credentials:
   ```
   VITE_SUPABASE_URL=https://your-project.supabase.co
   VITE_SUPABASE_ANON_KEY=your-anon-key
   ```

4. **Run Development Server**
   ```bash
   npm run dev
   ```

5. **Access the website**
   - Website: http://localhost:5173
   - Admin: http://localhost:5173/admin

## 🎨 Color Palette

- **Primary**: `#1d1e20` (Dark)
- **Secondary**: `#9557AF` (Purple)
- **Background**: `#0a0a0b` (Darker)

## 🛠️ Deployment on Vercel

### Step 1: Prepare Your Repository
1. Push your code to GitHub (or GitLab/Bitbucket)
   ```bash
   git add .
   git commit -m "Prepare for Vercel deployment"
   git push origin main
   ```

### Step 2: Deploy to Vercel

**Option A: Using Vercel Dashboard (Recommended)**
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New Project"
3. Import your GitHub repository
4. Vercel will auto-detect Vite framework
5. Configure project settings:
   - **Framework Preset**: Vite (auto-detected)
   - **Build Command**: `npm run build` (auto-detected)
   - **Output Directory**: `dist` (auto-detected)
   - **Install Command**: `npm install` (auto-detected)

**Option B: Using Vercel CLI**
1. Install Vercel CLI globally:
   ```bash
   npm i -g vercel
   ```
2. Run deployment:
   ```bash
   vercel
   ```
3. Follow the prompts to link your project

### Step 3: Configure Environment Variables
1. In Vercel Dashboard, go to your project → **Settings** → **Environment Variables**
2. Add the following variables:
   - **Name**: `VITE_SUPABASE_URL`
     **Value**: Your Supabase project URL (e.g., `https://xxxxx.supabase.co`)
   - **Name**: `VITE_SUPABASE_ANON_KEY`
     **Value**: Your Supabase anonymous key
3. Select **Production**, **Preview**, and **Development** environments
4. Click **Save**

### Step 4: Deploy
- If using Dashboard: Click **Deploy** (or push to your main branch for auto-deployment)
- If using CLI: Run `vercel --prod` for production deployment

### Step 5: Verify Deployment
1. Visit your deployment URL (provided by Vercel)
2. Test all pages and functionality
3. Check that Supabase connection works correctly

### Additional Configuration
- **Custom Domain**: Add your domain in Vercel Dashboard → Settings → Domains
- **Environment Variables**: Update for different environments (Production/Preview/Development)
- **Build Settings**: The `vercel.json` file is already configured for SPA routing

### Troubleshooting
- **Build fails**: Check that all dependencies are in `package.json`
- **Environment variables not working**: Ensure they start with `VITE_` prefix
- **404 errors on routes**: Verify `vercel.json` rewrites are configured correctly
- **Supabase connection issues**: Double-check environment variables in Vercel dashboard

## 📝 Cursor AI Prompts

### Add New Feature
```
Add a new page for [feature] with:
- Modern dark theme matching existing design (#1d1e20, #9557AF)
- Framer Motion animations
- SEO meta tags with react-helmet-async
- Mobile responsive design
- Integration with Supabase
Follow the existing code patterns in src/pages/
```

### Add Database Table
```
Create a new Supabase table for [feature]:
- Add migration SQL in supabase/migrations/
- Create db functions in src/lib/supabase.js
- Add RLS policies for public read and admin write
- Create admin CRUD page following AdminBlogs.jsx pattern
```

### Fix Styling Issue
```
Fix styling for [component] to match the Codynex theme:
- Primary: #1d1e20, Secondary: #9557AF
- Use glass morphism with backdrop-blur
- Add glow effects on hover
- Use existing btn-primary, btn-secondary, card classes
```

### Add Animation
```
Add entrance animations to [component]:
- Use Framer Motion
- Stagger children with 0.1s delay
- Use useInView hook for scroll triggers
- Follow patterns in src/pages/Home.jsx
```

## 🔧 Customization

### Update Content
Edit `src/lib/constants.js` for:
- SERVICES, PRICING_PLANS, PORTFOLIO_PROJECTS
- CONTACT_INFO, SOCIAL_LINKS
- Stats, testimonials, etc.

### Update Theme
Edit `tailwind.config.js` and `src/index.css` for colors and styles.

---

## 🛠️ Technical Stack

This website is built with modern web technologies:

- **Frontend**: React 18, Vite 5
- **Styling**: Tailwind CSS 3
- **Animations**: Framer Motion
- **Backend**: Supabase (PostgreSQL, Authentication, Storage)
- **Routing**: React Router DOM
- **Forms**: React Hook Form + Zod validation
- **Deployment**: Vercel

---

© 2024 Codynex Technologies. All rights reserved.
