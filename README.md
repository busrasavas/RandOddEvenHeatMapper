![github_title](https://user-images.githubusercontent.com/62547137/150113171-b1360c37-84b2-4338-bcef-1e76163b672e.png)

#### by Büşra Savaş

## Motivation

RandOddEvenHeatMapper is a tool created for final project of MBG6113 lecture given in Izmir Biomedicine and Genom Center by Ezgi Karaca ([CSB-KaracaLab](https://github.com/CSB-KaracaLab)). 

## Features of RandOddEvenHeatMapper
- Adjustable matrix size and number range, just by editing the corresponding cell.
```
required_size=100   #please state the size you require
number_range=100    #please state the number range you require
```
- 

**Quick Example(s)**

```
    #Load the output file of GROMACS covar ascii.
    covar = pd.read_csv(r'../application_example/covar-3a-cgc.dat', sep=' ', header=None)
    
    #Convert the covariance matrix to cross-correlation and save it to csv file.
    np.savetxt("../outputs/cross_corr_3a-cgc.csv", corr, delimiter=" ", fmt='%s')
    
    #Draw the graph and save it.
    fig.savefig('../outputs/cross_corr_3a-cgc.jpeg', dpi=500)
```
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
