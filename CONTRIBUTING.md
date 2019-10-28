Contributing to the Design-system-sketch-file 🌵
=================

There are three pages within the Sketch file:

##### Design System Page

The purpose of the Design System page is to showcase how different themes affect the look of components. It allows designers to experiment with different colour schemes and see what their designs will look like.

##### Symbols Page

The purpose of the Symbols page is to show all of the available components and what they look like in each of their states (active, inactive, etc.) in each of the themes (light, dark alt, etc.) while using the standard Design System palette.

##### Example Page

The purpose of the Example page is to showcase how an implementation of the Design System would look on different screen types.

## Adding a new component to the Sketch file.
----------------------------

When adding a new component, ensure that it is added to the Design System page **and** the Symbols page. When adding a new component, the example page does not have to be updated.

The change log within the Sketch file is no longer updated. Changes are now tracked on Github under the releases section.

The following conventions should be followed when adding a new component to the Sketch file:
- Maintain spacing of 150 pixels between components.
- Insert components alphabetically.
- At a minimum, include light and dark versions. Ideally, it should also have a responsive version and an alt version of both.
- When naming a component within the Design System Page, the name should follow this style: `Component -- Text input`. Elements within the component follow this style: `Background light Alt`.
- When naming a component within the Symbols page, with the exception of styling declaration of a component (dark, light or alt), all words should be capitalised. For example, Accordion / dark / Alt / Open
- When adding a component to the Symbols page, use the following order: _Dark, Dark Alt, Light, Light Alt_.

There are examples throughout the file. If you have any questions, reach out to us.

