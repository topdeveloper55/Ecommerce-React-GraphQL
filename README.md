# E-commerce Apparel Store feat. React & GraphQL

#### Author: Jarid [ <jarid@hey.com> ]

A sample e-commerce store, 'Sick Fits', that allows users to sign-up, add/edit/remove items to the store, and even check-out items with a (test-mode) credit card purchase. 

<img height="400" src="./readme-images/intro.gif">

## __Motivation__

Sickfits is an opportunity to learn more about React, GraphQL and a host of other modern technologies (listed below) to stay on the cutting edge of web development. In addition, I've wanted to build a fully-functioning E-commerce website with payment processing and an email server to improve my back-end skills.

## __Technology__

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Front-end

<img height="80" src="./readme-images/next-js.svg">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img height="80" src="./readme-images/react.svg">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img height="80" src="./readme-images/apollo.svg">
- **Next.js**: Server-side rendering, application routing, and tooling (built on Webpack)
- **React.js**: Client-side front-end UI framework
- **Apollo Client**: GraphQL queries and mutations, cacheing, and managing application state

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Back-end

<img height="80" src="./readme-images/graphql-yoga.png">&nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="./readme-images/expressjs.svg">&nbsp;&nbsp;&nbsp;&nbsp; <img height="80" src="./readme-images/prisma.jpg">
- **GraphQL Yoga**: Database layer used to resolve Queries and Mutations, credit card charges with [Stripe](https://www.stripe.com), permissions/authentication
- **Express/node.js**: Server framework underneath Yoga (which includes an email server)
- **Prisma**: CRUD APIs that can integrate with many databases (including postreSQL, mongoDB or mySQL), as well as schema definition

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Testing

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img height="80" src="./readme-images/jest-enzyme.jpeg">

- **Jest with Enzyme**: React testing by utilizing Jest's engine to "shallow" render components, and constantly comparing to a snapshot to ensure rendering is consistent

## __Features__

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Add Item to Store

<img height="400" src="./readme-images/item-upload.gif">

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Edit Existing Items

<img height="400" src="./readme-images/edit-item.gif">

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Credit Card Checkout

<img height="400" src="./readme-images/checkout.gif">

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sitewide Search

<img height="400" src="./readme-images/search.gif">

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;...Password Reset, Permissions Panel, Order History, and more


