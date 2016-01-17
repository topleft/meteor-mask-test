```
meteor add sewdn:masked-input

Template.templateName.rendered = function () {
  $('input').mask('(999) 999-9999', {placeholder: ' '})
}

```