# BANKI: All the questions to prep for interviews

- Any questions on this list are fair game for technical interviews.
- Resources where you can find most answers are at the end.
- Original list courtesy of https://leonnoel.com/100devs/

## Behavioral

Most of the behavioral questions should be answered in the CAR format. At least three sentences for each question (one for cause, one for action and one for result). When answering begin with "At my last opportunity..." or "At my last company". 

### CAR

- **Cause**
  - Why did you need to take action?
- **Action**
  - Steps you took so solve problem
  - Be positive
  - Don't be humble
- **Result**
  - How are you better?

### Questions

- [ ] Give me an example of a project or initiative that you started on your own. What prompted you to get started?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time you had to work on several projects at once. How did you handle this?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you felt you had not communicated well enough. What did you do? How did you handle it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about when you had to deal with conflict within your team. How was the conflict solved? How did you handle that? How would you deal with it now?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give me an example of a time you had to take a creative and unusual approach to solve coding problem. How did this idea come to your mind? Why do you think it was unusual?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you worked diligently on a project and it did not produce the desired results. Why didn't you get the desired results? What did you learn from the experience?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give an example of an important project goal you reached and how you achieved it.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you experienced difficulty in getting others to accept your ideas? What was your approach? How did this work? Were you able to successfully persuade someone to see things your way
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you were responsible for project planning. Did everything go according to your plan? If not, then why and what kind of counteractions did you have to take?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you made a mistake at work. What happened exactly and how did you deal with it? What steps did you take to improve the situation?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time when you worked with someone who was not completing his or her share of the work. How did you handle the situation? Did you discuss your concern with your coworker? With your manager? If yes, how did your coworker respond to your concern? What was your manager's response?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation when you worked effectively under pressure. How did you feel when working under pressure? What was going on, and how did you get through it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about yourself.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your experience at 100Devs.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you know about our company?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why do you want to work for us?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why are you interested in this opportunity?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your dream job?  What do you really want to do with your career?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me a time when you failed.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you read on a regular basis?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What's some critical feedback you've gotten recently?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Do you have any questions?
  - **Cause:**
  - **Action:**
  - **Result:**

## Technical Questions

Most of the technical questions should have a three sentence response in the EUE format:

- **Explanation**
- **Use**
- **Example**

### HTML

- [x] What does a doctype do?
  - **Explanation:** The doctype is the required first line <!DOCTYPE html> of an HTML document. 
  - **Use:** This line ensures that browsers will use full-standards mode when rendering the page. 
  - **Example:** Before the development of the W3C web standards, HTML documents were written in different versions for different browsers. The doctype ensures that your document will be parsed the same way by all browsers, according to the HTML5 web standards. 
  - **Source:** 
    - https://developer.mozilla.org/en-US/docs/Web/HTML/Quirks_Mode_and_Standards_Mode
    - https://www.freecodecamp.org/news/what-is-the-doctype-declaration-in-html/
- [x] How do you serve a page with content in multiple languages?
  - **Explanation:** You can serve a page with content in multiple languages by setting the lang attribute on any tags on the page. 
  - **Use:**  First, you set the lang attribute on the root/html tag with the default language of the content, so that it is inherited by the child elements. Then for any elements in a different language, set their lang attribute to that language. 
  - **Example:** For example, if you had a page of English text with a few quotes in French, you would set `<html lang="en">` and then `<q lang="fr">` on the quotes.
  - **Source:** https://www.w3.org/International/questions/qa-html-language-declarations
- [x] What kinds of things must you be wary of when DESIGNING for multilingual sites?
  - **Explanation:** Some issues you must be aware of when designing for multilingual sites include the inaccuracy of machine translations, the need to adjust content and assets for cultural sensitivity, and the need to organize content in a way that is intuitive for speakers of other languages. 
  - **Example:** For example, if you're designing a page in Arabic, which is written right to left, you'll want to arrange the navigation and menu options in reverse order from a typical page in English. You may also need to avoid images of women with loose hair and exposed skin, as this could be offensive to an Arabic audience.   
  - **Source:** https://www.popwebdesign.net/popart_blog/en/2018/01/multilingual-website-design-mistakes/
- [x] What kinds of things must you be wary of when DEVELOPING for multilingual sites?
  - **Explanation:** Some issues you must be aware of when developing for multilingual sites include:
    - using the lang attribute in your HTML (though you should always do this anyway) 
    - having menu options that allow the user to change the language of the page
    - avoiding placing text in raster-based images (e.g. png, jpg, gif), as each language will need a separate image
    - designing layouts and components that won't break if the translated text is much longer
    - being aware of differing perceptions of color
    - formatting currency and dates differently
    - not concatenating translated strings, as the word order may be different
    - organizing content with the language reading direction in mind             
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] What are `data-` attributes good for?
  - **Explanation:** Data attributes are used on elements to store custom data which relates to that application and for which there is no standard attribute. 
  - **Example:** For example, if you wanted to sort a list of music tracks by length, you could add `data-length="#"` to each track. 
  - **Use:** Data attributes are also useful as hooks for end-to-end testing frameworks such as Selenium.  
  - **Source:** 
    - https://www.frontendinterviewhandbook.com/html-questions#what-are-data--attributes-good-for
    - https://html.spec.whatwg.org/multipage/dom.html#embedding-custom-non-visible-data-with-the-data-*-attributes
    - https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes
- [X] Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  - **Explanation:** HTML5 is the newest version of the free and open source technologies on which the web is based, including HTML and web APIs. 
  - **Use:** The building blocks or new features of HTML5 include:
    - semantics - new elements to more precisely describe content (ex: `<main>`, `<section>`, `<nav>`)  
    - offline and client-side storage (ex: local storage and session storage)
    - native audio and video support ()
    - native support for dynamic 2D/3D graphics through the `<canvas>` element
    - access to new input and output devices (ex: cameras, microphones, screen sharing)
    - better performance and hardware integration
    - connectivity - new ways to communicate with the server
    - more sophisticated styling
  - **Example:**
  - **Source:** 
     - https://www.w3.org/wiki/Open_Web_Platform, https://developer.mozilla.org/en-US/docs/glossary/html5
     - https://www.frontendinterviewhandbook.com/html-questions#consider-html5-as-an-open-web-platform-what-are-the-building-blocks-of-html5
     - https://www.thoughtco.com/why-use-html5-canvas-3467995#:~:text=According%20to%20the%20HTML5%20specification,web%20page%20in%20real%2Dtime.
