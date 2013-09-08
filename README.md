# Agrid.css is a simple, light and responsive css grid !

It's work just like Twitter Bootstrap, but more configurable. 

### [Demo](http://yago31.github.com/agrid.css/)

## A very easy grid !

It's pretty simple to use, choose the number of column and give them the right class :

```
<div class="container">
    <div class="row">
        <div class="col-3"></div>
        <div class="col-3"></div>
        <div class="col-3"></div>
        <div class="col-3 last"></div>
    </div>
    <div class="row">
        <div class="col-3"></div>
        <div class="col-2 offset-4"></div>
        <div class="col-3 last"></div>
    </div>
</div>
```

```.container``` is the block who content all your rows<br />
```.row``` is just like his name, he contains the column of your layout<br />
```.col-1``` or ```.offset-1``` = one column <br />
```.last``` is the required class for the last column

## It gives you a complete control over the grid with the LESS/SASS file !

With ```@columnNumber``` you can choose how much columns your Grid had !<br />
You can choose the max-width of your grid with ```@maxWidth```<br />
And ```@columnRatio``` define the proportion between column and gutter !

This fiews parameters can completly change the look of your Grid. The LESS file is very easy to use, so don't be afraid and choose how is your Grid !
