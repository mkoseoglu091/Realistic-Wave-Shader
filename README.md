# Realistic Wave Shader
This is a shader I wrote for my Graphics and Interaction Class for a Unity Game we were working on.

This method uses the Gerstner Waves to animate a water surface. Before this approach a sine wave was used to displace vertices on the y-axis of a plane, but this creates unrealistic waves. Below is a comparison of how sine waves and gerstner waves displace vertices on a plane. The top represents a typical sine wave implementation, the bottom represents the gerstner wave implementation.

<img src="https://user-images.githubusercontent.com/97642386/212574854-1bbaea5a-ee7e-49e2-bf78-6269e7404846.png" width="250">

### Sine Wave Implementation
<img src="https://thumbs.gfycat.com/FineYoungErne-max-1mb.gif" width="250">
Sine waves are very rigid and predictable. They are not ideal for water surfaces. 

### Gerstner Wave Implementation
<img src="https://thumbs.gfycat.com/BitterGoldenHalicore-max-1mb.gif" width="250">
Gerstner waves are much better but they still do not look realistic enough... Which brings us to the next step.

### Multiple Waves
<img src="https://thumbs.gfycat.com/ThisFatherlyBrontosaurus-max-1mb.gif" width="250">
We can add multiple gerstner waves on top of one another, with a different direction, steepness and wavelength. This produces very interesting combinations. Playing around with the parameters can create very realistic results that can be used to simulate large bodies of water. Below is an example where 3 waves are used, creating a very interesting water surface.

### Transparency and Refraction
This shader also has parameters for transparency, refraction and underwater fog. These can be played around with to create even better looking transparent water surfaces.
