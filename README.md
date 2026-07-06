# whatsapp-profile-picture-converter
Reat application for whatsapp profile picture converter 
# Release Notes

## v1.0.0 - Initial Release

This is the first usable release of the WhatsApp Profile Picture Converter.

### Added

- Upload support for JPG, PNG, and WEBP images.
- Full-image conversion into a `640 x 640` WhatsApp-ready square.
- No-crop fitting, so the entire uploaded image remains visible.
- Background options:
  - Blurred image background
  - White background
  - Black background
  - Custom color background
- Square preview of the final image.
- Circular WhatsApp-style profile preview.
- Download button for saving the final image as `whatsapp-profile-picture.jpg`.
- Reset button for clearing the selected image.
- Responsive layout for desktop and mobile screens.

### Technical Notes

- Built with React and Vite.
- Uses the browser Canvas API for image conversion.
- Runs entirely in the browser; uploaded images are not sent to a server.

### Known Next Improvements

- Add rotate controls.
- Add manual zoom and positioning.
- Add drag-and-drop upload.
- Add PNG export option.

**Key information about the Source code **
Important Files
src/main.jsx
Main React code. Handles upload, conversion, preview, and download.

src/styles.css
Design and layout.

package.json
Lists required packages and commands.

README.md
Basic project guide.

RELEASE_NOTES.md
Notes for version 1.0.0.

you need node.js insatalled in you system 

Start app: 
npm run dev 

Build fial Prodcution version 
npm run build 

preview production build 
npm Run Preview 


