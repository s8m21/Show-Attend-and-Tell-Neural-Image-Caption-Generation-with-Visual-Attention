# Show-Attend-and-Tell-Neural-Image-Caption-Generation-with-Visual-Attention

Website: https://expo.baulab.info/2023-Fall/Ayush-Patel-10/

This repository provides two implementations for the paper "Show, Attend and Tell" using both VGG and InceptionV3 models trained on the MS COCO dataset. Below are the instructions to run, train, and evaluate the models.

## Intructions

1. **Training the Model:**
  - Open the TrainingAndSavingModel.ipynb Jupyter Notebook file.
  - Run the entire file to train the model. Ensure that the model is saved on your Google Drive.
  - You can adjust hyperparameters according to your system needs.

2. **Testing the Model:**
  - Open the LoadingAndTestingModel.ipynb Jupyter Notebook file.
  - Run the file to check the model's performance on your personal images.
  - Ensure that the images are in the required format.

3. **Evaluation:**
  - Open the cocoEvalCapDemo.ipynb Jupyter Notebook file.
  - Run the file to check the BLEU and METEOR scores for the models.
  - Note: Customized coco-caption is included in the repository, and some modifications have been made to meet the model's requirements.

## Usage

To use the pre-trained models on your images, follow the steps in the LoadingAndTestingModel.ipynb file.

## Training

If you want to train the models on your dataset:

1. Prepare your dataset in the required format.
2. Open the TrainingAndSavingModel.ipynb file.
3. Run the file, adjusting hyperparameters as needed.

We have trained the model on 5000 vocab size, 100000 images and captions. 

## Evaluation

Evaluate the models using the cocoEvalCapDemo.ipynb file to obtain BLEU and METEOR scores.

## Customization

Feel free to customize the code, adjust hyperparameters, or use different pre-trained models. These hyperparameters were adjusted according to our system requirements. You can increase the vocab size and the number of images and captions used.

## Results

We evaluated the model on 2 metrics - BLUE and METEOR. We achieved a BLUE-1: 36 and METEOR: 10.04.

## References

- Original Paper: https://arxiv.org/pdf/1502.03044.pdf

For any issues, contributions, or questions, please feel free to reach out. 

Linkedln: https://www.linkedin.com/in/spandanmaaheshwari/
