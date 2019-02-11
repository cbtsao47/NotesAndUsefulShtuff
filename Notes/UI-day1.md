# HTML- Hyper Text Markup Language

## href= hyper text reference

```
<a href='http://lambdaschool.com/' target="_blank">Lambda School</a>
```

- href is an attribute
- anything inside a tag is an attribute
- target links the website out ( creating a new tab )

```
<!DOCTYPE html>
```

- self closing
- tells the browser that this document is a html type, therefore using a set of standards that a group of nerds agreed upon.
- without it, it's hard to communicate between browsers

##### Standards

```
<h1>This is a tag following the standards</h1>
```

##### No Standards

```
<airport>This is a random custom tag!</airport>
```

##### Semantic === Meaningful

1. Accesibility ( for screen readers etc )
2. Developer reading your code ( easier to read for yourself in 6 months and other people )
3. SEO, google, bing, yahoo ( easier to read for search engines )

##### Presentational === Style

1. Layout of the site ( UX )
2. Marketing to your users ( instruction of your site )

```
<div class='container'>
        <header>
            <h1>International Airport</h1>     <!-- shows as the first thing in google -->
            <nav>
                <a>link 1</a>
                <a>link 2</a>
            </nav>
        </header>
</div>
<section>                                     <!-- basically a semantic div -->
    <h2>Fly with us</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime similique ad possimus non nesciunt, quaerat quidem dolores velit placeat iure commodi, tempora aliquam sequi tenetur et illo rem ea quae!

Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id fugit at suscipit, magnam blanditiis qui eum magni unde, veritatis quas neque possimus tempora est mollitia ex. Voluptatibus quo inventore itaque.

</p>

</section>
```

##### CSS

- called user agent stylesheet in chrome

[selector type] {
[property name]:[property value];
}

###### selector type

**universal selector**
\*{
color:red;
box-sizing:border-box;
}
**tag selector**
header{
color:red;
}
h1{
color:blue;
}
p{
color:purple;
}
**class selector**
.classname{
color:black;
}
.container{
color:green;
}
.random-class-name{
color:white;
}
**ID selector**

#idname{
font-size:16px;
}

- only one specific name per id, very high specificity
  **nested selector**
  header nav a{
  color:blue;
  }
  <!-- selects the specific a tag that's inside a nav tag that's inside a header tag, more specific -->

**property name**
https://www.w3schools.com/cssref/

**comments in CSS**
/_ write your comments in here. won't be read by the compiler _/
