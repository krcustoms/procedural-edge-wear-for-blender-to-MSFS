Template insructions:

Append the CUBE SHADER and WEAR_SHADER_1 materials from this blend file to your blend file.

Note: your mesh needs to be UV unwrapped before moving forward.

Add the CUBE SHADER material to the mesh you want to apply edge wear to and bake a bevel map texture using the Emit bake type. 

You can now apply the WEAR_SHADER_1 material to your mesh.

Add the bevel map you've just baked to the Bevel Map Texture node in the WEAR_SHADER_1 material.

Add an appropirate scratch or grunge texture to the Scratch\Grunge Texture node in the same material. You can use the one I've provided if needed.

Play around with the values in any of the map range or math nodes to achieve the look you want.

You're now ready to bake your albedo, roughness, ambient occlusion, metallic, and normal maps.

Note: For baking a metallic map, you can just take what is plugged into the metallic slot, move it to the roughness slot and bake using the Roughness bake type.
