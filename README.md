# 🎓 AMF English School - Complete Registration & Payment System

*A comprehensive educational website with advanced registration system, payment integration, and automated business notifications.*

[![Live Demo] (https://amf-us.vercel.app/)

[![Version](https://img.shields.io/badge/Version-2.1-green)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)]()

---

## 📋 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [🌟 Key Features](#-key-features)
- [🔄 Complete User Journey](#-complete-user-journey)
- [🎨 Figma Design Implementation](#-figma-design-implementation)
- [🏗️ System Architecture](#️-system-architecture)
- [📱 Website Sections](#-website-sections)
- [💳 Payment Integration](#-payment-integration)
- [📞 WhatsApp Integration](#-whatsapp-integration)
- [🖨️ Print Functionality](#️-print-functionality)
- [📁 File Structure](#-file-structure)
- [🛠️ Technologies Used](#️-technologies-used)
- [🎨 Design System](#-design-system)
- [📊 User Flow Diagrams](#-user-flow-diagrams)
- [🚀 Getting Started](#-getting-started)
- [📈 Development History](#-development-history)
- [🔧 Customization Guide](#-customization-guide)
- [🐛 Troubleshooting](#-troubleshooting)
- [📞 Support](#-support)
- [📜 License](#-license)

---

## 🎯 Project Overview

AMF English School is a comprehensive educational website featuring:

- **Complete Student Registration System** with multi-step validation
- **Secure Payment Integration** via Square payment gateway
- **Automated WhatsApp Notifications** for business management
- **Professional Receipt Generation** with print functionality
- **Responsive Design** optimized for all devices with enhanced mobile UX
- **Modern UI/UX** with clean, professional aesthetics and gradient designs
- **Enhanced Course Cards** with proper AMF branding and CEFR level indicators
- **Improved Form Experience** with standardized course level options

### 🎯 Mission
To provide AMF English School with a modern, professional online presence that streamlines student registration, payment processing, and business communication through automated systems.

---

## 🌟 Key Features

### ✅ Core Features
- **📝 Smart Registration Forms** - Multi-step validation with real-time feedback
- **🔒 Secure Payment Processing** - Square gateway integration
- **📱 Mobile-First Design** - Perfect on all devices
- **🤖 Automated Notifications** - WhatsApp business alerts
- **🖨️ Print Functionality** - Professional receipt generation
- **🎨 Modern UI/UX** - Clean, professional design
- **⚡ Fast Performance** - Optimized loading and interactions

### ✅ Advanced Features
- **🔄 Progressive Web App** - App-like experience
- **📊 Admin Dashboard Ready** - Data management prepared
- **🌐 Multi-language Support** - Extensible architecture
- **📈 Analytics Integration** - Tracking capabilities
- **🔧 Easy Customization** - Modular design
- **🛡️ Security First** - SSL encryption and validation

---

## 🔄 Complete User Journey

```
🌐 User Visits Website
    ↓
📝 Registration Form (Step 1)
    ↓ [Form Validation]
📋 Review Details (Step 2)
    ↓ [Data Verification]
💳 Payment Gateway (Step 3)
    ↓ [Square Processing]
✅ Success Confirmation
    ↓ [WhatsApp Notification]
🧾 Receipt Generation
```

### 📊 Detailed Flow Chart

```
┌─────────────────┐
│   🌐 Website    │
│   Landing Page  │
└─────────┬───────┘
          │
          ▼
┌─────────────────┐     ┌─────────────────┐
│   📝 Modal      │────▶│   📝 Form       │
│   Registration  │     │   Validation    │
│   (Auto-popup)  │     └─────────┬───────┘
└─────────────────┘               │
                                  ▼
┌─────────────────┐     ┌─────────────────┐
│   📋 Review     │────▶│   ✅ Confirm    │
│   Details Page  │     │   Information   │
└─────────┬───────┘     └─────────┬───────┘
          │                       │
          ▼                       ▼
┌─────────────────┐     ┌─────────────────┐
│   💳 Square     │────▶│   🔄 Processing │
│   Payment Link  │     │   Payment       │
└─────────┬───────┘     └─────────┬───────┘
          │                       │
          ▼                       ▼
┌─────────────────┐     ┌─────────────────┐
│   ✅ Success    │────▶│   📱 WhatsApp   │
│   Confirmation  │     │   Notification  │
└─────────┬───────┘     └─────────┬───────┘
          │                       │
          ▼                       ▼
┌─────────────────┐     ┌─────────────────┐
│   🧾 Receipt    │────▶│   🖨️ Print       │
│   Generation    │     │   Function      │
└─────────────────┘     └─────────────────┘
```

---

## 🎨 Figma Design Implementation

### 🖼️ FRAME 1: Landing Page
```
┌─────────────────────────────────────┐
│  [🎓] AMF English School            │  ← Header with Logo
├─────────────────────────────────────┤
│  🌟 Hero Section                     │
│  Welcome to Excellence in Education │
│  [Register Now Button]              │
├─────────────────────────────────────┤
│  ✨ Why Choose Us (4 Cards)         │
│  📚 Interactive Learning            │
│  👨‍🏫 Expert Instructors            │
│  🎯 Personalized Curriculum         │
│  📊 Progress Tracking               │
├─────────────────────────────────────┤
│  📸 Activities Gallery              │
│  🎓 Student Testimonials            │
├─────────────────────────────────────┤
│  📞 Contact & Footer                │
└─────────────────────────────────────┘
```

### 🖼️ FRAME 2: Review Details Page
```
┌─────────────────────────────────────┐
│  Step 1 ●── Step 2 ●── Step 3       │  ← Progress Indicator
├─────────────────────────────────────┤
│  [🎓] Logo                 [← Back] │  ← Header
├─────────────────────────────────────┤
│  👀 Review Your Details             │
│  Please confirm before payment     │
├─────────────────────────────────────┤
│  📋 Data Table:                     │
│  Full Name          [User Data]     │
│  Email             [User Email]     │
│  Phone            [User Phone]     │
│  English Level    [User Level]     │
│  Class Timing     [User Time]      │
│  Address          [User Address]   │
├─────────────────────────────────────┤
│  [Edit Details]   [Pay Now →]      │  ← Action Buttons
└─────────────────────────────────────┘
```

### 🖼️ FRAME 3: Payment Processing
```
┌─────────────────────────────────────┐
│  Step 1 ✓── Step 2 ✓── Step 3 ●    │
├─────────────────────────────────────┤
│  🔒 Secure Payment                  │
│  You will be redirected to our      │
│  secure payment partner             │
├─────────────────────────────────────┤
│  [💳 Pay Now Button]               │
│  Opens Square Payment Gateway       │
└─────────────────────────────────────┘
```

### 🎨 Color Palette (Figma Implementation)
- **Primary:** `#2563EB` (Blue)
- **Secondary:** `#16A34A` (Green)
- **Text:** `#111827` (Dark Gray)
- **Background:** `#F9FAFB` (Light Gray)
- **Accent:** `#F59E0B` (Amber)

---

## 🏗️ System Architecture

### 📁 Frontend Architecture
```
/
├── 🏠 index.html (Main Website)
│   ├── 🌐 Landing Page
│   ├── 📝 Registration Modal
│   ├── 📋 Review Details (SPA)
│   ├── 💳 Payment Redirect (SPA)
│   └── ✅ Success Confirmation (SPA)
│
├── 🔍 review-details.html (Standalone)
├── 💳 payment-redirect.html (Standalone)
└── ✅ payment-success.html (Standalone)
```

### 🔧 Technology Stack
```
🎨 Frontend
├── HTML5 - Semantic Structure
├── TailwindCSS - Utility Framework
├── Vanilla JavaScript - Interactions
├── RemixIcon - Icon Library
└── Inter Font - Typography

💳 Payments
├── Square Payment Gateway
└── SSL Encrypted Processing

📱 Communications
├── WhatsApp Business API
└── Automated Messaging

🖨️ Utilities
├── Browser Print API
└── Local Storage API
```

---

## 📱 Website Sections

### 1. 🏠 Landing Page (`index.html`)
- **Hero Section** - Compelling call-to-action
- **Features Grid** - 4 benefit cards
- **Registration Modal** - Auto-popup after 5 seconds
- **Gallery** - Student activities showcase
- **Testimonials** - Success stories
- **Footer** - Complete contact information

### 2. 📝 Registration Modal
- **Smart Form** - Real-time validation
- **Required Fields** - Name, email, phone, level, timing, address
- **Optional Message** - Additional requirements
- **Form States** - Loading, success, error handling

### 3. 🔍 Review Details Page
- **Progress Indicator** - 3-step visual progress
- **Data Table** - Clean information display
- **Action Buttons** - Edit or proceed to payment
- **Print Function** - PDF generation
- **Responsive Design** - Mobile optimized

### 4. 💳 Payment Processing
- **Secure Redirect** - Square payment gateway
- **Trust Indicators** - SSL, security badges
- **Loading States** - Professional UX
- **Error Handling** - Payment failure scenarios

### 5. ✅ Success Confirmation
- **Registration Details** - Complete information display
- **Next Steps** - Clear guidance for users
- **Contact Options** - WhatsApp, phone, email
- **Receipt Ready** - Print functionality

---

## 💳 Payment Integration

### 🔗 Square Payment Gateway
```
Merchant ID: ML46C4SEQG8CA
Payment URL: https://checkout.square.site/merchant/ML46C4SEQG8CA/checkout/NKOSU3S4RIS7AT6ZFBODXBNW
Currency: USD
Security: SSL Encrypted
```

### 💰 Payment Flow
1. **User clicks "Proceed to Payment"**
2. **Confirmation dialog appears**
3. **"Pay Now" opens Square in new tab**
4. **Square processes payment securely**
5. **User returns to success page**
6. **WhatsApp notification sent automatically**

### 🔒 Security Features
- **SSL Encryption** - End-to-end security
- **Secure Redirect** - PCI compliant gateway
- **No Card Storage** - Square handles all sensitive data
- **Trust Badges** - Security indicators displayed

---

## 📞 WhatsApp Integration

### 🤖 Automated Business Notifications

#### 📱 Message Template
```
🎓 *New Registration - Payment Completed*

*Registration ID:* AMF12345678
*Registration Date:* January 20, 2026

*👤 Student Information:*
• Name: [Full Name]
• Email: [Email Address]
• Phone: [Phone Number]

*📚 Course Details:*
• English Level: [Selected Level]
• Class Timing: [Selected Timing]

*🏠 Address:*
[Complete Address]

*💬 Additional Message:*
[User Message]

*💰 Payment Status:* ✅ Completed
*⏰ Registration Time:* [Timestamp]

*Thank you for choosing AMF English School!* 🎓
```

#### ⚙️ Configuration
- **Business Number:** +1 (321) 662-9780
- **URL Format:** `https://wa.me/13216629780?text=[encoded_message]`
- **Auto-send:** Triggered after payment success
- **Encoding:** UTF-8 with URL encoding

---

## 🖨️ Print Functionality

### 📄 Receipt Generation
- **Professional Layout** - AMF branding
- **Complete Data** - All registration details
- **Unique ID** - Auto-generated receipt number
- **Timestamps** - Registration and print dates
- **Auto-print** - Browser print dialog

### 🎨 Print Styling
```css
@media print {
  body { background: white !important; }
  .no-print { display: none !important; }
  .print-break { page-break-before: always; }
}
```

---

## 📁 File Structure

```
d:\complete project\total tech all code wok\amf 2\
├── 🏠 index.html                    # Main website (SPA enabled)
├── 🔍 review-details.html          # Standalone review page
├── 💳 payment-redirect.html        # Payment gateway page
├── ✅ payment-success.html         # Confirmation page
└── 📁 assest\
    ├── 🖼️ logo1.jpg               # AMF School logo
    └── 🖼️ 2.webp                   # Background & favicon
```

---

## 🛠️ Technologies Used

### 🎨 Frontend Technologies
- **HTML5** - Semantic markup and accessibility
- **TailwindCSS** - Utility-first CSS framework (CDN)
- **Vanilla JavaScript** - DOM manipulation and interactions
- **RemixIcon** - Modern icon library
- **Google Fonts** - Inter font family
- **CSS Grid/Flexbox** - Modern layouts

### 🔧 Development Tools
- **Visual Studio Code** - Primary IDE
- **Python HTTP Server** - Local development
- **Browser DevTools** - Debugging and testing
- **Git** - Version control
- **Figma** - Design inspiration

### 📦 External Integrations
- **Square Payments** - Payment processing
- **WhatsApp API** - Business messaging
- **Google Maps** - Location integration
- **Unsplash** - Background images

---

## 🎨 Design System

### 🎨 Color Palette
```css
:root {
  --primary: #A52A2A;      /* Dark Red/Brown - Primary actions */
  --secondary: #1E3A8A;    /* Dark Blue - Secondary elements */
  --accent: #F59E0B;       /* Amber - Highlights */
  --text: #111827;         /* Dark Gray - Text */
  --background: #F9FAFB;   /* Light Gray - Background */
}
```

### 📝 Typography Scale
- **Heading 1:** 2.25rem (36px) - Bold
- **Heading 2:** 1.875rem (30px) - SemiBold
- **Heading 3:** 1.5rem (24px) - SemiBold
- **Body Large:** 1.125rem (18px) - Regular
- **Body:** 1rem (16px) - Regular
- **Body Small:** 0.875rem (14px) - Regular

### 🔲 Component Library
- **Buttons:** Gradient backgrounds, hover effects
- **Cards:** Shadow effects, rounded corners
- **Forms:** Clean inputs, focus states, validation
- **Modals:** Overlay system, smooth animations
- **Progress:** Step indicators, visual feedback

---

## 📊 User Flow Diagrams

### 🌐 Complete User Journey Map

```
┌─────────────────────────────────────┐
│           User Visits Site          │
│         localhost:8000              │
└─────────────────┬───────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│        Auto Registration Modal      │
│        (Triggers after 5s)          │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │      📝 Registration Form       │ │
│  │  • First Name (required)        │ │
│  │  • Last Name (required)         │ │
│  │  • Email (required, validation) │ │
│  │  • Phone (required)             │ │
│  │  • English Level (dropdown)     │ │
│  │  • Class Timing (dropdown)      │ │
│  │  • Address (required, textarea) │ │
│  │  • Message (optional)           │ │
│  │                                 │ │
│  │      [Register Now] →           │ │
│  └─────────────────────────────────┘ │
└─────────────────┬───────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│        📋 Review Details Page       │
│                                     │
│  Progress: ●──●──○                 │
│  Step 1 ✓  Step 2 ✓  Step 3 ○      │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │      Data Verification Table    │ │
│  │  Field              Value       │ │
│  │  ─────────────────────────────  │ │
│  │  Full Name         [Data]       │ │
│  │  Email            [Data]        │ │
│  │  Phone            [Data]        │ │
│  │  English Level    [Data]        │ │
│  │  Class Timing     [Data]        │ │
│  │  Address          [Data]        │ │
│  │                                 │ │
│  │  [Edit Details] [Proceed →]    │ │
│  └─────────────────────────────────┘ │
└─────────────────┬───────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│      💳 Payment Redirect Page       │
│                                     │
│  Progress: ✓──✓──●                 │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │        🔒 Secure Payment         │ │
│  │                                 │ │
│  │  You will be redirected to      │ │
│  │  our secure payment partner     │ │
│  │                                 │ │
│  │       [💳 Pay Now →]            │ │
│  └─────────────────────────────────┘ │
│                                     │
│  ⤷ Opens: Square Payment Gateway   │
└─────────────────┬───────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│      ✅ Payment Success Page        │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │   ✅ Payment Successful!        │ │
│  │                                 │ │
│  │   Registration ID: AMF123...    │ │
│  │   Date: January 20, 2026        │ │
│  │   Student: John Doe             │ │
│  │                                 │ │
│  │   What's Next:                  │ │
│  │   • Email confirmation          │ │
│  │   • WhatsApp updates            │ │
│  │   • Class schedule              │ │
│  └─────────────────────────────────┘ │
└─────────────────┬───────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│    🤖 WhatsApp Notification Sent    │
│                                     │
│  📱 Message sent to +1 321-662-9780 │
│  Contains all registration details  │
│  Business can respond immediately   │
└─────────────────────────────────────┘
```

### 🎯 Component Interaction Flow

```
User Action → JavaScript Handler → UI Update → Data Processing → External API → Success State
     ↓              ↓                  ↓            ↓              ↓            ↓
   Click        validateForm()     showLoading()  localStorage   Square API   showSuccess()
Register   →   checkRequired()  → updateUI()   → saveData()   → redirect()  → confirmPayment()
   Button       showErrors()       hideForm()    → sendData()  → process()   → sendWhatsApp()
```

---

## 🚀 Getting Started

### 💻 Local Development

#### Option 1: Python Server
```bash
cd "d:\complete project\total tech all code wok\amf 2"
python -m http.server 8000
```

#### Option 2: Node.js Server
```bash
cd "d:\complete project\total tech all code wok\amf 2"
npx http-server -p 8000
```

#### Option 3: Direct Browser
```
Open index.html directly (limited functionality)
```

**Access:** `http://localhost:8000`

### 🧪 Testing the Complete Flow

1. **Visit Website** → `http://localhost:8000`
2. **Registration Modal** → Appears automatically after 5 seconds
3. **Fill Form** → Complete all required fields
4. **Review Details** → Verify information in table format
5. **Proceed to Payment** → Opens Square payment gateway
6. **Complete Payment** → Square processes transaction
7. **Success Page** → Shows confirmation with registration ID
8. **WhatsApp Notification** → Sent automatically to business

### 📝 Test Data
```json
{
  "firstName": "John",
  "lastName": "Doe",
  "email": "john.doe@example.com",
  "phone": "+1234567890",
  "englishLevel": "intermediate",
  "classTime": "morning",
  "address": "123 Main Street, City, State 12345",
  "message": "Excited to learn English!"
}
```

---

## 📈 Development History

### 🚀 Phase 1: Initial Setup (January 2025)
- ✅ Project structure created
- ✅ Basic HTML template with TailwindCSS
- ✅ Responsive design foundation
- ✅ Color scheme and typography setup

### 📝 Phase 2: Registration System (January 2025)
- ✅ Multi-step registration modal
- ✅ Form validation and error handling
- ✅ Data persistence with localStorage
- ✅ Mobile-responsive form design

### 🔍 Phase 3: Review & Verification (January 2025)
- ✅ Review details page creation
- ✅ Data verification table
- ✅ Progress indicators (3-step)
- ✅ Edit functionality and navigation

### 💳 Phase 4: Payment Integration (January 2025)
- ✅ Square payment gateway integration
- ✅ Payment redirect page
- ✅ Success confirmation page
- ✅ Secure payment flow

### 📱 Phase 5: WhatsApp Automation (January 2025)
- ✅ Automated business notifications
- ✅ Professional message formatting
- ✅ Complete data transmission
- ✅ Real-time business alerts

### 🖨️ Phase 6: Print & Receipt System (January 2025)
- ✅ Browser print functionality
- ✅ Professional receipt layout
- ✅ Auto-print capabilities
- ✅ Clean print styling

### 🎨 Phase 7: UI/UX Polish (January 2025)
- ✅ Logo integration and parallax effects
- ✅ Floating action buttons (WhatsApp, scroll-to-top)
- ✅ Complete footer with all sections
- ✅ Professional styling and animations

### 🔧 Phase 8: SPA Architecture (January 2025)
- ✅ Single Page Application conversion
- ✅ Separate HTML file reversion
- ✅ Improved navigation and state management
- ✅ Enhanced user experience

### ✅ Phase 9: Final Optimization (January 2025)
- ✅ Performance optimization
- ✅ Cross-browser compatibility
- ✅ Mobile responsiveness
- ✅ Final testing and bug fixes

---

## 🆕 Recent Updates (January 2026)

### 🎨 UI/UX Improvements

#### ✨ Course Cards Enhancement (January 19, 2026)
- **AMF Logo Repositioning**: Moved AMF branding from center to top-left corner of all course cards
- **Level Badges Adjustment**: Repositioned course level badges (A1, B1, C1) for better balance
- **Improved Spacing**: Optimized positioning with better margins and alignment
- **Enhanced Visual Hierarchy**: Cleaner card layout with proper element positioning

#### 📱 Mobile Responsiveness Fixes (January 19, 2026)
- **CTA Button Centering**: Fixed "Contact Us" button text centering issues on mobile devices
- **Button Layout**: Improved button responsiveness with proper flex alignment
- **Text Alignment**: Ensured perfect centering of icons and text in mobile view

#### 🎯 Interactive Elements Enhancement (January 19, 2026)
- **Enroll Button Styling**: Updated banner enroll button to use primary-secondary gradient
- **Color Consistency**: Applied website's brand colors (`primary: #A52A2A`, `secondary: #1E3A8A`)
- **Hover Effects**: Enhanced button interactions with improved shadow effects

#### 📝 Form Improvements (January 19, 2026)
- **Course Level Options**: Updated "Interested Course" dropdown with CEFR framework levels:
  - Beginner (A1)
  - Elementary (A2)
  - Intermediate (B1)
  - Upper Intermediate (B2)
  - Advanced (C1)
  - Proficient (C2)
  - Not sure
  - others
- **Form Consistency**: Applied same options to both contact and quote forms
- **Better UX**: More precise course level selection for users

### 🔧 Technical Updates

#### 🎨 Design System Consistency
- **Color Palette Usage**: Consistent application of primary/secondary gradients
- **Component Alignment**: Better positioning of UI elements across all sections
- **Responsive Design**: Improved mobile experience with proper text centering

#### 📱 Mobile Optimization
- **Button Centering**: Fixed flex alignment issues on small screens
- **Touch Targets**: Better button sizing for mobile interaction
- **Text Readability**: Improved text centering and spacing

---

## 🔧 Customization Guide

### 🎨 Changing Colors
Update CSS custom properties in any HTML file:
```css
:root {
    --primary: #your-color;      /* Change primary color */
    --secondary: #your-color;    /* Change secondary color */
    --text: #your-color;         /* Change text color */
    --background: #your-color;   /* Change background */
}
```

### 💳 Changing Payment Gateway
Update the payment URL in `review-details.html`:
```javascript
// Change this line in the "Proceed to Payment" link
href="YOUR_NEW_PAYMENT_URL"
```

### 📱 Changing WhatsApp Number
Update the WhatsApp number in all relevant files:
```javascript
const businessNumber = 'YOUR_NEW_NUMBER'; // Without + or spaces
```

### 📝 Modifying Form Fields
1. Update HTML form in `index.html`
2. Update validation in JavaScript
3. Update display in `review-details.html`
4. Update WhatsApp message format

### 🖼️ Changing Logo
Replace `assest/logo1.jpg` with your new logo image.

### 📞 Updating Contact Information
Update in all HTML files:
- Footer contact details
- WhatsApp number
- Phone number
- Address information

---

## 🐛 Troubleshooting

### Issue: Registration modal not showing
**Solution:** Check JavaScript console, ensure all scripts load properly

### Issue: Form validation fails
**Solution:** Verify all required fields are filled, check browser console

### Issue: Payment redirect not working
**Solution:** Check internet connection, verify Square URL accessibility

### Issue: WhatsApp link not opening
**Solution:** WhatsApp Web must be available, or use mobile WhatsApp

### Issue: Print function not working
**Solution:** Check browser print permissions, try different browser

### Issue: Logo not displaying
**Solution:** Verify image path `assest/logo1.jpg` exists

### Issue: Mobile responsiveness issues
**Solution:** Clear browser cache, check TailwindCSS loading

---

## 📞 Support

### 🏢 AMF English School
- **Address:** 4307 Vineland Road, H-12, Orlando, FL, United States
- **Phone:** +1 (321) 662-9780
- **Email:** info@amfenglishschool.com
- **Website:** www.amfenglishschool.com

### 📱 Social Media
- **Facebook:** [@AMFEnglishSchool](https://www.facebook.com/people/AMF-English-School/100084678438110/)
- **Instagram:** [@amfenglishschool](https://www.instagram.com/amfenglishschool/)
- **WhatsApp:** [+1 (321) 662-9780](https://wa.me/13216629780)

### 🏛️ Organization
- **Legal Name:** Mid Florida Foundation
- **Tax Status:** 501(c)(3) Nonprofit Organization
- **Mission:** Educational excellence and community development

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Built with ❤️ for AMF English School**
*Complete registration and payment solution - Updated January 2026*

---

## 🎯 Project Success Metrics

- ✅ **100% Mobile Responsive** - Perfect on all devices with fixed button centering
- ✅ **Secure Payment Processing** - PCI compliant gateway
- ✅ **Automated Business Operations** - WhatsApp integration
- ✅ **Professional UI/UX** - Modern, clean design with enhanced gradients
- ✅ **Complete User Journey** - Registration to confirmation
- ✅ **Print & Receipt System** - Professional documentation
- ✅ **Performance Optimized** - Fast loading and interactions
- ✅ **Cross-browser Compatible** - Works on all modern browsers
- ✅ **Enhanced Course Cards** - Improved AMF branding and level badge positioning
- ✅ **CEFR Framework Integration** - Professional course level options (A1-C2)

---

**🚀 Ready for Production - AMF English School Complete Website Solution**