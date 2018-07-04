# Html

### Doctype

Browser use doctype to determine hoe to render page.

### HTML 5 features


### HTML 5  API


### HTML5 new Form Elements
1. datalist
```
An <input> element with pre-defined values in a <datalist>

<input list="browsers">

<datalist id="browsers">
  <option value="Internet Explorer">
  <option value="Firefox">
  <option value="Chrome">
  <option value="Opera">
  <option value="Safari">
</datalist>

 ``` 
  2.output
  ```
  ```
  
  
#### New Input Types

```
New Input Types	

color
date
datetime
datetime-local
email
month
number
range
search
tel
time
url
week

New Input Attributes

autocomplete
autofocus
form

formaction
 <button type="submit" formaction="/action_page2.php">Submit to another page</button>
 
formenctype
formmethod
formnovalidate
formtarget
height and width
list
min and max
multiple

pattern (regexp)
<input type="password" name="pw" pattern="(?=.*\d)(?=.*[a-z])(?=.*[A-Z]).{8,}" title="Must contain at least one number and one uppercase and lowercase letter, and at least 8 or more characters">

placeholder
required
step
```

#### picture tag
```
<picture> element will be for art direction in responsive designs. Instead of having one image that is scaled up or down based on the viewport width, multiple images can be designed to more nicely fill the browser viewport.

<picture>
  <source media="(min-width: 800px)"
          sizes="80vw"
          srcset="lighthouse-landscape-640.jpg 640w,
                  lighthouse-landscape-1280.jpg 1280w,
                  lighthouse-landscape-2560.jpg 2560w">
  <img src="lighthouse-160.jpg" alt="lighthouse"
       sizes="80vw"
       srcset="lighthouse-160.jpg 160w,
               lighthouse-320.jpg 320w,
               lighthouse-640.jpg 640w,
               lighthouse-1280.jpg 1280w">
</picture>

```





