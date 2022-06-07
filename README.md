# EgyPyCurrency

A computer-vision-based project that detects Egyptian banknotes and classifies them using ORB (Oriented FAST and Rotated BRIEF) algorithm.


**(This code is valid for 1, 5, 10, 20, 50, 100, 200 LE)**

You can replace the dataset for your own banknotes, by replacing the reference images in `reference` directory by your desired ones, while preserving the same naming convention. Use `Space` to capture images and `ESC` to quit and explore the results.
The main purpose behind choosing ORB, is that it is rotation invariant, noise resistant and partially scale in variant.

#### The following Libraries are used in the project:
- OpenCV (version 4.5.1)
- matplotlib (version 3.4.3)
