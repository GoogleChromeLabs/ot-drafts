# Origin trial drafts

Welcome to the origin trial drafts repo. If you're implementing a new spec, there's no one more qualified than you to write reference materials for it, and there's no one who can do it faster. But if a feature is in an origin trial, it can't be documented on MDN. Even if it could be, the style guide for a site like MDN is thick and you're an engineer, not a writer. 

This repo helps you with these problems. 

## The puppy problem

Why are we asking you to help document features on MDN? Chrome is so robust at creating new web platform features that we have exceeded our capacity to document it.  

Imagine that you are a dog breeder and that you believe fervently that the world needs more dogs. They're our best friends, after all. The world is better with more of them. So you start breeding them as fast as you can. But instead of finding loving homes for them, you push them out the door to fend for themselves. Metaphorically speeking, we're breeding puppies and failing to find homes for them With a little help from you, we can stop doing this.

## I'm preparing for a developer trial or origin trial

The documentation produced in this stage will be minimal, focusing on accuracy and prioritizing a code example over document depth. Follow the instructions behind the appropriate link below. 

* [I am implementing one or more interfaces or events](./api-instructions.md).

* I am adding an interface member such as an event callback, a method, or a property: contact jmedley@.

* I am shipping a stable version of a feature soon and expect no more changes to the API surface: please use the more complete boilerplates in the [MDN Boilerplates](https://github.com/jpmedley/mdn-boilerplates) repo. 

## Why are there only interface pages for many features?

This repo contains mostly interface pages and only API-related pages. The pages in this repo are autogenerated and there is currently only a process for autogenerating API docs.

On MDN a fully documented API has and overview page as well as individual pages for interfaces, constructors, events, event callbacks, methods and properties. If your feature is in an origin trial, the API surface is still in flux. Keeping a complete documenation set in sysnc with changes can be a burden. However, it's useful to provide at least something to participants in an origin trial. Hence the boilerplates in this repo are only for interfaces. The provide space for basic descritpions of the interface and its members, and a place for code examples.