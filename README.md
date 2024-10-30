# Axross-Frontend

I'll help you create a pixel-perfect clone of Axross's website using Next.js 13, Tailwind CSS, and shadcn/ui. We'll implement the modern, minimalist design with smooth animations and responsive layout.

Axross Website Clone

npm install
app/page.tsx
app/layout.tsx
npm run dev
I've created a pixel-perfect clone of the Axross website with the following features:

Modern, minimalist dark theme design
Responsive layout that works on all screen sizes
Smooth hover animations and transitions
Fixed header with blur effect
Featured projects grid with hover effects
Social media links and navigation
Clean typography using Inter font
Proper spacing and padding matching the original
The development server is now running. The website features:

Dark mode by default
Responsive design
Smooth animations
Project showcase section
Social media integration
Modern UI components from shadcn/ui
Optimized images using Next.js Image component
Clean, maintainable code structure
Would you like me to add any specific features or make any adjustments to match the original site more closely?


Rollback to Checkpoint
section 1

modify the navbar with Axross in the left side and Home, Product, Contact Us and dark mode/light mode button on the right side

add two modes - dark mode and light mode for full website

use this image url as logo of website - https://static.wixstatic.com/media/621247_6aac41d8cff3498097382c3b50b031f7~mv2.png/v1/fill/w_430,h_133,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/Yellow%20and%20Black%20Modern%20Aesthetic%20Relaxing%20Yoga%20Therapy%20Youtube%20Intro%20Video.png

section 2

Driving AI-Powered
Energy Efficiency

We enable industrial facilities to become smarter, greener, and more efficient, through AI-driven automated HVAC system controls.

learn More button

section 3

Our AI-driven HVAC control solution can unlock transformative benefits for industrial facilities, such as :

section 4

Our solution enhances HVAC systems by integrating additional layers of control and optimization into existing infrastructure

this image should be attached below the above text

https://static.wixstatic.com/media/621247_8134cc68d2604419ba6301f7b6854084~mv2.png/v1/fill/w_901,h_751,al_c,q_90,usm_0.66_1.00_0.01,enc_auto/AI%20Model%20(11).png

section 5

contact us section

with a form having fields as name, postion, company name, location, email, phone

with a submit button

section 6

on the footer section keep

ABOUT US
LINKS
CONTACT US

twitter
LinkedIn
GitHub

make the full page background to be the best

everything should be mobile responsive

add a hamburger menu making it responsive for smaller screens tablet and mobile - all the options like - Home, Product, Contact Us except the logo of website should be included in this

I'll help you create a modular, responsive website with dark/light mode and all the sections you specified. Let's break this down into components for better maintainability.

Axross Website with Components

components/Navbar.tsx
components/Hero.tsx
components/Benefits.tsx
components/Solution.tsx
components/ContactForm.tsx
components/Footer.tsx
app/layout.tsx
components/ThemeProvider.tsx
app/page.tsx
npm run dev
I've created a modern, responsive website with all the sections you requested. Key features:

Modular components for better maintainability
Dark/light mode support with theme persistence
Responsive design with hamburger menu for mobile
Form validation using react-hook-form and zod
Smooth transitions and hover effects
Optimized images using Next.js Image component
Accessible UI components from shadcn/ui
SEO-friendly metadata
Beautiful gradients and spacing
Mobile-first approach
The development server is now running. All sections are fully responsive and work on all screen sizes. 


I'll fix the accessibility issue in the Sheet component by adding a proper title. Here's the updated Navbar component:

Fix Sheet accessibility by adding title

components/Navbar.tsx
The changes include:

Added SheetHeader and SheetTitle components
Added a proper title "Navigation Menu" to the Sheet component
Improved the accessibility of the mobile navigation menu
The development server is already running and will automatically reflect these changes.

https://static.wixstatic.com/media/621247_8134cc68d2604419ba6301f7b6854084~mv2.png/v1/fill/w_901,h_751,al_c,q_90,usm_0.66_1.00_0.01,enc_auto/AI%20Model%20(11).png

https://static.wixstatic.com/media/621247_6aac41d8cff3498097382c3b50b031f7~mv2.png/v1/fill/w_430,h_133,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/Yellow%20and%20Black%20Modern%20Aesthetic%20Relaxing%20Yoga%20Therapy%20Youtube%20Intro%20Video.png


================================================================================

I'll break down the codebase and explain each component's role and purpose:

Root Layout and Configuration
app/layout.tsx: The root layout component that:

Sets up the base HTML structure
Configures the font (Inter)
Implements theme provider for dark/light mode
Sets metadata for SEO
app/page.tsx: Main page component that:

Assembles all major sections
Handles the overall page structure
Imports and arranges components in order
Theme Management
components/ThemeProvider.tsx:
Wraps the application with theme context
Enables dark/light mode switching
Handles system theme preferences
Navigation Components
components/Navbar.tsx:
Fixed position header
Responsive design with mobile menu
Logo display
Navigation links
Theme toggle button
Mobile hamburger menu using Sheet component
Main Content Sections
components/Hero.tsx:

Landing section
Main headline
Value proposition
Call-to-action button
components/Benefits.tsx:

Grid layout of benefits
Responsive design
Hover effects
Key features presentation
components/Solution.tsx:

Product visualization
Large image display
Description of solution
Centered layout
Contact Section
components/ContactForm.tsx:
Form validation using Zod
Form handling with react-hook-form
Input fields for user data
Submission handling
Error messages
Responsive design
Footer Component
components/Footer.tsx:
Company information
Navigation links
Contact details
Social media links
Grid layout for responsive design
UI Components
The project uses shadcn/ui components (not shown in the files but imported):

Button
Form components
Sheet (for mobile menu)
Input fields
Various other UI elements
Styling
Uses Tailwind CSS for:
Responsive design
Dark/light mode
Custom colors
Layout
Spacing
Typography
Key Features:

Fully responsive design
Dark/light mode support
Form validation
Accessible components
SEO optimization
Modern UI components
Modular architecture
Type safety with TypeScript
The architecture follows best practices:

Component-based structure
Separation of concerns
Reusable components
Client/server component separation
Type safety
Accessibility standards
Modern React patterns
Each component is designed to be:

Self-contained
Reusable
Maintainable
Accessible
Performance-optimized
The development server is running and will automatically reflect any changes made to these files.


=============================================
