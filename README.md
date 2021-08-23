# minimal-bitbay-wallet-parser
A short python script to calculate the value of your bitbay crypto portfolio.
## Usage
Specify keys and voila.
```python
PUBLIC_KEY = "<BB public key>"
SECRET_KEY = "<BB private key>"

bitbay = BitBay(PUBLIC_KEY, SECRET_KEY)
wallet_value = bitbay.wallet_value()
```
