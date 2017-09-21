### React and Styling

#### Basic Concepts

- **Styling in React**  
  https://www.kirupa.com/react/styling_in_react.htm  
  An introduction to using React's built-in inline styling abilities
  
- **How To Style React**  
  http://andrewhfarmer.com/how-to-style-react/  
  An excellent overview of the four major ways to deal with styles in React, and what the various tools are.  Includes a decision tree to help you decide what to use.
  
- **CSS in JS**  
  http://blog.vjeux.com/2014/javascript/react-css-in-js-nationjs.html  
  Christopher Chedeau's classic talk that inspired the "CSS in JS" revolution
  
- **Components: A Styling Odyssey**  
  https://speakerdeck.com/alexlande/components-a-styling-odyssey  
  Slideshow discussing pros and cons of various approaches to managing styles for components
  
- **A Unified Styling Language**  
  https://medium.com/seek-blog/a-unified-styling-language-d0c208de2660  
  A fantastic article that reviews why people might want to write their styles in Javascript, explores possible benefits of doing so, and looks at how the "CSS" and "JS" communites can work together going forward.
  
- **U&I With React**  
  https://github.com/FarhadG/ui-react  
  A free online book that teaches how to modular, extendable, and scalable component-based UIs.  Covers best practices, and techniques like CSS preprocessors, CSS modules, inline styles, and more.  Chapters available to read for free on Github, and the Leanpub book can be picked up for free as well.
  

#### Components and Styling
  
- **Component Based Style Reuse**  
  https://www.youtube.com/watch?v=_70Yp8KPXH8  
  Pete Hunt talks about various approaches to defining styles for components in plain CSS and in React
  
- **Patterns for Style Composition in React**  
  http://jxnblk.com/writing/posts/patterns-for-style-composition-in-react/  
  Some great suggestions for defining reusable React components that can have variations in styling
  
- **Functional CSS From A Pure UI Perspective**  
  https://medium.com/@sharifsbeat/functional-css-from-a-pure-ui-perspective-bd04c8af4fdc  
  Thoughts on various ways to compose classes and styles together.
  
- **React JS Style Components**  
  https://www.youtube.com/watch?v=gNeavlJ7lNY  
  A talk describing ways to better compose existing styles in an application, using components.
  
- **Orthogonality and CSS in JS**  
  https://benmccormick.org/2017/01/03/orthogonality-and-css-in-js/  
  Some thoughts on the "separation of concerns" concept, and how that relates to defining modular code and components (including styling).
  
- **James Kyle's thoughts on styling and components**  
  https://twitter.com/i/moments/861549552901468160  
  A Twitter thread from James Kyle, discussing how many of the arguments about styling and components are a result of people building different kinds of applications
  
  
#### CSS-Based Approaches
  
- **CSS Modules by Example**  
  http://andrewhfarmer.com/css-modules-by-example/  
  A set of 7 examples demonstrating ways to use CSS modules.
  
- **Elephants, The Three Code Ilities, & Two Months With CSS Modules**  
  http://chrispearce.co/elephants-the-three-code-ilities-two-months-with-css-modules/  
  A look at how Lystable used CSS Modules to scale their codebase.
  
- **Functional CSS - The Good, The Bad, and Some Protips for React.js Users**  
  https://github.com/chibicode/react-functional-css-protips  
  An essay describing the "functional CSS" approach, pros and cons of using it, and tips for using that approach with React.
  
- **How we made our product more personalized with CSS Variables and React**  
  https://medium.com/geckoboard-under-the-hood/how-we-made-our-product-more-personalized-with-css-variables-and-react-b29298fde608  
  A walkthrough of how to build a themeable application using React components that update CSS variables for dynamic styles
  
  
#### JS-Based Approaches
  
- **Journey to Enjoyable, Maintainable Styling with React, ITCSS, and CSS-in-JS**  
  https://medium.com/maintainable-react-apps/journey-to-enjoyable-maintainable-styling-with-react-itcss-and-css-in-js-632cfa9c70d6  
  A long, in-depth article detailing one dev's progression through various approaches to handling CSS.
  
- **Thoughts on Inline Styles**  
  https://medium.com/@andrewingram/my-thoughts-on-inline-styles-da94682b5e35  
  A look at reasons why people might or might not use inline style approaches, and some opinions and suggestions on when to use different approaches.
  
