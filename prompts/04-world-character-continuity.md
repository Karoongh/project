# 04 — Visual World & Character Continuity Engine

## Purpose
Create a persistent Character Bible and World Bible so multiple generated images belong to the same visual universe.

## Character Bible
Maintain:
- Character ID
- Public/project name
- Face shape and proportions
- Eyes, nose, lips, jaw/chin
- Skin tone and texture
- Hair and beard/facial hair
- Age appearance
- Height
- Body proportions/build
- Distinctive features
- Typical posture and gestures
- Clothing history
- Accessories

If user-provided reference photos are available, use them as identity reference. Clothing may change; identity-defining characteristics should remain stable.

Never invent real credentials, employment history, income, trading performance or professional achievements and present them as factual.

## World Bible
Record:
- World ID
- Country/city if intentionally specified
- Building type and apartment floor
- Floor plan
- Room dimensions
- Ceiling height
- Window/door dimensions and positions
- Flooring and wall materials
- Furniture
- Desk, chair, monitor, laptop, smartphone, keyboard/mouse dimensions
- Lighting fixtures
- Balcony dimensions
- Exterior architecture/view

Use real-world physical scale and plausible relative dimensions.

## Camera system
Example persistent IDs:
- CAM-01 desk/front
- CAM-02 desk/side
- CAM-03 wide office
- CAM-04 living room
- CAM-05 kitchen
- CAM-06 bedroom
- CAM-07 balcony
- CAM-08 exterior

Each camera stores position, height, orientation, focal-length feel, field of view and typical framing.

Once the Bible exists, the user can request only location and camera.

## Continuity rules
Preserve architecture, room proportions, furniture locations unless intentionally changed, object dimensions, character identity and known exterior landmarks.

Allow controlled variation in clothing, lighting, weather, activity, camera, composition and small movable objects.

## Time/light continuity
Exterior light should broadly match the represented market/trade time and date. Astronomical precision is unnecessary unless specifically requested.

## Output
World ID, Character ID, location, camera, architecture, object dimensions, character state, lighting, continuity requirements and forbidden changes.
