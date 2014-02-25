Repository for CSS libraries for use with WAM (see web-asset-manager repo)


File Extension Standard
---

    .cse - Expandable
    .csd - Defines only
    .csa - Compiled css file containing a pragma or other preprocessor argument
    .css - Pure css file

Standard use
---

1. Macros take the place of functions and should begin with a lower case letter and be underscore separated (avoid camel case).
2. .cse files should only be included by .csd files.
3. .csd files should never contain css code
4. .css files should never contain preprocessor directives
5. No library file should be minified.
