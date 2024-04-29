# Image Similarity Checker

This Java program calculates the similarity between two images by comparing their pixel values. It splits both images into 3x3 regions and calculates the similarity of each region. Then, it averages the similarity of all regions to determine the overall similarity between the two images.

## Prerequisites

- Java Development Kit (JDK) installed on your system
- IDE (Integrated Development Environment) for running Java programs (e.g., IntelliJ IDEA, Eclipse)

## Usage

1. Clone the repository to your local machine:

2. Open the project in your preferred IDE.

3. Place the images you want to compare in the project directory.

4. Update the `image1Path` and `image2Path` variables in the `main` method of the `ImageSimilarity` class with the filenames of your images.

5. Run the `main` method.

6. The program will display the total pixels in each image, the overall similarity, and whether the images are similar or not.

## Example

Suppose you have two images named `pic1.jpg` and `pic2.jpg`. Place them in the project directory and update the file paths in the `main` method.

Run the program, and it will display the following output :
( if the images are the same then the following output is displayed)
Total pixels in image1: 1920
Total pixels in image2: 1920
Total pixels in both images: 3840
Similarity: 1.0
Images are similar.
Total similar pixels: 3840
Total dissimilar pixels: 0


