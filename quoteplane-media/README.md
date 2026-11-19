# QuotePlane media (public)

Finished QuotePlane Facebook videos. They are public on the QuotePlane Page anyway, so they live in this public repo where the browser can load them.
Not part of the Avion content agent's work: the Avion agent can ignore this folder.

Each folder `YYYY-MM-DD-slug/` holds:
- `video.mp4`: the finished video (1080×1920, 30 fps, AAC)
- `video.png`: the same bytes packed into a lossless PNG (header `QPV1` + uint32 length), which the posting run decodes in the browser to upload the file

Ideas, scripts and source code live in the private repo `moonnstarr/QuotePlane_Automation` under `videos/`.