- [X] Describe the difference between a cookie, sessionStorage and localStorage.
  - **Explanation:** Cookies, sessionStorage, and localStorage are all ways to store string data on the client side. However, cookies are sent back to the server with each subsequent HTTP request, whereas sessionStorage and localStorage are not. 
  - **Use/Example:** Cookies are typically used for remembering stateful information, such as whether two requests came from the same browser. For example, cookies might be used to remember a user's shopping cart contents, set user preferences, or track user behavior.
  - **Use/Explanation:** Local storage differs from session storage in that localStorage persists across browser sessions, but sessionStorage is cleared once the user closes that tab. 
  - **Use/Example:** A use case for sessionStorage would be to autosave user inputs to a form if the page is refreshed, while localStorage might be used for saving the scores for a simple game, like Wordle.  
  - **Source:** 
    - https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies#other_ways_to_store_information_in_the_browser
    - https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API
    - https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview#http_is_stateless_but_not_sessionless 
- [X] Describe the difference between `<script>`, `<script async>` and `<script defer>`.
  - **Explanation:** When execution reaches a plain `<script>` tag, the browser stops parsing the HTML, fetches the script file, and executes it before it resumes parsing the HTML. This causes two problems: 1) the script can't access any DOM elements that have not been parsed yet, and 2) the user can't see the rest of the page content until the script is finished. 
  - **Use:** `<script defer>` and `<script async>` are solutions to these problems. `<script defer>` downloads the scripts in the background and then executes the scripts in document order once the HTML document has been loaded and parsed. `<script async>` downloads the scripts in the background and then pauses the HTML to execute each script as it finishes loading. 
  - **Example:** `<script defer>` should be used for scripts which need the whole DOM or are dependent on each other, where `<script async>` should be used for completely independent scripts, like ads or Google Analytics.  
  - **Source:** 
    - https://javascript.info/script-async-defer
    - https://www.growingwiththeweb.com/2014/02/async-vs-defer-attributes.html#script 
- [X] Why is it generally a good idea to position CSS `<link>`s within `<head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  - **Explanation:** Placing CSS `<link>`s in the `<head>` allows the page to render progressively, which improves user experience. If `<link>`s are placed at the bottom of the document, some browsers block rendering so that elements do not need to be repainted if their styles change. Users will be stuck looking at a blank page or seeing flashes of unstyled content. The W3C standards specify that CSS `<link>`s should be placed in the `<head>`. 
  - **Example (Exception):** Two exceptions are HTML email, which uses inline styles, as it does not have access to external stylesheets, and critical path CSS, where the styles needed for generating the content above the fold are put directly into a `<style>` tag in the head. 
  - **Explanation:** Placing JS `<script>`s just before the closing `</body>` tag is a often good idea because it allows the browser to display the page content to the user first, without waiting for the `<script>` to load and execute. It also allows the script to access DOM elements without throwing an error.
  - **Example (Exception):** A downside to this approach is that the browser cannot start downloading the scripts until the entire document is parsed. A solution is to place the scripts in the <head> with the defer attribute. 
  - **Source:** 
    - https://codeburst.io/clearing-your-front-end-job-interview-html-706f8b2c7dca
    - https://www.frontendinterviewhandbook.com/html-questions#why-is-it-generally-a-good-idea-to-position-css-links-between-headhead-and-js-scripts-just-before-body-do-you-know-any-exceptions
- [X] What is progressive rendering?
  - **Explanation:** Progressive rendering refers to rendering the most critical content on the page first, and then rendering the non-critical content in stages, as needed by the user. 
  - **Use:** Progressive rendering is used to reduce the perceived load time of the page. 
  - **Example:** Techniques for progressive rendering include lazy loading of images (i.e. images do not load until the user scrolls to them), prioritizing "above the fold" content, and rendering critical content on the server and streaming it in chunks to the browser. 
  - **Source:**
    - https://stackoverflow.com/questions/33651166/what-is-progressive-rendering
    - https://medium.com/the-thinkmill/progressive-rendering-the-key-to-faster-web-ebfbbece41a4#:%7E:text=Progressive%20Rendering%20is%20the%20technique,the%20whole%20page%20to%20rendered.
- [x] Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  - **Explanation:** The srcset attribute allows you to specify multiple image files that the browser can choose from when displaying that image. 
  - **Use:** You would use this attribute when you need to display the same image in different sizes, depending on the size and resolution of the screen.
  - **Example:** When evaluating this attribute, the browser divides the width of each image by the screen's width to determines which image is the best size for the current screen. 
  - **Source:**
    - resolution switching problem (use srcset) vs. art direction problem (use <picture>)
    - https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images
    - https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/
    - https://cloudfour.com/thinks/responsive-images-101-definitions/
- [x] Have you used different HTML templating languages before?
  - **Explanation:** I've used primarily EJS in my fullstack applications to generate HTML dynamically.  
  - **Use:** At my previous job, I also used templated HTML in Google Apps Script, to build a spreadsheet add-on for managing student recommendations. 
  - **Example:** I love EJS for its simple syntax, but I've found that most HTML templating languages provide similar functionality.  
  - **Source:**

### CSS

- [x] What is CSS selector specificity and how does it work?
  - **Explanation:** CSS selector specificity is how the browser determines which styles to apply to an element. 
  - **Use:** The specificity weight of a declaration is determined by the number of selectors of each weight category: id selectors, class selectors, and tag selectors. Id selectors have the highest weight, while tag selectors have the lowest weight. 
  - **Example:** For example, the selector .main #hero-image would have a specificity of 1.1.0. 
  - **Explanation:** The browser calculates the specificity for each declaration that matches the element, and the declaration with the highest specificity is applied, or in case of a tie, the declaration that comes last in the stylesheet. 
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
- [x] What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  - **Explanation:** A CSS reset clears out all of the browser's default styling so that you can start from scratch. A "normalizing" stylesheet changes the default styles of different browsers to match each other. 
  - **Use:** Both of these solutions are used to make styles appear consisent across browsers. 
  - **Example:** I generally prefer to use the "normalizing" approach, to take advantage of some useful default styling, speed development, and keep my file size smaller. 
  - **Source:**
- [x] Describe floats and how they work.
  - **Explanation:** Float is a CSS positioning property that moves an element to the right or left and allows other elements to flow around it. 
  - **Use:** They were often used to make flexible column layouts, as well as to make text wrap naturally around an image. 
  - **Example:** Floats come with several problems. For instance, a parent element will collapse to zero height if it contains only floated elements, and elements around the float can also be affected by it. Flexbox and grid are better tools for creating flexible layouts. 
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/#describe-floats-and-how-they-work
- [x] Describe z-index and how stacking context is formed.
  - **Explanation:** Z-index controls the vertical stacking order of overlapping elements. 
  - **Use:** By default, elements stack vertically in the order they appear in the DOM, but the z-index property allows us to change this behavior. 
  - **Example:** Stacking contexts are created by the root <html> element, when an element is positioned and given a z-index value other than auto, or when an element has an opacity of less than 1. Stacking contexts create a separate layer. The children inside each stacking context are ordered relative to their parent, before that layer is in turn arranged relative to any outer stacking contexts. 
  - **Source:** 
     - https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context
     - https://www.frontendinterviewhandbook.com/css-questions/#describe-z-index-and-how-stacking-context-is-formed
     - https://www.oreilly.com/library/view/developing-web-components/9781491905685/ch04.html#:~:text=A%20stacking%20context%20is%20created,z%2Dindex%20value%20is%20auto%20.
- [x] Describe BFC (Block Formatting Context) and how it works.
  - **Explanation:** In the CSS rendering of a page, Block Formatting Context is a region in which blocks are laid out. New BFCs are created by floats, fixed or absolutely positioned elements, inline-blocks, table-cells, elements with overflow other than visible, and elements with display: flow-root.  
  - **Use:** A BFC is like a mini-layout inside your page, and it's important because contains any floats inside it and prevents margin-collapsing. 
  - **Example:** For example, if you needed to contain a floated box inside a parent container, you could eatablish a new BFC by setting display: flow-root on the container. 
  - **Source:** https://www.smashingmagazine.com/2017/12/understanding-css-layout-block-formatting-context/
     - https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context 
- [x] What are the various clearing techniques and which is appropriate for what context?
  - **Explanation:** One technique for clearing floats is the .clearfix hack. 
  - **Use:** The .clearfix hack works by inserting an element with no content just inside the closing tag of the parent container so that it can't collapse, and setting clear: both on this element.   
  
```css  
        .clearfix:after {
            content: "";
            display: table;
            clear: both;
        }
