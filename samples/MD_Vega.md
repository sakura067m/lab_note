[Vega](https://shd101wyy.github.io/markdown-preview-enhanced/#/diagrams?id=vega-and-vega-lite)

```vega-lite
{
    "$schema": "https://vega.github.io/schema/vega-lite/v2.json",
    "description": "",
    "data": {
        "values": [
            {
                "a": "A",
                "b": 20,
            },
            {
                "a": "a",
                "b": 55,
            },
            {
                "a": "A",
                "b": 20,
            },
            {
                "a": "A",
                "b": 20,
            },
            {
                "a": "A",
                "b": 20,
            },
            {
                "a": "A",
                "b": 20,
            },                {
                "a": "A",
                "b": 20,
            },
            {
                "a": "A",
                "b": 20,
            },
        ],
    },
    "mark": "bar",
    "encoding": {
        "x": {
                "field": "a",
                "type": "ordinal",
            },
        "y": {
                "field": "b",
                "type": "quantitative",
            },
    },
    "width": 500,
    "height": 400,
}
```
