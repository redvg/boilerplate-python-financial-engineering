# boilerplate-python-financial-engineering
Financial engineering with Python boilerplate


## [intro](intro.ipynb)
* prereqs: latex, charting..
* pricing call with bsm monte carlo sim
    - monte carlo to get terminal values under bsm gaussian
    - payoffs
    - average payoff pv
* historical volatility + data import&plot
    - daily rets
    - daily st dev
    - annualized via sq root of time
* perfomance considerations
    - looping with numpy, numexpr, multi-thread

## [implied volatility](implied-volatility.ipynb)
* imports HDFS mkt data of VSTOXX futures and calls on 'em
* implements python functions under bsm
    - call price
    - call vega
    - newton estimate of implied volatility
* calculates implied volatity smiles for set of maturities
* some useful pandas stuff





