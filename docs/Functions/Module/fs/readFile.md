# $readFile

This function reads the contents of a file at the specified path.

## Parameters

| Parameter | Description                               |
| --------- | ----------------------------------------- |
| filePath  | Path to the file to read the contents of. |

## Example

```js
<AoiClient>.addCommand({
  name: "misc",
  code: `
    $readFile[path/to/file.txt]
  `,
});
```
