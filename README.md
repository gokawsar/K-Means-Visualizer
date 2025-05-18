# K-Means Clustering Visualizer

An interactive web-based tool to visualize the K-Means clustering algorithm. This project allows users to see how the algorithm works step-by-step, experiment with different numbers of clusters, load custom data, and observe the iterative process of centroid movement and data point assignment directly in the browser.

## Features

*   **Interactive Visualization:** Visualize data points and centroids on a scatter plot.
*   **Dynamic K Adjustment:** Easily add or remove clusters.
*   **Data Handling:** Generate random data, upload data from a CSV file, and export clustered data to CSV.
*   **Real-time Updates:** Observe the clustering process as it iterates.
*   **Centroid Animation:** Centroids pulse to highlight their position.
*   **Visualization Options:** Toggle display of cluster centers, cluster spread (standard deviation), and potential outliers.
*   **Add Points:** Click on the chart to manually add new data points.
*   **Responsive Design:** Usable on different screen sizes.
*   **Cluster Statistics:** View iteration count, inertia, and cluster sizes.
*   **Color Customization:** Randomize or reset cluster colors.

## Technologies Used

*   HTML5
*   CSS3
*   JavaScript
*   Chart.js (for visualization)

## How to Run

This is a client-side web application. You can run it by simply opening the `index.html` file in your web browser.

1.  Clone or download the project files.
2.  Navigate to the project directory.
3.  Open `index.html` in your preferred web browser (e.g., Chrome, Firefox, Edge).

The visualizer should load with a default random dataset. Use the buttons and checkboxes in the menu to interact with the application.

## Screenshot

![image](https://github.com/user-attachments/assets/b21e7702-2bff-4242-bf38-09443751d93d)


## Project Structure

```
.
├── index.html              # Main application file (HTML, CSS, JavaScript)
├── Project_-_CSE-302.tex   # Project report (Web Programming perspective)
├── Project_-_CSE-316.tex   # Project report (AI/ML perspective)
├── Figures/                # Directory for figures referenced in reports (not included)
└── README.md               # This file
```

## Future Work

Potential enhancements and future directions for the project include:

*   **Performance Optimization:** Implement Web Workers or WebAssembly for better performance on larger datasets.
*   **Backend Integration:** Add a server-side component (e.g., Node.js, Python/Flask) for handling larger datasets and more complex computations.
*   **Support for Algorithm Variations:** Include K-means++ initialization, mini-batch K-means, or other clustering algorithms (DBSCAN, Hierarchical).
*   **Higher-Dimensional Visualization:** Explore dimensionality reduction techniques (PCA, t-SNE) to visualize higher-dimensional data.
*   **Improved Outlier Detection:** Implement more sophisticated outlier detection methods.
*   **Integration with Libraries:** Integrate with machine learning libraries like TensorFlow.js or scikit-learn.
*   **User Interface Enhancements:** Further refine the UI and add more interactive features.
*   **Containerization and Deployment:** Package with Docker and deploy to platforms like Netlify or Vercel.
