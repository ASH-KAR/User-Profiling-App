# Image Extraction Guide

This guide will help you extract images from the PDF documentation and add them to the GitHub repository.

## 📸 Images Needed for README

Based on the updated README.md, you need to extract the following images from `User Profiling App Documentation.pdf`:

### Required Images:
1. **app-overview.png** - Overall app screenshot or diagram
2. **architecture-diagram.png** - System architecture diagram
3. **features-overview.png** - Features showcase
4. **system-architecture.png** - Detailed system architecture
5. **power-apps-interface.png** - Power Apps UI screenshots
6. **power-automate-flows.png** - Workflow diagrams
7. **power-bi-dashboard.png** - Dashboard screenshots
8. **data-structure.png** - Data model diagram
9. **user-interface.png** - End-user interface
10. **admin-dashboard.png** - Admin interface
11. **analytics-overview.png** - Analytics overview
12. **reports-sample.png** - Sample reports

## 🛠️ How to Extract Images from PDF

### Method 1: Using Adobe Acrobat Reader (Recommended)
1. Open `User Profiling App Documentation.pdf` in Adobe Acrobat Reader
2. Right-click on any image → "Copy Image"
3. Open Paint or any image editor → Paste
4. Save as PNG with the appropriate name
5. Save to the `images/` folder

### Method 2: Using Online PDF to Image Converter
1. Go to a PDF to image converter (like smallpdf.com, ilovepdf.com)
2. Upload the PDF file
3. Convert to PNG/JPG
4. Download individual pages as images
5. Crop and rename as needed

### Method 3: Using Windows Snipping Tool
1. Open the PDF file
2. Use Windows Snipping Tool (Windows + Shift + S)
3. Select the area with the image/diagram
4. Save as PNG with appropriate name

## 📁 File Organization

Save all images in the `images/` folder with these exact names:
```
images/
├── app-overview.png
├── architecture-diagram.png
├── features-overview.png
├── system-architecture.png
├── power-apps-interface.png
├── power-automate-flows.png
├── power-bi-dashboard.png
├── data-structure.png
├── user-interface.png
├── admin-dashboard.png
├── analytics-overview.png
└── reports-sample.png
```

## 📝 Image Guidelines

- **Format**: PNG preferred (supports transparency)
- **Size**: Keep under 1MB each for faster loading
- **Resolution**: 800-1200px width recommended
- **Quality**: Clear and readable text in screenshots

## 🚀 After Extracting Images

1. Save all images to the `images/` folder
2. Commit and push to GitHub:
   ```
   git add images/
   git commit -m "Add documentation images and screenshots"
   git push
   ```

3. The README.md will automatically display the images once uploaded to GitHub

## 🔧 Optional: Image Optimization

To reduce file sizes:
- Use online tools like TinyPNG.com
- Or use PowerShell: `Compress-Archive` for batch processing

## ✅ Verification

After uploading to GitHub:
1. Check that all images display correctly in the README
2. Verify image links are working
3. Ensure images are properly sized and clear

---

**Note**: If you can't extract certain images, you can create placeholder images or skip them initially and add them later.
