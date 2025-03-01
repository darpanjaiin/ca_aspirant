# Product Requirement Document (PRD) - CA Exam Web App

## 1. Product Overview

### 1.1 Purpose
The CA Exam Web App is a free, frontend-only web tool designed to help CA (Chartered Accountant) students create personalized study plans for their exams. It addresses the common challenge of poor planning among CA aspirants by offering a simple, intuitive interface to generate study schedules based on user inputs, connect with successful CA passers for inspiration, and motivate students toward success. The app is 100% free, ad-free, and accessible via any web browser.

### 1.2 Target Audience
- CA students preparing for Intermediate or Final exams (e.g., November 2025 attempt).
- Age: 20–30 years, tech-savvy, often balancing articleship and studies.
- Needs: Clear study plans, motivation, and strategic guidance from CA success stories.

### 1.3 Value Proposition
- Free forever, no ads, no sign-ups—pure value for CA students.
- Personalized study plans in minutes, visually appealing and downloadable.
- Inspiration and connection with CA Trailblazers (successful first-attempt passers).

## 2. Product Features

### 2.1 Study Plan Generator (MVP)
#### Input Form:
- Exam level (CA Intermediate/Final).
- Exam date (e.g., November 2025).
- Start date for study (e.g., June 1st, 2025).
- Weak subjects (dropdown or checkboxes: e.g., Taxation, Costing).
- Daily study hours (optional slider or dropdown).

#### Output:
- A visually appealing timeline or calendar view showing study days per subject, revision cycles, and mock test dates.
- A downloadable CSV file with a detailed plan (e.g., Date, Subject, Task, Notes).
- Logic: Simple frontend calculations based on total days, subject count, and user inputs (e.g., allocate more days to weak subjects).

### 2.2 Visual Design
- Clean, modern UI/UX with a professional yet approachable aesthetic.
- Color scheme: Blue (trust), gold (success), white background, with optional accents (e.g., orange for motivation).
- Responsive design for desktop and mobile browsers.

### 2.3 Inspirational Elements
- A hero section with a motivational headline (e.g., “Sail Through Your CA Exams. Win with Ease.”) and subheadline (e.g., “Get a free, personalized plan from CA Trailblazers—100% free, no hassle.”).
- A “Why We Started” section (e.g., “We built this to light the path for CA students, free forever, drawing on our first-attempt success.”).
- Links or placeholders for connecting with CA passers (e.g., testimonial quotes or future chat features).

## 3. User Journey

### 3.1 Homepage
Users land on a simple hero section with:
- Headline, subheadline, and two CTAs (“Get Your Plan Now,” “Learn More”).
- Optional top banner (e.g., “Turning CA Aspirants into Chartered Accountants!”).
- Navigation to “How It Works,” “Why We Started,” and “Contact” sections.

### 3.2 Plan Generator Flow
1. User fills out a short form (dropdowns, checkboxes, date pickers).
2. App processes inputs client-side (HTML/CSS/JavaScript) to generate a plan.
3. User views a visual timeline (e.g., horizontal bar chart or calendar) and downloads a CSV via a button.
4. Optional feedback prompt or progress tracking placeholder.

### 3.3 Exit Points
- Download CSV button for offline use.
- “Learn More” link for deeper engagement with mentorship or motivation content.

## 4. Technical Requirements

### 4.1 Frontend Stack
- **HTML5**: For structure and semantic markup (e.g., forms, sections, buttons).
- **CSS3**: For styling, responsiveness, and animations (e.g., Flexbox, Grid, media queries for mobile/desktop).
- **JavaScript (Vanilla or Light Library)**: For basic interactivity (e.g., form validation, plan generation logic, CSV download). Avoid heavy frameworks for now to keep it lightweight and frontend-only.

### 4.2 Performance
- Load time < 3 seconds on a 3G connection.
- Mobile-responsive design (100% viewport width, touch-friendly buttons).
- No backend required—client-side processing only.

### 4.3 Accessibility
- WCAG 2.1 compliant (e.g., alt text for images, keyboard navigation, high-contrast colors).
- Screen-reader friendly forms and buttons.

### 4.4 Browser Support
- Chrome, Firefox, Safari, Edge (latest versions).
- No Internet Explorer support (focus on modern browsers for CA students).

## 5. Design Guidelines

### 5.1 Logo
- Use a simple logo (e.g., blue compass with gold graduation cap, as discussed earlier).
- Font: Futura Bold or similar sans-serif (clean, modern).

### 5.2 Colors
- **Primary**: Blue (#007BFF for trust).
- **Secondary**: Gold (#FFD700 for success).
- **Accent**: Orange (#FF8C00 for motivation).
- **Background**: White (#FFFFFF).

### 5.3 Typography
- **Headings**: Futura Bold or Montserrat Bold (24–36px).
- **Body**: Open Sans or Lato (16–18px, readable on mobile).

## 6. Non-Functional Requirements
- **Security**: No personal data collection (no backend, no forms requiring sensitive info beyond exam preferences).
- **Scalability**: Frontend can handle 1,000+ simultaneous users (lightweight code, CDN for assets if needed later).
- **Maintenance**: Easy to update HTML/CSS for new exam dates or features.

## 7. Success Metrics
- **Adoption**: 500 users in the first month, 5,000 in 6 months (via LinkedIn/CA groups).
- **Engagement**: 70% of users download a plan, 30% return within a week for adjustments.
- **Feedback**: Net Promoter Score (NPS) > 8 from early users.

## 8. Next Steps
### Phase 1 (1–2 days)
- Develop and test MVP (study plan generator) using HTML/CSS/JavaScript.
- Launch a beta on a free hosting platform (e.g., GitHub Pages).

### Phase 2 (3–6 weeks)
- Gather user feedback, refine UI/UX, add inspirational content (e.g., CA Trailblazer quotes).

### Phase 3 (6+ weeks)
- Expand with mentorship features, progress tracking, and marketing campaigns.

## 9. Assumptions and Constraints
### Assumptions
- CA students have internet access and basic browser knowledge.
- Users trust a free tool backed by a first-attempt CA passer.

### Constraints
- No backend or database (frontend-only).
- Limited development resources (HTML/CSS, no complex frameworks).
