# 🖼️ MyGallery

A clean, responsive photo gallery website built with pure HTML and CSS. Features a masonry-style layout across two pages.

## Live Demo

🌐 [gallery-navy-eight.vercel.app](https://gallery-navy-eight.vercel.app)

---

## Deployment

This is a static site — no build step needed. It's currently deployed on **Vercel**.

To deploy your own copy:

1. Push to a GitHub repo
2. Import the repo on [vercel.com](https://vercel.com)
3. Leave all build settings blank and click **Deploy**

Make sure your entry file is named `index.html` so the root URL loads correctly.

### ⚠️ Image path note

Image `src` attributes must use **relative paths** and **lowercase extensions** to work on case-sensitive servers (Linux/Vercel):

```html
<!-- ✅ Correct -->
<img src="image/image1.jpg">

<!-- ❌ Wrong — breaks on Vercel -->
<img src="/image/image1.JPG">
```
