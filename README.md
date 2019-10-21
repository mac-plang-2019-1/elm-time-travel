# Elm Time Travel

## To run locally:

Clone this repository **with the `--recurse-submodules` flag**:

    git clone --recurse-submodules https://github.com/mac-plang-2019-1/elm-time-travel.git
    cd elm-time-travel

[Install yarn](https://yarnpkg.com/lang/en/docs/install/#mac-stable) and Elm if you haven’t already, then install elm-live (for live reloading of elm projects):

    yarn global add elm-live

To launch the demo, from your cloned project directory:

macOS:

    elm-live src/* --open -- --output=elm.js

Windows (which apparently doesn’t understand wildcards):

    elm-live src\Asteroids.elm src\Mario.elm --open -- --output=elm.js
