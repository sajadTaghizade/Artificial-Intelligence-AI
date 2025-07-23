<div align="center">
  <h1>
    📊 Artificial Intelligence - Computer Assignment 3 🧠
  </h1>
  <h2>
    Predicting Student Performance with Machine Learning
  </h2>
  <p>
    This is the third assignment for the Artificial Intelligence course. The primary goal is to use <strong>Machine Learning</strong> techniques to predict the final grade of students in the AI course based on their demographic, social, and academic characteristics.
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
        This project is divided into two main phases. [cite_start]The first phase focuses on <strong>data preprocessing and feature engineering</strong> to prepare the dataset for modeling. [cite: 265, 274] [cite_start]The second phase involves developing, training, and evaluating several <strong>classification models</strong> to predict student performance. [cite: 265, 289]
      </p>
      <br>
      <h3>
        📈 Dataset Overview
      </h3>
      <p>
        [cite_start]The dataset contains student academic performance records, including demographic, social, and educational features such as age, gender, family status, study hours, past failures, and previous course grades. [cite: 268, 270, 271] [cite_start]The final grade in the AI course (`finalGrade`) is the target variable. [cite: 273]
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>
        ⚙️ Project Phases
      </h3>
      <h4>
        Phase 1: Preprocessing & Feature Engineering
      </h4>
      <ul>
        <li>
          [cite_start]Handling missing data using appropriate imputation methods. [cite: 278]
        </li>
        <li>
          [cite_start]Converting categorical features (like gender, address) into numerical values. [cite: 282]
        </li>
        <li>
          [cite_start]Transforming the continuous `finalGrade` into a categorical feature with four groups (A > 17, B: 14-17, C: 10-14, Failed < 10) to prepare it for classification models. [cite: 283, 285, 286]
        </li>
      </ul>
      <h4>
        Phase 2: Model Development & Evaluation
      </h4>
      <ul>
        <li>
          [cite_start]Splitting the data into training (80%) and testing (20%) sets to prevent overfitting. [cite: 292, 295]
        </li>
        <li>
          [cite_start]Applying Normalization/Standardization techniques to scale the features. [cite: 296, 297]
        </li>
      </ul>
    </td>
  </tr>
</table>

<hr>

### 🤖 Required Models

A variety of classification models are to be implemented and evaluated:

<table>
  <tr>
    <td valign="top" width="50%">
      <h4>
        Library-Based Models (Scikit-learn)
      </h4>
      <ul>
        <li>
          [cite_start]<strong>Naive Bayes</strong>: A simple yet powerful probabilistic classifier. [cite: 301]
        </li>
        <li>
          <strong>Decision Tree</strong>: Including tree pruning and hyperparameter optimization. [cite_start]The final tree should be visualized. [cite: 306, 311]
        </li>
        <li>
          <strong>Random Forest</strong>: An ensemble method using multiple decision trees. [cite_start]Hyperparameters should be tuned using <code>RandomizedSearchCV</code>. [cite: 315, 320, 326]
        </li>
        <li>
          <strong>XGBoost</strong>: A gradient boosting algorithm. [cite_start]Hyperparameters should be tuned using <code>GridSearchCV</code>. [cite: 327, 330]
        </li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h4>
        Implementation from Scratch
      </h4>
      <ul>
        <li>
          [cite_start]<strong>Decision Tree from Scratch</strong>: A custom implementation of the Decision Tree algorithm is required. [cite: 336] The class must include:
          <ul>
            <li>
              [cite_start]An <code>__init__</code> method to define parameters like <code>max_depth</code>. [cite: 337]
            </li>
            <li>
              [cite_start]A <code>fit</code> method to build the tree from training data using entropy for splitting. [cite: 343, 345, 346]
            </li>
            <li>
              [cite_start]A <code>predict</code> method to classify new data by traversing the tree. [cite: 347]
            </li>
          </ul>
        </li>
      </ul>
    </td>
  </tr>
</table>

<hr>

<details>
  <summary>
    <h3>✅ Model Evaluation & Course Info</h3>
  </summary>
  <h4>
    Evaluation Metrics
  </h4>
  <p>
    [cite_start]All models must be evaluated using the following metrics to compare their performance: [cite: 359, 360]
  </p>
  <ul>
    [cite_start]<li>Confusion Matrix [cite: 360]</li>
    [cite_start]<li>Accuracy [cite: 365]</li>
    [cite_start]<li>Precision [cite: 363]</li>
    [cite_start]<li>Recall [cite: 361]</li>
    [cite_start]<li>F1-Score [cite: 362]</li>
    [cite_start]<li>Macro, Micro, and Weighted Averages [cite: 366]</li>
  </ul>
  <hr>
