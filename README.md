# LumeniteFX Shaders

## LumaFlow
![LumaFlow_Poster](https://github.com/umar-afzaal/asset-repo/blob/mainline/lumenitefx/lumaflow_poster.png?raw=true)
LumaFlow is a motion estimation shader written for ReShade. It determines where each pixel in the current frame originated from in the previous frame, providing a 'motion vector' for this tracking. These motion vectors can enable various applications: frame generation (increases the framerate), temporal reprojection for e.g. Ray tracing usually accumulates samples for multiple frames, and other motion-dependent effects like motion blur.
