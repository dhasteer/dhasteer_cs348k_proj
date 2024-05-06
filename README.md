# Video Hypercompression

## Goals
**Primary Goal**: Explore whether and how replacing I-frames of video with generative AI-compatible information (ie. text+sketch) for reconstruction can be processed for computer vision tasks.

**Stretch Goal**: Modify H.264 bitstream appropriately for this format.

**Stretchier Goal**: Add more control to the I-frame reconstruction for better accuracy results and even human-satisfiable content.

## Defining Success
1. Developing infrastructure to automatically "encode" video input I-frames into relevant generative AI-compatible controls / information and use that data to "decode" the original video.
2. Being able to run computer vision tasks on the decoded video I-frames, without significant degredation of accuracy.

## Dataset
Massive amounts of video data, paired with computer vision tasks, points to the driving / traffic use case (as a task that would benefit greatly from video hypercompression tuned for CV). I plan on using this [Driving Dataset](https://github.com/KuntaiDu/dds).

## Relevant Papers / Projects
From what I've seen, no one has yet approached video generation from the lens of data compression. I plan to leverage work and models in the image/video generation area (some listed below) for these purposes.
- [AnimateDiff](https://animatediff.github.io/)
- [Text+Sketch: Image Compression at Ultra Low Rates](https://arxiv.org/pdf/2307.01944)
- [Survey on Video Diffusion Models](https://arxiv.org/pdf/2310.10647)