```
  - **Explanation:** Another technique is establishing a new block formatting context by setting overflow: auto or display: flow-root on the parent container. 
  - **Example:** I would go with .clearfix or display: flow-root in most contexts, as setting overflow: auto can lead to unintended scrollbars.
  - **Source:** https://css-tricks.com/snippets/css/clear-fix/
  
- [x] Explain CSS sprites, and how you would implement them on a page or site.
  - **Explanation:** CSS sprites are a way of combining multiple images into one image file, and then using the background-image and -position properties to display a part of the image each time. 
  - **Use:** They are used to increase performance, since you only need to download one image, rather than multiple images. 
  - **Example:** Image sprites are a great technique for small icons or a graphical text-editor menu. 
  - **Source:** https://css-tricks.com/css-sprites/
- [x] How would you approach fixing browser-specific styling issues?
  - **Explanation:** There are a number of approaches to this issue, such as serving browser-specific stylesheets and using a library like Bootstrap. I always start by using Normalize.css or Reset.css, to make styling consistent across browsers. I also research the feature support for the browsers I am using and implement vendor prefixes, fallback properties, and polyfills to take care of any browser-specific issues.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions#how-would-you-approach-fixing-browser-specific-styling-issues
- [x] How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?
  - **Explanation:** I prefer to plan for feature-constrained browsers from the beginning by building lightweight, simple sites using progressive enhancement. 
  - **Use:** If you focus on building the base HTML and CSS with semantics and accessibility in mind, you'll get a site that works well in feature-constrained browsers. I then layer on additional CSS and client-side JavaScript judiciously and use vendor prefixes, fallbacks, and polyfills to add support for newer features in older browsers as needed. 
  - **Example:** I also use CSS @support feature query rules to apply certain styles only if the browser supports them. 
  - **Source:** 
     - https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/HTML_and_CSS#common_cross_browser_problems
     - https://www.frontendinterviewhandbook.com/css-questions#how-do-you-serve-your-pages-for-feature-constrained-browsers-what-techniquesprocesses-do-you-use
- [x] What are the different ways to visually hide content (and make it available only for screen readers)?
  - **Explanation:** There are several ways to hide content visually but keep it accessible for screen readers. For instance, you can position it absolutely off screen (`left: -1000px; top: -1000px;`), set its height and width to 0, or use the clip-path or text-indent properties.
  - **Use:** I prefer to define a "visually hidden" class that combines all of the various solutions, to make sure that it works in all browsers. 
  - **Example:**
  
```css
  .visually-hidden {
      position: absolute;
      width: 1px;
      height: 1px;
      padding: 0;
      margin: -1px;
      overflow: hidden;
      clip-path: inset(0, 0);
      white-space: nowrap; /* added line */
      border: 0;
  }
  
