# Uniswap-Innovation
Design of a IUO tool for Uniswap V3
### designing IUO process 

The DeFi startup X need fund and offer XXX token. The valuation of A is **10 million** dollars and need **1 million **dollars.The total number of XXX tokens is **1 billion**, and 100 million tokens was participating in this IUO process.
Assume UNI price is 20 USDC when X applying IUO.  The remaining XXX tokens not invloving IUO will be locked for 1 year, which X will should promise and write it into a smart contract.
​


1. X apply for 50 thousands of  UNI and offering 1million XXX (50k UNI——1m XXX).
1. The voters who likes this project gather 50k UNI(if 50k UNI not fullfilled only 25k UNI gathered , then process 3 won't happen and  X get 25k UNI and give away 1m XXX )
1. Before the time lock , only the voters decide which IUO simulating curve the IUO process adopts and put intial liquidity into UNI-XXX pool.
1. During the time lock(1 day), investors can only buy XXX with UNI. Nobody could sell back XXX (which is written in the smart contract) 
1. After the time lock. X take fixed 50k UNI away, and voters will withdraw parts of  XXX to keep the price stable, and remaining LP UNI-XXX will be realeased in 12 months.



Let's take some examples.
a. 1st IUO curve(default)  is simulating Uniswap V2
​

![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639665760042-b6789389-b5b6-43ce-a19e-7efceb884c53.png#clientId=u03e41dc2-6c6e-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=229&id=u51e73ea5&margin=%5Bobject%20Object%5D&name=image.png&originHeight=458&originWidth=655&originalType=binary&ratio=1&rotation=0&showTitle=false&size=22895&status=done&style=none&taskId=u6363bd6d-30b6-4b68-b131-29e6f701f3b&title=&width=327.5)


- before time lock, the intial pool, 50k UNI-1000k XXX
- during time lock, investors use 50k UNI to buy 500k XXX

pool: 100k UNI-500k XXX

- after time lock, X get 50k UNI(a fixed number from inital pool)

pool remaining: 50k UNI- 500k XXX. In order to keep the price stable(from 100k UNI-500K XXX to 50k UNI to 250k XXX ),Voters get 250k XXX vesting for 12months . the 50k UNI- 250k XXX LP tokens are owned by the voters.


b. 2nd curve is simulating a single position in Uniswap v3 that means 
​

![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639666070784-13c55fe0-0f21-47ca-ab53-f42ce2cc5473.png#clientId=u03e41dc2-6c6e-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=218&id=ued0e0d6f&margin=%5Bobject%20Object%5D&name=image.png&originHeight=436&originWidth=579&originalType=binary&ratio=1&rotation=0&showTitle=false&size=18325&status=done&style=none&taskId=u7e363f5c-d832-4cd4-ac3a-017afcc3bb1&title=&width=289.5)


- before time lock,the initial pool, 50k UNI-1000K XXX and all XXX was put on $0.02 price.
- During time lock, investors use 20k UNI to buy 200K XXX (XXX: $0.02)

pool: 70k UNI-800k XXX

- after time lock, X get 50k UNI(a fixed number from initial pool)

pool remaininig:20k UNI-800k XXX. In order to keep the price stable(XXX: 0.02, from 20k UNI-800k XXX to 20k UNI-200k XXX), Voters get 600 XXX vesting 12 moths. the 20k UNI- 200k XXX LP tokens are owned by the voters.


c. 3rd curve is simulating a two-asset Balancer pool 


![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639666095114-6ae027a7-3e9f-403f-b368-4ed759c79d81.png#clientId=u03e41dc2-6c6e-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=181&id=rY1xQ&margin=%5Bobject%20Object%5D&name=image.png&originHeight=361&originWidth=511&originalType=binary&ratio=1&rotation=0&showTitle=false&size=17990&status=done&style=none&taskId=ue611217f-3db4-47a8-9655-360456f013c&title=&width=255.5)


That't same  because X take fixed 50k UNI away and voters will withdraw parts of  XXX to keep the price stable, and remaining LP UNI-XXX will be realeased in 12 months. The diffrence is the curve shape  make voters have more advantage that investors after. 

In this process: 
UNI Grants could be voters and participate in IUO process instead of just give UNI grants away. and if the votes come from UNI,then the XXX tokens will be burn after the time lock.
So IUO will make UNI Grants have greater capital capital efficiency. And Since all voters have to give away their UNI tokens instead of show their UNI tokens numbers, whale doesn't have any advantage against small investors.
