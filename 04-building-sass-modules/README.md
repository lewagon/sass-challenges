## Background & Objectives

In this challengen, you will write your first SASS modules, that you will be able to re-use on future projects.

## Specs

### Button module

Personal button classes are very powerfull to improve your site design, since buttons are everywhere. Code you **`components/button.css.scss`** module with the class of your choice. Here is an example of button module.

```scss
.btn-rounded{
  border-radius: 50px;
  padding: 0.3em 1.5em;
}

.btn-bordered{
  background: rgba(255, 255, 255, 0.8);
  transition: all 0.2s ease;
  font-weight: bold;
  &:hover{
    border: 2px solid white;
  }
  &-primary{
    color: darken($brand-primary, 20%);
    border: 2px solid darken($brand-primary, 20%);
  }
  &-success{
    color: darken($brand-success, 20%);
    border: 2px solid darken($brand-success, 20%);
  }
  &-danger{
    color: darken($brand-danger, 20%);
    border: 2px solid darken($brand-danger, 20%);
  }
  &-warning{
    color: darken($brand-warning, 20%);
    border: 2px solid darken($brand-warning, 20%);
  }
}
```

## Tips & Resources

Don't hesitate to create your own generic classes with the design and effect you like. A good tip is to look for inspiring example on http://codepen.io and then modify these example to create your own classes.