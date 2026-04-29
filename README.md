## Predicting Electricity Access In Africa using Machine learning
## What the Project Does

This project analyzes historical electricity access data across African countries, distinguishing between rural and urban areas. It performs extensive exploratory data analysis (EDA) to identify trends, disparities, and patterns in electrification. Building on this analysis, the project develops and evaluates several machine learning models (RandomForestRegressor, Neural Networks, and Linear Regression) to predict future electricity access percentages. A key output is an interactive tool that allows users to query predictions for specific countries, locations, and years.

## Why the Project is Useful

Electricity access is a critical driver of economic development and quality of life. This project provides:

 Insights into Electrification Progress: Visualizations and interpretations highlight which countries are excelling and which are lagging in providing electricity access, and the persistent rural-urban divide.
 Predictive Capabilities: The machine learning models offer a tool to forecast future electricity access, which can be invaluable for policy-makers, development organizations, and investors in planning electrification strategies and resource allocation.
 Data-Driven Decision Making: By understanding past trends and predicting future scenarios, stakeholders can make more informed decisions to accelerate sustainable energy access in Africa.
 Interactive Exploration:The interactive demo allows for easy, on-demand scenario analysis without requiring deep technical knowledge.

## How Users Can Get Started with the Project

To run this project locally or in a Colab environment:

1.  Clone the Repository:Download the project files from its GitHub repository.
2.  Setup Environment:
    *   Ensure you have Python 3.x installed.
    *   Install the required libraries using `pip install -r requirements.txt` (assuming a `requirements.txt` file is generated, which would typically include `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `tensorflow`, `ipywidgets`, `pycountry`, `pycountry-convert`, `gradio`).
3.  Data Source: The project uses data from the SDG 7.1.1 indicator. The data file (`sdg 7.1.1.xlsx`) is expected to be mounted from Google Drive at `/content/drive/MyDrive/sdg 7.1.1.xlsx` as shown in the notebook. Ensure this file is accessible.
4.  Run the Notebook: Open and run the Jupyter Notebook (`.ipynb` file). Follow the cells sequentially from data loading, EDA, to model training and evaluation.
5.  Interactive Demo: After running the machine learning model cells, you can interact with the `ipywidgets` demo directly in the notebook or launch the Gradio interface if the code is executed.

## Where Users Can Get Help with Your Project

  GitHub Issues: For bugs, feature requests, or general questions, please open an issue on the project's GitHub repository.
  Documentation: Refer to the comments and markdown cells within the Jupyter Notebook for detailed explanations of each step.
  Contact: For more in-depth discussions or collaborations, reach out to the project maintainers.

## Who Maintains and Contributes to the Project

This project is maintained by Mugide Gloria. Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.
