> # HTML Forms:

The HTML `<form>` element defines a form that is used to collect user input.Some of the attributes of `<form>` element are:


1. action attribute:

    The action attribute defines the action to be performed when the form is submitted.


2. target attribue:

    The target attribute specifies if the submitted result will open in a new browser tab, a frame, or in the current window.

    - `_self` value(default): the form will be submitted in the current window.

    - `_blank` value: make the form result open in a new browser tab.


3. method attribute:

    The method attribute specifies the HTTP method (`GET` or `POST`) to be used when submitting the form data.

    - `GET` value(default):

        When `GET` is used, the form data will be visible in the page's address field.

    - `POST` value:
        
        The `POST` method does not display the form data in the page address field.So if the form data contains sensitive or personal information, always use `POST`.


__SYNTAX:__
```html
<form action="#" target="_self or _blank" method="GET or POST">

    <label for="*"> </label>

    <input type="" id="*" name="*" value="" placeholder=""/>
    <!--value of (name ,id , for) should be same*-->

    .
    .
    .
</form>
```

>  ## HTML input Element:

The `<input>` element is the important element in HTML form.Some of the attributes of `<input>` element are:

1. type attribute:

    - `<input type="text">`:	Defines a single-line text input field

    - `<input type="radio">`:	Defines a radio button (for selecting one of many choices)

    - `<input type="submit">`:	Defines a submit button (for submitting the form)

2. name attribute:

    Each input field must have a name attribute to be submitted.If the name attribute is omitted, the data of that input field will not be sent at all.
