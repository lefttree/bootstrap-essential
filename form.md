#Form

## Basic Form

- `<label>`
- `<input class="from-control">`

`<div class="form-group"></div>` to make a little bit space between label, inputs

```html
<div class="form-group">
    <label for="inputName">Name</label>
    <input class="form-control" type="text" id="inputName" placeholder="Your name">
</div>
```

## Radio & Checkbox Contorols


```html
<div class="radio">
    <label>
        <input name="options" type="radio">
        One
    </label>
</div>

<div class="radio">
    <label>
        <input name="options" type="radio">
        two
    </label>
</div>
```

## inline form

`<form class="form-inline"></form>`

## Horizontal form

```
<form class="form-horizontal">
    <div class="form-group">
        <label class="col-sm-2 control-label" for="inputEmail">Email</label>
        <div class="col-sm-10">
            <input class="form-control" id="inputEmail" placeholder="Email">
        </div>
    </div>
</form>
```

## Validation styles

validation Style

```
<div class="form-group has-success">
    <label class="control-label" for="inputEmail">Email</label>
    <input class="form-control" id="inputEmail" placeholder="Email">
</div>
```

feedback

```
<div class="form-group has-success has-feedback">
    <label class="control-label" for="inputEmail">Email</label>
    <input class="form-control" id="inputEmail" placeholder="Email" aria-describedby="nameStatus">
    <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
    <span id="nameStatus" class="sr-only">(success)</span>
</div>
```

## Input groups

```html
<div class="form-group">
    <div class="input-group">
        <span class="input-group-addon">$</span>
        <input class="form-control" id="inputEmail" placeholder="Email">
    </div>
</div>

```

```html
<div class="form-group">
    <div class="input-group">
        <input type="text" class="form-control" placeholder="Search items">
        <span class="input-group-btn">
            <button class="btn btn-default" type="button">Search</button>
        </span>
    </div>
</div>

```

## miscellaneous style and sizing

- `<fieldset>`
- `disabled` attribute
- `readonly` attribute
- `.form-control`

## icons

- glyphicons
