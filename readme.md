# Initial Thoughts on React Ink

## Good

- React devs can get up and running very quickly. The library is pretty awesome, along with the component library it offers as well.

## Bad

- Not much. Some things in the Confusing section below might end up here. Same with the Undecided section.

## Undecided

- There's a lot of boilerplate. Maybe that comes with doing React dev. 

## Confusing

- Navigation is a bit odd. I'm not sure if what I came up with makes the most sense. `app.tsx` has a `switch` case for routes, pages are changed via an action `dispatch`'ed to `<Context />`. 
- It's `JSX` but it's not in the browser. I imagine this is similar to moving from `React and Browser` dev to `React Native` as well. It made doing some things like working with eslint and tsconfig.json rather confusing. I tried copying an eslint config from a `React and Browser` project and I was getting a lot of errors. I also tried starting with a basic eslint config but got stuck. 
- It's almost the same as `React and Browser` dev, but it's not. There are some bits that I'm not sure what's to blame. For example, I couldn't figure out why to import a file from `'Foo.tsx'` you import from `'Foo.js'`
0 It's `CSS` but it's not. React Ink claims to work like CSS Flexbox. However, I struggled a lot with text across multiple `<Text />` components that all ended up on the same line.

# Dev Notes

- I cannnot get eslint setup for this project. So, therefore no useCallbacks because I can't verify missing dependency array items.

# backup-sync

> This readme is automatically generated by [create-ink-app](https://github.com/vadimdemedes/create-ink-app)

## Install

From the root
```bash
$ npm link
```

## CLI

```
$ backup-sync --help

  Usage
    $ backup-sync

  Options
    --name  Your name

  Examples
    $ backup-sync --name=Jane
    Hello, Jane
```
