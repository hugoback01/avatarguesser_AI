# Avatar Episode Guesser

A small machine learning project that predicts which *Avatar: The Last Airbender* episode a screenshot comes from.

## Demo

Try it here:

https://avatarguesser.vercel.app/

## About

The model is trained on screenshots extracted from episodes of *Avatar: The Last Airbender*. Given a frame from the show, it attempts to identify the correct episode.

While the model achieves nearly **100% accuracy on the training set**, performance on unseen images is around **50%+**, illustrating how difficult it can be to avoid overfitting in image classification tasks.

## Results

| Dataset | Accuracy |
|----------|----------|
| Training | ~100% |
| Test | 50%+ |

## Challenges

- Similar scenes appear across multiple episodes.
- Consecutive episodes often share visual characteristics.
- The dataset is relatively small compared to modern computer vision benchmarks.
- Avoiding overfitting is much harder than achieving high training accuracy.

## Future Improvements

- Data augmentation
- Transfer learning with larger pretrained models
- Better validation and test splits
- Additional training data
