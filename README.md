# OpenClassFirstProject
Open Class First Project

Summary Document - New Booki
Website
Here are all the technical and functional aspects to take into account for
the development of the new Booki website. These elements have all been
approved by the Product team, so it is important that you respect them.
Functional Specifications
● Users will be able to search for accommodation in the town of their
choosing. The search field is an input field, so users will need to be
able to edit this. This field should be part of a form so that it can be
validated by W3C. The search part does not need to be functional
● All maps for accommodation and activities should be entirely
clickable (and not just the title). For the time being the links are
empty. You can use a “href=”#”” attribute to simulate the presence of
a link
● The filters should change appearance during mouseover. I’ll leave
the exact effect up to you, I’ve not had time to think about it. But it
doesn’t need to be functional
● The words, “Accommodation” and “Activities”, which are part of the
header, are links. They should lead to the “Accommodation in
Marseille” and “Activities in Marseille” sections, respectively
Technical Specifications
● Two mockups were made: one for desktop and the other a mobile
version. The website will also have to be adapted for tablet formats.
For tablets we are free to make the necessary changes. It is
important that nothing is cut off, however, and that the text is of
sufficient size
● Regarding breakpoints, we agreed with the client that we would use
992px and 768px. 992px for computer screens, 768px for tablets and
below 768 for mobile phones
● You need to do the embedding for computers first (i.e. desktop first)
before moving on to the tablet version and then the mobile version.
Using Media Queries will enable us to do the embedding for these
different devices● We exported several formats and sizes of images. You will have to
choose the most appropriate format depending on the resolution
and the loading time
● The icons come from the Font Awesome library. We could use a CDN
to help with the loading of the icons
● The colours of the chart are blue (#0065FC), a lighter version of this
blue (#DEEBFF), and grey for the background (#F2F2F2)
● The font used for the website is Raleway. We can use Google Font to
easily import this font into the code:
https://fonts.google.com/specimen/Raleway
● It is important that we use pixels and percentages rather than REMs
and EMs. The client prefers this solution for technical reasons
● It is important that we use Flexbox rather than Grid for the same
reason: our client is more comfortable with this solution
● You should not use any CSS frameworks (such as BootStrap or
TailwindCSS) or pre-processors (such as Sass or Less)
● It is important to use semantic tags (such as “main”, “header”, “nav”,
etc.)
● The code should be valid according to the W3C HTML and CSS
validators
● The mockup should be compatible with the latest versions of Google
Chrome and Mozilla Firefox. You should test the prototype on these
two browsers
● You do not need to use Git for versioning the code
