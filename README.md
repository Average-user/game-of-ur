# game-of-ur
[![CircleCI](https://circleci.com/gh/polymeris/game-of-ur.svg?style=svg)](https://circleci.com/gh/polymeris/game-of-ur)

[Live Demo](https://polymeris.github.io/game-of-ur/)

## Development Mode

### Run application:

```
lein clean
lein figwheel dev
```

Figwheel will automatically push cljs changes to the browser.

Wait a bit, then browse to [http://localhost:3449](http://localhost:3449).

## Production Build


To compile clojurescript to javascript:

```
lein clean
lein cljsbuild once min
```
