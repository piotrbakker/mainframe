# Mainframe

Mainframe is a framework for naming product design artifacts in Figma.

## Principles

* In general, follow [title case formatting rules](https://en.wikipedia.org/wiki/Title_case).
* Separate title values with hyphens.
* Separate component and style values with slashes.
* Express dates according to the [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) notation: [YYYY]-[MM]-[DD] or [YYYY]-[MM].
* Avoid sequential numbering to reduce clutter.
* Use clear, plain language that everyone can understand. 

## Figma’s File Structure

Figma uses the following file structure:

```
Organization > Workspaces > Teams > Projects > Files > Pages > Frames
```

In addition, `Components`, `Styles`, and `Variables` can be published as `Libraries` for access across different `Files`:

```
Libraries > Components / Styles / Variables
```

* `Components` are collections of `Variant Properties` that form a single element in a `Library`.
* `Styles` are collections of presentation properties that can be applied to different elements in a `File` or `Libary`.
* `Variables` are fixed values, like hexadecimal color codes or measures of size, that can be reused across any `File` or `Libary`.

## Projects

Organize `Projects` by your team’s product development workflow or organizational structure. For example, by stages of the user journey or design process, or more broadly by product type or platform.

## Files

File names are composed of the following elements:

```
[File Category] - [Product Name] - [Project Name] - [Branch Name]
```

Commonly used file categories include:

* Wires — low-fidelity wireframes & sketches;
* Visual — high-fidelity mockups;
* Library — separate shared style & component repositories;
* System — multiple shared style & component repositories organized into a single file.

## Pages

In progress...

## Frames

[Top-level frames](https://help.figma.com/hc/en-us/articles/360039959014) should include product name, appended by key technical information, such as product type, dimensions, layout grid settings.

## Styles

In progress...

## Components

In progress...

## Libraries

In progress...

## Examples

### Files

```
Wires - Mainframe - Web - Landing 2023-01
Visual - Mainframe - Web - Account 2023-01
Visual - Mainframe - Mobile - Checkout 2023-01
Library - Mainframe - Icons - Main
System - Mainframe - Web - Main
```

### Frames

```
Mainframe - Newsletter - 768px - Col-12 r1
Mainframe - Newsletter - 1024px - Col-12 r2
Mainframe - iOS - 4.7in - Col-4 r1
Mainframe - iOS - 5.8in - Col-4 r2
```

## License

Mainframe is available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Please link back to the source when you share and / or adapt any of the contents.
