# CryptoClustering
This project aims to cluster cryptocurrencies based on their market data using K-means clustering and Principal Component Analysis (PCA). The project follows a structured approach to load, preprocess, and analyze the data, ultimately clustering the cryptocurrencies into meaningful groups.

## Project Structure

- `Crypto_Clustering.ipynb`: Jupyter Notebook containing the entire analysis and clustering process.
- `Resources/crypto_market_data.csv`: CSV file containing the cryptocurrency market data.
- `README.md`: Project overview and instructions.

## Steps to Complete the Project

### Step 1: Set Up the Repository

1. Create a new repository named `CryptoClustering`.
2. Clone the repository to your local machine.
3. Download the challenge files and move them to your new repository.
4. Rename the `Crypto_Clustering_starter_code.ipynb` file to `Crypto_Clustering.ipynb`.
5. Push the changes to GitHub.

### Step 2: Load and Inspect the Data

1. Load the `crypto_market_data.csv` into a DataFrame.
2. Get the summary statistics.
3. Plot the data to visualize initial patterns.

### Step 3: Prepare the Data

1. Normalize the data using `StandardScaler()`.
2. Create a DataFrame with the scaled data for further analysis.

### Step 4: Find the Best Value for k Using the Elbow Method

1. Create a list with k values from 1 to 11.
2. Compute the inertia for each k and store it in a list.
3. Plot the Elbow curve to identify the optimal value for k.

### Step 5: Cluster Cryptocurrencies Using K-means

1. Initialize the K-means model with the best value for k.
2. Fit the model to the scaled data.
3. Predict the clusters.
4. Create a scatter plot to visualize the clusters.

### Step 6: Optimize Clusters with Principal Component Analysis

1. Perform PCA to reduce the features to three principal components.
2. Retrieve the explained variance.
3. Create a DataFrame with the PCA data.

### Step 7: Find the Best Value for k Using the PCA Data

1. Use the elbow method on the PCA data to find the best value for k.

### Step 8: Cluster Cryptocurrencies with K-means Using the PCA Data

1. Initialize the K-means model with the best value for k.
2. Fit the model to the PCA data.
3. Predict the clusters.
4. Create a scatter plot to visualize the PCA-based clusters.

### Step 9: Visualize and Compare the Results

1. Create composite plots to compare the Elbow curves.
2. Create composite plots to compare the cluster results.

### Step 10: Push the Final Notebook to GitHub

1. Save your notebook.
2. Push your final changes to GitHub.

### Step 11: Submit the Challenge

1. Save your work.
2. Submit the link to your GitHub repository.

## Dependencies

- pandas
- hvplot
- scikit-learn
- matplotlib

Install the dependencies using the following command:

```bash
pip install pandas hvplot scikit-learn matplotlib

```

## Usage

1. Clone the repository to your local machine.
2. Navigate to the repository directory.
3. Open the `Crypto_Clustering.ipynb notebook`.
4. Run the cells sequentially to perform the analysis and clustering.

## Disclaimer

Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
