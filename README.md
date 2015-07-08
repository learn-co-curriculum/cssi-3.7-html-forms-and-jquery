---
tags:
level:
languages:
resources:
---
# Html Forms And Jquery

Lots of the interaction on the web happens through forms. (For the most part) Whenever you are typing something into a box, clicking a checkbox or radio button, or sliding a slider, you are interacting with an HTML Form.

Facebook status update? Form. Tweet? Form. Instagram picture upload? Form!

So, how do we get form data with jQuery?

Well, as users are entering text in HTML text fields or changing values of checkboxes, sliders, and radio buttons, the browser is smart enough to already be updating the DOM with that information. Because the data is in the DOM, we can get it with javascript, and use it!

```
var user_text = $('input').val()
```
