#Tuesday Session

##HTML Forms

we learned how to create forms in html but just the frontend aspect.

For example:

    <form action="http://www.google.com">
        <input type="text" name="search">
        <input type="submit" value="Search">
    </form>

#Thursday Session

In this session we began learning about CSS, starting off with adding styles to the page.

##Adding CSS styles to an html element

###Inline CSS

To add inline css to an html element, you can use the style attribute. The style attribute can contain any CSS property.
Insert the style attribute in the opening tag of the element

<h1 style="background-color: blue">

###Internal CSS

To add internal css to an html element, you can use the style element. You can add css rules inside the style element.
Insert the style element in the head section of the html document.

<style>
h1 {
background-color: blue;
}
</style>

###External CSS

Similar to internal css, external css can be used to add css to an html element. The difference is that the css rules are stored in a separate file and linked it to the html document like this:

<link rel="stylesheet" href="styles/styles.css" />

Css selectors:

Element selector

Selects all elements with the specified name.

for example: h1 selects all h1 elements.

Class selector

Selects all elements with the specified class name.

for example: .intro selects all elements with class="intro".

Id selector

Selects the element with the specified id.

for example: #firstname selects the element with id="firstname".

Other selectors

~ selector (sibling selector) - selects all elements that are siblings of a specified element. For example:
h1 ~ p selects all p elements that are siblings of an h1 element.

- selector (adjacent sibling selector) - selects all elements that are the next sibling of a specified element. For example:
  h1 + p selects all p elements that are the next sibling of an h1 element.
  > selector (child selector) - selects all elements that are the child of a specified element. For example:
  > div > p selects all p elements that are the child of a div element.

* selector (universal selector) - selects all elements.

All other selectors to make your css more specific can be found here.
https://www.w3schools.com/cssref/css_selectors.php

Working on personal website project

This week I made a start on my personal website, as I have until the 12th November to complete a basic HTML/CSS version, which is necessary to pass the assignment. However I will be using JavaScript for some elements as I have some experience with it.

I actually began doing some design of the site before the course even started, using Figma to design the Nav and About section as well as the Contact form. I also coded those sections to see what would work. 
So a lot of the content was ready to be copied into the new version but I wanted to make some changes and to make it more responsive.

Also I began using Sass (CSS Preprocessor) initially, even in my earlier version, but as I have been working on the site on my lunch break using my phone a lot and cant use Sass on my phone, I decided to just use CSS. 

Nav section

On Sunday I started working out how to create a drop down nav menu, when viewing it on mobile. I spent a great deal of time getting a basic version of it done, but will change it up, as it doesn't look and function the way I'd like.

About section



Work section
 A lot of this week was working on the layout of the cards in the work section. Igot it working to my liking using grid as it displays the cards better tahn it did with flex. I also added some javascript to populate the cards with the data from JS objects.

Contact section

