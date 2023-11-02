![2023-11-02_15-26-27](https://github.com/rifkyzena/Blitz-Conquerors/assets/55536824/49b2dcae-5dff-4e26-886a-074554bbe3f9)

- [Play the game on your browser!](https://sharemygame.com/@RifkyZena66/blitz-conquerors)
- [Or download the Build](https://github.com/rifkyzena/Blitz-Conquerors/releases/tag/v1.0.0)

# Blitz Conquerors

Blitz Conquerors is a vertical shooter game in the sense of classics SHMUPS like Raiden and Ikaruga. Just like Plato's Cave, I made this game as a way to begin my first dive into Unity 2D fundamentals. Soar high above the ruins of civilization with your trusty aircraft against onslaught of endless enemies! Rake the highest score before going down in a blaze of glory! 

Controls: WASD to move the aircraft, left click to shoot

## Things that I've learned throughout making this project:

- Pathfinding, Instantiating Prefabs, Coroutines, endless looping level design
  ![image](https://github.com/rifkyzena/Blitz-Conquerors/assets/55536824/33af5acc-7a6a-4f5e-b6a7-8706557fe6a4)
  - https://en.wikipedia.org/wiki/Foreach_loop
  - https://docs.unity3d.com/ScriptReference/Vector2.MoveTowards.html
  - https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/statements/iteration-statements

- Damage and health calculation, 2D shooting mechanics, velocity, and quaternions
  ![image](https://github.com/rifkyzena/Blitz-Conquerors/assets/55536824/5c1b3512-fbcc-41d4-b010-4a895f687e48)
  - https://docs.unity3d.com/ScriptReference/MonoBehaviour.OnTriggerEnter2D.html
  - https://docs.unity3d.com/Manual/LayerBasedCollision.html
  - https://docs.unity3d.com/ScriptReference/MonoBehaviour.StopCoroutine.html
  - https://docs.unity3d.com/ScriptReference/Rigidbody-velocity.html
  - https://docs.unity3d.com/ScriptReference/Quaternion.Euler.html
  
- Particle effects, screen shake, scrolling background, music and sound effects
  ![image](https://github.com/rifkyzena/Blitz-Conquerors/assets/55536824/86bb7f92-72b8-4516-97e9-8e6c2752694f)
  - https://www.youtube.com/watch?v=tu-Qe66AvtY
  - https://docs.unity3d.com/ScriptReference/Camera.ViewportToWorldPoint.html
  - https://docs.unity3d.com/ScriptReference/ParticleSystem.html
  - https://docs.unity3d.com/ScriptReference/Random-insideUnitCircle.html
  - https://docs.unity3d.com/ScriptReference/WaitForEndOfFrame.html
  - https://docs.unity3d.com/ScriptReference/Material-mainTextureOffset.html
  - https://docs.unity3d.com/ScriptReference/AudioSource.html
  
- Game UI, connecting scripts to Health sliders and score counters
  ![image](https://github.com/rifkyzena/Blitz-Conquerors/assets/55536824/2b0bbd55-2e69-4c1f-9435-f0dfd44c70b2)
  - https://docs.unity3d.com/Packages/com.unity.ugui@1.0/manual/UIBasicLayout.html
  - https://docs.unity3d.com/Manual/com.unity.textmeshpro.html

- Singleton Pattern, WebGL Build
  ![image](https://github.com/rifkyzena/Blitz-Conquerors/assets/55536824/cec5c47d-25d0-4f1c-97a5-99101badad5b)
  - https://docs.unity3d.com/Manual/webgl-building.html
  - https://en.wikipedia.org/wiki/Singleton_pattern
  - https://sharemygame.com

## Assets Used:
1. https://opengameart.org/content/cyberpunk-moonlight-sonata
2. https://scutanddestroy.wordpress.com/2012/04/30/shmup-background-composited-layers/
3. https://www.kenney.nl/assets/pixel-shmup
