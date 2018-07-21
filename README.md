# RandomNameGenerator

This is a random name generator written in Haskell, available at: https://whispering-shore-20690.herokuapp.com/. This heroku instance uses the [Heroku Buildpack Stack](https://github.com/mfine/heroku-buildpack-stack.git) as the deploy script.

## Contributing

*Contributions welcome!*

You will need [Stack](https://docs.haskellstack.org/en/stable/README/#how-to-install) to build and run locally. If you want to run on Heroku, then you will need to use the [Haskell Stack Heroku buildpack](https://github.com/mfine/heroku-buildpack-stack) to deploy.

To run locally: 

```
stack build
stack exec -- randomNameGenerator
```

Then visit `localhost:3000`

To contribute, fork, make your changes, and open up a PR.
