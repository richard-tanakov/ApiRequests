# ApiRequests

To create queries, I used the libraries 
To get information about Token used the libraries: os,requests,dotenv,time,json

I used pipenv package manager as well as pipenv as a virtual environment. (Documentation)[https://pipenv.pypa.io/en/latest/] 

```
sudo apt install software-properties-common python-software-properties
sudo add-apt-repository ppa:pypa/ppa
sudo apt update
sudo apt install pipenv
```


send the token type at the request 
like Coin: Sui is: 0x2::sui::SUI

Token.parserInfo()


The Token class gives data in the format dict the list of given data below. The query time for one coin can be up to a minute, because if you remove the pauses between them Sui gives the text that there are too many queries

adress
coinType
coinName
coinSymbol
imgUrl
description
securityMessage
decimals
price
dominance
marketCap
circulatingSupply
creatorAddress
maxSupply
fdv
holdersCount
isVerified
isBridged
queryCount
uniqueQueryCount
gptSummary
onChainAt
urlCoin
totalSupply
volume
socialWebsite
socialDiscord
socialEmail
socialGitHub
socialTelegram
socialTwitter
totalElements 



