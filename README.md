# Work & Co Web Code Assessment

This is a copy of the [Redux Shopping Cart Example](https://github.com/reactjs/redux/tree/master/examples/shopping-cart).

To install dependencies, use the package manager [Yarn](https://yarnpkg.com/en/):

```
yarn
```

To start a development server:

```
yarn start
```

## Setup

Please create a new, public Github repository where your assessment can be reviewed. We recommend the following steps:

- Create a repository on your personal Github. Make sure the `Initialize this repository with a README` box is unchecked.
- Visit your new repository. Copy the `…or push an existing repository from the command line` code provided and run it in your terminal in the same directory as this README file. It will look something like this:

```
git remote add origin git@github.com:my-username/my-assessment.git
git push -u origin master
```

Note: You're encouraged to show your work by including multiple commits - we'll be looking through your git history.

## Tasks

1. [Implement Responsive Design](/tasks/01-responsive-design.md)
2. [Enhance Cart Functionality](/tasks/02-cart-enhancements.md)
3. [Hook Up Product API](/tasks/03-product-api.md)

You're welcome (but not required) to add any libraries you think would be helpful.

Please also update this README file: we'd love to see notes on your decision-making process, links to the most exciting pieces of code, or anything else that will give us additional context when reviewing your assessment.


# View Development Work

So, I'm not very familiar with how to code in react, nor with how to apply styles in react, so I implemented the wireframes on HTML mockups in within the [mockups folder](/mockups).

To view the full store mockup, you can view the [Store Mockup](/mockups/index.html) within the mockups folder. Clicking on the "Your cart is Empty" button will open a cart display that is already populate with products. Clicking the "X" button in the upper right hand corner will close the cart display.

To view a mockup of an empty cart display, you can view [The Empty Cart Mockup](/mockups/cart/cart_empty.html).

That should cover the implementations of all of the views within the wireframes, however, there is also a [Standalone Store Mockup Page](/mockups/store/store.html), a [Standalone Populated Cart Mockup Page](/mockups/cart/cart.html), and a [Buttons Display Page](/mockups/buttons/buttons.html) for just viewing the implementation of the buttons and contains one active and one disabled copy of each button style.

## About my development process
I wrote all of my styling code in SCSS files. My commited code contains both the SCSS files and the CSS files they compiled into. I did not write any of the CSS, it's all compiled, so to view MY code, just stick to the SCSS. The scaffolding was coded in HTML.

