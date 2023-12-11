# Mainframe

Mainframe is a framework for organizing product design files in Figma. 

## Figma’s File Structure

Figma uses the following file structure:

```
Organization > Workspaces > Teams > Projects > Files > Pages > Frames
```

In addition, `Components`, `Styles`, and `Variables` can be published as `Libraries` for access across different `Files`:

* `Components` are collections of `Variant Properties` that form a single element in a `Library`.
* `Styles` are collections of presentation properties that can be applied to different elements in a `File` or `Library`.
* `Variables` are fixed values, like hexadecimal color codes or measures of size, that can be reused across any `File` or `Library`.

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

File names are composed of the following elements:

```
[File Category] - [Product Name] - [Project Name] - [Branch Name]
```

## Frames

Top-level `Frames`, i.e, Frames placed directly on the `Canvas`, should include values such as product name and key technical information, such as product type, screen dimensions, and layout grid settings. Nested `Frames` should follow a semantic naming convention where applicable.

## Components

Use a semantic naming convention to give `Components` and `Variant Properties` descriptive names that convey function and meaning. Follow a consistent naming structure that aligns with your codebase.

## License

Mainframe is available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Please link back to the source when you share and / or adapt any of the contents.
