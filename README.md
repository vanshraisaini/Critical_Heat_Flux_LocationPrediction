# CHF Location Prediction with Machine Learning

This repository contains code for predicting the critical heat flux (CHF) location in power generation industries using machine learning techniques. The project also led to a successful publication in *Progress in Nuclear Energy* titled "Prediction of CHF location through applied machine learning" by V. Kumar et al. (2024).

## Abstract

The prediction of critical heat flux (CHF) location is a challenging task due to its dependency on various geometric parameters and operating conditions. This phenomenon exhibits non-linear relationships and involves complex interactions among factors such as pressure, power, mass flux, and subcooling. Traditional models struggle to account for all these factors simultaneously, leading to unresolved dependencies. In this study, we employ different machine learning models to predict CHF location and identify the most accurate model based on comparisons with benchmark experimental data. We utilize the Becker et al. (1983) data bank for model training and testing, owing to its wide range of operating conditions. Hyperparameter tuning is applied to optimize model performance. Among all implemented models, the artificial neural network (ANN) model demonstrates superior performance, with mean absolute percentage errors (MAPE) of 4.01% for training and 6.04% for testing datasets, and accuracy scores of approximately 96% for training and 94% for testing datasets. The proposed model provides valuable insights for design engineers and analysts in power plants, enabling design optimization and computational time reduction.

## Publication Details

- **Title:** Prediction of CHF location through applied machine learning
- **Authors:** V. Kumar, D. Pimparkar, V. Saini, R. Kohli, S. Gupta, and H. Pothukuchi
- **Journal:** *Progress in Nuclear Energy*
- **Volume:** 169
- **Page:** 105055
- **Publication Year:** 2024
- **DOI:** [10.1016/j.pnucene.2024.105055](https://doi.org/10.1016/j.pnucene.2024.105055)

## Usage

To use the code in this repository, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies listed at the start of the Jupyter notebook.
3. Run the main Jupyter notebook to train and test the machine learning models.
4. Evaluate the performance of different models using provided metrics.
5. Refer to the publication for detailed insights and analysis.

## Citation

If you find this work helpful in your research, please consider citing the publication:
@article{kumar2024prediction,
title={Prediction of CHF location through applied machine learning},
author={Kumar, V. and Pimparkar, D. and Saini, V. and Kohli, R. and Gupta, S. and Pothukuchi, H.},
journal={Progress in Nuclear Energy},
volume={169},
pages={105055},
year={2024},
publisher={Elsevier},
doi={10.1016/j.pnucene.2024.105055}
}



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to explore the code, contribute, or reach out with any questions or suggestions!
