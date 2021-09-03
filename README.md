# The Luisa scss toolkit
This repos intent is to provide the LeadDesk development team with easy-to-use tools for ensuring product alignment with the Luisa design system.
The idea is to provide different levels of implementation, and multiple ways of usage. Projects have different needs, and developer teams have different approaches.

## Testable development styles are currently available in the build folder
* luisa.all.css – Everything
* luisa.variables.css – All, but only, css custom properties
* luisa.mixins.css – All, but only, mixins
* luisa.classes.css – All, but only, the utility classes

### Swatches
#### Background
    mixin usage: @include luisa.background("[swatch]","[shade#]")
    class usage: .l-background:swatch:shade
#### Color
    mixin usage: @include luisa.color("[swatch]","[shade#]")
    class usage: .l-color:swatch:shade
### Typography
### Spacing
#### Border radius
    mixin usage: @include luisa.border-radius("[direction]","[size]")
    class usage: .l-border-radius:direction:size
