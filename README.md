# Minimal One-Page Academic Website (turbo-engine)

A very simple, scrollable, single-page personal website template designed for linguists and researchers.

This template includes:

- Profile photo
- Social media buttons
- Email button
- About / Research / Teaching / CV / Contact sections
- Fully responsive layout
- No frameworks, no build tools, no Jekyll required

Just plain HTML + CSS.

---

## File Structure
```text
your-repo/
│
├── index.html
├── style.css
└── assets/
    ├── photo.jpg
    └── cv.pdf (optional)
```

---

## How to Deploy on GitHub Pages

1. Push these files to your GitHub repository.
2. Go to **Repository → Settings → Pages**
3. Under **Build and Deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
4. Click **Save**

Your site will appear at:
https://YOUR-USERNAME.github.io/YOUR-REPO/

If your repository is named:
YOUR-USERNAME.github.io

Then your site will be available at:
https://YOUR-USERNAME.github.io/

---

## Customization Checklist

Here’s everything you’ll likely want to change:

### Basic Identity

- [ ] Replace `"Your Name"` in `index.html`
- [ ] Update the `<title>` tag
- [ ] Edit the tagline in the hero section
- [ ] Update the meta description

---

### Profile Photo

- [ ] Replace `assets/photo.jpg` with your own photo  
- [ ] Keep the filename the same **or** update it in `index.html`
- [ ] Recommended: keep the image under ~500KB

---

### Social Buttons

In `index.html`, update the links for:

- [ ] Google Scholar  
- [ ] GitHub  
- [ ] Twitter/X or Bluesky  
- [ ] LinkedIn  
- [ ] Any other platform you use  

To remove a button, delete its `<a class="btn">...</a>` line.

---

### Email Button

Replace:
mailto:you@university.edu
with your real email address.

Optional: Customize the subject line:
mailto:you@university.edu?subject=Hello%20from%20your%20website


---

### Research Section

For each project:

- [ ] Replace the title  
- [ ] Add a short description (1–2 sentences)  
- [ ] Add links (PDF / Slides / Code / Preprint)  
- [ ] Remove unused links  

To add more projects:  
Copy one `.item` block in `index.html` and edit it.

---

### Teaching Section

- [ ] Replace course names  
- [ ] Add term and institution  
- [ ] Add or remove list items as needed  

---

### CV Section

- [ ] Upload `assets/cv.pdf`
- [ ] Make sure the filename matches the link in `index.html`
- [ ] Or remove the entire section if you prefer not to host your CV

---

### Contact Section

- [ ] Update email  
- [ ] Add affiliation if desired  
- [ ] Add or remove booking link (Calendly, Cal.com, etc.)

---

## Optional Styling Tweaks

Open `style.css` and adjust the color variables at the top:
–accent
–bg
–card
–text
–muted

You can quickly change the accent color by modifying:
–accent: #7aa2ff;

---

## Removing Sections

If you do not need a section:

1. Delete the entire `<section>...</section>` block from `index.html`
2. Remove the corresponding link from the navigation bar

---

## Adding a New Section

Copy this into `index.html`:

```html
<section id="newsection" class="card">
  <h2>New Section</h2>
  <p>Your content here.</p>
</section>

Then add a matching link in the top navigation:
<a href="#newsection">new section</a>