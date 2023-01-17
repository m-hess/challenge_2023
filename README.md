# Instructions
Thank you for applying to the UCSF Center for Intelligent Imaging Summer 2023 Fellowship. Welcome to the coding challenge portion of the application – we hope the challenge will take you an hour or less, but there is no time limit on challenge completion other than the application deadline. We recommend but do not require that you use Python to complete the challenge. Feel free to use any resources you like to learn and complete the challenge, but please cite your sources with in-code comments.


For the challenge, you will be required to produce 3 images according to the below prompts. We will be using the [ChestMNIST dataset](https://zenodo.org/record/6496656#.Y8bnAOzMIUo) from the opensource [Medical MNIST](https://medmnist.com/) archive. Start by [downloading](https://zenodo.org/record/6496656/files/chestmnist.npz?download=1) the data (it will be 82MB, and you can delete it when you're done with the challenge). You can see example solutions to the first two prompts in the `sample/` folder.

You will be required to submit **both your images and your code** as part of the submission process. This challenge must be submitted by the application deadline, **Feb 28, 2023**.

# Prompts
***Note:** Please title each of your images `<YourFirstName>_<YourLastName>_<PromptNumber>.png`. For example, `Madeline_Hess_1.png`.*
1. Open one image (any image) from the ChestMNIST dataset. 
*(Hint: When you load the ChestMNIST datafile in Python using NumPy, the result will be a dictionary with keys `{'train_images', 'val_images', 'test_images', ...}`. The value associated with each of these keys is an array with the dimensions `(Number of Images, 28, 28)`. Index on the first dimension to retrieve your `28 x 28` pixel image. )*
Visualize your selected image and save it to a grayscale png, following the naming convention above. See `sample/Madeline_Hess_1.png` for an example of output.
2. Apply a filter to invert the contrast of your selected image (turn all black pixels white, and vice versa). Visualize the resulting image and save it to a png. See `sample/Madeline_Hess_2.png` for an example of output.
3. Apply any filter of your choice  to your selected image (as in any kind of image manipulation that is NOT contrast inversion like you completed in Step 2). No examples for this prompt, feel free to be creative! :smile:

# Submission
Upload all your code and your images to a [GitHub](https://github.com/) repository (see [here](https://docs.github.com/en/get-started/quickstart) if you need help getting started). Submit the URL to your GitHub repository with your solution to [this SmartSheet](). 
***Note:** Make sure that your repository is **publicly** visible and is not set to private mode so that we can see your solution and your code.*

Congratulations on completing the UCSF Center for Intelligent Imaging Summer 2023 coding challenge!