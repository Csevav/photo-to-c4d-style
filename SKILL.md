---
name: photo-to-c4d-style
description: "Transform an uploaded photo into a polished Cinema 4D-style 3D model while preserving the subject, composition, and recognizable details."
---

# Photo to C4D Style

Use this skill when the user provides a photo and asks for a C4D-style rubber, soft vinyl, silicone, or polished 3D model reinterpretation.

## Workflow

1. Confirm that an image is attached. If no image is available, ask the user to upload one before generating anything.
2. Use the available image-generation or image-editing capability with the uploaded photo as the image reference.
3. Preserve the recognizable subject, key silhouette, important objects, relative layout, and distinctive text or markings when they are legible. Do not invent a different scene unless the user asks for a redesign.
4. Rebuild the entire image as a complete, coherent 3D collectible model. Do not merely apply a C4D effect or rubber texture to the original photograph.
5. Apply this visual direction:
   - refined Cinema 4D-style 3D model with a polished product-render presentation
   - every visible major element rebuilt as dimensional geometry, including architecture, furniture, signs, plants, props, and figures
   - rounded, softly simplified forms with deliberate modeling, smooth bevels, and molded edges
   - refined soft rubber, silicone, or satin-vinyl material with an ultra-fine tactile microtexture, gentle elasticity, and silky controlled highlights
   - smooth molded surfaces with delicate roughness variation, soft edge roll-off, subtle color transitions, and premium injection-molded detail
   - vivid, clean, slightly luminous colors with balanced saturation; avoid dull, chalky, muddy, or cheap-plastic color
   - bright seamless white or very light neutral studio background, large softbox lighting, gentle fill light, clean rim highlights, soft form shading, and restrained local ambient occlusion without a cast ground shadow
   - carefully exposed product-render lighting: luminous surfaces, readable forms, dimensional shadows, and no harsh hotspots or crushed blacks
   - compact toy-model proportions, clear layered construction, and polished collectible-object presentation with an editorial C4D finish
6. Match the uploaded photo's original camera direction. First determine whether the source is near-front or genuinely angled. For a near-front source, use a clean frontal or near-frontal product view with stable verticals and natural, shallow depth; do not invent a three-quarter angle, exaggerated side thickness, fixed interior reveal, or cube-like cutaway. For a genuinely angled source, preserve the visible front, side, interior, and front-to-back relationships. In both cases, use parallel perspective to correct keystone distortion, slanted verticals, and obvious wide-angle distortion without flattening genuine three-dimensional structure.
7. Compose the image from the complete outer bounds of the entire model, not only its central subject: include the widest base, side structures, railings, lanterns, projections, accessories, and any other peripheral elements. Fit this complete outer bounding box before choosing the final scale. Center it horizontally and vertically, keep every outer structure fully inside the frame, reserve at least 20% clear background space on every side, and target a complete-model height of roughly 60–70% of the canvas. Keep the complete model within roughly 60–65% of the canvas width when the subject allows. If the source aspect ratio is too tight, expand the canvas horizontally or choose a wider product-display composition instead of cropping or enlarging the model to the edges.
8. After generation, inspect the complete outer silhouette independently from the material and subject. If any left, right, top, or bottom structure is clipped, touching the edge, or outside the intended margin, perform a second composition-only correction by expanding the background canvas, reframing, or scaling down the complete model. Do not change the subject, camera direction, model structure, material, lighting, or readable text during this correction.
9. Avoid photorealistic surfaces, flat illustration, generic architectural visualization, hard sterile CGI, clay, LEGO construction, metallic gloss, harsh outlines, excessive grain, and unnecessary background clutter.
10. Return the generated image as the primary result. Briefly mention that the original composition and subject were retained where possible; do not add a long explanation unless the user asks.

## Model construction and fidelity

