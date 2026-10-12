# PrintWorks Portfolio

# MASTER PROMPT: Premium Dynamic Portfolio Website for PRINTING AND REPRODUCTION OF RECORDED MEDIA

## 1. Project Overview

Build a complete, premium, modern, responsive, dynamic portfolio website for the business:

**PRINTING AND REPRODUCTION OF RECORDED MEDIA**

The website must represent a professional printing, commercial print production, and recorded-media reproduction business. It should look like a real, established business website designed by an experienced professional, not a generic AI-generated template.

This is a frontend demo website with a fully functional browser-based admin panel. All content must use mock data. No database or backend is required.

### Business Details

- Business Name: PRINTING AND REPRODUCTION OF RECORDED MEDIA
- Client Name: Not provided
- Business Category: Printing, Print Production and Reproduction of Recorded Media
- Phone: 2451324535
- Email: Not provided
- Address: Not provided
- Website Type: Dynamic Business Portfolio Website
- Developer Credit: Designed and development by SOSynch Ai Tech

Do not invent the company's address, email, founding year, certifications, actual clients, awards, or verified business statistics. Use clearly identified demo content where necessary.

## 2. Strict Technology Requirements

Use ONLY:

- React
- Vite
- Tailwind CSS

Do not use any other framework, UI library, component library, icon library, animation library, or CSS framework.

Do not use Next.js, Vue, Angular, Bootstrap, Material UI, shadcn/ui, Framer Motion, Lucide, or external icon packages.

Use React components, React hooks, Tailwind utility classes, and native HTML, CSS, and JavaScript.

Use inline SVG or CSS-created icons.

The project must run using the standard Vite development server and follow a clean, reusable component structure.

Do not add unnecessary dependencies.

## 3. Mock Data Only — No Database

This is a frontend-only demonstration.

- Do not connect MongoDB, MySQL, PostgreSQL, Supabase, Firebase, or any other database.
- Do not create backend APIs, Express servers, PHP services, or external authentication services.
- Use centralized JavaScript mock data.
- Use localStorage to persist website content and admin changes.
- Use sessionStorage for the simulated admin login session.
- Implement working CRUD operations wherever appropriate.
- Ensure admin changes update the public website immediately.
- Provide realistic initial mock content so the website looks complete on first launch.

All content management must work in the browser.

## 4. Premium Design System

Create a sophisticated visual identity inspired by premium commercial printing companies, editorial design studios, and industrial print production facilities.

### Exact Color Palette

- Deep Navy: #123047
- Print Teal: #087E8B
- Accent Gold: #F4B942
- Off White: #F5F7FA
- White: #FFFFFF
- Primary Text: #202B35
- Muted Text: #687785
- Border: #DFE6EC

### Color Usage

- Deep navy for navigation, footer, headings, and strong visual elements.
- Teal for buttons, links, interactive elements, and selected highlights.
- Gold for subtle accents, labels, and small decorative details.
- White and off-white for backgrounds.
- Dark text and muted grey for readable content.

### Design Principles

- Premium industrial and editorial style.
- Large, high-quality photography.
- Strong typography and visual hierarchy.
- Generous whitespace.
- Balanced layouts with carefully controlled spacing.
- Professional image crops and varied compositions.
- Subtle CSS transitions.
- Refined borders and restrained shadows.
- Avoid excessive gradients, neon colors, excessive rounded cards, and generic AI layouts.
- Make the website look naturally designed for a real business.

Use system font stacks instead of adding external font libraries.

## 5. Header and Navigation

Create a premium sticky navigation header with:

- Text-based business logo and a custom print-inspired SVG or CSS logo mark.
- Home
- About
- Services
- Portfolio
- Gallery
- Contact
- Get a Quote CTA

Every navigation link must work correctly.

Do not make all navigation links scroll to the same section.

Use separate React page components or a properly implemented browser-native navigation system with distinct pages or routes. Do not introduce another routing library.

Requirements:

- Home opens the homepage.
- About opens the About page.
- Services opens the Services page.
- Portfolio opens the portfolio.
- Gallery opens the gallery.
- Contact opens the contact page.
- Get a Quote opens the quote request form.
- Active navigation states must be visible.
- Mobile navigation must open and close properly.
- Browser back and forward navigation should work where applicable.
- Direct page refreshes on Vercel must not result in 404 errors.

## 6. Hero Section with Premium Banner Image

Create an impressive hero section with a large, professional printing-related photograph.

The hero image should feature one or more of the following:

- Modern commercial printing presses.
- Industrial offset printing machinery.
- High-quality printed sheets.
- A professional print production facility.
- Printed marketing materials and packaging.

