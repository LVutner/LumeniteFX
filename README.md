# LumeniteFX Shaders
Any questions, comments or need help? Join the Lumenite discord server: https://discord.gg/deXJrW2dx6

## LumaFlow
![LumaFlow_Poster](https://github.com/umar-afzaal/asset-repo/blob/mainline/lumenitefx/LumaFlow_poster.jpg)
**SPDX Identifier: CC-BY-NC-4.0**.

LumaFlow is a motion estimation shader written for ReShade. It determines where each pixel in the current frame originated from in the previous frame, providing a 'motion vector' for this tracking. These motion vectors can enable various applications: frame generation (increases the framerate), temporal reprojection for e.g. Ray tracing usually accumulates samples for multiple frames, and other motion-dependent effects like motion blur.

## LumeniteRT
![LumaFlow_Poster](https://github.com/umar-afzaal/asset-repo/blob/mainline/lumenitefx/LumeniteRT_poster.jpg)
LumeniteRT is a depth buffer based raytracing shader written for ReShade. It combines a few screenspace raytraced effects in one package: Bounce lighting, occlusion shadows and specular reflections. To be released in December 2025.
