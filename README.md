# YasBR - Yet another simple BitCoin Rotator

## Usage
This software will give you a framework, that will help claim BitCoins from all configured faucets.

The faucets are configured in the _faucets.js_.

```javascript
var obj = {
	url : "http://", // this is the URL where the BitCoin Faucet is located
	name : "",       // this is the name of button.
	timer : "",      // the time between Claims.
	iframe : "true"  // some of the faucets dont allow to be displayed in an iFrame, this is configured here
};
```

All the configured faucets will be displayed as a list of buttons.
After you click on one of the buttons the faucet will be displayed in an iframe.

Additionally you can save your walletId in the _faucets.js_.
```javascript
var walletId = "32etfEUfSpdvaYxq9mbRG7EQLWYhntYCPS";
};
```
The configured WalletId will be displayed and it should help you with some faucets where you have to enter your walletId.

## Dependency
1. jQuery