Use a real photographic image, not a plain gradient or abstract illustration.

### Hero Content

Eyebrow: PROFESSIONAL PRINTING & REPRODUCTION

Headline: Precision Printing. Professional Results.

Description: A concise, professional introduction to print production, printed materials, finishing, and attention to project requirements.

Primary CTA: Explore Our Services

Secondary CTA: View Our Work

Include a visually striking hero image with an appropriate crop and a clean text layout.

The hero headline, description, CTA labels, destinations, image URL, alt text, and visibility must be editable from the admin dashboard.

On mobile, stack the content vertically and ensure the banner remains visible and readable.

## 7. Mandatory Multiple Images Requirement

The website must include at least 12 distinct, relevant photographs across the homepage, services, portfolio, and gallery. Aim for 15–20 usable images when suitable assets are available.

Do not use one image repeatedly across every section.

### Required Photography

Include distinct images for:

1. Commercial offset printing machines.
2. Digital printing equipment.
3. Business cards and stationery.
4. Brochures and catalogues.
5. Magazine and editorial printing.
6. Printed product packaging.
7. Posters and promotional materials.
8. Large-format banners.
9. Bookbinding and print finishing.
10. Paper cutting equipment.
11. Printed marketing materials.
12. Professional print production facilities.
13. Corporate print collateral.
14. Product labels and packaging.
15. Quality inspection and finishing processes.

### Image Presentation

- Use a large banner image in the hero.
- Use unique images in service cards.
- Use different photographs in the portfolio.
- Include at least 12 distinct gallery images.
- Use varied aspect ratios where appropriate.
- Use responsive image sizing and object-fit: cover.
- Add meaningful alt text.
- Provide image fallbacks.
- Avoid watermarked images, unrelated stock images, and broken URLs.
- Do not use the same image for every card.
- Ensure images are relevant to the business.

Use project-hosted image assets wherever possible, especially for the hero banner and essential sections.

Do not introduce any external image SDK or image library.

## 8. Homepage Sections

Create a complete homepage containing the following sections.

### A. Hero Banner

Include the headline, description, printing banner image, and two functional CTA buttons.

### B. Business Introduction

Introduce the printing and reproduction category with professional, concise copy and a supporting photograph.

Do not claim unverified years of experience, production capacity, or company achievements.

### C. Services Overview

Create six service cards:

1. Commercial Printing
2. Digital Printing
3. Brochures and Catalogues
4. Business Cards and Stationery
5. Posters and Large-Format Printing
6. Binding and Print Finishing

Each card should include a unique image, title, description, and View Details action.

These are demo service categories and must be editable.

### D. Featured Portfolio

Display at least six visually appealing sample projects.

Example projects:

- Corporate Brand Stationery
- Premium Product Packaging
- Marketing Brochure Collection
- Promotional Poster Series
- Editorial Catalogue Design
- Large-Format Campaign Prints

Each project needs a unique image, title, category, short description, and View Project action.

Include working category filters and a View All Projects button.

Label sample projects appropriately and allow the admin to replace them with actual client work.

### E. Print Production Showcase

Create an editorial, image-led section showing:

- Pre-press preparation.
- Printing and reproduction.
- Color and quality checks.
- Finishing and binding.

Use multiple photographs with varied layouts rather than identical cards.

### F. Why Choose This Business

Include four editable value propositions:

- Attention to Print Quality.
- Multiple Printing Formats.
- Professional Finishing Options.
- Focus on Project Requirements.

Treat these as proposed marketing content, not independently verified claims.

### G. Gallery Preview

Display at least eight unique photographs in an attractive editorial grid.

Include category filters for Printing Equipment, Printed Materials, Packaging, and Finishing.

Add a View Full Gallery button.

### H. Quote Request CTA

Create a strong CTA section encouraging visitors to submit their printing requirements.

The Request a Quote button must open the quote form.

### I. Testimonials

Include clearly identified sample testimonials for demonstration purposes only.

Do not present invented statements as verified customer reviews.

Make them editable, removable, and hideable from the admin panel.

### J. FAQs

Create a functional accordion containing questions about printing formats, artwork files, print finishing, project requirements, and quote requests.

### K. Contact Section

Show the available phone number: 2451324535.

Do not invent an email address or postal address.

Include a contact form with:

- Full Name
- Phone Number
- Email Address
- Service Required
- Quantity
- Project Description

Validate inputs and show a success message when submitted. Clearly state that the form is simulated and does not send a real email.

### L. Footer

Create a professional multi-column footer containing:

