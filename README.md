# Adjust Design Tokens

This simple page acts as a temporary tool for communication and alignment, speaking to everyone who is about to use Adjust’s soon-to-come design system. It is hosted via GitHub pages, you can access it at https://adjust-design-system.github.io/design-tokens/

## Design Language

We put this thing up to show off the new UI design in a centralized and easy-to-consume way. Simply bookmak the page and you can always access the design – no need to install layout software or create another account for yet another tool.

## Design Tokens

The second – very important – goal for us is to provide all parts of the design which can be translated into code (sizes, spacings, colors, &hellip;) immideately to developers. This is a temporary solution, there is no _npm package_ or something similar. However, frontend developers can start building with the new _look & feel_. They can quickly find, copy & paste things like color values over into their code. This is what design tokens are about.

Furthermore, the designers of the design system team will soon be able to change the tokens themselves. When we finally publish the tokens with the design system, this page will become obsolete. The developers can than integrate the tokens as modules into their code while the designers can update them – all changes will get distributed by simply running an automated update routine.

## Contribution

Check out the repo to your machine. Make sure you have [node.js](https://nodejs.org/en/) installed. Then, from the project root, run:

```bash
$ npm install && npm run start
```

All changes pushed to `master` will update the page, hosted via [GitHub pages](https://adjust-design-system.github.io/design-tokens/).
