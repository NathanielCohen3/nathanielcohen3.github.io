og-card-2.jpg              -> 1200x630 link-preview card (name + AURA frames)
thumbs/aura.jpg        -> poster for static/videos/aura.mp4 (its first frame)
thumbs/slicedit.jpg    -> poster for static/videos/slicedit.mp4 (its first frame)
profile.jpg            -> optional portrait; the .avatar block was removed, see git history

The publication thumbnails are looping muted <video> clips; each poster above must
stay in sync with its clip (ffmpeg -i <clip> -frames:v 1 <poster>).
