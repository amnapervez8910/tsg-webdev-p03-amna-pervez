# Amna's Journal — learning starter

A three-page example to study and adapt while building your own internship project. The supplied brief allows AI for learning, research and ideation and requires original work and authorship verification. Do not present this unchanged as your own work; check the program's AI policy and build, personalize and understand your own version.

## Pages

- `index.html` — home and introduction
- `blog.html` — four example post cards
- `contact.html` — contact details and demonstration form
- `css/style.css` — shared styling for every page
- `images/` — four images generated using Notion AI for this learning example. Check your program’s rules before submitting AI-generated assets.
- `screenshots/` — local demonstration screenshots; capture fresh ones after making your own changes and deploying.

## Preview locally

Extract the ZIP, open the folder in VS Code, and open `index.html` in a browser. Click the navigation to visit the other two pages. No installation is required.

## Important: make it yours

1. Write your own introduction and four genuinely original post titles, dates and previews.
2. Check the internship’s AI rules before using AI-generated images; if needed, replace them with your own or properly licensed images and credit their sources here.
3. The contact page includes the email and GitHub profile supplied for publication. The form opens the visitor’s email app with a prepared message; the visitor must press Send in their email app. It does not send or store messages on the website. This requires an email app configured on the visitor’s device.
4. Study the code and customize the visual design yourself, especially the copy and colours. You may be asked to explain it during the review call.
5. Capture desktop and mobile screenshots of all three pages after your changes. Record your own 45–60 second screen recording navigating the live site.
6. Create your own public GitHub repository, deploy to Netlify/Vercel, test the public URL on your phone, and add real links here. No repository or deployment is included.
7. Put the required deliverables in a viewable Google Drive folder, test the link privately and submit through the official form with your batch ID. Do not publish the private project brief.

## How this example works

- Every HTML file links to the **same** `css/style.css`. Edit that file to change shared colours, typography and layout.
- The header and footer are copied consistently between pages. Each page marks its own navigation link with `aria-current="page"`.
- `href` links point to files in the same folder. Images are in `images/`, referenced by relative paths.
- CSS Grid creates the main two-column layouts; a media query switches them to one column on smaller screens. The viewport tag helps mobile browsers scale correctly.
- Form fields have labels and built-in HTML validation. A short JavaScript submit handler builds a `mailto:` link from the fields and opens the visitor’s email app; the visitor sends the email there. Without JavaScript, the form falls back to a basic mailto action. Neither method sends mail directly from the website.

## Verification checklist

- [ ] All three links and the active page indicator work on each page.
- [ ] No horizontal scrolling on mobile; labels and buttons are usable.
- [ ] All images have descriptive alt text, appropriate permissions and source credit.
- [ ] Contact details and form behavior are accurate; no placeholder links.
- [ ] GitHub and live links are public and tested; six current screenshots and a recording are included.
- [ ] You understand and can explain every part, and comply with the internship's authorship and AI rules.

## Example screenshots

| Page | Desktop | Mobile |
| --- | --- | --- |
| Home | [View](screenshots/index-desktop.png) | [View](screenshots/index-mobile.png) |
| Blog | [View](screenshots/blog-desktop.png) | [View](screenshots/blog-mobile.png) |
| Contact | [View](screenshots/contact-desktop.png) | [View](screenshots/contact-mobile.png) |

## Publishing steps (after confirming the project complies with the program rules)

1. On GitHub, sign in to your account and create a new public repository, e.g. `tsg-webdev-p03-amna-pervez`.
2. Upload the contents of this folder (not the parent folder), including `index.html`, `blog.html`, `contact.html`, `css`, `images`, `screenshots` and `README.md`.
3. In repository Settings → Pages, choose Deploy from a branch, select the default branch and `/ (root)`, and save. Wait for GitHub Pages to give you a live URL; visit it and test navigation and mobile layout. Alternatively deploy the folder through Netlify or Vercel.
4. Add the actual repository and live site links to this README. Capture screenshots of the final deployed pages and make your own 45–60 second screen recording.
5. Upload required deliverables to a Google Drive folder set to Anyone with the link can view, test the link in a private window and submit it using the official form and your batch ID.

Repository URL: not yet created.
Live URL: not yet deployed.

## Image credits

All four example images were generated with Notion AI for this example. Their use in the internship project is subject to the program's AI and asset rules; obtain confirmation if needed. No third-party fonts or icons are used.

## Walkthrough video

`tsg-webdev-p03-amna-pervez-walkthrough.mp4` is an approximately 51-second automated recording of the local example, without narration. It is not a recording of a live deployment. After making your own final changes and publishing, record a fresh walkthrough of your final site if required by your program.