- Business name and description.
- Quick navigation links.
- Service links.
- Phone number: 2451324535.
- Editable social media links.
- Copyright information.
- Admin Login link.

Display this exact developer credit:

**Designed and development by SOSynch Ai Tech**

The Admin Login link must open the admin login page.

## 9. About Page

Create a dedicated About page containing:

- Printing-related banner photograph.
- Business introduction.
- Printing and reproduction overview.
- Service categories.
- Production workflow.
- Quality-focused messaging.
- Multiple supporting images.
- Contact CTA.

All editable content must be manageable from the admin dashboard.

Do not invent a founding year, company history, founder names, employee count, or verified achievements.

## 10. Services Page

Create a dedicated Services page with:

- Unique image for each service.
- Service title.
- Detailed description.
- Features and applications.
- Optional editable specifications.
- Request a Quote button.
- Functional category filters.
- Working search field.
- Service detail views.

The admin must be able to add, edit, delete, reorder, and hide services.

## 11. Portfolio Page

Create a complete portfolio page with at least eight initial sample projects.

Features:

- Multiple unique project images.
- Category filters.
- Search by project title.
- Responsive image grid.
- Project detail views.
- Previous/next navigation where suitable.
- Clearly identified demo projects.

Suggested categories:

- Commercial Printing
- Packaging
- Marketing Materials
- Editorial Printing
- Large-Format Printing
- Business Stationery

The admin must be able to add, edit, delete, reorder, and publish or hide projects.

## 12. Gallery Page

Create a dedicated gallery containing at least 12 distinct relevant images.

Include:

- Category filters.
- Responsive masonry-style or editorial grid using CSS.
- Image lightbox implemented using React and CSS.
- Previous and next image buttons.
- Close button.
- Escape-key support.
- Descriptive captions.
- Keyboard-accessible controls.
- Lazy loading where suitable.

Do not use any external gallery or lightbox library.

Allow the admin to manage image URLs, titles, captions, alt text, categories, and visibility.

## 13. Contact and Quote Request Page

Create a dedicated inquiry page with:

- Business name.
- Phone number: 2451324535.
- Editable address and email fields.
- Contact form.
- Service dropdown.
- Quantity.
- Optional deadline.
- Project requirements.
- Validation and success messages.

Leave unavailable business contact details blank until an admin provides them.

Store submitted demo inquiries in localStorage. Explain that no backend service or real email delivery is connected.

## 14. Admin Login System

Create a functional frontend-only admin login page.

### Demo Credentials

- Username: admin
- Password: PrintAdmin@123

Show a clear notice that these are demo credentials.

Requirements:

- Dedicated login page.
- Username and password fields.
- Show/hide password button.
- Input validation.
- Invalid credentials error message.
- Successful login redirects to /admin/dashboard.
- Protected admin pages.
- Login session stored in sessionStorage.
- Logout functionality.
- Redirect unauthenticated visitors to the login page.
- Maintain the simulated login after a page refresh.
- Do not expose admin credentials on public pages.

This is only demo authentication, not production-grade security. Do not integrate an external authentication service or backend.

## 15. Admin Dashboard Layout

Create a premium responsive admin dashboard with a sidebar, top bar, content area, and overview cards.

### Dashboard Statistics

Calculate the following from the mock data:

- Total Services.
- Total Projects.
- Gallery Images.
- Quote Requests.

Include a recent quote requests section and useful management shortcuts.

### Sidebar Modules

1. Dashboard
2. Hero Section Manager
3. Website Content Manager
4. About Page Manager
5. Services Manager
6. Portfolio Manager
7. Gallery Manager
8. Testimonials Manager
9. FAQs Manager
10. Quote Requests Manager
11. Contact Details Manager
12. Navigation Manager
13. Footer and Social Links Manager
14. Website Settings
15. Logout

Every sidebar item must open a real, functional screen. Do not leave blank pages or non-working placeholder modules.

## 16. Admin Content Management

### A. Hero Section Manager

Allow editing of the hero label, heading, description, CTA labels, CTA destinations, banner image URL, alt text, and visibility.

Show an image preview and live preview where practical.

### B. Website Content Manager

Allow editing of homepage introduction, headings, descriptions, section visibility, CTA text, and section ordering.

### C. Services Manager

Provide add, edit, delete, search, filter, image URL editing, description editing, category management, visibility controls, and ordering.

### D. Portfolio Manager

Provide project creation, editing, deletion, category assignment, image management, descriptions, featured status, publication status, and ordering.

### E. Gallery Manager

Allow the admin to add images through URLs, preview them, edit captions and alt text, assign categories, remove images, and toggle visibility.

Handle invalid image URLs gracefully.

### F. Testimonials Manager

