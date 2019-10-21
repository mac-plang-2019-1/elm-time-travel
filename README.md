# Elm Time Travel

## To run locally:

Clone this repository **with the `--recurse-submodules` flag**:

    git clone --recurse-submodules https://github.com/mac-plang-2019-1/elm-time-travel.git
    cd elm-time-travel

[Install npm](https://www.npmjs.com/get-npm) and Elm if you haven’t already, then install elm-live (for live reloading of elm projects):

    npm install -g elm-live

To launch the demo, from your cloned project directory:

    elm-live src/* --open -- --output=elm.js
