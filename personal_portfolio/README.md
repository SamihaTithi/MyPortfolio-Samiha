# Personal Portfolio Website

A responsive, dark-modern personal portfolio built with HTML, CSS, and vanilla JavaScript.

## Files
- `index.html` — page content and sections
- `style.css` — responsive dark theme and visual styling
- `script.js` — mobile navigation, scroll reveal, active navigation
- `assets/` — add your profile photo and CV here

## Run locally
1. Extract the ZIP file.
2. Open the `personal_portfolio` folder in VS Code.
3. Open `index.html` in your browser, or use the VS Code Live Server extension.

## Personalize before publishing
Personal details already added:
- Name: Samiha Hossain Tithi (initials: ST)
- Degree: BSc in Computer Science and Engineering, United International University
- Expected graduation: 2027
- GitHub: https://github.com/SamihaTithi
- LinkedIn: https://www.linkedin.com/in/samiha-hossain-tithi-27a65b427/
- Email: samihahossaintithi@gmail.com

Still personalize before publishing:
- Confirm the wording of your bio and skills.
- Add your professional photo and latest CV.
- `assets/profile.jpg` — add your own professional photo (update the profile placeholder in `index.html` to use it).
- `assets/cv.pdf` — add your latest CV.
- `href="#"` — replace placeholder project links with real repository/demo links, or remove them.
- Education details — confirm your exact degree, department, and expected graduation date.
- Skills — keep only technologies you can confidently discuss.

## Add a profile photo
In `index.html`, replace the `.profile-placeholder` block inside `.profile-frame` with:
```html
<img class="profile-photo" src="assets/profile.jpg" alt="Your Name">
```
Then add this CSS rule to `style.css`:
```css
.profile-photo {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: inherit;
}
```

## Publish
You can publish this static site using GitHub Pages, Netlify, or Vercel. No build step is required.
