# Flexbox

flex-flow
This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap.

** .container {
  flex-flow: column wrap;
}


display
This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

.container {
  display: flex; /* or inline-flex */
}
