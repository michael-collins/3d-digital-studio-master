---
title: Introduction to Cameras, Lighting, and Rendering
subtitle: 
layout: page

---
1. **Video Screening**
   * ["Spectacle, Speculation, Spam"](https://alanwarburton.co.uk/spectacle-speculation-spam) by Alan Warburton
   * [Lighting Theory by Andrew Price](https://www.youtube.com/playlist?list=PLjEaoINr3zgH9vCr47kSS5W8PEJBNIiwK "Lighting Theory by Andrew Price")
2. **Demo**
   * [Lighting and Rendering Video (Unedited live demo)](https://vimeo.com/456374066)
3. **Technical Readings for 3D Rendering**
   * [FX Guide: "Art of Rendering"](https://www.fxguide.com/featured/the-art-of-rendering/)
   * [FX Guide: "State of Rendering"](https://www.fxguide.com/fxfeatured/the-state-of-rendering/)
4. **For your Bookshelf**
   * [How to Render by Scott Robertson](https://www.amazon.com/How-Render-fundamentals-shadow-reflectivity/dp/1933492961/)
   * [Software Takes Command](http://manovich.net/index.php/projects/software-takes-command) by Lev Manovich
   * [The Language of New Media](http://manovich.net/index.php/projects/language-of-new-media) by Lev Manovich
5. **Terminology**
   * **Lighting setups**
     * [3 point lighting](https://m5designstudio.com/2011/maya-3d-tutorials/studio-three-point-lighting/) (key, fill, rim)
     * Light types: Area, Spot, Directional or Sun, Point, Volumetric
     * Geometry-based lighting using Emission shader
     * Geometry-based lighting using [Principled Volumetric shader](https://www.youtube.com/watch?v=AXjE-t6dFZ8)
     * Staging lights: Light box with side and top lights, curved color background and floor
     * Image based lighting (IBL) [using HDR images](https://area.autodesk.com/tutorials/studio-lighting/)
     * Shadows: The larger the light source, the softer the shadows
     * Create edge bevels to capture highlights on hard surfaces
   * **Camera**
     * Perspective vs Orthographic
     * Sensor size
     * Depth of field using aperture F-Stop: Shallow depth of field is created with lower settings. (In Blender, very low settings may be needed such as 0.1)
     * Blades add flat sides to the Bokeh
     * You can create custom [Bokeh shapes](https://blender.stackexchange.com/questions/133191/custom-bokeh-shapes)
     * Safe area
     * Composition guides for layouts (golden ratio, golden triangle, thirds, etc.)
   * **Render quality in Cycles**
     * To reduce render times, keep material shaders simple. Use principled shader if working with photo-real renders.
     * 500 samples are usually needed to reduce noise.
     * Use [advanced denoising workflow](https://www.youtube.com/watch?v=Pw-OxOHHu5I) in the compositor
     * If using motion blur or depth of field, sample sizes must increase dramatically.
     * You can get away with 120 samples if you use denoising in the Compositor
   * **Render quality in EEVEE**
     * [EEVEE Lighting](https://www.youtube.com/watch?v=MFNurQ1AF2I)
     * Enable render settings including: Ambient Occlusion, Depth of Field, and Screen Space Reflections
     * Shadows: Increase the shadow map to 4K
