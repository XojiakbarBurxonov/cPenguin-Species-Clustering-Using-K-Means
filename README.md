# Penguin-Species-Clustering-Using-K-Means

**Overview**

This project applies K-Means clustering to a dataset containing penguin morphological measurements to classify different groups based on culmen length, culmen depth, flipper length, and body mass. The analysis helps in understanding species differentiation and identifying optimal cluster numbers using the Elbow Method.

**Dataset Features**

- 𝑪𝒖𝒍𝒎𝒆𝒏 𝑳𝒆𝒏𝒈𝒕𝒉 (𝒎𝒎) – Length of the penguin’s upper beak.
- 𝑪𝒖𝒍𝒎𝒆𝒏 𝑫𝒆𝒑𝒕𝒉 (𝒎𝒎) – Depth of the culmen (beak thickness).
- 𝑭𝒍𝒊𝒑𝒑𝒆𝒓 𝑳𝒆𝒏𝒈𝒕𝒉 (𝒎𝒎) – Length of the penguin’s flippers.
- 𝑩𝒐𝒅𝒚 𝑴𝒂𝒔𝒔 (𝒈) – Weight of the penguins in grams.

Key Steps in the Project

1. 𝑫𝒂𝒕𝒂 𝑷𝒓𝒆𝒑𝒓𝒐𝒄𝒆𝒔𝒔𝒊𝒏𝒈 – Cleaning and normalizing the dataset.
2. 𝑬𝒙𝒑𝒍𝒐𝒓𝒂𝒕𝒐𝒓𝒚 𝑫𝒂𝒕𝒂 𝑨𝒏𝒂𝒍𝒚𝒔𝒊𝒔 (𝑬𝑫𝑨) – Visualizing distributions and relationships.
3. 𝑲-𝑴𝒆𝒂𝒏𝒔 𝑪𝒍𝒖𝒔𝒕𝒆𝒓𝒊𝒏𝒈 – Finding the optimal number of clusters using the Elbow Method.
4. 𝑪𝒍𝒖𝒔𝒕𝒆𝒓 𝑨𝒏𝒂𝒍𝒚𝒔𝒊𝒔 – Interpreting cluster characteristics and comparing different groups.
5. 𝑽𝒊𝒔𝒖𝒂𝒍𝒊𝒛𝒂𝒕𝒊𝒐𝒏 – Plotting results for better understanding.

**Technologies Used**

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook / Google Colab
- GitHub for version control

**Results**

The clustering results highlight three main groups with varying body sizes, flipper lengths, and culmen dimensions, indicating potential species differences.

- 𝐂𝐥𝐮𝐬𝐭𝐞𝐫 𝟎 has the 𝒔𝒎𝒂𝒍𝒍𝒆𝒔𝒕 𝒃𝒐𝒅𝒚 𝒔𝒊𝒛𝒆, 𝒔𝒉𝒐𝒓𝒕𝒆𝒔𝒕 𝒄𝒖𝒍𝒎𝒆𝒏, 𝒂𝒏𝒅 𝒔𝒉𝒐𝒓𝒕𝒆𝒔𝒕 𝒇𝒍𝒊𝒑𝒑𝒆𝒓𝒔, but 𝐭𝐡𝐞 𝐝𝐞𝐞𝐩𝐞𝐬𝐭 𝐜𝐮𝐥𝐦𝐞𝐧 𝐝𝐞𝐩𝐭𝐡—𝐩𝐨𝐬𝐬𝐢𝐛𝐥𝐲 a species adapted for stronger biting.

- 𝐂𝐥𝐮𝐬𝐭𝐞𝐫 𝟏 represents 𝒂 𝒎𝒆𝒅𝒊𝒖𝒎-𝒔𝒊𝒛𝒆𝒅 𝒈𝒓𝒐𝒖𝒑, with moderate measurements across all features.
- 𝐂𝐥𝐮𝐬𝐭𝐞𝐫 𝟐 consists of the 𝒍𝒂𝒓𝒈𝒆𝒔𝒕 𝒊𝒏𝒅𝒊𝒗𝒊𝒅𝒖𝒂𝒍𝒔, 𝒉𝒂𝒗𝒊𝒏𝒈 𝒕𝒉𝒆 𝒍𝒐𝒏𝒈𝒆𝒔𝒕 𝒇𝒍𝒊𝒑𝒑𝒆𝒓𝒔, 𝒍𝒐𝒏𝒈𝒆𝒔𝒕 𝒄𝒖𝒍𝒎𝒆𝒏, 𝒂𝒏𝒅 𝒉𝒆𝒂𝒗𝒊𝒆𝒔𝒕 𝒃𝒐𝒅𝒚 𝒎𝒂𝒔𝒔, indicating 𝒃𝒊𝒈𝒈𝒆𝒓 𝒔𝒑𝒆𝒄𝒊𝒆𝒔.

**How to Use**
1. Clone the repository:

`git clone https://github.com/yourusername/penguin-clustering.git
cd penguin-clustering
`

2. Install dependencies:

`pip install -r requirements.txt`

3. Run the Jupyter Notebook or script to analyze the data.

**Contributing**

Feel free to fork the repo, submit pull requests, or raise issues!
