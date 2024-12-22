<link rel="stylesheet" href="{{ '/assets/css/video.css' | prepend: site.baseurl }}">

# Quick start

1. Prepare the scene and the object you want to break
2. Add the `Breaker` component to your GameObject
3. Add `Break By Click Collider`
4. Run the scene and click on the object to break it

{% include video.html youtube="O5hpIKY-d5w" %}

## Demo scene

You could use the `Demo` scene.

Just open it from the `Assets/CyberRevolution/BreakableObjectsSystem/Examples/Demo` folder. There you will find a simple
scene with a placeholder for objects.
You can put your own objects in the placeholder to see how they break or simply press the `Play` button to see the
default objects breaking.

## Further reading

[How to trigger destruction](triggering-destruction.md)