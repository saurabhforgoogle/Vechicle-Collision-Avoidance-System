# Vechicle-Collision-Avoidance-System
It is a google collab for realtime collison avoidance system.
<br/>
More About it in this slides: 
<br/>
<B> https://docs.google.com/presentation/d/1dkjH_VI-bjULZ-ZnSXUuhouA9zv4MXbvXOuESzh92WU/edit?usp=sharing </B>

<H1> Process</H1>
<br/>1. It uses Darknet library to get MS COCO dataset prediction.<br/>2.  Using that we can estimate size of every vechicle in a frame.<br/>
3. Using parallex angle and camera angle and vechicle size, We can estimate its distance from source.<br/>
4. Later we can calcultae speed from two or more frames.<br/>
