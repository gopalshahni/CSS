# CSS SLECTORS 

## Universal Selector
```html 
*{
    here style will be applied to all elements 
}

```

## Type Selector
```html
    h1,p,div etc
```

## Class Selector 
- Select many elements at one time 
- denoted by '.' in css
```html
    <div class="card"> ,, .card
```

## Id Selector
- Select only one element 
- denoted by '#' in css
```html
    <img src="animal"> ,, #animal
```

## attribute Selector 
- used for selecting properties/attributes of element 
- example input element
```html
 <input types = "text"> ,, input [type = 'text'] in the css 
```

## Descendant Selector 
- works on all the elements who are descendent of an root element 
- example
```html
      <div> <p></p></div> ,, div p{} in css
```

## Child Selector
- works only on child if there is more level down so the they refered as descendent

- example 
``` html
    <div><p></p></div> ,, div > p ,, so this will select all p in div and if there is a case <div><section><p></p></section></div> ,, it will be ignored.
```

## Adjacent Sibiling Selector 
- you have a same sibiling in you tree 
- example
```css
    h1 + p {}
```

## General Sibiling Selector
- Select all the sibilings from all places no matter what , if its the sibiling then it will be used 
- example
```css
    h2 ~ p {}
```

## Pseudo Class Selectors 
- usually used on some action is happen by user 
- easiest example 
- ``` css 
    button: hover {background-color : blue ;}
``
## Pseudo Elemnet Selector
- same like psuedo but gives more control over element 
- example Writing the first letter bold of each p for magazine sites

```css 
    p::first-letter { font-size:30px}
```
## Group Selectors 
- name define its meaning own
- example
``` css
    h1,div,p {some style here}
```
