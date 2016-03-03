# Widths Tools

The Predix Experience Widths Tools allows you to generate a suite of utility classes for sizing pieces of UI.



## Dependency

Px's Widths Tools module depends on one other PXd module:

* [px-defaults-design](https://github.com/PredixDev/px-defaults-design)

## Installation

Install using Bower:

    bower install --save https://github.com/PredixDev/px-widths-tools-design.git

Once installed, `@import` into your project's Sass file in its Tools layer:

    @import "px-widths-tools-design/_tools.widths.scss";

## Usage

This flag is available and, if fractions are not desired, should be set to false prior to importing the module:

    $inuit-use-fractions

## Mixin provided

The following mixin is provided:

* `inuit-widths`: Generates series of classes in the format `.u-7/12` or `.u-7-of-12` (dependent on how the `$inuit-use-fractions` flag is set) to be used for sizing.
