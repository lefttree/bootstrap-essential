## Row

`.row`

- Horizontal groups of columns
- Place within container (should always be inside container)
- should always include columns
- gets rid of container padding (remove the padding of container)


## Column

- **30px gutters**
    + 15px on each side
- use `col-size-span`
    + size: when it stacks
    + span: how many columns

### Example

```html
<div class="services container">
    <h2>Services</h2>
    <div class="row">
        <section class="col-md-4">
            <img class="icon" src="images/icon-exoticpets.svg" alt="Icon">
            <h3>Exotic Pets</h3>
            <p>We offer specialized care for reptiles, rodents, birds, and other exotic pets.</p>
        </section>

        <section class="col-md-4">
            <img class="icon" src="images/icon-grooming.svg" alt="Icon">
            <h3>Grooming</h3>
            <p>Our therapeutic grooming treatments help battle fleas, allergic dermatitis, and other challenging skin conditions.</p>
        </section>

        <section class="col-md-4">
            <img class="icon" src="images/icon-health.svg" alt="Icon">
            <h3>GeneralHealth</h3>
            <p>Wellness and senior exams, ultrasound, x-ray, and dental cleanings are just a few of our general health services.</p>
        </section>
    </div><!-- row -->
</div><!-- content container -->
```

### multiple column classes

`class="col-sm-6 col-md-4 col-lg-2"`

### resettings columns

`.clearfix visible-sm-block` 

- responsible utility class
- fix the dis-align problem

### offsetting columns

```html
<section class="col-xs-offset-3 col-xs-6 col-sm-offset-0 col-sm-6 col-md-4 col-lg-2">
```

`.col-xs-offset-3` offset
`.col-sm-offset-0` clear the offset when it reach `sm` breakpoint


### Nesting Columns

`.row` inside `.row`


```html
<div class="row">
    <section class="col-xs-offset-3 col-xs-6 col-sm-offset-0 col-sm-6 col-md-4 col-lg-12">
        <div class="row">
            <div class="col-lg-1 col-lg-offset-3">
                <img class="icon" src="images/icon-vaccinations.svg" alt="Icon">
            </div>
            <div class="col-lg-5">
                <h3>Vaccinations</h3>
                <p>Our veterinarians are experienced</p>
            </div>
        </div>
    </section>
</div>
```

### customizing column order with push and pull

`.col-xs-4 col-xs-push-8`

'.col-xs-4 col-sm-pull-8'

