📂 Contents
1. Dataset Exploration

Uses sns.get_dataset_names() to list available Seaborn datasets.

Loads the Tips dataset using:

df = sns.load_dataset('tips')


Displays the first few rows of the dataset using df.head().

2. Visualization

A Matplotlib bar chart is created to demonstrate basic plotting:

Fruits vs. their supply count

Custom labels and colors

Includes axis labels, title, and legend

🛠️ Requirements

Make sure the following Python libraries are installed:

pip install pandas seaborn matplotlib

▶️ How to Run

Open the notebook in Jupyter Notebook or VS Code.

Run the cells in order.

The final cell will display a bar chart visualizing fruit supply.

📊 Example Plot

The notebook generates a bar chart similar to:

x-axis: Fruit types

y-axis: Supply count

Legend: Fruit color tags
