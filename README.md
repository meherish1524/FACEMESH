# FACEMESH



![Screen_Shot](https://github.com/meherish1524/FACEMESH/blob/main/output.jpeg?raw=true)


## Overview

MediaPipe Face Mesh is a face geometry solution that estimates 468 3D face landmarks in real-time even on mobile devices. It employs machine learning (ML) to infer the 3D surface geometry, requiring only a single camera input without the need for a dedicated depth sensor. Utilizing lightweight model architectures together with GPU acceleration throughout the pipeline, the solution delivers real-time performance critical for live experiences.


## ML Pipeline
Our ML pipeline consists of two real-time deep neural network models that work together: A detector that operates on the full image and computes face locations and a 3D face landmark model that operates on those locations and predicts the approximate surface geometry via regression. Having the face accurately cropped drastically reduces the need for common data augmentations like affine transformations consisting of rotations, translation and scale changes

## Built With

* Python 3.6
* cv2
* mediapipe

## Contributing

1. Fork it
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request

## Authors

Manchala Meherish

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/meherish1524/Twitter_Sentiment_Analysis1524/blob/main/LICENSE.txt) file for details
