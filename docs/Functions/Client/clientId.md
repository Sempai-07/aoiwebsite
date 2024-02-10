# $clientId

## Usage

Unique identifier for this user or bot. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier

## Example

```javascript
<AoiClient>.addCommand({
  name: "command",
  code: `$replyMessage[$clientId]`,
});
```
