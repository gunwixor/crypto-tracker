# Crypto Tracker

Crypto Tracker is a Python module that allows you to track the prices of cryptocurrencies in real-time. You can specify the cryptocurrency you want to track and the module will provide you with live updates on its price.

<h3 align="center">

[![PyPi license](https://badgen.net/pypi/license/pip/)](https://pypi.org/project/coinprice/)
[![PyPI download month](https://img.shields.io/pypi/dm/coinprice.svg)](https://pypi.org/project/coinprice/)
[![PyPI format](https://img.shields.io/pypi/format/coinprice.svg)](https://pypi.org/project/coinprice/)
[![PyPi version](https://badgen.net/pypi/v/coinprice/)](https://pypi.org/project/coinprice)
[![GitHub branches](https://badgen.net/github/branches/7GitGuru/crypto-tracker)](https://github.com/7GitGuru/crypto-tracker/branches)
[![GitHub release](https://img.shields.io/github/release/7GitGuru/crypto-tracker.svg)](https://github.com/7GitGuru/crypto-tracker/releases/)

<!--- 
[![Github all releases](https://img.shields.io/github/downloads/7GitGuru/crypto-tracker/total.svg)](https://github.com/7GitGuru/crypto-tracker/releases/)

[![PyPI version fury.io](https://badge.fury.io/py/coinprice.svg)](https://pypi.org/project/coinprice/) 
-->

</h3>

---
## Features

- Track the prices of various cryptocurrencies.
- Flexible Command-line Usage.
- Customizable.
- Set a custom interval for price updates.
- Open-source project.

--- 

![image](https://github.com/7GitGuru/crypto-tracker/assets/154711952/e931d7e4-8714-4dd2-8051-aba7bfe0756d)

----

## Installation

You can install Crypto Tracker using pip:

```
pip install coinprice
```

## Usage

To track the price of a cryptocurrency, simply run the following command:

**[Here you can find a list of all cryptocurrencies you can use.](https://github.com/7GitGuru/crypto-tracker/blob/main/coin-names.json)**

```
price <coin> [--interval time]
```

Replace `<coin>` with the cryptocurrency you want to track (e.g., bitcoin, ethereum). You can optionally specify the interval (in seconds) for price updates using the `--interval` flag. By default, the interval is set to 15 seconds.

Example usage:

```
price btc                        Track the price of Bitcoin from all exchanges.
price eth --binance              Track the price of Bitcoin from Binance.
price ltc --bybit --interval 10  Track the price of Litecoin from Bybit with a check interval of 10 seconds.
```

### [Check out Telegram version!](https://github.com/7GitGuru/crypto-tracker/tree/telegram)

## Contributing

Contributions to Crypto Tracker are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request on GitHub.

## License

Crypto Tracker is released under the MIT License. See [LICENSE](https://github.com/7GitGuru/crypto-tracker/blob/main/LICENSE) for details.

### Show your support:

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/bohd4n)
