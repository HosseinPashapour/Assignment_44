
# Assignment 44 
# Machine Learning
# Linear Least Squares (LLS) 


# 1.Students Performance (Regression)

+ In this problem I find a relation between study hours  and grade of students with LLS algorithm.
First of all I made a data for study hours and grades of student with numpy library.
then I wrote a class for LLS algorithm and I use it for predict the slope of a line that pass through students data.


## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Students_Performance_Regression.ipynb file in jupyter notebook
```

## Results


<img src="Output\Students_Performance_Regression.png" width="550">


-----------------------------------------
# 2.Boston house-prices (Regression) 🏠


+ In this problem I find a relation between house price in boston and other parameter with LLS algorithm.
I use Boston dataset in kaggle site for this problem.
you can find this dataset in below link:
https://www.kaggle.com/datasets/puxama/bostoncsv

+ I find correlation of different features indataset to find two feature that have more relation to price of houses.
+ I found these two feature is rm and zn respectively.
then I use my lls algorithm to find two slope.
and then I draw a 3d plot by using matplotlib. I showed my predicted plane and real data in this plot.
you can see this plot in result part second problem.


## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Boston_housePrice_Regression.ipynb file in jupyter notebook
```

## Results

<img src="Output\heatmap.png" width="750">

Boaton Housing LLS on 3D Scatter
<img src="Output\boston.png" width="750">

-----------------------------------------