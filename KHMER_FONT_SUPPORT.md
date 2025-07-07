# Khmer Font Support Enhancement

## What was added:

### 1. Google Fonts Integration
- Added Battambang and Kantumruy Pro Khmer fonts from Google Fonts
- Updated the Google Fonts link in index.html to include these fonts

### 2. Font Options
- Added "Battambang (Khmer)" option to the handwriting font dropdown
- Added "Kantumruy Pro (Khmer)" option to the handwriting font dropdown
- Added "Khmer_Font" option for local font support

### 3. CSS Font-Face
- Added @font-face declaration for Khmer_Font to support local Khmer fonts
- Created placeholder for Khmer_Font.ttf file

### 4. Sample Content
- Updated default text content to include Khmer sample text
- Added samples for multiple languages (Khmer, Hindi, Chinese)

### 5. Documentation
- Updated README.md to highlight multi-language support
- Added language support section

## How to use:

1. **For online Khmer fonts**: Select "Battambang (Khmer)" or "Kantumruy Pro (Khmer)" from the font dropdown
2. **For local Khmer fonts**: Replace the placeholder Khmer_Font.ttf with an actual Khmer font file, or use the "Upload your handwriting font" feature
3. **Type or paste Khmer text** in the input area
4. **Generate the handwriting image** as usual

## Testing:

- Server is running at http://localhost:5000
- The font dropdown now includes Khmer options
- Sample Khmer text is included in the default content
- All existing functionality remains intact

## Note:

The Khmer_Font.ttf file is currently a placeholder. To use a local Khmer font:
1. Replace the placeholder file with an actual Khmer font file
2. Or use the "Upload your handwriting font" feature to upload a .ttf or .otf Khmer font

The Google Fonts (Battambang and Kantumruy Pro) should work immediately without any additional setup.
