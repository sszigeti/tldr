#FSWEBCAM

> small and simple webcam for *nix

- Take a picture

`fswebcam {{filename}}`

- Take a picture with custom resolution

`fswebcam -r {{width}}x{{height}} {{filename}}`

- Take a picture from selected device(Default is /dev/vidoe0)

`fswebcam -d {{device}} {{filename}}`

- Take a picture with timestamp(timestamp string is formatted by strftime)

`fswebcam --timestamp {{timestamp}} {{filename}}`
