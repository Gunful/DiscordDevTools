# DiscordDevTools

## Status
#### Not working. Ask the developer for new the latest release.

## What are they?
#### The Discord dev tools are a set of options that allow you to enable and configure upcoming features, usually,these are only available to beta testers, but by using this code you can enable them for yourself!

## What tools are there?
### Experiments
#### These are upcoming features or tests that can affect your client. For example, enabling `2022-03_avatar_decorations` adds a new option in the User Profile tab.
### Developer Options
#### There are many things to do here, such as enabling developer content, executing errors and crashes and overriding the system. **However,** most developer tools here are either broken or unavailable, so this makes it less useful.
### Hotspot Options
#### This is very similar to Experiments, however, it is with regular features which you can disable.
### Dismissable Contents
#### The same as Hotspot Options, but there are some small differences that don't change much.
### Payment Flow Models
#### These options generate UIs and Links for nitro, nitro classic and boosts. It can also reset them, but that is not recommended as it will make you lose your nitro.

## How do I get this?
#### Open up the console by pressing F12, typing the code below and pressing enter. You should now see the options at the bottom of settings and you can modify them for the best discord client!

```js
Object.defineProperty((webpackChunkdiscord_app.push([[''],{},e=>{m=[];for(let c in e.c)m.push(e.c[c])}]),m).find(m=>m?.exports?.default?.isDeveloper!==void 0).exports.default,"isDeveloper",{get:()=>true});
```

###### Credits to jwklong#5248 for the script
