# $modulo

Returns operation / the remainder when dividing.

## Parameters

| Parameter | Description                       |
| --------- | --------------------------------- |
| number    | Number to return the remainder of |
| number    | Number to return the remainder of |

## Example

```js
<AoiClient>.addCommand({
  name: "math",
  code: `
    $replyMessage[$modulo[16;6]]
   `,
});
```