```
  
  - **Source:** https://a11y-guidelines.orange.com/en/web/components-examples/accessible-hiding/
  
- [x] Have you ever used a grid system, and if so, what do you prefer?
  - **Explanation:** Yes, I have created grid layouts with floats, flexbox, and CSS grid. 
  - **Use:** I like to use flexbox for building smaller components, which can in turn be positioned on the page using CSS grid. I prefer using grid for the overall layout of the page, since it allows you to more precisely place elements along both axes. 
  - **Example:** Grid also allows you to easily create very different layouts for different breakpoints. 
- [x] Have you used or implemented media queries or mobile specific layouts/CSS?
  - **Explanation:** Yes, I use media queries and mobile-specific layouts on every site I build, to make my pages responsive. 
  - **Use:** I typically design for mobile first, locate the breakpoints, and use media queries to convert the layout from mobile to desktop. 
  - **Example:** For example, I often move the navigation bar inside a hamburger menu below a certain breakpoint, or change the flex-direction of a card container from row on desktop to column on mobile. 
- [x] Are you familiar with styling SVG?
  - **Explanation:** Yes, I am. SVGs can be styled by adding attributes to a node, using inline CSS, embedding a CSS section in a <style> tag in the definitions section, or linking external CSS files.
  - **Use:** I have edited logos and icons by using the `fill` and `stroke` attributes to change colors. 
  - **Example:** <rect width="100" height="100" stroke="blue" fill="purple" />
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Fills_and_Strokes  
- [x] Can you give an example of an `@media` property other than screen?
  - **Explanation:** In media queries, there are properties for media types and media features. 
  - **Use:** The three media types are all, screen, and print (others are deprecated). Some media features include min-width and max-width, aspect-ratio, resolution, orientation, color, grid, and bitmap.
  - **Example:** For example, you could write a query `@media screen and (max-width: 390px)` to target screen devices under 391px wide. 
  - **Source:** 
      - https://drafts.csswg.org/mediaqueries/#media-types
      - https://developer.mozilla.org/en-US/docs/Web/CSS/@media#accessibility_concerns
- [x] What are some of the "gotchas" for writing efficient CSS?
  - **Explanation:** It's important to keep in mind that browsers parse selectors from right to left, so they first find all the elements that match the key selector, and then parse the prequalifiers.
  - **Use:**  You want to avoid using long relationship selectors and key selectors that match many elements, like tag and universal selectors. The shorter the length of the selector chain, the faster the browser can render the styles. 
  - **Example:** For example, using a single class like `.hero_image` is a better choice than `.hero img`. 
  - You also want to be aware of properties that trigger reflow, repaint, or compositing, and avoid writing styles that change the layout. 
  - **Source:**
     - https://www.frontendinterviewhandbook.com/css-questions#what-are-some-of-the-gotchas-for-writing-efficient-css
     - https://csstriggers.com/
     - BEM Metholodology - "Block, Element, Modifier" - https://en.bem.info/methodology/quick-start/
     - https://web.dev/rendering-performance/
     - https://developers.google.com/speed/docs/insights/browser-reflow
- [x] What are the advantages/disadvantages of using CSS preprocessors?
  - **Explanation:** CSS preprocessors have a lot of useful features, like the ability to use variables, math operations, and mixins (to define reusable styles), as well as the ability to organize styles into multiple files and combine them later. 
  - **Use:** These features can make CSS faster to write and easier to maintain and organize. 
  - **Example:** For example, by using variables, you can change a color in one place instead of having to change it everywhere. 
  - **Explanation: ** One disadvantage is that debugging is harder, because the line numbers of the generated CSS don't correspond to the line numbers of our preprocessed CSS. Second, preprocessors can generate huge CSS files. Finally, the compilation step slows development (since you have to wait for it to finish in order to see your changes).  
  - **Source:**
     - https://techaffinity.com/blog/advantages-of-css-preprocessors/
     - https://sass-lang.com/guide
     - https://adamsilver.io/blog/the-disadvantages-of-css-preprocessors/
- [x] Describe what you like and dislike about the CSS preprocessors you have used.
  - **Explanation:** I've used Sass, especially to customize Bootstrap colors. 
  - **Use:** I find the ability to use variables and split code into multiple files very useful features.  
  - **Example:** I dislike having to wait for compilation to see my changes, as it slows my workflow and makes it harder to test each piece as I'm writing it. 
  - **Source:**
- [x] How would you implement a web design comp that uses non-standard fonts?
  - **Note:** web design comp = web design comprehensive = a mock-up 
  - **Explanation:** I would implement non-standard fonts by using the `@font-face` CSS rule and defining the weights needed for that font. 
  - **Use:** This approach will load the font from the server if the user does not have it installed on their computer. I would also be sure to define font fallbacks in the `font-family` property, in case for some reason the font files were blocked from downloading.
  - **Example:** You can also implement some non-standard fonts by linking a Google font stylesheet in the head of your HTML. 
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face
- [x] Explain how a browser determines what elements match a CSS selector.
  - **Explanation:** The broswer parses a CSS selector from right to left. It first finds all the elements that match the key selector. Then for the prequalifiesr, it traverses up it the elements' parents in the DOM to determine which elements match. 
  - **Example:** For example with the selector `p span`, browsers first find all the `<span>` elements and traverse up their parents all the way up to the root to find any `<p>` elements. For a particular `<span>`, as soon as it finds a `<p>`, it knows that the `<span>` matches and can stop its matching.
  - **Use:** This is why it is so important to use short selector chains and avoid key selectors that match many elements (like tags and *). 
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions#explain-how-a-browser-determines-what-elements-match-a-css-selector
- [x] Describe pseudo-elements and discuss what they are used for.
  - **Explanation:** Pseudo-elements are keywords added to a CSS selector that let you style a particular part of the selector or add content that is not in the HTML. 
  - **Use:** They include `:first-letter`, `first-line`, `::before` and `::after`.  
  - **Example:** For example, if you wanted to make the first letter in each paragraph larger, you could use `p:first-letter`. If you wanted to add decorative icons without cluttering the document tree with unsemantic elements, you could use `::before` to insert them. 
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions#describe-pseudo-elements-and-discuss-what-they-are-used-for
- [x] Explain your understanding of the box model and how you would tell the browser, through CSS, to render your layout in different box models.
  - **Explanation:** In the box model, every element on the page is represented as a rectangular box of content, with optional padding, border, and margin. The box model is responsible for calculating the dimensions of each box and whether or not their padding or margin will overlap or collapse. 
  - **Use:** In the default content-box setting, the browser calculates a box's size by taking its specified height/width and adding any padding and border to get its total size. 
  - **Example:** So for example, if an element's width is set at 100px, but it has a left padding and right padding of 20px each, the box's total width would be 140px. 
  -**Explanation:** To use the more intuitive border-box model, you would set `{box-sizing: border box}` on the universal selector (and any before/after pseudo elements). This allows you to specify the total dimensions of a box, including any padding or border, with the `height` and `width` properties. So in the previous example, if the total width of the element is set at 100px and it has a left and right padding of 20px each, the content would be only 60px wide, to account for the 40px of padding. 
  - **Source:** https://www.smashingmagazine.com/2010/06/the-principles-of-cross-browser-css-coding/#understand-the-css-box-model
- [x] What does `* { box-sizing: border-box; }` do? What are its advantages?
  - **Explanation:** Setting `* { box-sizing: border-box; }` allows you to specify the total dimensions of a box, including any padding or border, with the `height` and `width` properties.  
  - **Use:** This allows you to set actual sizes and avoid having to do any math to take padding and borders into account.
  - **Example:** So for example, if the total width of the element is set at 100px and it has a left and right padding of 20px each, the content would be only 60px wide, to account for the 40px of padding. 
  - **Source:** https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#the_alternative_css_box_model
- [x] What is the CSS `display` property and can you give a few examples of its use?
  - **Explanation/Use:** The `display` property defines whether an element is treated as a block or inline element in the flow layout of the page, and also the layout used for its children, such as flow layout, grid or flex.
  - **Example:** For example, if you set `display: block`, you're setting the outer display value; the next element will start on a new line, so that the boxes are laid out vertically. If you set `display: flex` you're setting the inner display value, so the element's children will be laid out as flex items within that container. You can also set values like `display: none`, which renders the page without the element, or combo values like `display: inline-flex`, which treats the element itself as an inline element in the flow layout, but lays its children out as flex items. 
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/display
- [x] What's the difference between `inline` and `inline-block`?
  - **Explanation:** Inline elements are laid out horizontally on the same line, and wrap to a new line when they run out of space. They can have horizontal padding and margin, but cannot be given explicit width, height, or vertical margin. 
  - **Use:** Inline-block elements are still laid out horizontally on the same line, but can take on all box model properties, like block elements can (including width, height, and vertical margin).
  - **Example:** A good use case for inline-block elements could be links in a navigation menu, so that they can be arranged horizontally, but can be given consistent dimensions (rather than defaulting to the width of the link text). 
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flow_Layout/Block_and_Inline_Layout_in_Normal_Flow
- [x] What's the difference between a `relative`, `fixed`, `absolute` and `static` positioned element?
  - **Static** is the default value for the `position` property, and it means that the element is positioned according to the normal flow of the document. 
  - **Relative** behaves the same way as static, unless you combine it with box-model offsets, like `top`, `bottom`, `left`, and `right`, which shift the element relative to its default position. For example, `position: relative `and `left: 20px` shift the element 20px to the left of its normal position. Other elements will not fill the space it would otherwise have occupied, but they may overlap at its new position. 
  - **Absolutely** positioned elements are removed from the document flow and no space is left for them in the page layout. The box offset properties position the element relative to its nearest positioned parent (or the body).  
  - **Fixed** also works in conjunction with the same box offest properties, but the element is positioned relative to the viewport and stays in that position when the screen is scrolled. 
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/position
- [x] What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
  - **Explanation:** I have used Bootstrap in production. 
  - **Use:** It's useful for making a site look decent quickly, but your sites end up looking very similar to other Bootstrap sites. You can also end up with a lot of extra divs and other unsemantic mark-up, which isn't great for accessibility.
  - **Example:** I would improve Bootstrap by making semantic HTML and accessibility core features of the framework, rather than something you can make work if you're adding the right aria roles, etc. 
  - **Source:** 
    - https://betterprogramming.pub/3-reasons-to-abandon-bootstrap-in-2021-aa71bbc1af14
- [x] Have you played around with the new CSS Flexbox or Grid specs?
  - **Explanation:** Yes, I have used both flexbox and grid, and both have their advantages for different situations. 
  - **Use:** Flexbox solves many traditional CSS problems, like vertical centering of elements within a container. It's is primarily meant for layouts in one direction, while grid is meant for laying out content in both directions.
  - **Example:**  I often use flexbox to build smaller components or sections, and then use grid to arrange those components on the page. I love how grid allows you to create very different layouts at different breakpoints by using `grid-template-areas`. 
  - **Source:** https://philipwalton.github.io/solved-by-flexbox/
- [x] Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
  - **Explanation:** A responsive website is coded to dynamically adapt its content and layout based on different screen sizes, orientations, and devices. A mobile-first strategy is also responsive, but all styles are defined for the mobile breakpoint first, and then additional styles are defined for larger screens. 
  - **Use:** Using a mobile-first strategy for responsive design can ensure that mobile users have a seamless and optimized experience. 
  - **Example:** For example, mobile-first sites perform better on mobile devices with limited bandwidth, since their styles don't have to be checked against media queries before being applied. 
  - **Source:**
     - https://www.frontendinterviewhandbook.com/css-questions#can-you-explain-the-difference-between-coding-a-website-to-be-responsive-versus-using-a-mobile-first-strategy
- [x] How is responsive design different from adaptive design?
  - **Explanation:** In a responsive site, the design changes fluidly and continually based on the size of the browser at any point, whereas in an adaptive site, the design changes at specific breakpoints or on specific devices. 
  - **Use:** Both strategies are used to optimize a website's content and layout for different screens. 
  - **Example:** One way to think about the difference is smooth vs. snap design. For example, as the browser width increases, a responsive container smoothly expands. An adaptive container, however, might start at one size and then snap to another size once the browser width is above 500px.  
  - **Source:**
     - https://css-tricks.com/the-difference-between-responsive-and-adaptive-design/
     - https://www.fastcompany.com/3038367/9-gifs-that-explain-responsive-design-brilliantly-2
- [x] Have you ever worked with retina graphics? If so, when and what techniques did you use?
  - **Explanation:** Retina is a marketing term coined by Apple to describe screens with high enough pixel density that the human eye can't pick out individual pixels. In order to keep images looking crisp on high resolution screens, we need to use high resolution graphics whenever possible, while also minimizing page load times.
  - **Use:** One technique I use to overcome this issue is serving responsive images using the HTML5 `srcset` attribute.  
  - **Example:** This allows us to provide a set of image options at different sizes and let the browser calculate the best image for the screen size and resolution.  
  
   ```
  <img
  src="/images/test-1600.jpg"
  srcset="
    /images/test-400.jpg   400w,
    /images/test-800.jpg   800w,
    /images/test-1200.jpg 1200w
  "/>
  ```
  
  - **Source:**
     - https://www.frontendinterviewhandbook.com/css-questions#have-you-ever-worked-with-retina-graphics-if-so-when-and-what-techniques-did-you-use
     - https://imulus.github.io/retinajs/
- [x] Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?
  - **Use:** `transform: translate()` is a much better choice for animations than `absolute` positioning. 
  - **Explanation:** `absolute' positioning changes the layout, so it triggers reflow, paint, and compositing. `translate()` on the other hand only triggers compositing, so it is much more efficient and results in smoother animations. 
  - **Example:** When using `translate()`, the element's original space on the page is still preserved (sort of like `position: relative`), so you might want to use `absolute` positioning if that's not the desired behavior. 
  - **Source:**
     - https://web.dev/animations-overview/#pipeline
     - https://web.dev/animations-guide/ 
     - https://csstriggers.com/transform

