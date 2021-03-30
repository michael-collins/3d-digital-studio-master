---
title: Animating Evolved Virtual Creatures
layout: blocks-assignment-view
date-assigned: 2020-08-31T04:00:00.000+00:00
date-due: 2020-09-08T03:59:00.000+00:00
page_sections:
- template: assignment-description
  block: assignment-a-description
  title: Description
  content: In this exercise, you will practice animation techniques by recreating
    creatures from Evolved Virtual Creatures by Karl Sims.
- template: assignment-learningobjectives
  block: assignment-b-learningobjectives
  title: Learning Objectives
  numbered-items-list:
  - Practice applying the 12 principles of animation
  - Practice keyframe animation of translation, rotation, and scale properties.
  - Practice applying camera effects.
  list-item: []
- template: assignment-referencedmaterial
  block: assignment-d-referencedmaterial
  video:
  - title: 'Evolved Virtual Creatures '
    youtube_url: https://www.youtube.com/watch?v=JBgG_VSP7f8
    custom: ''
  - title: Karl Sims - Virtual creatures
    youtube_url: https://www.youtube.com/watch?v=WmrTNrtE-Lk
    custom: ''
  - title: Virtual Creature Bloopers (1994)
    youtube_url: https://www.youtube.com/watch?v=pxgLHuWfMS8
    custom: ''
  title: Inspiration
  links:
  - url: https://www.karlsims.com/evolved-virtual-creatures.html
    link_style: new tab
    title: Karl Sims Website
  - url: https://www.karlsims.com/papers/siggraph94.pdf
    title: Evolving Virtual Creatures SIGGRAPH Paper
    link_style: new tab
- template: assignment-supportingmaterial
  block: assignment-c-supportingmaterial
  title: Blender Tutorials
  content: To get a deeper understanding of how Blender's rendering system works,
    have a look these tutorials
  material:
  - readings:
    - _readings/beginner-lesson-1-reading.md
  readings: []
  video:
  - title: 12 Principles of Animation
    custom: <iframe width="100%" height="100%" src="https://www.youtube.com/embed/videoseries?list=PL-bOh8btec4CXd2ya1NmSKpi92U_l6ZJd"
      frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media;
      gyroscope; picture-in-picture" allowfullscreen></iframe>
  - title: Blender Foundation 2.8 Videos (28-41)
    custom: <iframe width="100%" height="100%" src="https://www.youtube-nocookie.com/embed/videoseries?list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6"
      frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope;
      picture-in-picture" allowfullscreen></iframe>
  - title: Parenting in Blender
    youtube_url: https://www.youtube.com/watch?v=kd1O0oqQ3Uw
    custom: ''
  - title: Adding a tracking constraint
    youtube_url: https://www.youtube.com/watch?v=ageV_llb0Hk
    custom: ''
  links: []
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
- " camera"
- keyframe
- graph editor
- bezier
- 12 principles of animation
prerequisites: []
difficulty_level: advanced
header_image: "/uploads/airline-chair-header-compressed.jpg"
header:
  image_fullwidth: "/uploads/banner-creatures-compressed.jpg"
accordion_mode: true

---
## Instructions

1. Watch the animation tutorials.
2. Create a creature animation using only primitives inspired by [Evolved Virtual Creatures](https://www.youtube.com/watch?v=JBgG_VSP7f8). It must include the following:
   * Armature rig
   * At least 2 creatures with at least 3 moving pieces appendages
   * Camera movement
   * Easing applied to keyframes of moving objects (non-linear tangents in graph editor)
   * At least 10 seconds of animation at 24 frames per second (240 frames)
3. To create a "playblast" animation, you can capture the animation directly from the viewport. To create a video of the viewport's animation, save the `.blend` file and set the render settings output folder to the project folder. Under **File Format**, choose **FFMpeg Video**, change the encoding format to **MPEG-4**.
4. No need to render using EEVEE, a viewport render is fine.
5. Choose **View** ⟶ **Viewport Render Animation** to create the animation file. Check that the animation file was created.
6. Compress the project folder once you’ve completed the tutorial and rename it **_LASTNAME_-creatures.zip.**
7. Upload the .zip file to the assignment dropbox.
8. Double check that you've included all files and that your .zip file can be downloaded and opened.