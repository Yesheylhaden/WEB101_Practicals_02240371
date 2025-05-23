# Reflection on TikTok Project

## Documentation

### Main Concepts Applied:
1. Next.js App Router
- Used for routing between pages (Home, Profile Upload, Login, etc.).
- Implemented nested layouts (MainLayout.jsx) for consistent UI across pages.

2. Tailwind CSS
- Styled components using utility classes for responsive design.
- Applied hover effects, flexbox, and grid layouts for TikTok-like UI.

3. React Components & Props
- Created reusable components (VideoCard, VideoFeed).
- Passed data (e.g., DUMMY_POSTS) via props for dynamic rendering.

4. Form Handling & Validation
- Used React Hook Form for login/signup forms.
- Implemented validation rules (required fields, email patterns, password matching).

5. State Management
- Managed UI state (e.g., liked in VideoCard) with useState.
- Simulated loading states during form submission.

6. File Structure Organization
- Followed Next.js conventions (/app, /components, /lib).
- Separated UI logic from page layouts.

## Things I Learned:

1. Next.js Routing:
- Learned how the App Router simplifies nested layouts compared to Pages Router.
- Used Link for client-side navigation without full page reloads.

2. Tailwind CSS Efficiency:
- Became comfortable with utility-first styling (e.g., flex, hover:bg-gray-100).
- Learned to customize breakpoints for mobile/desktop responsiveness.

3. Form Validation:
- Gained experience with react-hook-form for error handling.
- Practiced regex patterns for email/password validation.

4. Component Reusability:
- Structured VideoCard to accept dynamic props (likes, comments, shares).
- Avoided duplicate code by centralizing layouts (MainLayout).

## Challenges and Solutions

1. Sidebar Layout Issues
**Problem:** 
The fixed sidebar caused content overflow on small screens.
**Solution:**
- Added overflow-y-auto to enable scrolling.
Used ml-60 on the main content to prevent overlap.

2. TypeScript Migration
**Problem:**
- Initially skipped TypeScript but later realized its benefits.
**Solution:**
- Manually added PropTypes for key components (e.g., VideoCard props).
**Future plan:**
- Migrate to TypeScript for better type safety.

## Conclusion
Through this TikTok practical, I gained a hands-on experience with essential frontend development tools and frameworks like Next.js, Tailwind CSS, and React Hook Form. It deepened my understanding of routing, component-based architecture, and form validation. The practical taught me how to structure scalable code, build reusable UI components, and handle user interactions effectively. Despite facing challenges like layout responsiveness and form validation, I was able to overcome them by applying best practices and debugging techniques. Therefore, this practical has enhanced both my technical skills and my confidence in building modern, responsive web applications.