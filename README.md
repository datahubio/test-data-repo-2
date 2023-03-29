CBOE Volatility Index (VIX) time-series dataset including daily open, close,
high and low. The CBOE Volatility Index (VIX) is a key measure of market
expectations of near-term volatility conveyed by S&P 500 stock index option
prices introduced in 1993.

# Data components

## FrictionlessView

```
<FrictionlessView viewId={0} />
```

<FrictionlessView viewId={0} />


```
<FrictionlessView fullWidth viewId={0} />
```

<FrictionlessView fullWidth viewId={0} />


## Table

```
<Table url="data/vix-daily.csv" />
```

<Table url="data/vix-daily.csv" />


```
<Table fullWidth url="data/vix-daily.csv" />
```

<Table fullWidth url="data/vix-daily.csv" />


## Vega and Vega Lite

```
<VegaLite data={ { "table": [ { "y": -0.418, "x": 1850 }, { "y": 0.923, "x": 2020 } ] } } spec={ { "$schema": "https://vega.github.io/schema/vega-lite/v4.json", "mark": "bar", "data": { "name": "table" }, "encoding": { "x": { "field": "x", "type": "ordinal" }, "y": { "field": "y", "type": "quantitative" } } } } />
```

<VegaLite data={ { "table": [ { "y": -0.418, "x": 1850 }, { "y": 0.923, "x": 2020 } ] } } spec={ { "$schema": "https://vega.github.io/schema/vega-lite/v4.json", "mark": "bar", "data": { "name": "table" }, "encoding": { "x": { "field": "x", "type": "ordinal" }, "y": { "field": "y", "type": "quantitative" } } } } />


```
<VegaLite fullWidth data={ { "table": [ { "y": -0.418, "x": 1850 }, { "y": 0.923, "x": 2020 } ] } } spec={ { "$schema": "https://vega.github.io/schema/vega-lite/v4.json", "mark": "bar", "data": { "name": "table" }, "encoding": { "x": { "field": "x", "type": "ordinal" }, "y": { "field": "y", "type": "quantitative" } } } } />
```

<VegaLite fullWidth data={ { "table": [ { "y": -0.418, "x": 1850 }, { "y": 0.923, "x": 2020 } ] } } spec={ { "$schema": "https://vega.github.io/schema/vega-lite/v4.json", "mark": "bar", "data": { "name": "table" }, "encoding": { "x": { "field": "x", "type": "ordinal" }, "y": { "field": "y", "type": "quantitative" } } } } />

## Line chart

```
<LineChart data={
    [
      ["1850",-0.41765878],
      ["1851",-0.2333498],
      ["1852",-0.22939907],
      ["1853",-0.27035445],
      ["1854",-0.29163003]
    ]
  }
  />
```

<LineChart data={
    [
      ["1850",-0.41765878],
      ["1851",-0.2333498],
      ["1852",-0.22939907],
      ["1853",-0.27035445],
      ["1854",-0.29163003]
    ]
  }
/>


```
<LineChart fullWidth data={
    [
      ["1850",-0.41765878],
      ["1851",-0.2333498],
      ["1852",-0.22939907],
      ["1853",-0.27035445],
      ["1854",-0.29163003]
    ]
  }
  />
```

<LineChart fullWidth data={
    [
      ["1850",-0.41765878],
      ["1851",-0.2333498],
      ["1852",-0.22939907],
      ["1853",-0.27035445],
      ["1854",-0.29163003]
    ]
  }
/>


## Image

```
<Image src="https://i0.wp.com/abglt.org.br/wp-content/uploads/2020/10/wallpaper-pc1-scaled-1.jpg?fit=2560%2C1440&ssl=1" />
```

<Image src="https://i0.wp.com/abglt.org.br/wp-content/uploads/2020/10/wallpaper-pc1-scaled-1.jpg?fit=2560%2C1440&ssl=1" />


```
<Image fullWidth src="https://i0.wp.com/abglt.org.br/wp-content/uploads/2020/10/wallpaper-pc1-scaled-1.jpg?fit=2560%2C1440&ssl=1" />
```

<Image fullWidth src="https://i0.wp.com/abglt.org.br/wp-content/uploads/2020/10/wallpaper-pc1-scaled-1.jpg?fit=2560%2C1440&ssl=1" />

