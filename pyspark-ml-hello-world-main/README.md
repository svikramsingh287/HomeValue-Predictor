# PySpark ML 'Hello World'

![Houses side by side](assets/4454911539_b118315672_c.jpg)

License [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/) license: by [ell brown](https://www.flickr.com/photos/39415781@N06)

A simple repository to apply Linear Regression using [PySpark](https://spark.apache.org/docs/latest/api/python/index.html) to predict the houses' price. 

I tried not to use operations apart from PySpark that require processing all the data, for example, plotting the features (I processed it in PySpark and used the result in the graphs). This makes it more realistic when you have a larger set of data than you can plot all the elements.

Of course, it is totally viable to use [Pandas](https://pandas.pydata.org/) and [Scikit-learn](https://scikit-learn.org/stable/) to create the regression model and predict, this repository is just the first step to understanding PySpark Framework.

**Jupyter Notebook:** [PySparkML](./PySparkML.ipynb)

**Dataset link:** [https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data)


# Python Dependencies

```console
$ pip install pyspark matplotlib seaborn numpy scipy
```

- Remember to create a virtual environment first!

---

<p align='center'>
<strong>MIT License</strong><br>
This project is licensed under the MIT License - see the LICENSE file for details.<br><br>
&copy; 2023 BrenoAV
</p>