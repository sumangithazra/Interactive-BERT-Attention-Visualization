# Interactive BERT Attention Visualization Notebook


This project is a single Google Colab notebook for visualizing the internal attention mechanisms of a pre-trained BERT model. It uses the `bertviz` library to create interactive visualizations, helping to demystify how Transformers understand language.

The notebook is self-contained and includes all necessary code for setup and execution.



## Features

-   **All-in-One:** All code, from installation to visualization, is in one `.ipynb` file.
-   **Multiple Views:** Generates `head_view`, `model_view`, and `neuron_view` to provide a comprehensive analysis of attention.
-   **Flexible Analysis:** The code is structured to analyze both single sentences (for ambiguity) and sentence pairs (for contextual reasoning).
-   **Interactive:** Leverages `bertviz` for dynamic, hands-on exploration of model internals.

## Setup and Usage

Getting started is simple. All you need is a web browser and a Google account.

#### **Step 1: Open in Google Colab**

Click the "Open in Colab" badge at the top of this `README` (or manually open the `.ipynb` file in [Google Colab](https://colab.research.google.com/drive/1UG0Foc7-avANHvM3qNE-bgtNNt2_NhPW#scrollTo=4u7DqcCxtZgX)).

#### **Step 2: Install Dependencies**

The first code cell in the notebook contains the necessary installation commands. Run this cell to install `bertviz`, `transformers`, and other required libraries.

```python
# The first cell in the notebook will look like this:
!pip install bertviz
```

#### **Step 3: Run the Cells**

Execute the notebook cells in order from top to bottom. The notebook is structured to:
1.  Install dependencies.
2.  Load the pre-trained BERT models and tokenizers.
3.  Define the visualization function.
4.  Run examples for both single-sentence and two-sentence analysis.

## About the Visualizations

This notebook allows you to explore three different levels of attention:

* **`head_view`:** A detailed look at a single attention head to analyze specific linguistic patterns.
* **`model_view`:** A high-level summary of attention across all 144 heads of the model.
* **`neuron_view`:** A microscopic view of the individual neuron interactions that cause attention between words.



## License


This project is licensed under the MIT License.

