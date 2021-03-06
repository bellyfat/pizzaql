# [![PizzaQL](media/logo/horizontal-scaled.png)](https://github.com/pizzaql/pizzaql)

> Modern OSS Order Management System for Pizza Restaurants.

[![Build Status](https://travis-ci.org/pizzaql/pizzaql.svg?branch=master)](https://travis-ci.org/pizzaql/pizzaql)
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/xojs/xo)
[![style: styled-components](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/styled-components/styled-components)
[![Cypress.io tests](https://img.shields.io/badge/cypress.io-tests-green.svg)](https://cypress.io)

<p align="left">
  <a href="https://opencollective.com/pizzaql" target="_blank">
    <img src="https://cdn-std.dprcdn.net/files/acc_649651/Q5nVhT" height="80" alt="Open Collective">
  </a>
  <a href="https://www.patreon.com/akepinski" target="_blank">
    <img src="https://cdn-std.dprcdn.net/files/acc_649651/plrSCT" height="80" alt="Patreon">
  </a>
</p>

## Goal

The goal of this project is to provide a modern and easy to use order management system with order placement form as well. You can track progress in our TODO list :smile: 

More information coming soon. Please note that this project is currently **work in progress** and you shouldn't use it in production!

## Docs

[Here :zap:](https://pizzaql.now.sh/)

## Screenshots

![Order Placement Form (Light)](media/screenshots/light.png)
![Order Placement Form (Dark)](media/screenshots/dark.png)
![Admin Dashboard (Light)](media/screenshots/dashboard-light.png)
![Admin Dashboard (Dark)](media/screenshots/dashboard-dark.png)

[See more screenshots](https://github.com/pizzaql/pizzaql/tree/master/media/screenshots)

## TODO

**Order Placement System**
* [x]  Basic Frontend
  * [x] Production-ready Frontend (styles etc.)
* [x]  Working Backend
  * [x] Creating orders
    * [x] Rewrite to Apollo Client and get rid of graphql-request
* [x] Better delivery time selection
* [x] Lock order placement system between specific hours

**Order Management System**

* [x] Login
  * [x] Full security with Auth0
* [x]  Basic Frontend
  * [x] Listing orders
    * [ ] **Rewrite to GraphQL Subscriptions (work in progress, requires custom resolver)**
  * [x] Ability to delete orders
  * [ ] Ability to manually add orders
  * [ ] Production-ready Frontend (styles etc.)
* [x]  Working Backend

**Project Page**

* [x] Home page
* [x] About page

**Other**

* [x] Testing with Cypress.io
* [x] Move from Prisma Cloud to Docker
* [x] Use GraphQL Yoga server
* [ ] Integration with Algolia Places API (?)
* [x] Documentation (not fully done)
* [ ] Release a public demo

(?) - unsure.

## Built with:

- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [Apollo Client](https://github.com/apollographql/apollo-client)
- [styled-components](https://www.styled-components.com/)
- [Blueprint](https://blueprintjs.com/)
- [Formik](https://jaredpalmer.com/formik/)
- [Auth0](https://auth0.com/)
- [Prisma](https://www.prisma.io/)
- [GraphQL](https://graphql.org/)
- [Babel](https://babeljs.io/)

and many other awesome technologies :unicorn:

## Big Thanks

Cross-browser Testing Platform Provided by [Sauce Labs][homepage]

[homepage]: https://saucelabs.com

## License

MIT
