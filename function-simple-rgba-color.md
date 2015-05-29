# Simple RGBa Color Function

You can use this simple RGBa color function to the alpha transparency of your colors.

*Be sure you ```@import``` compass*

### Function Creation
```scss
@import "compass";

@function white($opacity) {
    @return rgba(255,255,255,$opacity)
}
```

### Function Usage

```scss
/* 
* - Declare the white color function and set the alpha transparency to .75
*/
h1 {
    color: white(.75);
}
```
