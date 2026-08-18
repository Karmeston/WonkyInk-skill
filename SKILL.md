---
name: wonkyink
description: Redraw an existing image into a deliberately low-skill black gel-pen WonkyInk on white paper. Preserve source composition, subject identity, scene identity, and prominent facial attitude. Use integrated gears where lower gears become simpler and clumsier, but never collapse into a floating cutout with no environment. Suppress sketch polish, keep contours visibly irregular, and keep descriptive text off by default.
---

# WonkyInk — v1.0.0

Transform existing images into deliberately imperfect black gel-pen doodles.

Core principles:

> Keep the scene. Kill the polish.

> The line should look hand-guessed, not hand-traced.

> Few marks per object, many objects per scene.

Preserve:
- source composition
- subject identity
- scene identity
- important expressions
- environmental anchors

Avoid:
- polished sketches
- clean tracing
- systematic hatching
- realistic rendering
- excessive added text

## Gear System

Gear controls semantic richness and clumsiness together.

### Gear 1
Very crude. Keep subject and minimum environment anchors. Compress background, never delete it.

### Gear 2
Loose crude doodle. Preserve main structures and support objects.

### Gear 3
Balanced default. Preserve full scene structure with low local completion.

### Gear 4
Rich crude mode. Add more environmental fragments and repeated details without increasing drawing skill.

### Gear 5
Dense crude mode. Maximum observed information, minimum local polish.

## Background Rule

Lower gear compresses the background. It does not delete the background.

Every occupied region should retain meaningful cues.

## Contour Rule

Contours should be:
- slightly shaky
- uneven
- hand-guessed
- imperfectly closed
- mildly asymmetric
- occasionally restarted

Do not create clean vector-like outlines.

## Facial Expression Rule

Simplify facial structure, not facial attitude.

Preserve:
- gaze
- eyelid shape
- eyebrow angle
- mouth attitude
- head tilt

## Text Rule

Added descriptive text is disabled by default.

Only preserve or simplify existing signs and labels when useful.

## Final Target

Recognizable scene, visible environment, irregular human contours, rich observation, dumb technique, no sketch polish.
