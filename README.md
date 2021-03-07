# CSS Playground

See it live at [https://budavariam.github.io/css-playground](https://budavariam.github.io/css-playground)

Minimal css playground with only html and css.

Only works in webkit browsers (Safari/Chrome).

## How it works

There are 2 tricks involved:

- `contenteditable` prop to the style element
- `[contenteditable] {-webkit-user-modify: read-write-plaintext-only;}` css to handle newlnes properly
