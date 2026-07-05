### Custom Physics 2D Overview

# SF Physics 2D Package
<p>For a while I have been creating my own custom in the Unity game engine that do not use Collider2D or Rigidbody2D. My custom solution is written with burst and multi-threading support in mind.
These use the PhysicsShape and PhysicsBody API built on the open source Box 2D 3.1 library. They don't have to be on a gameobject in scene to make objects react to collisions or send physics events.
</p>


## SF Physics 2D Examples

### First Dynamic Particle Simulation Test
<iframe width="560" height="315" src="https://www.youtube.com/embed/AMQSOS6vLHM?si=sKiI8CTUBtFWMHPY"
title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture;
web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
</iframe>

### 50,000 Physics Shape - First Performance Test 
<iframe width="560" height="315" src="https://www.youtube.com/embed/iKNO4IPImHI?si=fzlJpBymZU1zT5U1" 
title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
</iframe>


## Unity Physics Core 2D Module
Important Note: Unity 6.3 this was originally called the Low Level Physics 2D API and in Unity 6.5 it was renamed to the Physics Core 2D Module due to it being the future core foundation for Unity Physics 2D.


<p> Unity implemented the Box2D 3.1 release in Unity 6.5. With it you can write your own custom physics algorithms, components, multi-thread your own code, and a lot more.
Here are some early tests of the Physics 2D systems I have been working on multithreading and burst compiling inside of the Unity Game Engine.
Note after making these videos I was able to improve performance mainly thanks to SIMD improvements that was introduced and usable in Unity 6.5.
</p>


### Physics 2D