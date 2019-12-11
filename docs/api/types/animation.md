# Animation

## Description

This object represents an animation file (GIF or H.264/MPEG-4 AVC video without sound).


## Attributes

| Name | Type | Description |
| - | - | - |
| `file_id` | `#!python str` | Identifier for this file |
| `width` | `#!python int` | Video width as defined by sender |
| `height` | `#!python int` | Video height as defined by sender |
| `duration` | `#!python int` | Duration of the video in seconds as defined by sender |
| `thumb` | `#!python Optional[PhotoSize]` | Optional. Animation thumbnail as defined by sender |
| `file_name` | `#!python Optional[str]` | Optional. Original animation filename as defined by sender |
| `mime_type` | `#!python Optional[str]` | Optional. MIME type of the file as defined by sender |
| `file_size` | `#!python Optional[int]` | Optional. File size |



## Location

- `from aiogram.types import Animation`
- `from aiogram.api.types import Animation`
- `from aiogram.api.types.animation import Animation`

## Related pages:

- [Official documentation](https://core.telegram.org/bots/api#animation)
- [aiogram.types.PhotoSize](../types/photo_size.md)