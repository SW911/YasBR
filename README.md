# YasBR
Yet another simple BitCoin Rotator

## Dependency
1. jQuery

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
