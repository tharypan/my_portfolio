# How to Add Your Profile Picture

## 📸 Quick Steps:

### Method 1: Use Your Own Photo
1. **Take or choose a profile photo**
   - Use a smartphone or camera
   - Good lighting, clean background
   - Face should be clearly visible

2. **Prepare the image**
   - Crop it to a square format (1:1 ratio)
   - Resize to at least 300x300 pixels
   - Save as JPG or PNG format

3. **Add to your website**
   - Save the image as `profile.jpg` in your `d:\AboutMe\images\` folder
   - The website will automatically use it!

### Method 2: Current Setup (Fallback System)
- If `images/profile.jpg` exists → shows your photo
- If `images/profile.jpg` is missing → shows "PT" initials
- This ensures your website always looks professional

## 📁 File Structure Should Look Like:
```
d:\AboutMe\
├── index.html
├── styles.css
├── script.js
├── README.md
├── image-instructions.md
└── images/
    └── profile.jpg  ← Add your photo here
```

## 🎯 Image Requirements:
- **Format**: JPG, PNG, or WebP
- **Size**: Minimum 300x300 pixels (square)
- **File name**: Exactly `profile.jpg` (lowercase)
- **Location**: Must be in the `images/` folder
- **Quality**: High resolution for crisp appearance

## 🛠️ Tools for Image Editing:
- **Windows**: Paint, Photos app
- **Online**: Canva, Photopea, GIMP
- **Mobile**: Built-in photo editors

## ✅ Testing:
1. Add your `profile.jpg` file to the `images/` folder
2. Open `index.html` in a browser
3. Your photo should appear in a circle
4. If something goes wrong, it will show "PT" initials

**Note**: Your profile picture is located at `images/profile.jpg` - make sure it's in the `images/` folder, not the main folder!

That's it! Your portfolio will have a professional profile picture. 🎉
