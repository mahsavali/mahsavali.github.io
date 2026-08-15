# Personal Website

A lightweight personal/academic website designed for GitHub Pages.

## Customize

Edit `index.html` and replace:
- `Your Name`
- bio and role
- education
- publications
- projects
- email
- GitHub / LinkedIn / Google Scholar links

Put your CV at `assets/cv.pdf`.

To use a real profile photo, replace the `<div class="avatar">YN</div>` element with:

```html
<img class="avatar photo" src="assets/profile.jpg" alt="Your Name">
```

Then add your image as `assets/profile.jpg` and add this CSS to `assets/styles.css`:

```css
.avatar.photo { object-fit: cover; }
```

## Publish with GitHub Pages

1. Create a GitHub repository named `YOUR_USERNAME.github.io`.
2. Upload all files in this folder to the repository root.
3. Commit and push.
4. In GitHub, open **Settings → Pages** and choose **Deploy from a branch**, then select `main` and `/ (root)`.
5. Your site will be available at `https://YOUR_USERNAME.github.io/`.
