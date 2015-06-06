## Short Stack: Simple & Lightweight Responsive Tables

Short Stack is a simple & lightweight (< 1kb minified, 411bytes to be exact) collection of CSS styles that provide a simple stacking mechanism for table rows on mobile screens. Short Stack is easily customizable to suit your needs, and plays very nicely with front-end frameworks.

## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
short-stack/src/
├── css/
│   ├── short-stack.css
│   └── short-stack.min.css
├── less/
│   └── short-stack.less
└── sass/
    └── short-stack.scss

```


## How To

Using Short Stack is very straight forward. Simply add the class "short-stack" to any table and you're done.

### Example:

```html
<table class="short-stack">
    <thead>
        <tr>
            <th>Column Heading 1</th>
            <th>Column Heading 2</th>
            <th>Column Heading 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td data-label="Column Heading 1">Some column text</td>
            <td data-label="Column Heading 2">Some column text</td>
            <td data-label="Column Heading 3">Some column text</td>
        </tr>
        <tr>
            <td data-label="Column Heading 1">Some column text</td>
            <td data-label="Column Heading 2">Some column text</td>
            <td data-label="Column Heading 3">Some column text</td>
        </tr>
                <tr>
            <td data-label="Column Heading 1">Some column text</td>
            <td data-label="Column Heading 2">Some column text</td>
            <td data-label="Column Heading 3">Some column text</td>
        </tr>
                <tr>
            <td data-label="Column Heading 1">Some column text</td>
            <td data-label="Column Heading 2">Some column text</td>
            <td data-label="Column Heading 3">Some column text</td>
        </tr>
    </tbody>
</table>

```
