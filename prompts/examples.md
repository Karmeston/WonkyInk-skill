# WonkyInk Prompt Examples

WonkyInk is designed to work with short gear commands. The gear already contains the style decisions.

## Basic usage

```text
WonkyInk Gear 1
```

```text
WonkyInk Gear 3
```

```text
WonkyInk Gear 5
```

## Scene examples

### Portrait

```text
WonkyInk Gear 2
```

Goal:
- preserve facial attitude
- keep expression anchors
- simplify facial structure, not emotion

### Street scene

```text
WonkyInk Gear 4
```

Goal:
- preserve environmental richness
- keep repeated objects
- avoid turning the scene into a clean sketch

### Dense interior

```text
WonkyInk Gear 5
```

Goal:
- keep many background cues
- preserve clutter rhythm
- keep every local object crude

### Minimal doodle

```text
WonkyInk Gear 1
```

Goal:
- maximum clumsiness
- minimum local completion
- background still exists

## Natural language mapping

Examples:

"画得更笨一点" → lower gear

"保留更多环境细节，但不要变精细" → higher gear

"像灵魂画手随手画的" → WonkyInk style