### Javascript

- [x] Explain event delegation
  - **Explanation:** Event delegation is a technique for adding the same event handling to many similar DOM elements. 
  - **Use:**  You add one event handler to the parent element, rather than separate event handlers to each child element. When the event is triggered on any of the children, the listener will fire due to event bubbling. 
  - **Example:** For example, if we wanted to highlight a list item on click, we could add an event listener to the `<ul>`, use the event.target property to check which `<li>` was clicked, and use that to highlight the correct `<li>`. 
  - **Source:**
     - https://www.frontendinterviewhandbook.com/javascript-questions/#explain-event-delegation
     - https://javascript.info/event-delegation
- [x] Explain how `this` works in JavaScript
  - **Explanation:** `this` refers to the object that is executing the current function. 
     - If the function is called with the `new` keyword, `this` refers to the new object created by the constructor. 
     - If `apply`, `call`, or `bind` are used to call/create a function, `this` inside the function is the object that is passed in as the argument.
     - If the function is a method, `this` refers to the object that the function is a property of. 
     - If the function is not tied to an object, `this` refers to the global object, or the Window object if the code is being executed in the browser. 
  - **Use:** `this` is very useful for assigning properties to an object when instantiated from a class. 
  - **Example:**
     
     ```
     class Dog {
        constructor(name, breed) {
           this.name = name, 
           this.breed = breed
          }
     } 
     const rover = new Dog('Rover', 'labrador')
     console.log(rover.name)
     ```
  
  - **Source:** Mosh: https://www.youtube.com/watch?v=gvicrj31JOM
     - https://codeburst.io/the-simple-rules-to-this-in-javascript-35d97f31bde3
     - https://www.frontendinterviewhandbook.com/javascript-questions/#explain-how-this-works-in-javascript
  - **Note:** ES6 arrow functions - `this` works differently
