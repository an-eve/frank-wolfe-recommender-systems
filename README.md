# Frank-Wolfe Recommender Systems

This project demonstrates the application of the Frank-Wolfe algorithm to optimize recommendation systems. It focuses on the implementation of matrix completion to predict user-item interactions in sparse datasets.

## Project Structure

The repository is organized as follows:

```
Frank-Wolfe-Recommender-Systems/
├── data/                               # Placeholder for dataset files
├── FW Recommendation Systems Slides/
│   ├── image/
│   ├── include/
│   └── main.tex                        # Main LaTeX file for slides
│   └── FW_Recommendation_Systems_Slides.pdf # PDF version of the presentation
├── Report FW Recommender Systems/
│   ├── images/
│   ├── include/
│   ├── logo/
│   └── main.tex                        # Main LaTeX file for the report
│   └── Report_FW_Recommender_Systems.pdf # PDF version of the report
├── .gitignore                          # Git ignore file
├── main.ipynb                          # Jupyter notebook for experimentation
├── utils.py                            # Python utility functions for matrix completion
```


## Datasets

This project uses two publicly available datasets:

1. **MovieLens 20M Dataset**  
   - Contains 20 million ratings for over 27,000 movies by 138,000 users.  
   - Download link: [MovieLens Dataset](https://doi.org/10.1145/2827872)

2. **Anime User Score Dataset**  
   - Includes ratings for 16,500 anime titles from 270,033 users.  
   - Download link: [Anime Dataset](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset/data?select=users-score-2023.csv)

## Implementation Details

The project focuses on using the Frank-Wolfe algorithm for matrix completion to predict missing user-item interactions in recommendation systems. The following techniques are applied:

- **Matrix Initialization**: Low-rank random initialization normalized to observed data properties.
- **Step Size Strategies**: Includes diminishing, exact line search, and Armijo rule for step size optimization.
- **Loss and Dual Gap Monitoring**: Tracks performance over iterations.
- **Frank-Wolfe Algorithm for Matrix Completion**: Adapted for matrix completion, includes different step size strategies and stopping conditions.
- **Visualization**: Loss function and dual gap plots for different strategies.

## Outputs

- **Reports and Slides**:
  - `Report_FW_Recommender_Systems.pdf`: Detailed report of the project.
  - `FW_Recommendation_Systems_Slides.pdf`: Presentation slides summarizing the project.
