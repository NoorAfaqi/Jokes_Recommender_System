# Jokes_Reccomender_System

This repository contains code for a generating recommendations according to top-k similar users.

Process includes two main tasks:
1. **Text Preprocessing**: Cleaning and preparing textual data for further analysis.
2. **Identifying Top K Users**: Analyzing user data using PySpark to identify the top K users based on specific metrics.

## Architechure Diagram:

![Architechure Diagram](https://github.com/user-attachments/assets/1d73866a-ddcc-48ff-a958-3906aeb2ddfb)


## Project Structure

The project includes the following Jupyter Notebook files:

- **`TextPreprocessing.ipynb`**: Focuses on text preprocessing and includes steps for:
  - Cleaning raw text data.
  - Handling missing values.
  - Removing outliers.
  - Scaling values to a specific range.

- **`Top_K_Users.ipynb`**: Contains the implementation for analyzing user data with PySpark and generate recommendations as:
  - Splitting dataset into test and train.
  - Compute similarities.
  - Test against test data.
  - Generate outputs based on top-k users.

![image](https://github.com/user-attachments/assets/3ce8371f-a9e0-45dc-a69f-d51c73196122)

![image](https://github.com/user-attachments/assets/1c8d7b01-98ce-4f44-8604-78174a1992d9)



## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. For major changes, open an issue first to discuss what you would like to change.


For questions or feedback, please contact noorafaqi363@gmail.com

