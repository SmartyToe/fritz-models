# Fritz AI Models

A collection of machine and deep learning models designed to run on mobile devices.

Models in this repository contain code and utilities for training models as well as converting them to mobile-friendly formats like Core ML, TensorFlow Mobile, and TensorFlow Lite.

## Fritz AI

Fritz AI is the machine learning platform for iOS and Android developers. Teach your mobile apps to see, hear, sense, and think. Get started quickly with [our pre-trained APIs](https://www.fritz.ai/product/pretrained.html?utm_source=github&utm_campaign=fritz-models, or use [our end-to-end platform](https://www.fritz.ai/product/platform.html?utm_source=github&utm_campaign=fritz-models) to build and deploy your own custom models.

If you're ready to start building mobile apps powered by ML, [sign up](https://www.fritz.ai/pricing/?utm_source=github&utm_campaign=fritz-models) for a free Fritz AI account.

## Models

- [Image Labeling](image_labeling/): Label images based on their content.
- [Object Detection](object_detection/): Localize and label objects in an image with a bounding box.
- [Style Transfer](style_transfer/): Transform images into works of art by transfering the style of one image onto the content of another.
- [Image Segmentation](image_segmentation/): Semantic segmentation of images. Assign a value to each pixel of an image corresponding to the type of object it belongs to.
- [Create ML Playgrounds](create_ml_playgrounds/): A series of playgrounds for training models with Apple's Create ML tool

Don't see the model you're looking for? Open an issue and let us know!

## Add to your app

To see live demonstrations of these models running on-device, the Heartbeat App is available in both the [App Store](https://itunes.apple.com/us/app/heartbeat-by-fritz/id1325206416?mt=8) ([source code](https://github.com/fritzlabs/heartbeat-ios)) and [Play Store](https://play.google.com/store/apps/details?id=ai.fritz.heartbeat) ([source code](https://github.com/fritzlabs/heartbeat-android)).

If you'd like to incorporate any of these models or versions you've trained into your own app, head over to [Fritz](https://fritz.ai/?utm_source=github&utm_campaign=fritz-models). SDKs are available for both iOS and Android.

## A note about large files

Large files like model checkpoints, data, and archives of compiled code are managed via `git lfs`. You need to have Git LFS installed in order to download these files. Installation instructions are available [here](https://github.com/git-lfs/git-lfs#getting-started).

If you have Git LFS installed, large files will download automatically by default. This can take a while and require a good connection. To clone this repository without downloading the model checkpoints, you can run:

```
GIT_LFS_SKIP_SMUDGE=1 git clone ...
```

## Stay in touch with Fritz AI

To keep tabs on what we’re up to, and for an inside look at the opportunities, challenges, and tools for mobile machine learning, subscribe to the [Fritz AI Newsletter](https://www.fritz.ai/newsletter?utm_campaign=fritz-models&utm_source=github).

## Join the community

[Heartbeat](https://heartbeat.fritz.ai/?utm_source=github&utm_campaign=fritz-models) is a community of developers interested in the intersection of mobile and machine learning. [Chat with us in Slack](https://fritz.ai/slack?utm_source=github&utm_campaign=fritz-models), and stay up to date on industry news, trends, and more by subscribing to [Deep Learning Weekly](https://www.deeplearningweekly.com/?utm_campaign=fritz-models&utm_source=github).

## Help

For any questions or issues, you can:

- Submit an issue on this repo
- Visit our [Support Forum](https://support.fritz.ai/?utm_source=github&utm_campaign=fritz-models)
- Message us directly in [Slack](https://fritz.ai/slack?utm_source=github&utm_campaign=fritz-models)
