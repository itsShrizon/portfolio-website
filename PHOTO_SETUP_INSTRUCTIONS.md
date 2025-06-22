# How to Add Your Photo to the Portfolio

## Step 1: Convert HEIC to JPG/PNG

Your image `IMG_0388.HEIC` needs to be converted to a web-compatible format. Here are several ways to do this:

### Option A: Using Windows Photos App
1. Right-click on `IMG_0388.HEIC`
2. Choose "Open with" → "Photos"
3. Click the "..." menu in the top right
4. Choose "Save as" → "JPEG"
5. Save as `tanzir-profile.jpg`

### Option B: Using Online Converter
1. Go to https://convertio.co/heic-jpg/
2. Upload your `IMG_0388.HEIC` file
3. Download the converted JPG file
4. Rename it to `tanzir-profile.jpg`

### Option C: Using Paint
1. Open `IMG_0388.HEIC` in Windows Photos
2. Click "Edit" → "Save a copy"
3. Open the copy in Paint
4. File → Save As → JPEG
5. Name it `tanzir-profile.jpg`

## Step 2: Add Photo to Portfolio

1. Copy the converted `tanzir-profile.jpg` file
2. Paste it into: `Portfolio Website/assets/images/`
3. Make sure the filename is exactly: `tanzir-profile.jpg`

## Step 3: Commit and Deploy

After adding the photo:

```bash
git add assets/images/tanzir-profile.jpg
git add index.html styles/main.css
git commit -m "Add profile photo to portfolio"
git push origin main
```

## Expected Result

Your portfolio will show:
- Your actual photo in a circular frame
- Golden border around the image
- Professional appearance in the hero section
- Photo will be responsive and look great on all devices

## Troubleshooting

If the photo doesn't appear:
1. Check the filename is exactly `tanzir-profile.jpg`
2. Check it's in the correct folder: `assets/images/`
3. Try clearing browser cache (Ctrl+F5)
4. Check browser console for errors (F12)

The photo styling is already configured with:
- 250px diameter circular frame
- Golden border
- Proper centering and responsive design
- Shadow effects for professional look
