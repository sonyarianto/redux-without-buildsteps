[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fsonyarianto%2Fredux-without-buildsteps)

# redux-without-buildsteps

Learning Redux sometimes hard, even still hard for me, even harder if we just learn and never use it. That's why I create simple examples on this repository about using Redux and remove all complexities. Just pure how Redux works, no CSS things, no import things, no `npm install` things, just sit, read, relax, analyze and focus. Don't forget to prepare your coffee. Every sample is on its own HTML file and on that each single file will contains all code.

## Installation

No, no need to install anything. We just use everything from CDN. We just use CDN version of React, React Redux and Redux Toolkit. So no need to install anything, just open the HTML file on your browser.

## Should I do the `npm install` things?

Why? Do you want the `npm install` things? Hahaha. No need to do that, even we don't need web server to run the html file.

## What is Redux?

Redux is predictable state management bla bla bla, waitttt.... just go to https://redux.js.org/. All respect to Redux team that makes the product great.

## What is included in this repo?

I have 5 (five) files here at the moment. No need `npm install` or anything, just HTML files that has a demo of how to setup and using Redux. So basically you can just run using local web server or even you don't need a web server, just run each of HTML file on your browser via file system. You also can deploy this project to Vercel or any other static hosting provider.

- `redux-with-react.html`, show you Redux with React, basically the old school Redux.
- `redux-with-react-and-react-redux.html`, show you Redux with React and React Redux (the React binding to Redux).
- `redux-with-react-and-redux-toolkit.html`, show you modern Redux, using React and Redux Toolkit only.
- `redux-with-react-and-react-redux-and-redux-toolkit.html`, show you modern Redux nowdays, using React, React Redux and Redux Toolkit (this is the recommended way today).
- `redux-without-react-but-only-with-redux-toolkit.html`, show you how to use Redux Toolkit without React, just pure Redux and Redux Toolkit.

## Technical notes

Because we use CDN version of React, React Redux and Redux Toolkit, we need to use `window.React`, `window.ReactRedux` and `window.RTK` to access the library. So if you want to use React, React Redux and Redux Toolkit, you need to use `window.React`, `window.ReactRedux` and `window.RTK` to access the library.

## License

MIT

Maintained by Sony Arianto Kurniwan <<sony@sony-ak.com>> and contributors.
