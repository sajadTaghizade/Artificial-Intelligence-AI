<div align="center">
  <h1>
    🎶 Artificial Intelligence - Computer Assignment 5  clustering
  </h1>
  <h2>
    Clustering English Song Lyrics
  </h2>
  <p>
    This project is the fifth and final assignment for the Artificial Intelligence course. It focuses on <strong>Unsupervised Learning</strong>, specifically using <strong>Clustering</strong> techniques to analyze and group a dataset of English song lyrics based on their underlying topics and semantic similarities.
  </p>
</div>

<hr>

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>
        📖 Project Description
      </h3>
      <p>
        The primary goal is to apply a complete data science pipeline to an unstructured text dataset. This involves cleaning the text data, converting the lyrics into meaningful numerical representations (feature vectors), and then using various clustering algorithms to discover natural groupings within the songs.
      </p>
      <br>
      <h3>
        ⚙️ Phase 1: Preprocessing & Feature Extraction
      </h3>
      <ul>
        <li>
          <strong>Text Preprocessing</strong>: Cleaning the raw lyric data by removing stop words, applying stemming or lemmatization, and stripping punctuation.
        </li>
        <li>
          <strong>Feature Extraction</strong>: Using the <strong><code>Sentence-Transformers</code></strong> library with the pre-trained <strong><code>all-MiniLM-L6-v2</code></strong> model to convert the cleaned lyrics into high-dimensional feature vectors.
        </li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>
        ⚙️ Phase 2: Clustering & Visualization
      </h3>
      <ul>
        <li>
          <strong>Clustering</strong>: Applying various clustering algorithms to the generated feature vectors to group the songs. This involves experimenting with different hyperparameters to achieve the best results.
        </li>
        <li>
          <strong>Dimensionality Reduction</strong>: Using <strong>Principal Component Analysis (PCA)</strong> to reduce the high-dimensional feature vectors into 2D or 3D representations. This allows for the visualization and comparison of the discovered clusters.
        </li>
      </ul>
    </td>
  </tr>
</table>

<hr>

### 🤖 Required Algorithms & Metrics

<table>
  <tr>
    <td valign="top" width="50%">
      <h4>
        Clustering Algorithms
      </h4>
      <ul>
        <li>
          <strong>K-Means</strong>: With the optimal number of clusters (K) determined by the <strong>Elbow Method</strong>.
        </li>
        <li>
          <strong>DBSCAN</strong>: A density-based clustering algorithm.
        </li>
        <li>
          <strong>Hierarchical Clustering</strong>: An algorithm that builds a hierarchy of clusters.
        </li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h4>
        Dimensionality Reduction
      </h4>
      <ul>
        <li>
          <strong>PCA</strong> (Principal Component Analysis)
        </li>
      </ul>
      <h4>
        Evaluation Metrics
      </h4>
      <ul>
        <li>
          <strong>Silhouette Score</strong>
        </li>
        <li>
          <strong>Homogeneity Score</strong>
        </li>
      </ul>
    </td>
  </tr>
</table>

<hr>
