# Class 4 Notes

## CSS

Using CSS, you can control exactly how HTML elements look in the browser.
specifying how documents are presented to users — how they are styled, laid out, etc.

CSS is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

 ```h1 {
    color: red;
    font-size: 5em;
}```

Opens with selector, followed by curly braces, inside of which are one or more declarations called property and value

#### 3 ways to insert
- External
- Internal
- Inline

#### Assigning color can be assigned using different values
* HEX body {color: #92a8d1;}
* RGB body {color: rgb(201, 76, 76);}
* RGBA body {color: rgba(201, 76, 76, 0.6);}
* HSL body {color: hsl(89, 43%, 51%);}
* HSLA body {color: hsla(89, 43%, 51%, 0.6);}

#### Basic rule syntax
```style-rule ::=
    selectors-list {
      properties-list
    }

Where :

selectors-list ::=
    selector[:pseudo-class] [::pseudo-element]
    [, selectors-list]

properties-list ::=
    [property : value] [; properties-list]
```

[Home](README.md)