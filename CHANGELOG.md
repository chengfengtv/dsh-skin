# Changelog

## 0.2.2

- Apply opacity through a dedicated CSS token layer so it updates reliably
  without recursively publishing Harness theme changes.
- Keep blur-only updates coalesced without rebuilding theme state.

## 0.2.1

- Keep opacity and blur sliders responsive by coalescing rapid updates.
- Avoid reassigning the wallpaper data URL during slider movement.
- Skip theme-token reconstruction when only the blur radius changes.
- Preserve correct behavior after removing and reselecting a wallpaper.
