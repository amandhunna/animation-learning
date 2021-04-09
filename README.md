- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties

#transition-timing-function

- cushioning: animation/time,
- eas-in: accelerate, comes slowly and out-false
- ease-out: deaccelerate or comes fast and out-slowly
- linear: straight constant
- ease-in-out: or comes and out slow but fast in the middle
- steps: -----------------
- cubic-bezier: make your own animation rate:https://cubic-bezier.com/#.17,.67,.83,.67 or https://easings.net/

.class {
animation : name duration timing-function animation-delay iteration-count
}

timing-function, animation-delay, iteration-count=1are optional
