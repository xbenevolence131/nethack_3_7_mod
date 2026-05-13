# Project Notes

- Windows vanilla tile builds should use the external 24px `classic24.bmp`
  spritesheet as the baseline tile sheet. Configure `NetHackW` with
  `tile_file:classic24.bmp`, `tile_width:24`, and `tile_height:24` rather than
  relying on the embedded 16px `win/win32/tiles.bmp` fallback.
