---
layout: page
title: "Breakable glass and objects system: Simple procedural solution"
permalink: /projects/breakable-glass-simple
---

# [Download at Unity Asset Store](https://assetstore.unity.com/packages/tools/physics/breakable-glass-and-objects-system-simple-procedural-solution-205206)

# Main features

1. Procedural mesh fracturing right in Unity Editor. Textured meshes are supported.
2. A lot of options for broken objects
3. Shards pools that can be used to share the same shards between similar objects

# Important notes

<img alt="breakable-simple-img0.png" src="{{ '/images/breakable-simple-img0.png' | prepend: site.baseurl }}" width="512"/>

Please note that the provided solution is SIMPLE. So, there are some points:

1. Destruction algorithm works by slicing with random planes
2. By default the new geometry will be generated for inner surfaces. Interpolated UV-coordinates and the original
   material will be applied. It will work properly only if your mesh is convex. If your mesh is concave or too difficult
   you may encounter some problems or graphical artifacts. You can play around with some values or disable option **“Add
   new geometry”** in this case