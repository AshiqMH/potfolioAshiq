# Assets Folder

This folder contains all the media and document files for your portfolio website.

## 📁 Structure

```
assets/
├── images/          # Project screenshots, profile photos, logos
└── documents/       # Resume, certificates, project documents
```

## 📸 Images Folder

Add your project screenshots and images here:
- Profile photo (recommended: 400x400px)
- Project screenshots (recommended: 800x600px)
- Logo files (PNG/SVG format)
- Background images

## 📄 Documents Folder

Store important documents:
- Resume/CV (PDF format)
- Certificates
- Project documentation
- Portfolio PDF version

## 🔗 Usage in HTML

To use images in your portfolio, reference them like this:
```html
<img src="assets/images/your-image.jpg" alt="Description">
```

To link to documents:
```html
<a href="assets/documents/resume.pdf" target="_blank">Download Resume</a>
```

## 📏 Recommended Image Sizes

- **Profile Photo**: 400x400px
- **Project Screenshots**: 800x600px
- **Hero Background**: 1920x1080px
- **Logo**: 200x200px

## 🎨 Image Optimization

Before adding images:
1. Compress them using tools like TinyPNG
2. Use appropriate formats (JPEG for photos, PNG for graphics)
3. Consider using WebP format for better performance
4. Keep file sizes under 500KB for web optimization

---

**Note**: This folder is included in version control. For large files, consider using Git LFS or hosting images on a CDN. 