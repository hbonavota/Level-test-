# Frontend Test Task

## Main file

+ index.html

## Styles -->

+ styles /


# UPDATE

## Information To Change Bar Progress

+ To change the progress bar you must access the "progress-bar-fill" class or the id = "progress-fill" and modify the width property of it.

+ Example:
____
```
.progress-bar-fill {
  width: 75%;
} 

Or

#progress-fill {
width: 75%;
}
```

+ Or inline-style ( take in the span id="progress-fill" and modify the style inline )

```

<span id="progress-fill" class="progress-bar-fill" style= width:75%></span>


```

### Important: 
+ hardcoding was used to display the two positions that the progress bar has (39.9% and 100%) and were added to the media queries for sample purposes only.