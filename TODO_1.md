# TODO List for Aetherlabs Customization

This file outlines the planned customizations based on Step 2 from the initial analysis. These are high-level tasks to personalize the website template beyond the basic name change from "Ochi" to "Aetherlabs". Prioritize as needed, and we can address them sequentially.

## 1. Update Visual Assets (Logo, Favicon, Images)
- Replace `aetherlabs_dev/public/logo.svg` with the actual Aetherlabs logo (referenced in footer and possibly other places).
- Update `aetherlabs_dev/public/favicon.ico` for the browser tab icon.
- Review and replace placeholder images in `public/` such as `banner.png`, `perfection.jpg`, `eyes.png`, etc., with Aetherlabs-specific content (e.g., hero banners, project images, testimonials).
- Update assets in subfolders like `public/projects/`, `public/reviewers/`, and `public/socials/` for projects, reviews, and social icons.

## 2. Personalize Content and Copy
- Revise descriptions: Update the brief in `src/components/websiteBrief/Brief.jsx` to describe Aetherlabs' focus (e.g., AI, innovation, or specific services). The marquee text ("we are aetherlabs") is already updated but can be refined.
- Social links: Replace generic placeholders in `src/components/footer/Footer.jsx` and `src/components/websiteBrief/Brief.jsx` (e.g., Instagram, Behance) with real Aetherlabs social media URLs.
- Contact info: In `src/components/footer/Footer.jsx`, update the email (`wespy07@gmail.com`), addresses (currently Vancouver and Lviv placeholders), and add phone numbers if relevant to reflect actual Aetherlabs details.

## 3. Update Project Showcases and Sections
- Explore and modify components in `src/components/Projects/` for case studies or work samples—update images, text, and links with Aetherlabs' real projects.
- Personalize testimonials in `src/components/reviews/` with actual reviewer quotes and feedback.
- Customize the hero section in `src/components/hero section/`—update intro text, buttons, or animations to align with Aetherlabs' brand.
- Check other sections like `preloader/`, `readySet/`, `eyes/`, etc., for any hardcoded text or images that need changes.

## 4. Technical and Deployment Tweaks
- Add SEO/meta tags in `index.html` (e.g., Open Graph, Twitter cards) tailored to Aetherlabs for better search visibility.
- Update the deployment URL in `README.md` to the actual hosted site (e.g., `https://aetherlabs.com`).
- Ensure custom fonts (e.g., "font-neue") are properly loaded; add or replace if Aetherlabs has specific typography.
- Improve accessibility and performance: Run `npm run lint`, optimize images, and test for issues.

## 5. Advanced Features (If Needed)
- Add new sections like a team page, blog, or contact form using the existing React routing.
- Integrate external APIs for features like email capture (e.g., Mailchimp) or analytics (e.g., Google Analytics).
- Test responsiveness on various devices and adjust Tailwind CSS classes as necessary.
- Customize animations (using Framer Motion and GSAP) for timings or new effects that match Aetherlabs' style.

Track progress by checking off items as they're completed. If additional details (e.g., specific URLs or assets) are provided, these can be refined further.