# crypProj

Here are a few starters:
1) you need to install python 3+ (python 2.something differs in a lot of things from python 3.something, its important to be consistent with that so unless     there is any resistance, we'll start in python3)
2)some important links:
    https://github.com/ccxt/ccxt - a huge open source repository owned by MIT, which implements (in javascript,php and python) public and private apis for huge amount of exchanges.
        (public - getting general info from exchanges like prices, exchange pairs etc., 
        private - registered user options, like buy,sell, account info etc.)

    https://www.cryptocompare.com/api/ - an api giving market data from various exchnges

    https://medium.com/@agalea91/cryptocompare-api-quick-start-guide-ca4430a484d4 - a detailed explanation with examples of how to implement in python some features from the cryptocompare api.
    
    
    

for now theres a super basic test.py file which in most is copied from the 3rd url above, and have the option to return a live price of given pairs
usage: price(<From coin symbol>, <array of To coin symbols>)

example:
open python3 terminal in the same folder as test.py
then:

"
import test
print(test.price('BTC',['USD','ETH']))
"

(if it tells you youre missing some module/library, use "pip installer" - 
for example if it tells you you're missing the module named "requests", you just do "pip install requests" in python terminal)