- [x] Explain how prototypal inheritance works.
  - **Explanation:** All JavaScript objects have a `__proto__` property that refers to another object, which is called its prototype. These `__proto__` properties form a chain that links all the way up to the global Object prototype. 
  - **Use:** Prototypal inheritance lets us to define properties and methods once on the prototype object, and any objects created from that prototype will also have access to those properties and methods. When we access a property on an object, if it is not found on that object, the JS engine looks for the property on that objects's prototype, and then the prototype's prototype, and so on, until it finds the property or reaches the end of the chain. 
  - **Example:** For example, if we have an array `const numbers = [1, 2, 3]` and call the method numbers.join(''), the JS will first look for the `.join` method on the numbers object. When it can't find it there, it goes to the prototype, which is the Array object, finds the `.join`. method there, and calls it. 
  - **Source:**
    - https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes
    - https://www.frontendinterviewhandbook.com/javascript-questions#explain-how-prototypal-inheritance-works
  
- [ ] What do you think of AMD vs CommonJS?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Explain why the following doesn't work as an IIFE: `function foo(){ }();`. What needs to be changed to properly make it an IIFE?
  - **Explanation:** This code doesn't work as an IIFE (immediately invoked function expression) because it is using a function declaration rather than a function expression. The parser interprets it as two separate statements, a function declaration `function foo(){ }` and then an empty function call `()`.
  - **Use:**  To make this code work, you need to add parentheses around the function (i.e. starting from the word function and ending after the curly braces). The added parentheses make the function an expression, which is then immediately called with the ending set of parentheses `()`.
  - **Example:** `(function foo(){ })();` 
  - You also need to be sure to use semicolons at the end of each statement when working with IIFEs, or your code will throw an error. 
  - **Source:**
     - https://www.javascripttutorial.net/javascript-immediately-invoked-function-expression-iife/
     - https://www.frontendinterviewhandbook.com/javascript-questions/#explain-why-the-following-doesnt-work-as-an-iife-function-foo--what-needs-to-be-changed-to-properly-make-it-an-iife
