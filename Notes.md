# What Impacting the Performance?
- Why we are downloading the resources which we are not going to use?
  - Hero Section Image (Desktop, Tablet and Mobile)
- Why we are downloading the resources which is yet not visible in the viewport?
  - Other Section Images
- Image Size is also impacting the performance (200Kb -300Kb)

# Improvements
1. Avoid Oversized Images -> 1920 (2400)
- Image Dimention (Oversized Images)

2. Converting and Compressing Images
- Compress images and use mordern formats
 : Faster Download
 : Less Data Consuption

3. Handling Responsive Images using Picture Element
- Handling Responsive loding images

- Lazy loading
- Add correct attributes for image elements

-----------------------------------------------------------------------------------------------------

# Fixing CLS:
CLS with old and New Images
- Set width and height explicitly [Calculates the Aspect Radio and Reserve the Space for the Images]

Hidden Elements: (Cause CLS)
Usability Problems

----------------------------------------------------------------------------------------------------

# Lazy Loading (offloading the images) - visible in Viewport:
loading="lazy"

----------------------------------------------------------------------------------------------------

# Reduce JavaScript Execution Time (Lazy load the complete section which is not visible)
(product.js)

----------------------------------------------------------------------------------------------------

# Render Blocking Resources:
- Google Font (Self Host the font file)
- Cookies script (defer the script - to not blocking the rendering of the UI)

---------------------------------------------------------------------------------------------------

# Defer Scripts
Use defer attribute for script want to load after UI rendering

# ------------------------------------- Fix Accessibility Issues ----------------------------------
It's important to fix the Accessibility issues because the people having vision imperiments, they use the internet using Screen Reader.

- Always use alt attributes with img element to more describe the image in textual form
- Always check the Color Contrast of an element - use Constrast Checker online tool (Always check with designer)