* Crear un parrafo simple flotando hacia la izquierda.

````html

<!DOCTYPE html>
<html>
<head>
<style>
span {
    float: left;
    width: 0.7em;
    font-size: 400%;
    font-family: algerian,courier;
    line-height: 80%;
}
</style>
</head>
<body>

<p>
<span>L</span>orem ipsum dolor sit amet, consectetur adipiscing elit. Sed consectetur, eros vitae consequat scelerisque, ligula erat feugiat felis, 
quis vestibulum massa neque id diam. Aliquam porttitor eros velit, vitae ornare quam convallis ut. Donec nec lorem vestibulum, 
iaculis arcu at, volutpat libero. Duis quis ultricies odio, quis viverra odio. In dui felis, pellentesque interdum risus nec, 
pretium accumsan ex. Etiam vel ligula in enim pharetra tempor. Donec fermentum nunc neque, tristique eleifend mi rhoncus nec. 
Ut suscipit id velit ac fringilla. Sed cursus ullamcorper metus a efficitur. Nam sed ullamcorper mi, at imperdiet odio. 
Aenean tristique egestas tellus non aliquam.

Nulla facilisi. Suspendisse porta turpis in lectus vulputate scelerisque. In hac habitasse platea dictumst. 
Ut sagittis nisi eget ultricies elementum. Sed ligula purus, sodales a volutpat sed, suscipit sit amet elit. 
Vestibulum tempus eu ante a pellentesque. Donec justo nulla, feugiat vel quam eget, tristique ultricies sem. 
Pellentesque vel gravida arcu. Nulla euismod sem sit amet est rutrum, nec aliquam urna congue. Proin pellentesque tincidunt ante, 
nec tempor diam aliquet ac. Quisque varius, odio eu pretium dapibus, felis risus tincidunt elit, in porta nisi est quis ante. 
Donec pretium nunc at quam porta pretium. Nulla at urna eu diam tempus tempus eget eget est. Mauris sapien metus, pharetra ut lorem non,
tempor luctus sapien. Proin vitae velit ante.
</p>

</body>
</html>

````

* Crear un menu horizontal.

````html
<!DOCTYPE html>
<html>
<head>
<style>
ul {
    float: left;
    width: 100%;
    padding: 0;
    margin :0;
    list-style-type: none;
}

a {
    float: left;
    width: 6em;
    text-decoration: none;
    color: white;
    background-color: purple;
    padding: 0.2em 0.6em;
    border-right: 1px solid white;
}

a:hover {background-color: #ff3300;}

li {display: inline;}
</style>
</head>
<body>

<ul>
  <li><a href="#">Link one</a></li>
  <li><a href="#">Link two</a></li>
  <li><a href="#">Link three</a></li>
  <li><a href="#">Link four</a></li>
</ul>

</body>
</html>

````
