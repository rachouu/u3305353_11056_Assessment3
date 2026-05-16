# Canberra Modern Website Redesign Rationale

## Overview

This project involved the redesign and front end development of a website for Canberra Modern, a volunteer led organisation focused on celebrating and preserving Canberra’s twentieth century architectural heritage. The objective of the redesign was to improve the organisation's digital presence through a more contemporary, accessible, and user-centred interface. The project required the transformation of a high fidelity prototype into a fully responsive website using HTML5 and CSS3 while considering usability, accessibility, responsiveness, and maintainability.

The overall design approach was guided by principles of minimalism and clarity. Architecture focused websites often rely heavily on imagery and spatial presentation, therefore the interface was intentionally restrained to allow visual content to remain the primary focus. Large scale photography, spacious layouts, and simplified navigation structures were used to create a contemporary visual identity that aligns with the modernist architectural themes promoted by Canberra Modern. According to Garrett (2011), successful user experiences emerge through the careful organisation of structure, interface, and visual presentation. These principles strongly informed the final outcome of the website.

## Design and Development Decisions

The navigation bar was designed as a fixed horizontal layout positioned at the top of each page. This decision aimed to improve navigation efficiency and maintain access to important sections regardless of scroll position. The “What's On” button was highlighted using a contrasting blue background in order to direct user attention towards events, which were identified as one of the primary user goals during the planning stage. This reflects Nielsen's (1994) usability heuristic concerning visibility and recognition, as key actions should remain clear and immediately accessible.

The hero section of the homepage was simplified during development. Earlier low fidelity concepts explored a more experimental visual approach involving large scale typography and a hidden pop out navigation menu. However, the pop out menu was ultimately removed from the final coded version because of difficulties implementing the interaction reliably through JavaScript within the project timeframe. Instead, the design evolved toward a cleaner and more stable fixed navigation system. This change demonstrates an important aspect of front end development practice, where design ambitions must occasionally be adapted in response to technical limitations and usability concerns.

Typography choices focused on readability and consistency across devices. Arial and Helvetica were selected because they are accessible sans serif fonts with strong legibility on digital interfaces. Clear typographic hierarchy was established through variations in scale, weight, and spacing. Lupton (2014) explains that typography contributes significantly to usability because it shapes how users scan and interpret content. Larger headings and generous white space were therefore used throughout the website to improve readability and reduce visual clutter.

The colour palette combined black and white foundations with blue and orange accent colours. This combination created visual contrast while maintaining a restrained and professional appearance. Blue was primarily used for navigation and interactive elements, while orange highlighted calls to action such as buttons. These colours provided visual distinction without overwhelming the content. Accessibility considerations also informed these choices because sufficient contrast improves readability for users with visual impairments (World Wide Web Consortium, 2018).

Responsiveness was an important component of the development process. CSS Grid and Flexbox were used extensively to create layouts that adapt smoothly across desktop, tablet, and mobile devices. Media queries adjusted typography, spacing, and layout structure at smaller breakpoints. Developing responsive layouts highlighted the importance of flexibility within modern web design practice. Some sections required repeated refinement to maintain visual balance across different screen sizes, particularly the events and footer layouts.

## Reflection on the Production Process

One of the strongest aspects of the final website is its visual consistency. The restrained aesthetic, balanced spacing, and structured layouts effectively communicate the architectural focus of Canberra Modern while maintaining clarity and usability. The navigation system is straightforward and intuitive, allowing users to move between sections with minimal confusion.

The project also revealed several challenges. The largest difficulty involved implementing the original hidden side navigation menu. While the interaction worked partially during experimentation, problems emerged surrounding event listeners and menu state behaviour. Rather than submitting an unstable feature, the decision was made to simplify the navigation system. This experience reinforced the importance of prioritising usability and reliability over unnecessary complexity.

Another challenge involved balancing visual aesthetics with responsive behaviour. Certain layouts that appeared effective on desktop screens became difficult to maintain on smaller devices. This required ongoing testing and adjustment through media queries and layout restructuring. Although the final outcome is functional and responsive, additional time would have allowed for further refinement of spacing, transitions, and accessibility features.

Overall, the project strengthened both technical and conceptual understanding of interaction design and front end development. The coding process demonstrated how design decisions directly influence usability, accessibility, and user experience. It also highlighted the importance of iterative problem solving throughout the development cycle.

## Annotated Resource List

- Garrett, J. J. (2011). *The elements of user experience: User centered design for the web and beyond*.  
  Used to guide decisions relating to structure, navigation, and user centred interaction design principles.

- Lupton, E. (2014). *Thinking with type*.  
  Referenced during typography selection and hierarchy development to improve readability and visual organisation.

- Nielsen Norman Group.  
  Consulted for usability principles relating to navigation clarity, feedback, and interface consistency.

- MDN Web Docs.  
  Used extensively throughout development to troubleshoot HTML and CSS implementation challenges, particularly responsive layouts and Flexbox behaviour.

- W3Schools.  
  Referenced during experimentation with CSS Grid, media queries, and responsive image handling.

- Canberra Modern website.  
  Used as the primary content source for organisational information, event details, and partner references.

## References

Garrett, J. J. (2011). *The elements of user experience: User centered design for the web and beyond* (2nd ed.). New Riders.

Lupton, E. (2014). *Thinking with type* (2nd ed.). Princeton Architectural Press.

Nielsen, J. (1994). *Usability engineering*. Morgan Kaufmann.

World Wide Web Consortium. (2018). *Web content accessibility guidelines (WCAG) 2.1*. https://www.w3.org/TR/WCAG21/