![Laticss](http://i.imgur.com/6alQr3p.png)

*Intuituve, scalable and simple micro framework-grid system*

With Laticss YOU choose how many columns you want ! You can work with 2, 3, 4, 5, 6, 8, 10, 12 columns and more combinations !

Quick start
-----------
So, let's begin !

A simple exemple with 5 columns

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Laticss - test</title>
        <link href="laticss.css" rel="stylesheet">
    </head>
  
    <body>
        <!-- We want 5 columns, we divide by 5 -->
        <div class="row div5">
            <div class="use">
                <p>Ok, I'm one column</p>
            </div>
        
            <div class="use3">
                <p>I'm tree columns !</p>
            </div>
            
            <div class="use">
                <p>And me, I'm the last column</p>
            </div>
        </div>
    </body>
</html>
```

 * `.row` : Create a row
 * `.divN` : The number of columns you want (N can be 2, 3, 4, 5, 6, 8, 10, 12)
 * `.useN` : Use the number of columns you want (with N < the divN parent) (`use` is an alias for `use1`)
 * `.offN` : Add offset (0 < N < 12) (`off` is an alias for `off1`)

So, if you want 24 columns you can use `div2` and `div12`.
You want 40 columns ? Divide by 4 (`div4`) and divide each columns by 10 (`div10`). Easy, no ?

If you want a responsive grid just add `laticss-responsive.css` to your page.