Allow adding, editing, deleting, and hiding testimonials. Clearly label initial sample entries.

### G. FAQs Manager

Allow adding, editing, deleting, reordering, and hiding FAQ entries.

### H. Quote Requests Manager

Show all simulated inquiries submitted from the public website.

Include:

- Search.
- Service filters.
- Submission date.
- Customer details.
- Project requirements.
- Status management: New, In Progress, Completed.
- Delete action.
- Empty states.

Persist requests in localStorage.

### I. Contact Details Manager

Allow editing the business name, phone, email, address, social links, and contact descriptions.

Pre-fill only the provided business name and phone number. Keep unavailable details blank.

### J. Navigation Manager

Allow editing navigation labels, page destinations, visibility, ordering, and CTA labels.

Keep admin access separate from editable public navigation.

### K. Footer Manager

Allow editing footer descriptions, quick links, service links, social URLs, copyright text, and visibility settings.

The required developer credit must remain visible:

Designed and development by SOSynch Ai Tech

### L. Website Settings

Include editable website title, logo text, logo image URL, brand colors, SEO title, meta description, and section visibility.

Provide a Restore Demo Defaults button with a confirmation dialog.

## 17. Data Architecture and Persistence

Use a clean folder structure such as:

src/
- components/
- pages/
- admin/
- data/
- hooks/
- utils/
- App.jsx
- main.jsx
- index.css

public/
- images/
- favicon.svg

Create centralized JavaScript data files for services, projects, gallery images, testimonials, FAQs, website settings, navigation, contact details, and quote requests.

Implement reusable localStorage utilities using native JavaScript.

Requirements:

- Load initial mock data when no saved data exists.
- Persist all relevant admin changes.
- Update public pages when content changes.
- Validate input before saving.
- Handle malformed stored data safely.
- Use stable unique IDs.
- Avoid inconsistent copies of the same state.
- Include a confirmed reset-to-defaults action.

No database, API, server, or third-party persistence service.

## 18. CRITICAL: Image Paths Must Work After Vercel Deployment

**This requirement is mandatory. Do not consider the project complete if images work in the Lovable preview but fail on Vercel.**

### A. Store Important Images in the Project

- Keep critical website images inside `public/images/`.
- Use real image files committed to the Git repository.
- Include the hero banner and essential service, portfolio, and gallery images in the project assets wherever possible.
- Use root-relative asset paths, for example:
  - `/images/printing-hero.jpg`
  - `/images/offset-printing.jpg`
  - `/images/digital-printing.jpg`
  - `/images/packaging-print.jpg`
  - `/images/brochure-printing.jpg`
- Confirm that every referenced file actually exists.
- Do not reference images stored only on a local computer.
- Do not use paths such as `C:\Users\...`, `file:///...`, or temporary development URLs.
- Do not use `/src/assets/...` as a public URL. For images stored inside `src/assets`, import them correctly into React components.
- Do not rely on Lovable preview URLs, temporary image-generation URLs, expiring links, or local development server paths.
- Avoid spaces and special characters in filenames.
- Ensure filenames match their actual case, including uppercase and lowercase letters. Vercel production is case-sensitive.
- Ensure image assets are included in Git and are not excluded by `.gitignore`.

### B. Image URLs and Remote Images

If remote image URLs are used:

- Ensure the URL is publicly accessible.
- Use a stable HTTPS URL.
- Verify that the image returns actual image content and not an HTML page.
- Avoid URLs that require authentication, cookies, or temporary signed access.
- Do not assume a remote image works simply because it appears in the editor preview.
- Prefer local project assets for the hero and essential images.
- Do not add an image SDK or external image-processing library.

### C. Image Error Handling

Implement a reusable image component using native React functionality.

It must:

- Display the intended image.
- Use `onError` to handle loading failures.
- Switch to a valid local fallback image or an attractive styled fallback.
- Prevent infinite fallback loops.
- Preserve image dimensions and layout.
- Provide meaningful alt text.
- Avoid showing broken image icons.
- Avoid hiding the entire section if an image fails.

If the admin enters a new image URL, show a preview and validate whether the image loads before saving where practical.

### D. Vite and Asset Configuration

- Use Vite's standard asset handling.
- Use correct paths for files in the `public` directory.
- If assets are imported from `src/assets`, import them in the React component rather than constructing a public path.
- Do not hardcode `localhost`, `127.0.0.1`, or development-only asset URLs.
- Keep the deployment configuration compatible with a normal Vite project deployed to Vercel.
- Configure SPA fallback/rewrite behavior if required so that direct navigation and refreshes on application routes work.
- Do not add a base path that breaks root-relative image URLs on Vercel.

