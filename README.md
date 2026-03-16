# chart-line

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web component that creates a line chart from CSV data.

## Demo
[https://code4fukui.github.io/chart-line/](https://code4fukui.github.io/chart-line/)

## Features
- Supports single or multiple line datasets
- Responsive design that scales to the container size
- Customizable with attributes for minimum value, color, etc.
- Can load data from inline text or external CSV file

## Usage
To use the `<chart-line>` element, include the `chart-line.js` file and add the element to your HTML:

```html
<script type="module" src="./chart-line.js"></script>
<chart-line>
  name,value
  A,30
  B,20
  C,70
</chart-line>
```

Alternatively, you can load the data from an external CSV file:

```html
<chart-line src="https://example.com/data.csv"></chart-line>
```

## Data / API
This project uses the [D3.js](https://d3js.org/) library for data visualization and the [CSV.js](https://js.sabae.cc/CSV.js) library for parsing CSV data.

## License
MIT License — see [LICENSE](LICENSE).