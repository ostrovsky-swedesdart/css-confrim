# Using to lib:

```js
import ArrayFrom from "css-confrim";

const body = ArrayFrom({
name: "back",
tag: { color: "red", bancroudcolor: "blue" },
type: true
});

console.log(body) /* <style>
back {
color:red;
bancroudcolor:blue;
}
</style> */
```