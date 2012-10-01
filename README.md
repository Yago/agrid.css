# Agrid.css is a simple, light and responsive css grid !

It's work just like Twitter Bootstrap, but with less code. 

### [Demo](http://www.yago-art.ch/agrid/)

## A 12 columns grid !

It's pretty simple to use, choose the number of column and give them the right class :

```
<div class="container">
    <div class="row">
        <div class="span3"></div>
        <div class="span3"></div>
        <div class="span3"></div>
        <div class="span3 last"></div>
    </div>
    <div class="row">
        <div class="span3"></div>
        <div class="span2 offset4"></div>
        <div class="span3 last"></div>
    </div>
</div>
```

```.container``` is the block who content all your rows<br />
```.row``` is just like his name, he contains the column of your layout<br />
```.span1``` or ```.offset1``` = one column <br />
```.last``` is the required class for the last column

## It gives you a complete control over the grid with the LESS file !

```@maxWidth``` is the max width of your grid<br />
```@columnRatio``` is the proportion between column and gutter

With this two parameters, you can make the grid just like you want.


## Adding some columns is easy !
For abvanced user, juste change ```@columnNumber``` and add few lines for ```/* SPAN WIDTH */``` and ```/* OFFSET WIDTH */```
