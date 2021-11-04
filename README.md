# Sanity Shopify Demo

**Full documentation to follow!**

---

This demo consists of the following packages:

## [`hydrogen-app`](/packages/hydrogen-app/README.md)

A customised version of Hydrogen's official starter, tailored to showcase:

- Portable text
- Simple and easy to understand product option customisation

It is designed to be as simple as possible with few dependencies and built with the expectation that users will add their own flavour of styling, animation and own structure.

This is currently deployed on [https://hydrogen-demo.fly.dev/](https://hydrogen-demo.fly.dev/)

## [`sanity-studio`](/packages/sanity-studio/README.md)

An opinionated Sanity studio built with defaults aimed at simpler shopfronts that want a clear path for managing (and customising) their shop content.

It's been structured to accomodate the default sync options provided by the upcoming Shopify Sync app.

We try and provide a few studio affordances to give users more visibility into product availability – such as displaying when products are not available (due to Shopify configuration) or if products have since been removed on Shopify's end.

---

Also associated with this demo is a Shopify Storefront (`sanity-dev-store.myshopify.com`) which hosts all demo product content.

## Getting started

Install dependencies

```sh
yarn
```

Run the hydrogen app

```sh
yarn dev-hydrogen
```

Run Sanity Studio locally

```sh
yarn dev-sanity
```