- Treat the source as a design reference for a complete miniature model, not as a photograph to be preserved with a material filter.
- Rebuild all scene-defining objects as connected 3D forms with consistent scale, believable thickness, layered construction, and clear front-to-back relationships.
- Keep the original viewpoint, composition, relative scale, and important spatial relationships unless the user explicitly requests a new composition.
- Compose from the complete outer bounds of the entire model, including the widest base, side structures, railings, lanterns, projections, and accessories. The leftmost and rightmost points must be clearly inside the frame with at least 20% clear background space on each side. Center the model horizontally and vertically, and target a complete-model height of roughly 60–70% of the canvas. Keep the complete model within roughly 60–65% of the canvas width when the subject allows. No part of any object may touch or be cropped by the image boundary. If the model would become too small, expand the canvas horizontally, use a wider product-display composition, or render at a larger resolution rather than reducing the margin or cropping the model.
- Before finalizing, inspect the complete outer silhouette independently from the material and subject. If any side has less than 20% clear space, if the model height is substantially outside the 60–70% target, if the model is visually crowded, or if any major structure is clipped, perform a composition-only correction: expand the background canvas, reframe, or scale down the complete model. Do not regenerate or redesign the subject, material, lighting, camera direction, or readable text just to fix framing.
- Preserve large, readable text and logos as closely as possible. When source text is too small to reproduce reliably, preserve its placement and visual shape rather than confidently inventing new wording.
- If the photo contains a person, preserve identity and pose without exaggerating facial features or changing age, unless the user explicitly requests a character redesign.
- If a supplied reference shows a 3D model, use it to guide the model presentation, proportions, framing, material finish, and lighting; do not copy unrelated subject matter from it.
- Use a professional studio-lighting setup: a large softbox key light, broad front or side fill, subtle top or rim light, delicate controlled reflections, soft form shading between modeled parts, restrained local ambient occlusion, and carefully balanced exposure. Keep the background bright and clean while preserving dimensional form and material highlights. Do not add a cast shadow on the ground, a dark floor patch, or a heavy grounding effect beneath the model.

## Optional collectible base

Offer this as an optional presentation mode when the user asks for a collectible model, designer toy, or product-style display. Do not add it by default when the user only asks for a C4D conversion.

- If the user chooses no base, keep the transformed scene on its natural ground or use a clean neutral background.
- If the user chooses a base, place the complete 3D model on a clearly separate, thin, low-profile circular display disc that is slightly wider than the model, leaving balanced breathing room around it.
- Use a pristine bright silver titanium or stainless-steel finish with precise machining, smooth rounded edges, subtle satin micro-brushing, and controlled highlights. Avoid dirt, grime, stains, rust, scratches, dents, rough grain, or distressed patina.
- Integrate the title and collection number as small, flush laser engraving directly into the front curve of the metal surface. Do not use a raised plaque, attached badge, border, screws, packaging, transparent case, or accessory compartments.
- Keep the base visually quiet and let the rendered model remain the hero. If the user has not specified whether to add it, ask them to choose between no base and the independent metal display base.

## Prompt template

Use the following direction as a base, adapting it to the uploaded subject:

