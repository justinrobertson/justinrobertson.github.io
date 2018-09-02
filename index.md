(#top)
[Banzhaf & Yamamoto book](#Banzhaf)
List of relevant articles
MetaChem
York referencing
Source code examples and breakdown
Academic resources
Online Courses

## Banzhaf & Yamamoto book

Remember that SS stressed the importance of the bibliography.

*Nonconstructive chemistry:* one in which all the molecular objects are known beforehand.

*Well-stirred vessel:* A reaction vessel in which the actual position of the molecules is not modelled and so has no effect on the reactions taking place. The state of the system in a well-stirred vessel is fully described by the concentrations of each species present.

*Spatial reactor:* A reaction vessel that takes account of the physical distance between potential reactants. They cannot react unless they meet.

### The general structure of an AC

* S: The set of molecules.
This can be infinite.
* R: The rules by which molecules combine. When two molecules collide, if a set of rules is fulfilled then combination occurs. Parameters for proximity, rate, probability of reaction, energy, etc, can be included here.
* A: The algorithm describing the dynamics of the reactor vessel, e.g. is it well-stirred or spatial, does it have inflow and outflow, and how are collisions modelled.

#### Modelling collisions

##### Stochastic collisions

This is the naive approach that immediately suggests itself. The system is sampled at random (perhaps according to concentration) and a collision is then assumed between the selected molecules. A matching rule is sought and if one is found then the molecules combine according to the rule, otherwise they return to the reactor. Each collision is a separate event. *Most systems of interest are open systems relying on an inflow of raw materials and energy and an outflow of waste.* Presumably closed systems reach an equilibrium quickly. 


## York referencing (#referencing)
## List of relevant articles
## MetaChem
## Source code examples and breakdown

It's very easy to make some words **bold** and other words *italic*  and yet other ~~strikthrough~~ with Markdown. You can even [link to Google!](http://google.com)

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

* Item 1
* Item 2
  * Item 2a
  * Item 2b

  1. Item 1
  1. Item 2
  1. Item 3
     1. Item 3a
     1. Item 3b

![My image](/img/pic.png)
Format: ![Alt Text](url)

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

Links
http://github.com - automatic!
[GitHub](http://github.com)

Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.

Inline code
I think you should use an
`<addr>` element here instead.

[Top of page](#top)
