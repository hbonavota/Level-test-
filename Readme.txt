# Frontend Test Task

## main file

+ index.html

## Styles -->

+ styles /

## Information To Change Bar Progress (Javascript)
+ To change the progress bar you must access the 'Id' and then the ::before as follows

```
window.getComputedStyle(document.querySelector('#bar1-progress', '::before'));

window.getComputedStyle(document.querySelector('#bar2-progress', '::before'));
```
+ after use the property


```

getPropertyValue('width') // to access

setPropertyvalue('width','newValue') // to change
```