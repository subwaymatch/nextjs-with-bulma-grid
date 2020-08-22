# Next.js with Bulma Grid example

**[Demo - https://nextjs-with-bulma-grid.vercel.app/](https://nextjs-with-bulma-grid.vercel.app/)**<br /><br />

This is a basic example to demonstrate how to use [Bulma](https://bulma.io) Grid with selective `sass` imports in [Next.js](https://nextjs.org).

![nextjs-with-bulma-grid-screenshot](https://user-images.githubusercontent.com/1064036/90951723-f04fbd00-e422-11ea-8ed5-6cae541091b5.png)

## Why Bulma?

I've been searching for a Grid system that plays well with [Next.js](https://nextjs.org). I list a few other options I've considered, but [Bulma](https://bulma.io) just felt "right" for me :+1:.

- [Bootstrap](https://getbootstrap.com/) - De-facto standard (based on popularity) when it comes to a CSS framework, but it feels too bloated. Yes, you can import only the grid components. But it's unclear which `sass` files I need to import and how to customize them without extensively reading the `sass` code.
- [Material UI](https://material-ui.com/) - Great alternative. The only reason I don't use it is since I can't apply `framer-motion` animations directly to Material-UI components.
- [Flexbox Grid](http://flexboxgrid.com/) - Used to be (and continues to be) popular, but isn't maintained anymore.