- **Style as a Function of State**  
  https://medium.com/@rofrischmann/styles-as-functions-of-state-1885627a63f7  
  A look at how styles can be managed similar to UI, and an example using the author's new styling library
  
- **Invidual Paint for your React Components**  
  https://vimeo.com/album/4199344/video/187454103  
  A talk discussing various approaches to manage styles and themes for React
  
- **Writing Your Styles in JS != Writing Inline Styles**  
  http://mxstbr.blog/2016/11/inline-styles-vs-css-in-js  
  Max Stoiber describes the key difference between "inline styles" and "CSS-in-JS" approaches: styles applied to elements vs styles added to a style tag.  
  
- **CSS-in-JS comparisons**  
  https://github.com/MicheleBertoli/css-in-js  
  A repository that contains implementation comparisons between many different CSS-in-JS libraries
  
- **Comparing CSS in JS Solutions**  
  http://ludovf.net/blog/comparing-css-in-js-solutions/  
  An overview of the various CSS-in-JS libraries and how their implementations differ.
  
- **CSS in React Comparison Examples**  
  https://github.com/joeshub/css-in-react  
  A repo that demonstrates the basics of several different React CSS approaches and libraries.
  
- **Should I use CSS-in-JS with React?**  
  https://reactarmory.com/answers/should-i-use-css-in-js  
  Some opinionated thoughts on the pros and cons of using CSS-in-JS approaches, including concerns about possibly security issues.
  
  
#### Style Libraries

- **Styling ReactJS Applications**  
  https://www.youtube.com/watch?v=19gqsBc_Cx0  
  Max Stoiber's talk at ReactNL 2016, comparing various options for styling React applications and introducing his new library, Styled-Components.
  
- **Scalable Styles in Production JS**  
  https://medium.com/front-end-hacking/scalable-styles-in-production-js-cde88016f357  
  Some comparisons between various approaches to managing styles (plain CSS, inline styles, CSS-in-JS), and why Aphrodite can help solve some of the issues that come up.
  
- **"Styled Components or Glamor?"**  
  https://www.reddit.com/r/reactjs/comments/5eq8ew/styled_components_or_glamor/  
  Discussion and comparisons between some different CSS-in-JS libraries
  
- **The magic behind styled-components**  
  http://mxstbr.blog/2016/11/styled-components-magic-explained/  
  A look at how the styled-components library uses the new ES6 "tagged template literals" feature to interpolate arguments and build up CSS
  
- **Styled-Components: Enforcing Best Practices**  
  https://www.smashingmagazine.com/2017/01/styled-components-enforcing-best-practices-component-based-systems/  
  A look at some best practices for writing styles for reusable components, and how the styled-components library can help enforce those principles.

- **A 5-Minute Intro to Styled Components**  
  https://medium.freecodecamp.com/a-5-minute-intro-to-styled-components-41f40eb7cd55  
  A quick intro to the styled-components library
  
- **CSS in JS: The Argument Refined**  
  https://medium.com/@steida/css-in-js-the-argument-refined-471c7eb83955  
  The author of the Este.js boilerplate describes his investigation of various React styling libraries, and how he ended up building his own
  
- **Styled-Components in Action**  
  https://medium.com/@lvarayut/styled-components-in-action-723852f2a93d  
  A tutorial that walks through the main goals and concepts of Styled-Components, with examples
  
- **Emotion: The Next Generation of CSS-in-JS**  
  https://medium.com/@tkh44/emotion-ad1c45c6d28b  
  The author of the Emotion library gives an overview of its principles, benchmarks, and uses.

  
  
  
#### Techniques and Examples

- **How to build animated microinteractions in React**  
  https://medium.freecodecamp.com/how-to-build-animated-microinteractions-in-react-aab1cb9fe7c8  Examples of various ways to create small animations to give feedback as the user interacts with components
  
- **Create That Component**  
  https://medium.com/taitounited/create-that-component-1-7a2267bc2833  
  https://medium.com/taitounited/create-that-component-2-f6e6ba2e6b5a  
  https://medium.com/taitounited/create-that-component-3-25f1f722cead  
  A series of examples that build components for assorted concepts like toggle switches, ripple effects, and toasts, using libraries like styled-components.
  
