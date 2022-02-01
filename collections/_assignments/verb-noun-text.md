---
title: 'PBR: Abstract architecture, type, and materials'
layout: blocks-assignment-view
date-assigned: 2020-08-31T04:00:00.000+00:00
date-due: 2020-09-08T03:59:00.000+00:00
page_sections:
- template: assignment-description
  block: assignment-a-description
  title: Description
  content: In this exercise, you will practice using PBR materials, modeling, lighting,
    and rendering. You will also use compositional theory from art and design to organize
    elements in a 3D scene to create an image.
- template: assignment-learningobjectives
  block: assignment-b-learningobjectives
  title: Learning Objectives
  numbered-items-list:
  - Become familiarized with the PBR workflow.
  - Practice good composition from art and design theory.
  list-item: []
- template: assignment-demo
  block: assignment-a-demo
  video:
  - custom: <iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PL-V2nChTadrVzwK_273DPBW9SzcZpxu77"
      frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    title: PBR Materials Texturing and Lighting Videos
  content: These demonstration videos show how to set up PBR materials and realistic
    HDRI environment lighting.
  title: Demonstration Videos
- template: assignment-supportingmaterial
  block: assignment-c-supportingmaterial
  title: Composition Theory
  links: []
  video:
  - title: The Secret of Making High-Quality Art (in Blender and Everywhere) by Gleb
      Alexandrov
    youtube_url: https://www.youtube.com/watch?v=qMH_J_vcoqE
    custom: ''
- template: assignment-supportingmaterial
  block: assignment-c-supportingmaterial
  title: Blender PBR Tutorials
  content: To get a deeper understanding of how Blender's rendering system works,
    have a look these tutorials
  material:
  - readings:
    - _readings/beginner-lesson-1-reading.md
  readings: []
  video:
  - title: Adding Type
    youtube_url: https://www.youtube.com/watch?v=Lrhwq3cxz_c
    custom: ''
  - title: PBR and the Principled BSDF Shader
    youtube_url: https://www.youtube.com/watch?v=cvu5XYrZT6Q
    custom: ''
  links:
  - title: PBR Blender Add-on
    url: https://3d-wolf.com/products/materials.html
    link_style: new tab
  - title: What is a BSDF?
    link_style: new tab
    url: https://cgcookie.com/tutorial/what-in-the-world-is-a-bsdf-cgc-weekly-16
  - title: Index of Refraction list
    link_style: new tab
    url: https://pixelandpoly.com/ior.html
- template: assignment-supportingmaterial
  block: assignment-c-supportingmaterial
  title: Modeling with Curves and Booleans
  video:
  - title: Blender 2.8. Modelling with Curves, how to make pipes
    youtube_url: https://www.youtube.com/watch?v=F2SIbAxLftc
    custom: ''
  - title: Blender 2.8 Subsurf & Boolean Modifier Tutorial
    youtube_url: https://www.youtube.com/watch?v=bUWZqiXY2lg
    custom: ''
  - title: Blender Make Pipes Horns Spouts with Curve Beveling Blender 2.8
    youtube_url: https://www.youtube.com/watch?v=VtSDpIZ6DiE
    custom: ''
- template: assignment-referencedmaterial
  block: assignment-d-referencedmaterial
  title: Inspiration
  links:
  - title: Behance.net
    link_style: new tab
    url: https://www.behance.net/search?search=3d%20type
  - title: 36 Days of Type
    link_style: new tab
    url: https://www.instagram.com/36daysoftype/
  - title: Course Website Artist List
    url: https://michaelcollins.xyz/3d-digital-studio-master/resources/inspiration/
    link_style: new tab
- template: assignment-referencedmaterial
  block: assignment-d-referencedmaterial
  links:
  - title: CC0 Textures
    url: https://cc0textures.com/
    link_style: new tab
  - title: Textures.com
    link_style: new tab
    url: https://www.textures.com/
  - title: HDRI Haven
    url: https://hdrihaven.com/hdris/
    link_style: new tab
  - title: PBR Material Add-on
    url: https://3d-wolf.com/products/materials.html
    link_style: new tab
  title: Texture and material resources
  content: Use these websites to find textures to apply to your model.
