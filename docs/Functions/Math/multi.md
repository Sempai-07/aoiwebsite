# $multi

Returns will multiplicate given number

## Parameters

| Parameter | Description                 |
| --------- | --------------------------- |
| number    | Number you want to multiply |
| number    | Number you want to multiply |

## Example

```js
<AoiClient>.addCommand({
  name: "math",
  code: `
    $replyMessage[$multi[6;8]]
   `,
});
```
