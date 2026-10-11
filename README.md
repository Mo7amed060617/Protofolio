# Mohamed Ahmed — Portfolio Website

## How to use
Open `index.html` in any browser. Everything is in one file — no build step, no dependencies.

## How to add your work
Open `index.html` in any text editor and find the `EDIT YOUR CONTENT HERE` section
near the bottom (inside the `<script>` tag). Everything is data-driven:

### Add design projects
In the `PROJECTS` list, set `image` to your file path, e.g. `image:'work/ad-01.jpg'`.
For multiple images in the project view, use `images:['work/ad-01.jpg','work/ad-01b.jpg']`.
For a project video, set `video:'videos/ad-01.mp4'`.
Set `featured:true` to show it in the big Featured section (up to 6).
To go beyond 12 projects, copy any entry block and change its values.

### Add videos
In the `VIDEOS` list, set `src:'videos/my-ad.mp4'` and optionally `thumb:'videos/thumb.jpg'`.
NOTE: The Videos section is hidden from the website while the list is empty.
Add one video and the whole section (plus its menu link) appears automatically.

### Certificates — auto-hide
The Certificates section also hides itself while `CERTIFICATES` has no names filled in.
Fill the empty slot (name/org/date/desc/image) and it shows up automatically.

### Add certificates
In the `CERTIFICATES` list, set `name`, `org`, `date`, `desc` and `image`.

### Update social & contact
Edit the `SOCIALS` list (replace the placeholder URLs) and the `CONTACT` email/WhatsApp.

### Add your portrait & about photo
Search the file for `Replace the placeholder below with your photo` and
`Replace with your workspace/about photo` and swap in `<img src="...">` lines.

### Adjust skills
Edit the `SKILLS` list — name and level (0–100).

## Notes
- Placeholder designs are clearly labeled "Replace with your design" and disappear
  automatically once you set a real image path.
- All images/videos can be local files or full URLs.
- Responsive for desktop, tablet and mobile. Works offline except Google Fonts.
