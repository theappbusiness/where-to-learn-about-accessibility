# Where to learn about accessibility

Here are some of the best resources to start learning about accessibility and inclusive design.

We’ve included a wide range of formats and topics, often covering overlapping content. 

Click on whichever piques your curiosity. 

**Please feel free to ask questions, raise issues and contribute.**

Happy learning!

## Good general introductions

* [Google’s great free course on Udacity](https://eu.udacity.com/course/web-accessibility--ud891)

* [The Home Office’s ‘Dos and Donts’ posters](https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_en-UK/accessibility-posters-set.pdf)

* [A four part accessible design strategy](https://www.youtube.com/watch?v=4QsYk8XOUlw) (Government Digital Service)

* [London Accessibility Meetup Youtube channel](https://www.youtube.com/channel/UCDIVL2ytbhD9ZCn8GaEIi_g)

* [A Web For Everyone](https://www.amazon.co.uk/Web-Everyone-Designing-Accessible-Experiences/dp/1933820977) (book by Sarah Horton, message @jfhector to borrow a copy)

* [Mismatch](https://mitpress.mit.edu/books/mismatch) (book by Kat Holmes, which is the best book I've read on Inclusive Design)

## Learning about the Web Content Accessibility Guidelines

* https://www.w3.org/TR/WCAG21/ (W3C official)

The following resources cover the same guidelines (or sometimes more), but are written to be easier to read:

* [Deque's Accessibility Checklist](https://dequeuniversity.com/checklists/web/)

* [BBC Mobile Accessibility Guidelines](https://www.bbc.co.uk/guidelines/futuremedia/accessibility/mobile/summary)

* [Digital Accessibility Standards](https://home.barclays/who-we-are/our-suppliers/our-requirements-of-external-suppliers/#digital%20accessibility%20standards-tab) (Barclays, covers web, iOS and Android accessibility techniques)

## Learning about how people with disabilities use websites and apps

* [Web Accessibility Perspectives videos](https://www.w3.org/WAI/perspective-videos/) (W3C)

* [Personas for Accessible UX](https://rosenfeldmedia.com/a-web-for-everyone/personas-for-accessible-ux/) (from the book A Web For Everyone)

* [Certified Accessibility Professional Core Competencies preparation course](https://dequeuniversity.com/curriculum/courses/iaap-cpacc#iaap-cpacc) (Deque, $45)

### Learning about assistive technologies

* Rob Dodson's video demos of [macOS VoiceOver](https://www.youtube.com/watch?v=5R-6WvAihms), [iOS VoiceOver](https://www.youtube.com/watch?v=bCHpdjvxBws), [Android TalkBack](https://www.youtube.com/watch?v=0Zpzl4EKCco) and [Switch devices](https://www.youtube.com/watch?v=V1yoOLhx_qA)

* Deque's [Screen Reader Keyboard Shortcuts and Gestures](https://dequeuniversity.com/screenreaders/) cheat sheets show you how to use all the main screen readers

## Design-specific

* [Annotating designs for accessibility](https://drive.google.com/a/theappbusiness.com/file/d/1n0DkLoFydmbNxLisivqHh8xoo467HgBJ/view?usp=sharing) (TPG)

## Guides on how to test accessibility (which is everyone's job)

* [Accessibility Insights](https://accessibilityinsights.io/) (Microsoft’s great browser extension guides you through manual web accessiblity testing. It also integrates [Axe](https://www.deque.com/axe/) for the bits that can be tested automatically)

## Getting your questions answered

* #topic-accessibility on TAB’s Slack

* #grp-topic-a11y on TAB’s or K+C’s Slack

* Web-a11y.slack.com (Open to everyone. Ask @jfhector or anyone who’s already in to send you an invite)

* #a11y on Twitter

* You can also ask any question and get experts' answers quickly on [WebAIM mailing list](https://webaim.org/discussion/)

## Resources that require some knowledge about web development

* [Rob Dodson’s A11ycast Youtube Short Videos Series](https://www.youtube.com/playlist?list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g) (Google)

* [Accessibility | Web Fundamentals](https://developers.google.com/web/fundamentals/accessibility/) (Text version of [Google’s video course on Udacity](https://eu.udacity.com/course/web-accessibility--ud891))

* The [online web accessibility courses by Deque](https://dequeuniversity.com/curriculum/online-classes/) are very comprehensive and explain things in a lot of details. They are the easiest way to get good at web accessibility. Individual courses cost $45, and there’s a [bundle covering everything you need to know for $150](https://dequeuniversity.com/curriculum/packages/iaap-was).

* https://a11yproject.com/ Use the nav at the top of the page to find Patterns, Checklist and Resources

### Resources that require more knowledge about web development

#### Understanding ARIA and how to use it

* [Using ARIA](https://www.w3.org/TR/using-aria/) is a great official W3C document that explains in plain, concrete language how ARIA works, and how to use ARIA without messing things up. It’s a much more engaging read than the ARIA specs.

* [ARIA in HTML](https://www.w3.org/TR/html-aria/) is another short W3C document that explains ARIA semantics are implied by the different HTML elements, and what ARIA roles and attributes you can use on what HTML elements.

* Michael Fairchild's [a11ysupport.io](https://a11ysupport.io/) is still in its early days but is the best support table available for ARIA roles and attributes

#### Understanding how to build accessible UI components

* The [ARIA Authoring Practices Guide](https://www.w3.org/TR/wai-aria-practices-1.1/) is a great document that tells you how to implement a broad range of very common UI patterns (e.g. tabs, switches, toggles, dialog, feed, etc). Concretely, it tells you:
  * What keyboard support you need to implement to meet users’ expectations (which are largely set by how the same patterns are implemented in operating systems)
  * How to build these components using ARIA. (But be careful to read the document's 'Read me first' section if you intend to reuse these coding patterns as is)

##### Here are some great guides on how to design and code high-quality UI components

The following component examples are fully supported by browsers and screen readers today. They include more accessibility best practices than covered by the Web Content Accessibility Guidelines:

###### Guides or tutorials

* [Inclusive Components](https://inclusive-components.design/) by Heydon Pickering. This book/blog is a great place to start
* Scott O’Hara’s [Accessible Components](https://github.com/scottaohara/accessible_components) and [The Accessibility of Styled Form Controls](https://github.com/scottaohara/a11y_styled_form_controls) 
* This [great talk by Oliver Byford](https://obyford.com/posts/inclusive-forms/) explaining some accessibility considerations and implementation techniques behind the GDS Design System
* Lots of component patterns on [Adrian Roselli’s blog](https://adrianroselli.com/tag/accessibility)

###### Other components with good code annotations

Here are some other examples of highly accessible components:

* [TenonUI](https://www.tenon-ui.info/) (in React)
* [The technical guide of the BBC GEL design system](https://bbc.github.io/gel/)
* [The GDS Design System](https://design-system.service.gov.uk/)
