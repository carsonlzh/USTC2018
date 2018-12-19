##    目录结构

```
./
|
|--- feature_analyzation
|                       |--- feature_analyzation_name.pdf
|
|
|--- result
|          |--- titanic-submission_name.csv
|          |--- result_name.png
|
|
|--- src
|       |--- model_name.py
|
|
|--- readme.md
```

*    `./feature_analyzation` 文件夹，包含如下文件

*    文件名 `feature_analyzation_.pdf` 的 `pdf` 文档。

<br>

*    `./result` 文件夹，包含如下文件

*    `titanic-submission_lizhihao.csv`, 预测结果。

*    `result_name.png`, 提交结果的截图。
<br>

*    `./src` 文件夹，包含如下文件

*    `model_lizhihao.py`

<br>

*    最后，`readme.md` 放在根目录 `./` 中

<br>
##      简介
<br>

*    使用了两层的模型融合，Level 1使用了：RandomForest、AdaBoost、ExtraTrees、GBDT、DecisionTree、KNN、SVM ，一共7个模型，Level 2使用了XGBoost使用第一层预测的结果作为特征对最终的结果进行预测

*    特征工程参加群文档文件夹 `feature_analyzation`

这里使用了 `'Sex', 'Age', 'Pclass', 'Title', 'Parch', 'Name_length', 'fare', 'Title',
作为输入特征

<br>


##    参考资料

*    https://blog.csdn.net/Koala_Tree/article/details/78725881




