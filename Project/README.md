## What you’ll get here?
- `Python` version 3.7.9
- Configured `Jupyter Lab` (Image size 1.83 GB)
- Installed Libraries (Most of the ML libraries including `tensorflow 2.3.0` for DL)
- No need to worry about dependencies
- Root privileges which means you can also install libraries if you want or required.
- Some public datasets
- `Demo codes` from almost all crucial ML concepts

## Prerequisite
- Only `Docker  >= 19.03.12`

## Tips and Tricks
The base image is python version 3.7.9. However I did that because I felt suitable. If you want some other base image, you don't need to research again. You can just leverage the --build-arg flag during docker build.

```docker build --build-arg BASE_CONTAINER=<Your preferred base image> -t <your preferred tag> .```