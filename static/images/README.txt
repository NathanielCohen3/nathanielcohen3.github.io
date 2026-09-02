og-card-3.jpg          -> 2400x1260 link-preview card (2x, so LinkedIn/Retina downscaling stays sharp)
thumbs/aura.jpg        -> poster for static/videos/aura.mp4 (its first frame)
thumbs/slicedit.jpg    -> poster for static/videos/slicedit.mp4 (its first frame)
profile.jpg            -> optional portrait; the .avatar block was removed, see git history

The publication thumbnails are looping muted <video> clips; each poster above must
stay in sync with its clip (ffmpeg -i <clip> -frames:v 1 <poster>).
