
# Machine Learning to Detect UC Severity

Uses Turi Create Image Classification to categorize the severity of ulcerative colitis from endoscopic images.



## Installation

Set up a virtual environment, install Turi Create, then navigate to the folder and run

```bash
  jupyter notebook
```

There are 3 notebooks:
1. Dataset To Json - converts raw dataset (link in notebook) into a format Turi can work with.
2. Json To Sframe - loads the dataset into an SFrame. This allows you to delete the original dataset images, since the SFrame contains all images and training data.
3. UC Detector - Trains the model and evaluates performance.
## License

[MIT](https://choosealicense.com/licenses/mit/)

