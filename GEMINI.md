# Project Overview: Professional ATS-Friendly Static Resume

This project is a modern, responsive, and ATS-friendly static resume template built using standard web technologies. It features a professional two-column layout designed to be visually appealing to human recruiters while maintaining a clean structure for Applicant Tracking Systems.

## Main Technologies
- **HTML5:** Semantic structure for content.
- **CSS3:** Custom styling using CSS Variables and Grid layout.
- **Google Fonts:** Utilizes 'Roboto' for a clean, professional look.
- **Font Awesome:** Iconography for contact info and section headers.

## Architecture
- `index.html`: The main entry point containing the resume content and structure.
- `styles.css`: Contains all styling logic, including layout, theme variables, and responsive design.

## Usage and Development

### Customizing Content
To update the resume with your personal information, modify the text within the following sections in `index.html`:
- **Profile:** Name and professional title.
- **Contact Info:** Email, phone, location, and social links.
- **Technical Skills:** Categorized lists of your expertise.
- **Certifications:** Professional credentials.
- **Professional Summary:** A brief overview of your career.
- **Professional Experience:** Your work history with bulleted achievements.
- **Education:** Academic background.

### Styling
Global styles are managed via CSS variables in `:root`:
- `--primary-color`: Used for main headings and borders.
- `--secondary-color`: Used for accents and icons.
- `--dark-bg`: Background color for the left panel.

### Responsive Design
The resume uses a CSS Grid layout that collapses into a single column on screens smaller than `968px`.

### Printing
The CSS includes a `@media print` block to ensure the two-column layout and colors are preserved when saving as a PDF or printing. For best results, ensure "Background Graphics" is enabled in your print settings.

## Future Enhancements
- [ ] Add a "Languages" section.
- [ ] Add a "Projects" section in the main content area.
- [ ] Integrate with a static site generator for easier content management.
