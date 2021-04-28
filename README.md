[CodeSandbox Link](https://codesandbox.io/s/dark-cache-zmfq9)

# R3F rendering experiment
**StatefullBox** rotates using state, so it rerenders on every state mutation.\
**StatelessBox** rotates using ref, so it doesn't rerender. \
**StatefullBoxWithZustand** rotates using Zustand transient updating state, so it's stateful but doesn't rerender.

Look at the console to see all the components updates.

### `yarn start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.