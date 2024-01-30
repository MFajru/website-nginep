# Nginep


Nginep is an app that help the user to rent homes/apartments. User can see lists of houses/apartments, both in Desktop and Mobile screens (responsive).

## Objectives[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#objectives "Direct link to heading")


-   Able to init a basic web project (with HTML, CSS and maybe JavaScript)
-   Able to choose the correct semantic HTML
-   Able to do slicing from Figma or other design tools
-   Able to immplement a style with pure CSS
-   Able to make responsive web with the help
-   Able to use Flexbox, Grid and Media Queries

## Restriction[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#restriction "Direct link to heading")


-   Cannot use CSS Library or Framework except for "Browse our list" page

## Directions[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#directions "Direct link to heading")


1.  Open [Nginep Figma](https://www.figma.com/file/DfAvyxyav1aBcDkfQdPIlW/Nginep?node-id=314%3A4)
2.  Init the project
3.  Slice per page with release as described below

## Releases[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#releases "Direct link to heading")


### Release 1 - Navbar and Hero[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#release-1---navbar-and-hero "Direct link to heading")

Create a navbar and hero section in the Home page. If you can, you may use Flexbox.

![Navbar and Hero section of Nginep](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/assets/images/homepage-top-f8ff16be1a51ae0704d81d91a256cc8b.png)

### Release 2 - Home Page[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#release-2---home-page "Direct link to heading")

Continue to create a full Home page with Flexbox and Grid. Make sure that the page is responsive! It is recommended to apply a mobile-first approach. You can see the design on the Figma above.

![Home page of Nginep](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/assets/images/homepage-acdb54529deca2eebbeeefce56809340.png)

### Release 3 - Browse Page[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#release-3---browse-page "Direct link to heading")

Continue to create Browse page using a CSS Library. You may use Bootstrap, Tailwind or others but those 2 are the recommended one.

![Browse page of Nginep](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/assets/images/browse-5ef811261ec300df32904967eb06cec0.png)

### Release 4 - Contact Us Page[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#release-4---contact-us-page "Direct link to heading")

Continue to create Contact Us page. You can use plain CSS or Bootstrap/Tailwind. For the table section you may use horizontal scroll while in lower resolution. The form will have these features:

-   All fields are required
-   When submitted, the message will be added to the table and the form will be reset (all fields are empty)
-   Number in the table are auto increment
-   When a message is deleted, it will be removed from the table and the number will be updated accordingly (e.g. if the deleted message is the first one, the second message will be number 1)

#### Optional features:[​](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/docs/fe-stream/web-basic/exercises/nginep#optional-features "Direct link to heading")

-   Add more validation in the form:
    -   Full name should be at least 3 characters long
    -   Email should be a valid email
    -   Phone number should be a number from 9 - 15 digits
    -   Message should be at least 10 characters long
-   Delete button should only appear when the message row is hovered (hovered area is from the number to the delete button)
-   Add loading state in the button when the form is submitted. You can use spinner icon or other loading animation, and use `setTimeout` to simulate the loading state (the loading state should be at least 2 seconds)
-   When no message is added, the table will show a message "No message yet" in the second row (after the header) with only one column that span the whole table

![Browse page of Nginep](https://sea-labs-id.git-pages.garena.com/trainers/digi-wiki/assets/images/contact-us-e5b712d43b6a83685515eb5eb9175811.png)
