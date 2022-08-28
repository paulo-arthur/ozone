# Ozone

## Stylizing a website can be a difficult task, right? Ozone is an ultra-simple style sheet that provides many tools to upgrade a website build process.

Ozone uses pre-declared classes to speed up the building of websites. All the classes are declared in the `ozone.css` file.

## List of Classes:
### Colors:
Some colors are declared in the `root`.

* --default-black: #212529;
* --shiny-black: #313235;
* --shadow: #14141495;
* --default-gray: #ccd0d4;
* --default-white: #eaf6ff;

### ozone:
The `ozone` class sets font-color and background-color to the page and should be applied on the `body` tag.

### box:
The `box` class creates a simple box on the screen.

### horizontal-menu:
The `horizontal-menu` class creates a menu bar and all the list elements inside will be displayed inline.

### row:
The `row` class is a structural class and displays all the elements inside a row.

### column:
The `column` class is a structural class and displays all the elements inside a column.

### Icons:
There are 4 sizes of icons: `s-icon`, `m-icon`, `l-icon`, `xl-icon`.
* s-icon  -> 15px
* m-icon  -> 30px
* l-icon  -> 50px
* xl-icon -> 75px

### text-input:
The `text-input` class provides style to the `input` tags.

### button:
The `button` class provides style to the `button` tags.

### parralax:
The `parallax` class configures a container to roll with the parallax effect.
```
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
```

### image:
The `image` class just set the `width` size to 100%.

### footer:
The `footer` class sets a `margin-top: 10rem` to space a container from the other elements.