![github_title](https://user-images.githubusercontent.com/62547137/150113171-b1360c37-84b2-4338-bcef-1e76163b672e.png)

#### by Büşra Savaş

## Motivation

RandOddEvenHeatMapper is a tool created for final project of MBG6113 lecture given in Izmir Biomedicine and Genom Center by Ezgi Karaca ([CSB-KaracaLab](https://github.com/CSB-KaracaLab)). 

## Features of RandOddEvenHeatMapper
- provides adjustable matrix size and number range, just by editing the corresponding variables in the jupyter notebook.
```
required_size=100   #please state the matrix size you require
number_range=100    #please state the number range you require
```
- produces a random matrix (i.e. 100*100 numpy array composed of random numbers in range of 0 to 100).
```
random_matrix=np.random.randint(number_range+1, size=(required_size, required_size))
```
- checks the all elements in the produced matrix if they are odd or even.
```
OddEvenMatrix=random_matrix%2==0
OddEvenMatrix=OddEvenMatrix.astype(int)
```
- creates a heatmap figure for both random matrix and random odd/even matrix and saves the figures.

<img src="https://user-images.githubusercontent.com/62547137/150119783-280cda8a-d61e-4069-b210-fe8028b45d6f.jpg" width="450" height="450">
<img src="https://user-images.githubusercontent.com/62547137/150121475-4687dffc-146f-4ba4-83c5-20548cd7d1e8.jpg" width="450" height="450">
## Our folders describe:

- **Script** contains the jupyter notebook script that produces a random matrix and heatmap.
- **Outputs:** contains the output files produced by jupyter notebook script.
  

## To clone the repository

```
git clone https://github.com/busrasavas/RandOddEvenHeatMapper.git
```
or if you would like to get the content directly via wget:
```
wget https://github.com/busrasavas/RandOddEvenHeatMapper/archive/master.zip
```

## Contact
buusrasavas@gmail.com
