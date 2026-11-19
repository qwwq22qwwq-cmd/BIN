---
name: bin-interior-styling
description: >
  Carefully edit interior-design images while preserving the supplied design,
  geometry, camera, composition, materials, and lighting. Use for localized
  render edits, material changes, restrained styling, and style transfer onto
  a new clay or massing render.
---

# bin-interior-styling

## CORE PRINCIPLE

**Preservation has priority over styling.** The supplied base image is the authority
for the existing design. Follow the user's explicit change request. Do not redesign,
reinterpret, or improve anything the user did not ask to change.

The goal is a faithful, photorealistic edit of the intended design—not a new design
that merely resembles it.

## RULE 01 — SOURCE OF TRUTH

Use this hierarchy:

1. The user's explicit instructions define exactly what may change.
2. The current base image controls existing room geometry, layout, fixed elements,
   camera, perspective, and composition.
3. Reference images guide only the aspect assigned to them: material appearance,
   color, furniture detail, or atmosphere. A reference does not authorize copying
   unrelated layout or objects.

When older finished renders are supplied with a new clay/massing image:
- The new clay/massing image controls geometry, openings, built-ins, furniture
  positions, camera, and composition.
- Older renders guide style, material language, and atmosphere only.
- Do not transfer walls, doors, windows, cabinetry, or furniture from an older
  render unless explicitly requested.

A marked region is the edit boundary.

## RULE 02 — DESIGN AND GEOMETRY LOCK

Unless explicitly requested, preserve:
- Room dimensions, wall positions/thicknesses, openings, and circulation.
- Ceiling height, beams, soffits, coves, curves, and ceiling details.
- Door/window positions, sizes, frames, and opening directions.
- Built-in cabinetry, shelves, niches, joinery, and dimensions.
- Existing furniture identity, position, orientation, proportions, and silhouette.
- Floor layout, flooring direction, skirting, and transitions.
- Existing materials, colors, textures, and finishes.
- Lighting fixtures, positions, and arrangement.
- Camera position, angle, perspective, framing, composition, and aspect ratio.

Do not add, remove, move, resize, straighten, simplify, or reinterpret architectural
features unless directly requested. Curves, radii, and distinctive geometry must
remain consistent with the base image.

## RULE 03 — LOCALIZED EDITS ONLY

- Change only the object, surface, or region specified by the user.
- Keep every unmarked area visually unchanged.
- Do not let a local edit spill onto adjacent walls, floors, ceilings, furniture,
  windows, or cabinetry.
- Preserve an object's dimensions, placement, and orientation when only its
  material, color, or finish is being changed.
- When removing an item, remove only the named item—not its backing structure,
  adjacent trim, or surrounding construction unless requested.
- When moving an item, move only that item.

If the requested edit cannot be isolated without affecting important geometry,
ask one concise clarification rather than guessing.

## RULE 04 — RESTRAINED STYLING

Styling remains secondary to the architecture and the user's design.

Small decorative elements may include books, vases, plants, cushions, throws, and
small tabletop objects—but only add, remove, or change them when the user's request
allows it.

Do not autonomously introduce:
- Large furniture or replacement furniture.
- Rugs or large floor coverings.
- Murals, feature walls, or new architectural cladding.
- Main light fixtures, new ceiling lights, or prominent lighting systems.
- Extra cabinetry, shelving, niches, partitions, or decorative construction.

Do not fill empty space simply because it looks empty. Negative space is part of
the composition.

## RULE 05 — MATERIAL AND COLOR ACCURACY

When a material or color change is requested:
- Apply it only to the named surface or object.
- Preserve underlying geometry, panel boundaries, joints, edges, and reveals.
- Match the reference's color, texture, relief, sheen, and visual scale as closely
  as possible.
- Respect stated physical module dimensions (for example, 50 × 50 cm or
  70 × 40 cm per piece).
- Respect stated installation direction, such as vertical grain, horizontal grain,
  or a specified pattern orientation.
- Keep seams and repetition believable at the actual room scale.
- Do not change neighboring materials to coordinate with the new material.

A material reference is not permission to change the wall size, TV position, door,
shelving, or any other part of the scene.

## RULE 06 — LIGHTING AND PHOTOREALISM

Preserve the base image's lighting direction, time-of-day impression, shadow
placement, exposure, contrast, and tonal character unless lighting changes are
requested.

Target:
- Natural, believable interior light.
- Realistic material response, texture, reflections, and contact shadows.
- Warm but controlled white balance; avoid excessive yellow or orange cast.
- Low-to-medium saturation and restrained contrast.
- High-end residential interior photography rather than an artificial CGI look.

Do not add dramatic sunbeams, glowing edges, extra light sources, heavy bloom,
filters, or exaggerated reflections without instruction.

## RULE 07 — CAMERA AND DELIVERY

- Keep the original camera angle, perspective, framing, and aspect ratio.
- Do not crop, rotate, stretch, or recompose unless requested.
- Do not introduce text, labels, borders, logos, or watermarks.
- Target 4K output where the image tool supports it.
- Prefer PNG for final delivery when available.
- Never claim native 4K unless it was actually produced at that resolution. Disclose
  limitations if the tool cannot meet the requested resolution or framing.

## TWO-STEP WORKFLOW

### Step 1 — Analyze and lock
Identify the base image, exact target, marked edit boundary, and role of each
reference. Record what must remain unchanged. Confirm material dimensions,
direction, and pattern scale when supplied.

### Step 2 — Apply the local edit and verify
Make only the requested change. Compare the result against the base image:
geometry, object position, camera, composition, lighting, adjacent materials, and
unmarked areas must remain consistent. Correct unintended drift before presenting
the result. State any remaining limitation plainly.

## RESPONSE STANDARD

Be concise. State what changed and, where relevant, what was deliberately
preserved. Do not claim exact dimensional tiling, pixel-level preservation, or
native 4K unless actually verified.
