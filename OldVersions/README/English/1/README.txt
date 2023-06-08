
***

# ChromaTags_ForGit
Linguist color coding for Git-based programming, and much more. Inspired by [GitHub Linguist](https://github.com/github/linguist)

## Lua

Lua is used for this project, as I don't utilize it enough. It is really good for scripting in projects like this.

## Goals

ChromaTags are the names of the languages being displayed in the linguist.

There can only be 1 configuration per view (per webpage/repository) with a maximum of 6 total views. This means that there can be a linguist in up to 6 different locations at once. The following view types are available:

- Pi chart
- Tube
- Rectangle
- Squiggly tube
- Squiggly rectangle
- Bar list (each language is its own separate chart line, and can be sorted %+ to %- or %- to %+)

I am currently deciding whether 6 different configurations can be allowed at once.

## Graphics

Multiple graphics options can be applied at once. They include:

- Transparency/Opaque
- Glow
- Rainbow
- Strobing level

## Transitions:

Multiple transitions (animations) can be applied at once, but a left to right of the same type cannot be applied at the same time as a right to left of the same type.

- Fill up instantly on load (default)
- Fill up on load (left to right)
- Fill up on load (right to left)
- Fade in on load
- Electrify on load (full spectrum)
- Electrify on load (left to right)
- Electrify on load (right to left)
- Glow on load (full spectrum)
- Glow on load (left to right)
- Glow on load (right to left)

## Location:

You can duplicate the counter to any/all locations, which include:

- Above the commit message
- Below the `README` file
- Above, left sidebar
- Below, left sidebar
- Above, right sidebar
- Below, right sidebar

## Original draft

```plain-text
ChromaTags

Views:

You can have 1 view per setup, with a maximum of 6 separate views

Pi chart
Tube
Rectangle
Squiggly tube
Squiggly rectangle
Bar list (each language is its own separate chart line, and can be sorted %+ to %- or %- to %+

Graphics:

Multiple graphics options can be applied at once

Transparency/Opaque
Glow
Rainbow
Strobing level

Transitions:

Multiple transitions can be applied at once

Fill up instantly on load (default)
Fill up on load (left to right)
Fill up on load (right to left)
Fade in on load
Electrify on load (full spectrum)
Electrify on load (left to right)
Electrify on load (right to left)
Glow on load (full spectrum)
Glow on load (left to right)
Glow on load (right to left)

Location:

You can duplicate the counter to any/all location

Above
Below
Above, left sidebar
Below, left sidebar
Above, right sidebar
Below, right sidebar
```

**🌱️ This [`README.md`](/README.md) file is a major stub, and needs significant expansion.**

***

# File info

**File version:** `1 (2023, Wednesday, June 7th at 11:14 pm PST)`

***
