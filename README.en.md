# Photo to C4D Style

[中文版](README.md)

Transform an uploaded photo into a refined, detailed C4D-style 3D model.

This is a Codex Skill for turning storefronts, buildings, streets, objects, pets, or people into complete collectible 3D models while preserving the original subject, composition, camera direction, and recognizable features whenever possible.

## What It Does

- Rebuilds a photo as a complete C4D-style 3D model instead of applying a simple filter
- Uses soft rubber, silicone, or satin-vinyl materials
- Creates fine microtexture, rounded bevels, soft highlights, and refined molded surfaces
- Uses bright, clean, studio-quality product lighting
- Determines whether the source is frontal or angled and preserves parallel perspective
- Keeps near-front photos in a clean frontal or near-frontal model view
- Preserves the main silhouette, key objects, relative layout, and readable signage
- Leaves generous canvas space around the model so it is not cramped or cropped

## Usage

Invoke it explicitly in Codex:

Use $photo-to-c4d-style to transform the uploaded photo into a polished C4D-style 3D model.

For a Chinese request, you can also write:

把这张照片转换成精美的 C4D 风格 3D 模型，使用细腻的软橡胶材质、工作室级灯光和充足留白。

## Visual Direction

- Refined Cinema 4D-style 3D model
- Soft rubber, silicone, or satin-vinyl materials
- Ultra-fine microtexture, delicate roughness variation, and soft edge highlights
- Vivid, clean colors with a premium finish
- Large softbox key light, broad fill light, and subtle rim light
- Bright pale background, balanced exposure, and delicate dimensional shading
- No cast ground shadow, dark floor patch, or heavy grounding effect

## Composition and Perspective

- Preserve the source photo's camera direction and composition
- For near-front sources, use a stable frontal or near-frontal product view without inventing a three-quarter angle
- For genuinely angled sources, preserve the visible front, side, and front-to-back relationships
- Use parallel perspective to correct keystone distortion, slanted verticals, and obvious wide-angle distortion
- Use a larger canvas so there is at least 20% clear background space between the model's outer silhouette and each image edge
- Keep the model centered and fully visible without making it too small because of the margins

## Limitations

This Skill depends on image-generation or image-editing capabilities available in the current environment. A single photo can produce a plausible stylized interpretation, but unseen sides, backs, or interior structures may not be accurate reconstructions.

Small text in the source image may not be reproduced character-for-character. The Skill tries to preserve its placement, hierarchy, and visual shape rather than confidently inventing exact wording.

## Project Structure

- SKILL.md: Skill instructions
- README.md: Chinese documentation
- README.en.md: English documentation
- agents/openai.yaml: Interface metadata
