

White Plastic
 * Metallic->Metallic: 0.4
 * Roughness->Roughness: 0.35

Mirror
 * Metallic->Metallic: 1
 * Roughness->Roughness: 0.02

Dark Wood
 * Albedo->Color: R: 206, G: 147, B: 92, A: 255
 * Albedo->Texture: res://materials/texture_wood.png
 * Metallic->Metallic: 0.48
 * Roughness->Roughness: 0.28

Cheese
 * Albedo->Texture: res://materials/texture_cheese_albedo.png
 * Roughness->Roughness: 0.64
 * Normal Map->Enabled: On
 * Normal Map->Texture: res://materials/texture_cheese_normal.png
 * Ambient Occlusion->Enabled: On
 * Ambient Occlusion->Texture: res://materials/texture_cheese_ao.png
 * Depth->Enabled: On
 * Depth->Texture: res://materials/texture_cheese_depth.png
 * Subsurf Scatter->Enabled: On

Stones
 * Albedo->Texture: res://materials/texture_rock_albedo.png
 * Metallic->Metallic: 0.86
 * Metallic->Texture: res://materials/texture_rock_metal.png
 * Roughness->Roughness: 0.47
 * Normal Map->Enabled: On
 * Normal Map->Texture: res://materials/texture_rock_normal.png
 * Ambient Occlusion->Enabled: On
 * Ambient Occlusion->Texture: res://materials/texture_rock_ao.png
 * Depth->Enabled: On
 * Depth->Texture: res://materials/texture_rock_depth.png

Brick
 * Albedo->Texture: res://materials/texture_bricks_albedo.png
 * Metallic->Metallic: 1
 * Metallic->Texture: res://materials/texture_bricks_metal.png
 * Roughness->Roughness: 0.56
 * Normal Map->Enabled: On
 * Normal Map->Texture: res://materials/texture_bricks_normal.png
 * Depth->Enabled: On
 * Depth->Texture: res://materials/texture_bricks_depth.png

Wool
 * Albedo->Texture: res://materials/wool_albedo.png
 * Metallic->Metallic: 0.1
 * Roughness->Roughness: 0.77
 * Normal Map->Enabled: On
 * Normal Map->Texture: res://materials/wool_normal.png
 * Depth->Enabled: On
 * Depth->Texture: res://materials/wool_depth.png

Aluminium
 * Albedo->Texture: res://materials/aluminium_albedo.png
 * Metallic->Metallic: 0.59
 * Roughness->Roughness: 0.4
 * Normal Map->Enabled: On
 * Normal Map->Texture: res://materials/aluminium_normal.png
 * Anisotropy->Enabled: On
 * Anisotropy->Flowmap: res://materials/aluminium_flow.png

Marble
 * Parameters->Diffuse Mode: Lambert Wrap
 * Albedo->Texture: res://materials/marble_albedo.png
 * Metallic->Metallic: 0.1
 * Roughness->Roughness: 0.1
 * Rim->Enabled: On
 * Subsurf Scatter->Enabled: On

Wet Sand
 * Albedo->Texture: res://materials/sand_albedo.png
 * Metallic->Metallic: 1
 * Metallic->Texture: res://materials/sand_metal.png
 * Roughness->Roughness: 1
 * Roughness->Texture: res://materials/sand_rough.png
 * Normal Map->Enabled: On
 * Normal Map->Texture: res://materials/sand_normal.png

Rock
 * Albedo->Texture: res://materials/rock_albedo.png
 * Metallic->Metallic: 0.12
 * Roughness->Texture: res://materials/rock_rough.png
 * Normal Map->Enabled: On
 * Normal Map->Texture: res://materials/rock_metal.png
 * Ambient Occlusion->Enabled: On
 * Ambient Occlusion->Texture: res://materials/rock_ao.png
 * Depth->Enabled: On
 * Depth->Texture: res://materials/rock_depth.png

Ice
 * Parameters->Depth Draw: Never
 * Albedo->Color: R: 255, G: 255, B: 255, A: 0
 * Albedo->Texture: res://materials/rock_albedo.png
 * Metallic->Metallic: 1
 * Roughness->Roughness: 0.62
 * Normal Map->Enabled: On
 * Normal Map->Texture: res://materials/rock_metal.png
 * Ambient Occlusion->Enabled: On
 * Ambient Occlusion->Texture: res://materials/rock_ao.png
 * Refraction->Enabled: On

Toon
 * Parameters->Diffuse Mode: Toon
 * Parameters->Specular Mode: Toon
 * Albedo->Color: R: 231, G: 91, B: 25, A: 255
 * Roughness->Roughness: 0.04
 * Material->Next Pass: New Spatial Material
   * Flags->Unshaded: On
   * Parameters->Cull Mode: Front
   * Parameters->Grow: On
   * Albedo->Color: R: 7, G: 0, B: 0, A: 255
 
# Exercise-05d-Materials
Exercise for MSCH-C220, 5 April 2021

An exploration of PBR Materials in Godot.

## Implementation
Built using Godot 3.2.3

## References
[Godot 3 Tutorial: PBR Materials](https://www.youtube.com/watch?v=pM5j8x71HcE)

## Future Development
None

## Extra Credit
None

## Created by 
Gwen Hall
