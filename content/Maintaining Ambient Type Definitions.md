# Maintaining Ambient Type Definitions

So you’re a library author who doesn’t want to rewrite your library into TypeScript, but you *do* want TypeScript users to be able to use your library. How can you do that successfully?

## 1. Publish types which represent your public API

<!-- TODO: fill out the big picture here -->

A key here will be to recruit people who *do* know TypeScript to collaborate with you on writing the types. The folks who *want* the TypeScript definitions are great candidates for this!


## 2. Integrate type tests

Once you have types written, how do you know that they don’t break? The same way you do with runtime code: with tests—but in this case, *type tests*. These capture what you expect your public API to be.

<!-- TODO: explain how type tests work and what to do in CI -->


## 3. Keep your types in sync with your code

Now, you have a small additional responsibility whenever you make changes to your code: update your type definitions to match. This is usually *much* less work than writing the type definitions in the first place. If you’re adding a new method to a class, you open the type definitions and 

<!-- TODO: explain how to deal with this over time -->


## 4. Fix TypeScript errors for future versions

<!-- TODO: *very* short summary of the kind of thing that happens -->

If it’s unclear how to fix it, and your regular TypeScript maintainers are stumped, reach out in the TypeScript Discord channel as well as in your own community’s communication channels (for example, the Ember or Svelte Discord channels).

<!-- TODO: explain how to fix and link out to SemVer guide for deep dive -->


## 5. Update your TypeScript support over time

<!-- TODO: analogize to Node -->
