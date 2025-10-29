# LumeniteFX Shaders

## LumaFlow
LumaFlow is a motion estimation shader written for ReShade. It determines where each pixel in the current frame originated from in the previous frame, providing a 'motion vector' for this tracking. These motion vectors can enable various applications: frame generation (increases the framerate), temporal reprojection in Ray tracing (where results accumulate across multiple frames), and other motion-dependent effects like motion blur, for example.
