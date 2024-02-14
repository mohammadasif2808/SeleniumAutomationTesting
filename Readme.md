### Console Commands
$('p.error')            use this in the console to check for unique css selector

## Locators Available
- Id
- Xpath
- Css selector
- name
- Class name
- Tag name
- Link Text
- Partial Link Text

## ways to use locator
### Css Selector
- Class name -> tagname.classname ->  Button.signInBtn -> .error
- Id -> tagname#id      ->   input#inputUsername
- Tagname[attribute=’value’]
- <input type="text" placeholder="Username” value=" ">

- Input [placeholder=’ Username’]

- //Tagname[@attribute=’value’]:nth-child(index). -  Child items
- Parenttagname childtagname
- input[type*='pass'] – CSS
- tagname




### Xpath
- //Tagname[@attribute=’value’]
- //input[@placeholder=’ Username’’]
- ```<input type="text" placeholder="Name">```
- //input[@placeholder=’ Name’]
- //Tagname[@attribute=’value’][index]
- //parentTagname/childTagname
- //button[contains(@class,'submit')].  – Regular expression
- //tagname
- //header/div/button[1]/following-sibling::button[1]
- //header/div/button[1]/parent::div
