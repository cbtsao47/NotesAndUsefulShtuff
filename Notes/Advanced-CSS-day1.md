# RWD

- Responsive Web Design

### Adaptive

- uses media queries

### Fluid

- uses % based layout

### Responsive

- uses both media queries and % based layout

## View Port

- viewport basically means screen size (browser window size)

```
<meta name="viewport" content ="initial=scale=1.0, maximum-scale=1.0, user-scalable=no">
```

- the viewport meta tag tells the browser that there's a viewport property that the browser can use (via CSS to change how the page looks)

- us the developer console to help you with different resolutions on

#### Media Query

```
@media (max-width:500px){
    .container{
        background:gray;
    }
}
```

- tells the browser to use the style when the width is 500px and below

```
@media (min-width:500px){
    .container{
        background:gray;
    }
}
```

- tells the browser to use the style when the width is 500px and above
