# FLEXBOX

The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.

## Flexbox Keywords

|       Name      |                                      Value                                     |          Initial          |         Applies to         |                       Com­puted value                       |
|:---------------:|:------------------------------------------------------------------------------:|:-------------------------:|:--------------------------:|:-----------------------------------------------------------:|
|  align-content  | flex-start \| flex-end \| center \| space-between \| space-around   \| stretch |          stretch          | multi-line flex containers | specified keyword                                           |
|   align-items   | flex-start \| flex-end \| center \| baseline \| stretch                        |          stretch          | flex containers            | specified keyword                                           |
|    align-self   | auto \| flex-start \| flex-end \| center \| baseline \| stretch                |            auto           | flex items                 | specified keyword                                           |
|       flex      | none \| [ <‘flex-grow’> <‘flex-shrink’>? \|\|   <‘flex-basis’> ]               |          0 1 auto         | flex items                 | see individual properties                                   |
|    flex-basis   | content \| <‘width’>                                                           |            auto           | flex items                 | specified keyword or a computed <length-percentage>   value |
|  flex-direction | row \| row-reverse \| column \| column-reverse                                 |            row            | flex containers            | specified keyword                                           |
|    flex-flow    | <‘flex-direction’> \|\| <‘flex-wrap’>                                          | see individual properties | see individual properties  | see individual properties                                   |
|    flex-grow    | <number>                                                                       |             0             | flex items                 | specified number                                            |
|   flex-shrink   | <number>                                                                       |             1             | flex items                 | specified value                                             |
|    flex-wrap    | nowrap \| wrap \| wrap-reverse                                                 |           nowrap          | flex containers            | specified keyword                                           |
| justify-content | flex-start \| flex-end \| center \| space-between \| space-around              |         flex-start        | flex containers            | specified keyword                                           |
|      order      | <integer>                                                                      |             0             | flex items                 | specified integer                                           |

## Links

* https://www.w3.org/TR/css-flexbox-1/#placement
* https://www.w3schools.com/css/css3_flexbox.asp