- template: assignment-referencedmaterial
  block: assignment-d-referencedmaterial
  title: PBR Theory
  content: These guides discuss some of the physics behind the physical properties
    of materials and how various texture maps in 3D applications can mimic these properties.
  links:
  - link_style: new tab
    url: https://academy.substance3d.com/courses/the-pbr-guide-part-1
    title: PBR Guide Part 1
  - title: PBR Guide Part 2
    link_style: new tab
    url: https://academy.substance3d.com/courses/the-pbr-guide-part-2
  headline: PBR Guides
- template: assignment-rubric
  block: assignment-f-rubric
  title: Rubric
  content: ''
  rubric_criteria:
  - criteria_title: Attention to Detail
    criteria_description: This criteria looks at if the assignment was submitted on
      time, if each step was completed to a high degree of accuracy, and if file naming
      conventions were followed.
    criteria_weight: 5 pts
  - criteria_title: Learning by doing (Completed all steps)
    criteria_description: This criteria assess whether you completed the assignment's
      given set of instructions. This indirectly infers how well you acquired foundational
      skills and theory.
    criteria_weight: 5 pts
topics_covered:
- rendering
- sampling
- " camera"
- " focal length"
- compositing
- " light"
- PBR
prerequisites: []
difficulty_level: " beginner"
header_image: "/uploads/airline-chair-header-compressed.jpg"
header:
  image_fullwidth: "/uploads/type-material-banner2-compressed.png"
accordion_mode: true

---
## Instructions

 1. Watch linked tutorials in learning resources.
    * **NOTE:** These are not step-by-step tutorials for how to complete the assignment, rather they give you an understanding of Blender tools and concepts that you can use to solve the exercise requirements. This is not an animation exercise, so please do not submit an animation.
 2. Create a new project folder.
 3. **Design an outdoor sculpture garden** using a PBR workflow for the objects in the scene.
    1. Model the architectural space
    2. Model the objects present in the garden (don't spend too much time on them, the emphasis is on materials for this assignment).
    3. Organize the space and camera to create pleasing image compositions.
    4. Add realistic lighting
 4. Practice modeling, texturing, lighting, and rendering. Include the following in your Blender scene:
    * **Polygonal objects:** Model abstract and architectural objects using polygon modeling techniques you have learned. You can also experiment with boolean modifiers and curve tools. At least one of the polygonal objects must use a PBR texture pack that includes a **base color**, **normal**, **roughness**, and may also include other textures as well like **metalness** and **ambient occlusion**, and **height**. Follow tutorials to learn how to apply them to your model.
    * **Minimum of three PBR Materials:** You can use the [random material generator](https://perchance.org/building-material) to get a minimum of three material ideas to use in your scene if you cannot decide which materials you prefer to use.
    * **Typography:** Add text using the Text tool in Blender.
    * **Curves with geometry:** Add curves and configure their geometry attributes to create procedural shapes based on bezier and other curves.
    * **Lighting:** Use either HDRI lighting or Blender's sky node to light the scene.
    * **Background elements:** Background elements can include a floor, backdrop, terrain features, and/or other elements that help build a composition.
 5. Inspiration:
    * [Behance.net](https://www.behance.net/search?search=3d%20type)
    * [36 Days of Type](https://www.instagram.com/36daysoftype/)
    * [Course Website Artist List](https://michaelcollins.xyz/3d-digital-studio-master/resources/inspiration/)
 6. Save your material texture packs to a folder called **textures** in your project folder.
 7. Add lights and adjust the background elements or color to enhance the composition.
 8. Render using cycles
 9. Configure your render camera with an appropriate focal length and compose your layout.
10. Configure the render settings **sampling** to be high enough to reduce noise. Somewhere between 250 and 750 should give results with low noise.
    1. Enable adaptive sampling if using Blender 2.8-2.9 (Blender 3.0 is slightly different).
11. Render an image. Save and import the image into Photoshop to adjust saturation, contrast.
    1. PNG is fine, however rendering an EXR and using the 'HDR Toning' feature in Photoshop will give the best results.
12. Save or export the image as **_LASTNAME_-pbr.png**, etc. in the project folder. Name the files in an organized in a logical way.
    1. Do not submit an EXR as the final image, they are for image production process only.
13. Remove large Photoshop files that you may have in the project folder before compressing for upload.
14. Save the 3D scene file as **_LASTNAME_-pbr** in the project folder.
15. Compress the project folder once you’ve completed the tutorial and rename it **_LASTNAME_-pbr.zip.**
16. Upload the .zip file to the assignment dropbox.
17. Double check that you've included all files and that your .zip file can be downloaded and opened.