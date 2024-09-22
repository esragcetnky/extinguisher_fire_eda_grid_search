# Sound Wave Flame Extinguishing System - Machine Learning Project

This project aims to predict the extinguishing status of flames using sound waves based on a dataset obtained from flame-extinguishing tests. The dataset includes various features related to fuel types, flame size, sound wave frequency, decibel levels, airflow, and the flame's extinction state.

## Dataset Description

The dataset was collected from 17,442 experiments with a sound wave extinguishing system. The experimental setup used 4 subwoofers (4,000 Watts), amplifiers, and several measuring devices, including:

- An anemometer to measure airflow,
- A decibel meter to measure sound intensity,
- An infrared thermometer for temperature readings,
- A camera to record flame extinction time.

The dataset contains:
- **6 input features**: fuel container size, fuel type, sound wave frequency, decibel levels, distance, and airflow.
- **1 output feature**: the extinction status of the flame (extinguished or not).

### Features Explanation:
1. Fuel container size (representing flame size)
2. Fuel type
3. Frequency (Hz)
4. Decibel level
5. Distance (cm)
6. Airflow (measured by anemometer)
7. Extinction status (extinguished/non-extinguished)

The dataset has a balanced class distribution: 8,759 records of non-extinguished flames and 8,683 records of extinguished flames.

## How to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/your_repo_name.git
    cd your_repo_name
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook or Python scripts to train and evaluate the models.

## Results

Each model undergoes hyperparameter tuning using grid search. After training, the accuracy and best parameters for each model are displayed. You can modify the parameters in the code to improve the performance further.

# Contact 
For any questions or suggestions, feel free to reach out:

- Email: esragcetinkaya@gmail.com
- Linkedin : [esragcetinkaya](https://www.linkedin.com/in/esra-gul-cetinkaya/?locale=en_US)
