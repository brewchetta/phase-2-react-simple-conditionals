# Conditionals and Debugging Challenge

This app is mega broken. First, fix all the errors so that your console is clear when you reload the page. At that point, begin working on the other deliverables.

## Getting Started

Fork and clone the repository and then run `npm install` followed by `npm start`.

Familiarize yourself with the app. You're getting an array of planet data from `src/data/planets.js` which you'll use throughout.

## Deliverable One

Fix all the errors! You should find at least 4 errors to fix.

## Deliverable Two

When a planet card is clicked, change it so that instead of the picture, it displays the planet's information. This can be toggled so if it gets clicked again, it shows the planet picture again.

To make your life easy, everything you'll need for the planet's facts is located in the `PlanetFacts` component.

## Deliverable Three

If a planet is not classified as a planet (probably a dwarf planet) then give the planetary image a `className` of `not-planet`. For example:

```html
<img className="not-planet" />
```

If a planet _is_ in fact a planet, leave its `className` empty with an empty string or `null`.

## Deliverable Four

We're already in dark mode... so let's set up a light mode!

There's already a button at the top of the screen for this purpose, however it doesn't have any functionality.

To create the light mode, just apply the `light-mode` to the `App` component's `className`:

```html
<App className="App light-mode" />
```

Additionally, as we switch from dark mode to light mode and back, the button text should reflect which mode we're able to switch to.
