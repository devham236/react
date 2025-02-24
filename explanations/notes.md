# Notes

- Warum kann man nicht mehrere Elemente in React bzw. im JSX einer Komponente hinzufügen, zum Beispiel so:

```js
function MyComponent() {
    return(
        <h1>Hello World</h1>
        <p>lorem ipsum</p>
    )
}
```

- Weil letztenendes der Browser bzw. Javascript die Methode "createElement()" verwendet und in dieser Methode man nur ein Element als Argument übergeben kann:

```js
const newElement = createElement("h1");
```
