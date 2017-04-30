# HTML-CSS-jQuery
HTML-CSS-jQuery Example Repository

- Collapsing Header
- Hover Effect via CSS
- Slide over menu

# Collapsing Header

This will fix header and keep it top of the stack, fix banner with content scrolling under header.

[https://github.com/adityasingh11/HTML-CSS-jQuery/tree/master/Collapsing%20Header]

# Hover Effect

Suppose you define a div container and gave it an id as "alpha"
```
alpha{
  background-image = url("space-picture.jpg");
}
```

To apply hover effect on this you just have to add colon and hover keyword

```
alpha:hover {
  background-image = url("pool-picture.jpg");
}
```

So now when you take your mouse at space-picture.jpg it will change to pool-picture.jpg image.

# Slide over Menu

A simple toggle button to slide open the menu and close it.

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script type="text/javascript">
        window.jQuery || document.write("<script src='jquery-3.2.1.js'><\/script>");
    </script>
    <script type="text/javascript">
        $(function(){
            $(".nav-toggle").on("click",function(){
                $(".main-navigation").toggleClass("open");
            });
        });
    </script>
```