- [x] What's the difference between a variable that is: `null`, `undefined` or undeclared? How would you go about checking for any of these states?
  - **Explanation:** 
     - An undeclared variable is created when you assign a value to a variable that has not previously been declared with `let`, `const`, or `var`. 
     - A variable that is undefined has been declared, but has not been assigned a value.
     - A variable that is null has been explictly assigned the value `null`, which represents no value. 
  - **Use:**
     - An undeclared variable will cause an error unless it is wrapped in a try/catch block. 
     - You can check for the values `undefined` and `null` by using the strict equality operator `===`. 
  - **Source:**
     - https://www.30secondsofcode.org/articles/s/javascript-undeclared-undefined-null 
     - https://www.frontendinterviewhandbook.com/javascript-questions#whats-the-difference-between-a-variable-that-is-null-undefined-or-undeclared-how-would-you-go-about-checking-for-any-of-these-states
- [ ] What is a closure, and how/why would you use one?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Can you describe the main difference between a `.forEach()` loop and a `.map()` loop and why you would pick one versus the other?
  - **Explanation:**
     - A `.forEach()` loop iterates through an array and executes a callback function for each element. 
     - A `.map()` loop iterates through an array and maps each element to a new value by calling a callback function on each element. 
     - The main difference is that `.forEach()` does not have a return value, whereas `.map()` returns an array of the new values.
  - **Use:** It's best to use `.map()` when you need to use the resulting array, or when you want to be sure not to mutate the original array. If you just need to do something for each element in the array but don't need to use the return value, you should use `.forEach()`. 
  - **Example:** For example, you might use `.forEach()` to log each element of the array or save it to a database. 
  - **Source:** https://codeburst.io/javascript-map-vs-foreach-f38111822c0f
- [x] What's a typical use case for anonymous functions?
  - **Use:** Anonymous functions are often used when you're passing one function to another function as an argument/callback.
  - **Example:** For example, if I'm writing a click event handler and the function I'm running on click doesn't need to be used anywhere else, I'll often use an anonymous function expression to write the code inline. I also do this with functions passed to methods like map and forEach. 
  - **Explanation:** Anonymous functions are also useful in IIFEs, to encapsulate a piece of code in local scope so that the variables declared inside it do not pollute the global scope. 
  - **Source:**
    - https://www.quora.com/Whats-a-typical-use-case-for-anonymous-functions-in-JavaScript
    - https://www.frontendinterviewhandbook.com/javascript-questions#whats-a-typical-use-case-for-anonymous-functions
- [ ] How do you organize your code? (module pattern, classical inheritance?)
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] What's the difference between host objects and native objects?
  - **Explanation:** Native objects are those built into the language itself, whereas host objects are are built into the environment we're running our code in. 
  - **Use:** For example, in Javascript, native objects are those defined in the ECMA Script standards, like String, Array, Object, Function, and RegExp. We always have access to these objects, no matter what runtime environment we're using. 
  - **Example:** Objects like window, location, and setTimeout are host objects; they are provided by the browser environment, and we do not have access to them when we're running our code in a different environment, like Node. 
  - **Source:** https://stackoverflow.com/questions/7614317/what-is-the-difference-between-native-objects-and-host-objects
- [x] Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  - **Explanation:** Since the convention is to capitalize the names of constructor functions, I would expect `function Person(){}` to be a constructor function and use `this` to define the properties of the object.   
  - **Use:** `var person = new Person()` correctly calls the Person() constructor with the `new` keyword, and returns an instance of the Person object that inherits the properties of `Person.prototype`. 
     - `var person = Person()` incorrectly calls Person() as a regular function, so the `person` variable will end up as `undefined`. 
  - **Example:**
  ```
    function Person(name) {
      this.name = name;
    }

    var person = Person('John');
    console.log(person); // undefined
    console.log(person.name); // Uncaught TypeError: Cannot read property 'name' of undefined

    var person = new Person('John');
    console.log(person); // Person { name: "John" }
    console.log(person.name); // "John"
  ```
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new
     - https://www.frontendinterviewhandbook.com/javascript-questions/#difference-between-function-person-var-person--person-and-var-person--new-person
- [x] What's the difference between `.call()` and `.apply()`?
  - **Explanation:** Both `.call()` and `.apply()` allow you to call a function, using the first argument passed in as the function's `this` value. The difference is that for any additional arguments of the function, `.call()` takes individual comma-separated arguments, while `.apply()` takes an array of arguments.  
  - **Use:** One use case for `.call()` and `.apply()` is to chain object constructors. 
  - **Example:** 
      ```
      function Product(name, price) {
        this.name = name;
        this.price = price;
      }

      function Food(name, price) {
        Product.call(this, name, price);
        this.category = 'food';
        // add other food-specific fields here
      }

      function Beverage(name, price) {
        Product.call(this, name, price);
        this.category = 'beverage';
        // add other beverage-specific fields here
      }

      const cheese = new Food('feta', 5);
      const wine = new Beverage('wine', 15);
  
      ```
  - **Source:** https://betterprogramming.pub/when-to-use-bind-call-and-apply-in-javascript-1ae9d7fa66d5
    - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call
