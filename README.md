
```markdown
#  Linear Discriminant Analysis (LDA) on Iris Dataset  


This project demonstrates **Linear Discriminant Analysis (LDA)** on the classic [Iris dataset](https://huggingface.co/datasets/scikit-learn/iris).  
It includes data preprocessing, model training, evaluation, and **beautiful visualizations** of the dataset in LDA-reduced space.  

---

## ⚙️ Setup & Installation  

Clone the repository and install dependencies:  

```bash
git clone https://github.com/your-username/LDA-Iris.git
cd LDA-Iris
pip install -r requirements.txt
````

Or manually install:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn datasets
```

---

## ▶ Usage

Open the notebook and run all cells:

```bash
jupyter notebook lda_iris.ipynb
```

Or upload it to [Google Colab](https://colab.research.google.com/).

---

##  Results

###  Model Performance

* **Accuracy**: \~100% on test set

* **Confusion Matrix**:

  ```
  [[10  0  0]
   [ 0 10  0]
   [ 0  0 10]]
  ```

* **Classification Report**: Perfect precision, recall, and F1 across all classes

---

###  Visualizations

####  LDA Projection (2D Scatter Plot)

Data projected onto 2 linear discriminants shows **perfect separation** between species.

*( plot)*
![LDA Scatter](https://github.com/RishabhVerma08/Assignment-1/blob/main/image.png)

####  Explained Variance Ratio

Shows how much variance each discriminant captures.

*(plot)*
![LDA Variance](https://github.com/RishabhVerma08/Assignment-1/blob/main/variance-barplot.png)

---

##  Key Learnings

* LDA reduces dimensionality while maximizing **class separability**
* For *k* classes, at most *k − 1* discriminant axes are available
* On Iris (3 species), 4D features → 2D LDA space with **perfect separation**

---

##  References

* [Scikit-learn: Linear Discriminant Analysis](https://scikit-learn.org/stable/modules/lda_qda.html)
* [HuggingFace Iris Dataset](https://huggingface.co/datasets/scikit-learn/iris)


