# Cryptoprice: a CLI tool to check the price of a given cryptocurrency in USD

## Installation:
Just download the script into a folder where you keep executables (like .local/bin or /usr/local/bin), and make it executable with chmod +x. 

## How it runs:
It's fairly straight forward. Here's an example:

```
cryptoprice monero
```

Unfortunately, short names like BTC, XMR, ETH etc. don't work, but i might look into adding that functionality in the future. Using any uppercase letters won't work either, so you will get an error if you try "cryptoprice Bitcoin" for example.

## Dependencies:
The only dependencies are curl, jshon the json parser, cut and rev. You can remove/modify cut and rev if you need that many decimals for some (probably dumb) reason.