> Rebuild the uploaded image as a complete, coherent Cinema 4D-style collectible 3D model. Keep the same subject, viewpoint, composition, recognizable silhouette, important objects, relative layout, and distinctive markings. Reconstruct every major visible element as dimensional modeled geometry with clear layered construction, believable thickness, rounded bevels, soft molded edges, consistent toy-model proportions, and natural depth. Replace clay with an exceptionally refined soft rubber, silicone, or satin-vinyl material: ultra-fine tactile microtexture, delicate roughness variation, gentle elasticity, silky soft edge roll-off, subtle color transitions, and smooth controlled highlights. Use vivid clean colors with a slightly luminous premium finish. Light it like a high-end C4D product image with a bright seamless white or pale neutral background, large softbox key light, broad fill light, delicate rim highlights, soft form shading between modeled parts, restrained local ambient occlusion, luminous surfaces, and carefully balanced exposure. Keep the model cleanly presented against the background without a cast ground shadow, dark floor patch, or heavy grounding effect. Make it feel like a meticulously crafted, bright, delicate, cheerful, dimensional C4D collectible model with premium editorial polish. Preserve readable signs and markings as closely as possible. Do not turn it into a photograph with a filter, a flat illustration, a generic architectural visualization, hard sterile CGI, clay, LEGO, dull plastic, or a different scene.
> Match the uploaded photo's original camera direction. Determine whether the source is near-front or genuinely angled. If it is near-front, normalize it into a stable frontal or near-frontal parallel perspective with a level base, corrected horizontal and vertical lines, and natural shallow depth; do not preserve accidental tilt, convergence, or skew, and do not invent a three-quarter angle or exaggerated side thickness. If it is genuinely angled, preserve its meaningful visible front, side, interior, and front-to-back relationships while using parallel perspective. Do not use an orthographic projection or flatten the model into a single plane. First fit the complete outer bounding box of the entire model, including the widest base, side structures, railings, lanterns, projections, and accessories. Keep the complete leftmost and rightmost points clearly inside the frame with at least 20% clear background space on each side; center the model, target a complete-model height of roughly 60–70%, and keep the model within roughly 60–65% of the canvas width when the subject allows. If the aspect ratio is too tight, expand the canvas horizontally or choose a wider composition instead of cropping or enlarging the model to the edges. After generation, perform a composition-only check and, if needed, expand the background, reframe, or scale down the complete model without changing the subject, camera, material, lighting, or text. Use a bright high-end studio-lighting setup with a large softbox key, broad fill, subtle rim light, delicate reflections, soft form shading between modeled parts, restrained local ambient occlusion, and balanced exposure. Do not add a cast ground shadow, dark floor patch, or heavy grounding effect beneath the model.

When the user selects the optional collectible base, append: “Place the rendered model on a clearly separate, slightly oversized, very thin circular display disc made of pristine bright silver titanium or stainless steel. Use an immaculate precision-machined finish with subtle satin micro-brushing, smooth rounded edges, and clean controlled highlights. Add only flush laser engraving directly into the front curve of the metal surface for the title and collection number. No raised plaque, attached badge, screws, rectangular base, thick pedestal, packaging, or plastic case.”

## Avoid

- Do not leave the source looking like a real photograph with a generic CGI filter; the output must read as a complete standalone 3D model.
- Do not use flat vector art, rough low-poly geometry, clay, LEGO construction, wireframe, or a generic architectural visualization unless explicitly requested.
- Do not make every surface equally glossy. Keep the overall material language soft rubber, silicone, or satin vinyl, with fine microtexture, soft edge highlights, controlled reflections, and a premium molded finish rather than hard plastic shine.
- Do not use flat lighting, gray muddy colors, harsh directional shadows, blown-out highlights, or a dark dramatic architectural-render look. The result should feel bright, delicate, polished, and carefully lit like a premium C4D product image.
- Do not add a cast shadow on the ground, a dark floor patch, or a heavy grounding effect beneath the model. Keep the background clean and unobstructed.
- Do not allow less than 20% clear space on any side when the subject can be reframed to fit, and do not solve insufficient margins by cropping the source or enlarging the model; expand the canvas or reduce the model scale instead.
- Do not make the complete model so small that it loses visual focus, or so large that it breaks the 20% safety margins or the 60–70% height target.
- Do not measure margins from the central building alone. Include every peripheral part in the outer bounding box, especially wide bases, side structures, railings, lanterns, signs, projections, and accessories.
- If the first result violates the outer-boundary rule, correct only the composition in a second pass. Do not alter the subject, camera direction, model structure, material, lighting, or text while fixing the frame.
- Do not add unrelated objects, redesign the scene, invent prominent text, or change the subject's identity.
- Avoid excessive bloom, lens flare, chromatic aberration, harsh outlines, dramatic lens distortion, heavy grain, muddy shadows, clipped highlights, and overdone depth of field.
- Do not add a display base by default when the user asks only for a material conversion and has not requested a collectible presentation.

## Interaction rules

- Treat requests for a different rubber finish, color palette, background, camera angle, level of detail, or degree of realism as overrides only when they do not conflict with the user's requested C4D-model direction.
- If the user asks for a more stylized or more realistic result, adjust geometry, material response, lighting, and detail while retaining the complete collectible-model requirement.
- If text is too small to preserve reliably, keep its placement and visual structure rather than confidently inventing wording.
