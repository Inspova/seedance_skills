# Camera

## Purpose

This module governs all camera-related decisions.

Its goal is to produce camera work that is intentional, physically believable, and emotionally supportive of the story.

The camera should never move, frame, or choose a lens randomly. Every camera decision must reinforce:

- narrative intent
- emotional focus
- subject readability
- spatial clarity
- cinematic realism

This module determines:

- whether the camera should move
- how the camera should move
- how the subject should be framed
- which lens characteristics should be used
- which perspective best supports the scene
- how camera continuity is maintained

---

# Camera Philosophy

Treat the camera as a professional cinematographer would.

The camera exists in physical space and should behave as if operated by a deliberate camera operator.

Every camera choice should answer:

"What does this camera decision help the audience understand or feel?"

Avoid camera choices that exist only to appear cinematic.

Cinematic does not mean:

- excessive movement
- unnecessary lens changes
- dramatic angles without purpose
- constant reframing

Cinematic means every visual decision has intention.

---

# Camera Decision Hierarchy

When creating camera direction, prioritize decisions in this order:

1. Storytelling purpose
2. Subject clarity
3. Emotional impact
4. Spatial understanding
5. Camera realism
6. Visual style

Lower priorities must not compromise higher priorities.

---

# Camera Decision Process

Before defining camera behavior, analyze the scene.

## Step 1 — Determine Narrative Purpose

Identify the main purpose of the shot.

Possible purposes:

- introduce a character
- reveal information
- create intimacy
- increase tension
- show scale
- follow action
- observe naturally
- emphasize emotion
- create mystery

The camera choice should support this purpose.

---

## Step 2 — Decide Whether Movement Is Necessary

Ask:

"Does camera movement improve the storytelling?"

If no:

Use:

- static camera
- minimal movement
- observational framing

If yes:

Consult:

`movement.md`

Choose the movement technique that best supports the emotional goal.

Examples:

- Push In → increase emotional intensity
- Tracking → follow subject movement
- Crane → reveal scale or transition perspective
- Pan → reveal information horizontally
- Tilt → reveal vertical relationships

---

## Step 3 — Select Framing

Determine how close the audience should feel to the subject.

Consult:

`framing.md`

Use:

### Wide framing

When:

- environment matters
- scale is important
- isolation is desired

Examples:

- Extreme Wide Shot
- Wide Shot

---

### Medium framing

When:

- character and environment both matter
- natural interaction is required

Examples:

- Medium Wide Shot
- Medium Shot

Default choice when no emotional direction is provided.

---

### Close framing

When:

- emotion is important
- psychological connection is required

Examples:

- Medium Close-Up
- Close-Up
- Extreme Close-Up

---

## Step 4 — Select Lens Characteristics

Determine how the audience should perceive space.

Consult:

`lenses.md`

Lens selection should support framing and emotion.

Use:

### Wide lenses

When:

- environment matters
- immersion is desired
- spatial relationships are important

Examples:

24mm–35mm

---

### Normal lenses

When:

- realism is desired
- the camera should feel invisible

Example:

50mm

---

### Telephoto lenses

When:

- emotional isolation is desired
- background separation is important

Example:

85mm

---

# Camera Contract

All camera behavior must obey:

## Physical Continuity

The camera must:

- exist within continuous three-dimensional space
- maintain believable position changes
- preserve spatial orientation
- move with realistic inertia

Avoid:

- impossible jumps
- unexplained camera teleportation
- sudden direction changes
- inconsistent perspective

---

## Movement Continuity

During movement:

Maintain:

- consistent speed
- consistent direction
- stable subject relationship
- believable acceleration and deceleration

Avoid changing multiple camera variables simultaneously unless intentionally motivated.

---

## Subject Relationship

The camera must maintain awareness of:

- subject position
- screen direction
- distance from subject
- emotional relationship

The camera should not lose the subject unless the loss of visibility is intentional.

---

# Camera Combinations

Camera elements should work together.

Do not select movement, framing, lens, and angle independently.

Examples:

## Emotional Revelation

Possible combination:

- slow Push In
- Close-Up
- 85mm lens
- shallow depth of field

Purpose:

Increase emotional intimacy.

---

## Environmental Introduction

Possible combination:

- slow Crane or Dolly Out
- Wide Shot
- 24mm lens

Purpose:

Reveal scale and location.

---

## Natural Observation

Possible combination:

- static camera
- Medium Shot
- 50mm lens

Purpose:

Create realistic documentary feeling.

---

# Continuity Rules

Throughout a shot, preserve:

- camera direction
- lens characteristics
- framing logic
- movement style
- horizon level
- spatial relationships

Avoid unnecessary changes.

A camera should feel like one continuous physical observer.

---

# Conflict Resolution

When instructions conflict, prioritize:

1. Subject readability
2. Narrative purpose
3. Spatial continuity
4. Physical realism
5. Cinematic style
6. Decorative effects

Ignore lower-priority instructions if necessary.

---

# Default Camera Behavior

When no camera direction is provided:

Use:

- static or minimal movement
- Medium Shot framing
- eye-level perspective
- 50mm lens characteristics
- natural camera distance

The default camera should feel invisible.

It should observe rather than perform.

---

# Output Format

When generating camera instructions, specify:

- movement
- framing
- lens
- angle
- speed
- direction
- emotional purpose

Recommended format:

```
Camera:
[Movement]

Framing:
[Shot size]

Lens:
[Focal length or lens characteristic]

Purpose:
[Emotional or narrative reason]
```

Avoid describing camera techniques without explaining their purpose.

---

# Library References

When making camera decisions, consult:

- `movement.md` for camera motion techniques
- `framing.md` for shot composition and emotional distance
- `lenses.md` for perspective and optical characteristics
- `angles.md` for viewpoint and psychological effect

These libraries provide the available techniques.

This skill file determines how and when to use them.