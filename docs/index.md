---
id: index
title: What is Babel-Blade?
---

> **obligatory note**: babel-blade is not yet production ready! Please proceed only if you are an early adopter.

`babel-blade` is a babel plugin (or [macro](https://github.com/kentcdodds/babel-plugin-macros)) that helps to **generate graphql query strings inline** and solves **[the double declaration problem](declarationdeclaration)** in clientside GraphQL.

## See 7 minute introductory video

[![babel blade walkthrough on youtube](https://user-images.githubusercontent.com/6764957/42730215-f92fc024-87bc-11e8-9929-c614710920ee.png)](https://www.youtube.com/watch?v=z9wKcRjNqlw)

Here's [a longer 25 minute talk at GraphQLNYC](https://youtu.be/7OHXz7vXC0g) going through more of the API and the motivations behind what `babel-blade` is.

## Try it out on ASTExplorer

The quickest, zero-install way to try it out is on [astexplorer](http://astexplorer.net/#/gist/01983f61e310f1eaf6b12a221556a937/7e9ae4d3b406ed94d92f6931c0474f964e1ae990). If you like it, head over to our **Getting Started** docs to see how to install the babel plugin in your app.

## Official Emoji

It is the ⛸️. Basically when I explained this idea to coworkers they said "oh it's just **inline** GraphQL". My boss at the time liked inline skating, which is commonly known as Roller Blading, and so the name stuck.

## Internal stucture

Here is a chart of how the package is set up:

![test](/img/dependencygraph.svg)
