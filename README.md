# PRQL Press materials and branding

PRQL is a modern language for transforming data — a simple, powerful, pipelined SQL replacement.
For more information about the language, see the
[PRQL site](https://prql-lang.org).

We call this project "prequel", and write its name in upper-case as `PRQL`.
(It's a backronym for "Pipelined Relational Query Language".) 
We name the repo and some libraries `prql` because of a strong convention around
lowercase, but everywhere else we use `PRQL`.

#### Licenses

We make PRQL software available under the
[Apache 2.0 License](https://github.com/PRQL/prql/blob/main/LICENSE).

We make the PRQL logo and wordmark available under the
[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)
(CC BY 4.0) license.
We seek to emulate the Rust Foundation's approach for their logo policy,
see the
[Rust logo policy and media guide](https://foundation.rust-lang.org/policies/logo-policy-and-media-guide/)

## About the logos and wordmarks

<!-- markdownlint-disable MD033 — Tell markdownlint that it's OK to scale the PNG images using inline CSS   -->

| Logo | Wordmark |
| ---- | -------- |
| <img style="margin-left:auto; margin-right:auto; display:block; height:75px" src="./logo/PNG/prql-logo.png" > | <img style="margin-left:auto; margin-right:auto; display:block; height:75px" src="./logo/PNG/prql-wordmark.png" > |

The _logo_ directory contains the **PRQL logo**
(multi-colored vertical stack of disks with descending white arrow) and
**PRQ wordmark** (the logo plus "PRQL") in various graphical formats:
SVG, PDF, PNG, JPEG, EPS, Ai.
Each format folder contains graphics with these filenames:

* **prql-logo.xxx** - the graphical PRQL logo
* **prql-wordmark.xxx** - the graphical PRQL logo including "PRQL"

**Font:** The PRQL wordmark uses the
[Inter](https://fonts.google.com/specimen/Inter)
Google font in ExtraBold (800) weight.

The images were created as a SVG.
Each document dimensions were adjusted so they exactly contain the content,
with no "whitespace" surrounding the image.
That makes it easier to use these images in graphic layout,
since it's easier to add padding to an image than to remove it.

_Note: Earlier versions of this repo did not
use consistent naming conventions for the logo files.
Those files have been updated to use the new font,
but retain the original dimensions
for backward compatibility._

## Tests

The _tests_ directory has an [HTML page](./tests/test-logos.html)
that places each PRQL logo on a
`dimgrey` background with a dashed `hotpink` border. 

If it is necessary to edit any of the logo files,
this page makes it easy to see that the image dimensions
remain exactly the same size as the image 
(with no "white space" around the edges of the image.)