- [x] Explain `Function.prototype.bind`.
  - **Explanation:**  `Function.prototype.bind` returns a new function that will use the first argument passed in as its `this` value when it is called. (The new function's `this` value is "bound" to that object.)
  - **Use:**  It's similar to `.call()` and `.apply()`, except that with .bind(), the function does not immediately run.  
  - **Example:** `.bind()` can be very useful for binding a callback function's `this` value. Otherwise, the callback's `this` value will be set to the `this` value of the enclosing higher-order function.
  - **Source:** https://thenewstack.io/mastering-javascript-callbacks-bind-apply-call/
     - https://betterprogramming.pub/when-to-use-bind-call-and-apply-in-javascript-1ae9d7fa66d5
- [x] When would you use `document.write()`?
  - **Explanation:** `document.write()` is an outdated part of the DOM web API. It writes a string of text to a document that has been previously opened with `document.open`. 
  - **Use:** I would not use this method, because the HTML spec specifically discourages it due to its unpredictable behavior. 
  - **Example:** For example, if `document.write()` is called on a closed/loaded document, it will also call `document.open()`, which clears the contents of the document. Some browsers specifically block scripts inserted with `document.write()` from executing. 
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/API/Document/write
- [ ] What's the difference between feature detection, feature inference, and using the UA string?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain Ajax in as much detail as possible.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the advantages and disadvantages of using Ajax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain how JSONP works (and how it's not really Ajax).
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you ever used JavaScript templating? If so, what libraries have you used?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain "hoisting".
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe event bubbling.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between an "attribute" and a "property"?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is extending built-in JavaScript objects not a good idea?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Difference between document `load` event and document `DOMContentLoaded` event?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] What is the difference between `==` and `===`?
  - **Explanation:** Triple equals `===` is the strict equality comparison operator, meaning that it checks whether the two  values are the same in both value and type. Double equals `==` is the loose equality comparison operator, meaning it checks that the two operands match in value, but disregards their type. For `==`, if the two values are not the same type, they are converted to the same type before being compared.
  - **Example:** For example, `"1" === 1` evaluates to false, since one is a string and the other is a number. However, `"1" == 1` evaluates to true; the number 1 is converted to the string `"1"` for the purposes of comparison. 
  - **Use:** I generally use the strict equality operator whenever possible, since I think it makes the code clearer and leaves fewer questions.  
  - **Source:**
- [ ] Explain the same-origin policy with regards to JavaScript.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5] `
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it called a ternary expression, what does the word "ternary" indicate?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is "use strict";? what are the advantages and disadvantages to using it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain what a single page app is and how to make one SEO-friendly.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the extent of your experience with Promises and/or their polyfills?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the pros and cons of using Promises instead of callbacks?
  - **Explanation:** avoiding callback hell
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What tools and techniques do you use debugging JavaScript code?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What language constructions do you use for iterating over object properties and array items?
  - **Explanation:** 
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the difference between mutable and immutable objects.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the difference between synchronous and asynchronous functions.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is event loop? What is the difference between call stack and task queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the differences on the usage of foo between `function foo() {}` and `var foo = function() {}`
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the differences between variables created using `let`, `var` or `const`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the differences between ES6 class and ES5 function constructors?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What advantage is there for using the arrow syntax for a method in a constructor?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the definition of a higher-order function?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you give an example for destructuring an object or an array?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you give an example of a curry function and why this syntax offers an advantage?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the benefits of using spread syntax and how is it different from rest syntax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How can you share code between files?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why you might want to create static class members?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Javascript General

- [ ] Can you name two programming paradigms important for JavaScript app developers?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is functional programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between classical inheritance and prototypal inheritance?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the pros and cons of functional programming vs object-oriented programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are two-way data binding and one-way data flow, and how are they different?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is asynchronous programming, and why is it important in JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Node

- [ ] What is Node.js? Where can you use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why use Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the features of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you update NPM to a new version in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is Node.js Single-threaded?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain callback in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is callback hell in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you prevent/fix callback hell?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the role of REPL in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Name the types of API functions in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the functionalities of NPM in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between Node.js and Ajax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are “streams” in Node.js? Explain the different types of streams present in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain chaining in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are Globals in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Event-driven programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Event loop in Node.js work? And How does it work?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the purpose of `module.exports` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between Asynchronous and Non-blocking?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Tracing in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How will you debug an application in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Difference between `setImmediate()` and `setTimeout()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is `process.nextTick()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is package.json? What is it used for?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is libuv?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are some of the most popular modules of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is `EventEmitter` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### CS Theory 

- [ ] What is recursion and give an example using javascript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are types?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are data structures?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is an algorithm?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is scope / lexical scope in javascript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is polymorphism?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is encapsulation?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Doubly Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Stack?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Hash Table?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Heap?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Trie?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Binary Search Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Disjoint Set?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Bloom Filter?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Bubble Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Insertion Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Merge Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Quicksort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

## Questions to ask your interviewer

1. How does Bob’s Burgers measure the success of their engineers?
2. What challenges can an engineer come across while working at Bob’s Burgers?
3. Can you explain "thing you read on their engineering blog" and how it affects Bob’s Burgers Engineers?
4. What traits are hard to find in an engineer that Bob’s Burgers would like to have?
5. How is critique given to engineers at Bob’s Burgers?
6. Do you have any questions or concerns about my qualifications?

Here is a helpful list of other reverse interview questions: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)

## Whiteboard

When talking through a whiteboard problem or a coding challenge with an interviewer you should use the PREP method. (Don't write PREP in the actual interview, but use it now while doing codewars/leetcode). Going through this will help you engage with the interviewer (and possibly burn up some time 😉)

- **Parameters**
  - Inputs
  - Ask questions
    - Will it always be a number?
    - Will it ever be negative?
    - Any gotchas?
- **Returns**
  - Ask questions
    - Do you want it returned or is a console.log better?
    - Should I pass a whole array of solutions back or just a single solution?
- **Examples**
  - Show a couple black box examples, aka test cases
    - I pass in these arguments and get these results, is that correct?
  - Examples are a good idea because "you have the receipts" if the interviewer decides to change things.
- **Pseudocode**
  - Write pseudocode of each of the steps

## Resources:

- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
- [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [https://github.com/yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook)
- [https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [https://www.simplilearn.com/node-js-interview-questions-and-answers-article](https://www.simplilearn.com/node-js-interview-questions-and-answers-article)
- [https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678](https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678)
