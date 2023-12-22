# Viewport Scaling in Godot

#gamedev #godot

## HUD and UI

Use a CanvasLayer for HUD! This enables full rect fitting for the viewport which adds a lot of responsiveness to different resolution, provided you're using proper anchor points.

## 2D Backgrounds

This one is more tricky, because you might have different use cases.
|Camera|Image|Proposal|Example|
|---|---|---|---|
|Static|Static, Cover|TextureRect or Sprite2D covering viewport| [[creating-pong-godot|Pong]] |
|Pans|[Parallax](parallax-godot.md)|TextureRect or Sprite2D, manually designed to cover???| ??? |

