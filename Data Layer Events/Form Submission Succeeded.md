# Form Submission Succeeded

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Form Submission Succeeded",
    "form": {
        "formID": "<formID>",
        "formName": "<formName>",
        "formType": "<formType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|form.formID|string|Unique identifier of a form. |F-0113, 2543, CU001, PI-0988|||||||
|form.formName|string|Plain text form name. Generally used if formID is not obtainable. |Payment Info, Mailing Address, Payment Address, Contact Us|||||||
|form.formType|string|Form type used for grouping of similar forms in reports.  |Address, Contact, Comment, Review, Payment|||||||




