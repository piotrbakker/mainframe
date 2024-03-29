# Mainframe

Mainframe is a framework for organizing product design files in Figma. 

## Figma’s File Structure

Figma uses the following file structure:

```
Organization > Workspaces > Teams > Projects > Files > Pages > Frames
```

In addition, `Variables`, `Styles`, and `Components` can be published as `Libraries` for shared access across different `Files`:

* `Variables` are fixed values, like hexadecimal color codes or measures of size, that can be reused across any `File` or `Library`.
* `Styles` are composites of properties or settings that can be applied to different elements in a `File` or `Library`.
* `Components` are collections of `Variant Properties` that form a single element in a `File` or `Library`.

## Naming Convention

* In general, follow [title case formatting rules](https://en.wikipedia.org/wiki/Title_case).
* Separate title values with hyphens.
* Separate `Component` and `Style` values with slashes.
* Express dates according to the [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) notation: [YYYY]-[MM]-[DD] or [YYYY]-[MM].
* Avoid sequential numbering to reduce clutter.
* Use clear, plain language that everyone can understand.

## Projects

Organize `Projects` by your team’s product development workflow or organizational structure. For example, by stages of the user journey or design process, or more broadly by product type or platform.

## Files

Establish a consistent file naming convention to make it easy to identify and locate specific files. For example:

```
[File Category] - [Product Name] - [Project Name] - [Branch Name]
```

## Pages

Use `Pages` to separate rounds of design iterations, or different sections and user flows within your product. 

## Frames

_Top-level Frames_, i.e, Frames placed directly on the `Canvas`, should include values such as product name and key technical information, such as product type, screen dimensions, and layout grid settings. _Nested Frames_ should follow a semantic naming convention where applicable.

## Libraries
Set up your `Library` in a single or separate `Files`. Consider breaking up your `Library` into separate `Files` if you need to support multiple platforms, themes, products, brands or whether access to certain `Components` or `Styles` should be limited only to specific collaborators.

## Variables

Use `Variables` to create a design token structure for managing and maintaining alignment and consistency in a design system. 

Use the following syntax:

```
[Asset]-[Type]-[Property]-[State]
```

* Use full words instead of abbreviations.
* Use generic, platform- and brand-agnostic names.

## Styles

Group `Styles` by color scheme, product theme, function, effect or hue. Avoid creating distinct entities for every single style in use. Document rarely used styles as exceptions instead. 

## Components

* Take a modular approach to building components, for example by following [Atomic Design Principles](https://atomicdesign.bradfrost.com/chapter-2/).
* Use a semantic naming convention to give `Components` and `Variant Properties` descriptive names that convey function and meaning. 
* Follow a consistent naming structure that aligns with your codebase.

## Versioning

Set up a change log to track `Library` updates.

Best practices:
* Follow a [semantic versioning](https://en.wikipedia.org/wiki/Software_versioning#Semantic_versioning) version scheme.
* Give people time to transition and adopt changes.
* Establish a contribution process, for example through surveys or comments.

## License

Mainframe is available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Please link back to the source when you share and / or adapt any of the contents.
