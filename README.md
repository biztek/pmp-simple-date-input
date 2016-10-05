[![Build Status](https://travis-ci.org/biztek/pmp-simple-date-input.svg?branch=master)](https://travis-ci.org/biztek/pmp-simple-date-input)

_[Demo and API docs](https://rajkumarajce.github.io/pmp-simple-date-input/components/pmp-simple-date-input)_

# \<pmp-simple-date-input\>

`<pmp-simple-date-input>` is a single-line text field to hold valid Date of Birth of pattern MM/DD/YYYY.

```html
<pmp-simple-date-input label="Input label"></pmp-simple-date-input>
```

It includes an optional label,invalid,autovalidate and required attributes.

```html
<pmp-simple-date-input label="Input label"></pmp-simple-date-input>
<pmp-simple-date-input invalid="boolean value"></pmp-simple-date-input>
<pmp-simple-date-input autoValidate="boolean value"></pmp-simple-date-input>
<pmp-simple-date-input required="boolean value"></pmp-simple-date-input>
```

### Listening for input changes

By default, it listens for changes on the `bind-value` attribute on its children nodes and perform
tasks such as auto-validating and label styling when the `bind-value` changes.

### Validation

If the `auto-validate` attribute is set, element validates the input whether it is valid date of pattern MM/DD/YYYY  and DOB falls within 18years from now and update
the label styling when the input value changes.

