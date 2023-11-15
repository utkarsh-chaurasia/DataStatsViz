# DataStatsViz

## Detailed Report on the Design and Implementation of the Statistical Analysis and Plotting Application
### Introduction
The Statistical Analysis and Plotting Application is a versatile tool designed to perform statistical analysis and generate visualizations from CSV data. This application leverages the capabilities of the Prompt and Llama-2 models to analyze and present insights from the data comprehensively. The application's user-friendly command-line interface allows users to effortlessly navigate through its functionalities.

### Design Overview
The application's design adheres to a modular approach, where each module encapsulates a specific task. This modular structure promotes code maintainability, extensibility, and enhances code comprehension. The primary modules of the application are:

CSV Reader and Parser: This module handles the task of reading and parsing CSV files into Pandas DataFrames, providing a structured representation of the data for further analysis.

Statistical Analysis Module: This module encompasses functions for performing statistical analysis on the data. It calculates measures of central tendency (mean, median, mode) and dispersion (standard deviation) and quantifies the strength of relationships between variables (correlation coefficient).

Plotting Module: This module generates various types of plots to visualize the data effectively. It creates histograms to illustrate the distribution of variables, scatter plots to explore relationships between variables, and line plots to showcase trends over time.

Question Answering Module: This module utilizes the Prompt and Llama-2 models to answer user-posed questions about the data in a comprehensive and informative manner. It extracts relevant information from the data and presents it in a clear and concise way.

### Implementation Details
The application is implemented using a combination of Python libraries, including:

Python: Python serves as the primary programming language for the application, providing a robust foundation for data manipulation and analysis.

Prompt: Prompt is a Python library specifically designed for creating command-line interfaces (CLIs). It facilitates user interaction and simplifies the process of executing commands.

Transformers: Transformers is a powerful library for natural language processing (NLP) tasks. It provides the necessary tools for handling text-based interactions, such as answering questions using the Llama-2 model.

Matplotlib: Matplotlib is a widely used Python library for generating high-quality plots. It offers a comprehensive set of functions for creating various types of visualizations.

Pandas: Pandas is a fundamental library for data analysis and manipulation in Python. It facilitates data cleaning, transformation, and exploration, providing a structured representation of the data.

### Testing Methodology
The application has undergone rigorous testing to ensure its correctness, accuracy, and user-friendliness. A combination of unit tests, integration tests, and user acceptance tests have been employed to validate its functionality.

Unit Tests: Unit tests focus on individual modules, ensuring that each component functions as expected.

Integration Tests: Integration tests evaluate the interactions between different modules, verifying that they work seamlessly together.

User Acceptance Tests: User acceptance tests assess the application's usability and ability to meet user requirements.

### Evaluation Criteria
The application has been evaluated against the following criteria:

Accuracy of Statistical Analysis: The application should produce accurate statistical results, ensuring the validity of the insights derived from the data.

Quality of Plots: The generated plots should be clear, informative, and visually appealing, effectively conveying the underlying patterns and trends in the data.

Ability to Answer Questions About the Data: The application should be able to answer user-posed questions about the data in a comprehensive and informative manner, providing meaningful insights.

### Conclusion
The Statistical Analysis and Plotting Application stands as a valuable tool for data analysis and visualization. Its modular design, comprehensive functionalities, and user-friendly interface make it a powerful asset for extracting insights from CSV data. The application's ability to perform statistical analysis, generate informative plots, and answer user questions makes it a versatile tool for data exploration and understanding.

Colab Link: https://colab.research.google.com/drive/1CUBqXWqDQe_FowJXA6Y1di3SJ395mL7r?usp=sharing
