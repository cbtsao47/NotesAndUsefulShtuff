# Flex box Day

**images from CSS-Tricks**
**[CSS-TRICKS](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)**

---

![Flex model](https://i.imgur.com/uxQI7sl.png)

- Main axis
  -default horizontal line from left to right ( start to end )
  -associated with `justify-content` property
- Cross axis
  -default vertical line from top to bottom ( start to end )
  -associated with `align-items` property
- Flex direction
  -default to be row ( horizontally from left to right )
- Flex wrap
  -default to no wrap

### Flex box is a module that contains a parent and children

## **A parent container is called a Flex Container and a child container is called a Flex Item in flex box terminology**

![Flex Container](https://i.imgur.com/efZUy5A.png)

- You set `display:flex` on a parent container to make the container display the direct children inside in `flex` mode ( awesome mode )

```
.example-container{
    display: flex;
}
```

# `display:flex` is required in the parent container for any flex properties to work !!!!!

---

![Flex items(children)](https://i.imgur.com/eo5ieKO.png)

- You don't need to set any properties on the children at all.
- There are some `Flex item` properties you can assign them with

```
.example-item{
    order:1
}
```

---

### Flex Container Properties

---

![flex-Direction](https://i.imgur.com/e1or6BC.png)
![flex-wrap](https://i.imgur.com/D88Qr25.png)
![justify-content](https://i.imgur.com/UgKYK8H.png)
![align-items](https://i.imgur.com/bh71b5a.png)
![align-content](https://i.imgur.com/yxcsUWK.png)

### Flex Items Properties

---

![order](https://i.imgur.com/QsmhQ7f.png)
![flex-grow](https://i.imgur.com/2Up8yP6.png)
![flex-shrink](https://i.imgur.com/Yd2EaEf.png)
![flex-basis](https://i.imgur.com/0fS3qy9.png)
![align-self](https://i.imgur.com/5HFy34z.png)
