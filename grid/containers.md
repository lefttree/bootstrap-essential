## Container

- 12-column grid
- accessed through CSS classes
- 3 key concepts
    + Containers
    + Rows
    + Columns

### Container class

- Control layout
- Add padding
    + 15px each side
    + Element inside would not reach the side
- Two types
    + fluid (always ajust to the size of the device)
        * `.container-fluid`
    + fixed-width (depends on the size of device, show fixed size)
        * `.container`
        * extra small, small, medium, large


### example

```html
<header class="bgimage">
    <div class="container">
        <h1>Headline</h1>
    </div>
</header>


<div class="container">
<h1>Headline</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab libero, cupiditate veniam officiis itaque in porro iure fugit iusto reprehenderit commodi earum cum blanditiis quos error similique quod, facere! Hic.</p>
</div>


<div class="container-fluid">
<h1>Headline</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab libero, cupiditate veniam officiis itaque in porro iure fugit iusto reprehenderit commodi earum cum blanditiis quos error similique quod, facere! Hic.</p>
</div>
```

```css
.bgimage {
    background-image: url('../images/reptiles.jpg');
    background-position: center center;
    background-size: cover;
    height: 200px;
}
```
