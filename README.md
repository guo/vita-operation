# vita-operation

## set alias
```
ioctl alias set vita io1hp6y4eqr90j7tmul4w2wa8pm7wx462hq0mg4tw
```

##  claim
```
ioctl action invoke vita 0 -b  4e71d92d -l 200000 -p 1 -s [your wallet alias]
```

## view balance 

```
# need latest build, try install `ioctl update -t unstable`
ioctl xrc20 balanceOf [account] -c vita
```
## also transfer etc using `ioctl xrc20 [xxx]`

## bid 
```
ioctl alias set donation io16alj8sw7pt0d5wv22gdyphuyz9vas5dk8czk88

# alert! this will transfer your IOTX to donation pool, in return you will get VITA proportionally to your donation
# it shows as 'bid' in web wallet
ioctl action invoke donation [IOTX amount of your donation] -l 400000  -b 1998aeef -s [signer]

```
