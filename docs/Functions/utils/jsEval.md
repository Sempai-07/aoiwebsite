# $jsEval

Evaluates JavaScript code and returns the result.

## Parameters

| Parameter | Description                      |
| --------- | -------------------------------- |
| content   | JavaScript code to be evaluated. |

## Example

```js
<AoiClient>.addCommand({
  name: "misc",
  code: `
    $jsEval[2 + 2]  // Returns the result of the JavaScript expression
  `,
});
```
