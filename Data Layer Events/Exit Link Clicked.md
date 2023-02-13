# Exit Link Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Exit Link Clicked",
    "linkInfo": {
        "linkId": "<linkId>",
        "linkTarget": "<linkTarget>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkInfo.linkId|string|Identifier of the link clicked|act now, cancel, ok, 3456, 8765|||||||
|linkInfo.linkTarget|string|HREF of the link.  Primarily useful for exit link tracking. |https:\/\/www.usda.gov. https:\/\/msnbc.com|||||||




