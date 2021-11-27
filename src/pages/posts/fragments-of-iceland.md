---
title: React
excerpt: >-
  Iceland is a Nordic country between the North Atlantic and the Arctic Ocean.
  It has a population of 325,671 and an area of 103,000 km2 (40,000 sq mi),
  making it the most sparsely populated country in Europe.
date: '2019-03-27'
thumb_img_path: images/7.jpg
thumb_img_alt: Icelandic horses
content_img_path: images/7.jpg
content_img_alt: Icelandic horses
seo:
  title: Fragments of Iceland
  description: Iceland is a Nordic country between the North Atlantic and the Arctic Ocean.
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: Fragments of Iceland
      keyName: property
    - name: 'og:description'
      value: >-
        Iceland is a Nordic country between the North Atlantic and the Arctic
        Ocean.
      keyName: property
    - name: 'og:image'
      value: images/7.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Fragments of Iceland
    - name: 'twitter:description'
      value: >-
        Iceland is a Nordic country between the North Atlantic and the Arctic
        Ocean.
    - name: 'twitter:image'
      value: images/7.jpg
      relativeUrl: true
template: post
---
# React Cheat Sheets:&#xA;&#xA;

# React Patterns:

## React Cheat Sheet

React:

*   \<script src="https://unpkg.com/react@15/dist/react.js">\</script>

*   $ npm install react --save

*   $ bower install react --save

React DOM:

*   \<script src="https://unpkg.com/react-dom@15/dist/react-dom.js">\</script>

*   $ npm install react-dom

*   $ bower install react-dom --save

## Rendering

### Rendering (ES5)

### Rendering (ES5+JSX)

## Server-side Rendering

## Components

### ES5

### ES5 + JSX

### ES6 + JSX

// notes: don't forget the command lines

## Advanced Components

### Options (ES5)

*   propTypes object: Type validation in development mode

*   getDefaultProps function(): object of default props

*   getInitialState function(): object of the initial state

ES5:

ES5 + JSX:

ES6 + JSX:

## Lifecycle Events

Modern React lifecycle methods (v16+) ![](https://bgoonz-blog.netlify.app/docs/react/cheatsheet/DZ-97vzW4AAbcZj.jpg)

Legacy Lifecycle Events:

*   componentWillMount function()

*   componentDidMount function()

*   componentWillReceiveProps function(nextProps)

*   shouldComponentUpdate function(nextProps, nextState)-> bool

*   componentWillUpdate function(nextProps, nextState)

*   componentDidUpdate function(prevProps, prevState)

*   componentWillUnmount function()

Sequence of lifecycle events:

![](https://bgoonz-blog.netlify.app/docs/react/cheatsheet/lifecycle-events.png)

Inspired by [http://react.tips](http://react.tips/)

## Special Props

*   key: Unique identifier for an element to turn arrays/lists into hashes for better performance, e.g., key={id}

*   ref: Reference to an element via this.refs.NAME, e.g., ref="email" will create this.refs.email DOM node or ReactDOM.findDOMNode(this.refs.email)

*   style: Accept an object of styles, instead of a string (immutable since v0.14), e.g., style={{color: red}}

*   className: the HTML class attribute, e.g., className="btn"

*   htmlFor: the HTML for attribute, e.g., htmlFor="email"

*   dangerouslySetInnerHTML: raw HTML by providing an object with the key \__html

*   children: content of the element via this.props.children, e.g., this.props.children\[0]

*   data-NAME: custom attribute, e.g., data-tooltip-text="..."

## propTypes

Types available under React.PropTypes:

*   any

*   array

*   bool

*   element

*   func

*   node

*   number

*   object

*   string

To make required, append .isRequired.

More methods:

*   instanceOf(constructor)

*   oneOf(\['News', 'Photos'])

*   oneOfType(\[propType, propType])

### Custom Validation

## Component Properties and Methods

Properties:

*   this.refs: Lists components with a ref prop

*   this.props: Any props passed to an element (immutable)

*   this.state: State set by setState and getInitialState (muttable) — avoid setting state manually with this.state=...

*   this.isMounted: Flag whether the element has a corresponding DOM node or not

Methods:

*   setState(changes): Change state (partially) to this.state and trigger re-render

*   replaceState(newState): Replace this.state and trigger re-render

*   forceUpdate(): Trigger DOM re-render immediately

## React Addons

As npm modules:

*   [react-addons-css-transition-group](http://facebook.github.io/react/docs/animation.html)

*   [react-addons-perf](http://facebook.github.io/react/docs/perf.html)

*   [react-addons-test-utils](http://facebook.github.io/react/docs/test-utils.html)

*   [react-addons-pure-render-mixin](http://facebook.github.io/react/docs/pure-render-mixin.html)

*   [react-addons-linked-state-mixin](http://facebook.github.io/react/docs/two-way-binding-helpers.html)

*   react-addons-clone-with-props

*   react-addons-create-fragment

*   react-addons-css-transition-group

*   react-addons-linked-state-mixin

*   react-addons-pure-render-mixin

*   react-addons-shallow-compare

*   react-addons-transition-group

*   [react-addons-update](http://facebook.github.io/react/docs/update.html)

## React Components

*   <https://github.com/brillout/awesome-react-components> and <http://devarchy.com/react-components>: List of React components

*   [Material-UI](http://www.material-ui.com/): Material design React components

*   [http://react-toolbox.com](http://react-toolbox.com/): Set of React components that implement Google Material Design specification

*   [https://js.coach](https://js.coach/): Opinionated catalog of open source JS (mostly React) packages

*   [https://react.rocks](https://react.rocks/): Catalog of React components

*   <https://khan.github.io/react-components>: Khan Academy React components

*   [http://www.reactjsx.com](http://www.reactjsx.com/): Registry of React components