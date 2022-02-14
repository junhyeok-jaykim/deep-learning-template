# Machine Learning Project Structure

## Principles
* Separation of concerns: distinct componet, hence, easily modifiable
* Don’t Repeat Yourself (DRY): reusable

## Requirements
* Easy to experiments
* Easy to convert into production mode


## Project Structure

```bash
$ tree -L 1

.
├── README
├── __init__.py
├── app
├── configs          <- Phrase(dev/real), hyperparams, paths, metrics, flags, etc
├── dataloader       <- Data loading, preprocessing
├── evaluation       <- Evaluate performance
├── executor         <- All the functions and scripts that train the model 
						or use it for prediction in different environments(cpu/gpu/distribute).
├── main.py
├── model            <- Actual deep learning code
├── notebooks        <- Jupyter/Colab notebook
├── ops              <- Operations not related with machine learning such as algebraic transformations,
						image manipulation techniques or maybe graph operations.
└── utils            <- Utility functions that are used in more than one plac

```

## References
* https://github.com/The-AI-Summer/Deep-Learning-In-Production
  * In first commit, i simply copied subdirectory in this repo.


