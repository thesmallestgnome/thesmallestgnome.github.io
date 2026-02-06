# Portfolio Timeline Images

## Image Specifications

All timeline images follow these specifications:
- **Aspect Ratio**: 16:9 (landscape)
- **Recommended Dimensions**: 1200x675 pixels
- **Format**: JPEG, WebP, or AVIF
- **Target File Size**: < 200kb each (optimized/compressed)
- **Naming Convention**: descriptive-kebab-case-16x9.jpg

## Required Images (9 total)

1. **hero-intro-16x9.jpg** - Hero image showing Knee Monitor sensors and mobile app
2. **step0-challenge-16x9.jpg** - Split-screen: athlete with sensors → medical setting
3. **step1-research-16x9.jpg** - Research pivot flowchart (surgeon → physiotherapist)
4. **step2-persona-16x9.jpg** - Dual persona illustration (PT ↔ Patient relationship)
5. **step3-wireframes-16x9.jpg** - Wireframes and design evolution sketches
6. **step4-prototype-16x9.jpg** - B&W prototype screens, design system components
7. **step5-branding-16x9.jpg** - Brand transformation (B&W → color)
8. **step6-solution-16x9.jpg** - Sticker solution diagram (correct vs incorrect placement)
9. **step7-reflection-16x9.jpg** - Product in use, metrics dashboard

## How to Add/Replace Images

### Simple Workflow
1. Place your optimized image file in this directory (`public/images/`)
2. Ensure filename matches exactly (case-sensitive)
3. Reload the browser - image displays automatically
4. **No code changes needed!**

### Image Optimization Tips

**Before adding images:**
- Resize to 1200x675 or 1600x900 (maintain 16:9 ratio)
- Compress using:
  - [TinyPNG](https://tinypng.com/) - Smart compression
  - [Squoosh](https://squoosh.app/) - Advanced control
  - [ImageOptim](https://imageoptim.com/) - Mac app
- Target: 100-200kb per image

**Format Recommendations:**
- **JPEG**: Universal support, good for photos
- **WebP**: 25-30% smaller than JPEG (modern browsers)
- **AVIF**: 50% smaller than JPEG (2026 standard)

### Current State

Images currently use placeholder URLs (via.placeholder.com) for development. Replace with production assets by adding image files to this directory with the filenames listed above.

## Testing

After adding images:
1. Clear browser cache
2. Open DevTools → Network tab
3. Scroll through page - images should load lazily (on demand)
4. Verify no layout shift occurs when images appear

## Troubleshooting

**Image not displaying:**
- Check filename matches exactly (case-sensitive)
- Verify file is in `public/images/` directory
- Clear browser cache and hard reload (Cmd+Shift+R / Ctrl+Shift+F5)

**Image looks pixelated:**
- Increase source resolution (1600x900 or higher)
- Ensure image quality setting during export (JPEG quality 80-90%)

**Large file size:**
- Use compression tools (see optimization tips above)
- Convert to WebP or AVIF format
- Reduce dimensions if higher than 1600x900

---
*Last updated: 2026-02-06 (Phase 3)*