### E. Verify Every Image Category

Before completing the project, inspect the following:

1. Hero banner image.
2. About page images.
3. All service card images.
4. All portfolio project images.
5. Gallery images.
6. Production showcase images.
7. Admin image previews.
8. Fallback behavior when an image URL is invalid.

Ensure all local image files exist and all remote images are valid and accessible.

### F. GitHub and Vercel Deployment Compatibility

The project must work when:

1. Run locally with Vite.
2. Built using `npm run build`.
3. Cloned from the GitHub repository.
4. Deployed to Vercel.
5. Opened directly using the production URL.
6. Refreshed on a nested page.
7. Opened on desktop and mobile.

Use the correct production build settings for Vite.

- Build command: `npm run build`
- Output directory: `dist`

Resolve all build errors before considering the project finished.

Do not claim the production deployment has been tested unless the actual deployed website has been inspected.

**Final image rule: No broken images, no missing local assets, no temporary preview links, and no images that work only in the local environment.**

## 19. Responsive Design

Ensure the complete website and admin dashboard work on:

- 360px mobile.
- 390px mobile.
- 768px tablet.
- 1024px laptop.
- 1440px desktop.
- Large desktop screens.

Requirements:

- No horizontal overflow.
- Mobile navigation works correctly.
- Responsive image layouts.
- Properly stacked hero content on mobile.
- Readable typography.
- Comfortable form controls.
- Responsive admin sidebar.
- Tables scroll or adapt on small screens.
- Modal dialogs fit within the viewport.
- Buttons have suitable touch targets.

## 20. Accessibility and User Experience

Implement:

- Semantic HTML.
- Accessible labels.
- Keyboard-accessible navigation.
- Visible focus states.
- Descriptive alt text.
- Sufficient color contrast.
- Accessible modals and lightbox.
- Useful validation messages.
- Loading, error, and empty states.
- Confirmation before destructive actions.
- Consistent button and link behavior.

Use native CSS transitions and avoid animation libraries.

## 21. SEO and Performance

Implement basic SEO for public pages:

- Meaningful page titles.
- Meta descriptions.
- Proper heading hierarchy.
- Descriptive image alt attributes.
- Correct route and refresh handling.
- Lazy loading for below-the-fold images.
- Suitable image dimensions.
- Lightweight components.
- No unnecessary dependencies.

Do not lazy-load the primary hero image if doing so harms initial visual loading.

## 22. Final Functional Acceptance Checklist

Before completing the project, verify all of the following:

- [ ] Homepage loads correctly.
- [ ] Premium navy, teal, gold, and off-white palette is consistent.
- [ ] Hero contains a relevant printing banner image.
- [ ] At least 12 distinct relevant images are included.
- [ ] No repeated image is used unnecessarily.
- [ ] Navigation links open the correct pages or sections.
- [ ] All CTA buttons work.
- [ ] Service filters and search work.
- [ ] Portfolio filters and project detail views work.
- [ ] Gallery filters and lightbox work.
- [ ] Contact and quote forms validate.
- [ ] Demo quote requests are saved in localStorage.
- [ ] Admin login works with the supplied demo credentials.
- [ ] Admin routes are protected within the demo.
- [ ] All sidebar modules open functional screens.
- [ ] CRUD operations work for manageable content.
- [ ] Admin edits update public pages.
- [ ] Changes persist after refresh.
- [ ] Restore defaults works with confirmation.
- [ ] Footer contains the Admin Login link.
- [ ] Footer displays the exact developer credit.
- [ ] All images use valid, deployable paths.
- [ ] Image fallback works for invalid URLs.
- [ ] All important image files are included in Git.
- [ ] `npm run build` completes successfully.
- [ ] The website supports Vercel production deployment.
- [ ] Direct page refreshes work on deployed routes.
- [ ] No broken images, dead links, or unfinished modules remain.
- [ ] No database, backend, or additional UI libraries have been introduced.

## Final Instructions

Build the entire website and admin dashboard, not merely a landing-page mockup.

Prioritize a premium real-world design, professional printing photography, varied image layouts, complete content management, working navigation, reliable image loading, and production-compatible asset paths.

Use React + Vite + Tailwind CSS only. Use mock data only. Do not use any database, backend, or additional libraries.

Do not leave any major section or admin module as a non-functional placeholder.

The website must be designed to work locally, in the Lovable preview, and after being cloned to GitHub and deployed to Vercel.

The footer must include this exact credit:

**Designed and development by SOSynch Ai Tech**

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/38635a88-2fe8-4871-8792-16839210a4ba).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
