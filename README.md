# cryptodash

> Cryptocurrency information and charts displayed in a dashboard from your terminal.

<img src="./screenshot.png" width="750">

# Install

Make sure to have [golang](https://golang.org/) installed, then do:

```bash
go get -u github.com/miguelmota/cryptodash/cryptodash
```

# Usage

```bash
$ cryptodash {coin} {chart_date_range ie. 1h | 1d | 2d | 7d | 30d | 2w | 1m | 3m | 1y}
```

Example for getting latest ethereum info, and chart data for last 30 days.

```bash
$ cryptodash ethereum 30d
```

## Notes

- Data gets polled once every minute.

- Data is from [Coin Market Cap](https://coinmarketcap.com/)

# License

MIT
