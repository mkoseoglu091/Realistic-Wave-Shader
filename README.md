# Realistic-Wave-Shader
Shader I wrote for my Graphics and Interaction Class for a Unity Game we were working on.

This method uses the Gerstner Waves ti animate water a water surface. Before this approach a sine wave was used to displace vertices on the y-axis of a plane, but this creates unrealistic waves. Below is a comparison of how sine waves and gerstner waves displace vertices on a plane. The top represents a typical sine wave implementation, the bottom represents the gerstner wave implementation.

<img src="https://user-images.githubusercontent.com/97642386/212574854-1bbaea5a-ee7e-49e2-bf78-6269e7404846.png" width="250">

### Sine Wave Implementation
Sine waves are very rigid and predictable. They are not ideal for water surfaces
<br>
<img src="https://thumbs.gfycat.com/FineYoungErne-max-1mb.gif" width="250">

### Gerstner Wave Implementation
Gerstner waves are much better but they still do not look realistic enough... Which brings us to the next step.
<br>
<img src="https://thumbs.gfycat.com/BitterGoldenHalicore-max-1mb.gif" width="250">

We can add multiple gerstner waves on top of one another, with different direction, steepness and wavelength. This produces very interesting combinations. Playing around with the parameters can create very realistic results that can be used to simulate large bodies of water. Below is an example where 3 waves are used creating a very interesting water surface.
<br>
<img src="https://thumbs.gfycat.com/ThisFatherlyBrontosaurus-max-1mb.gif" width="250">




