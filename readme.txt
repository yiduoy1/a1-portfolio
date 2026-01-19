--Readme document for *YOUR NAME*, *YOUR_EMAIL@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

*/10
- */1 Readme
- */2 Basic HTML content
- */1 Basic CSS styling
- */1 Advanced feature
- */2 Responsive layout
- */1 Passes validation checks
- */2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features



(b) CSS features



(c) Advanced features




3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.



4. How long, in hours, did it take you to complete this assignment?



5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)



6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?



7. Is there anything special we need to know in order to run your code?

//////////////////////
Readme document for Yiduo Yao, yiduoy1@uci.edu

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else's code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features (6 included, 3 required):
- Images with descriptive alt attributes: Profile photo (my_protrait.JPG), experience page images (EEG.jpeg, Beckman.jpeg, ncasd.jpeg, ocPark.jpeg), and decorative background (background_leaf.jpeg)
- Appropriate headings and paragraph text: h1 for name, h2 for subtitle and section headings, paragraph text for experience descriptions
- Links to external pages: LinkedIn profile, research paper PDF (biorxiv.org), Beckman Laser Institute website, OC Parks Collections website, Calit2 Data Ecosystem website, and resume PDF download
- Multiple pages with appropriate navigation: 5 pages total (index.html + 4 experience detail pages) with fixed sidebar navigation and back buttons
- Semantic HTML tags: <main>, <header>, <nav>, <footer>, <section> used throughout for proper document structure
- Custom icons from Font Awesome: fa-at (email), fa-phone, fa-linkedin, fa-file (resume), fa-arrow-left (back button), fa-external-link (external links)

(b) CSS features (4 included, 2 required):
- Modifying padding and margins: Applied throughout for readability, including experience boxes, footer sections, description containers, and form elements
- Modifying colors: Green gradient color scheme on experience boxes (darkest #2D3B1A to lightest #4A5928), black/white theme for text and backgrounds, red (#c00) for required field indicators
- Custom Google fonts with fallbacks: Aboreto (headings), Bungee Hairline (logo and initials), SUSE Mono (body text and form elements), all with appropriate system-ui or monospace fallbacks

(c) Advanced features (4 included, 1 required):
- Complex page layout with fixed sidebar/navigation bar: Fixed sidebar containing logo "YY" and resume download icon, visible on all pages
- Embedded HTML5 media with fallback: Audio element on EEG experience page (EEGaudio.wav) with fallback text "Your browser does not support the audio element"
- Nested CSS selectors: Used for experience box styling (e.g., .experience-row:nth-child(1) .experience-box .title) to create gradient color effect across rows
- Contact form using HTML forms: Functional contact form with name (text), email (email), and message (textarea) fields, integrated with Formspree for form submission

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

I addressed all errors flagged by the accessibility checker. The remaining items are "Manual Check Required" warnings which require human judgment rather than code fixes:

- "Alt text may not convey the same information as the image" (Check 178): My alt texts are descriptive and accurate (e.g., "EEG research equipment showing a participant wearing an EEG cap with electrodes while brain activity is displayed on a computer monitor"). These describe the actual content of images for screen reader users.

- "Image may be decorative" (Check 16): The decorative background leaf image has alt="" and role="presentation" to correctly indicate it is decorative.

- "Link text may not be meaningful" (Check 19): All links have descriptive aria-labels (e.g., aria-label="View EEG research experience at UC Davis Health Department of Anesthesiology and Pain Medicine") that provide context for screen reader users.

- "Title might not describe the document" (Check 54): Page titles are descriptive (e.g., "EEG Research | Yiduo Yao - Portfolio") and accurately reflect page content.

- "Headings may be used for formatting" (Checks 42, 43): Headings are used semantically for document structure, not just visual formatting. The heading hierarchy (h1 for name, h2 for sections) is logical.

- "Form submission error messages" warnings: The form uses HTML5 required attributes and Formspree handles validation and error messaging appropriately.

- "Text direction" and "language of parts" warnings: The entire site is in English with no mixed-direction or foreign language content requiring special markup.

4. How long, in hours, did it take you to complete this assignment?

Approximately 8-10 hours, including design planning, coding, accessibility remediation, and validation testing.

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

- Google Fonts (https://fonts.google.com/) - for Aboreto, Bungee Hairline, and SUSE Mono fonts
- Font Awesome (https://fontawesome.com/) - for icon library
- Formspree (https://formspree.io/) - for contact form backend integration
- MDN Web Docs (https://developer.mozilla.org/) - for HTML5 audio element syntax and ARIA attributes
- W3C Validator (https://validator.w3.org/) - for HTML validation
- W3C CSS Validator (https://jigsaw.w3.org/css-validator/) - for CSS validation
- WAVE Web Accessibility Evaluation Tool (https://wave.webaim.org/) - for accessibility checking
- AChecker (https://achecker.achecks.ca/checker/) - for accessibility validation
- Claude AI (Anthropic) - used for code assistance, debugging CSS issues, implementing accessibility fixes, and generating content descriptions

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

None.

7. Is there anything special we need to know in order to run your code?

- All files use relative paths and should work when opened directly in a browser
- The contact form requires an internet connection to submit via Formspree
- The audio file (EEGaudio.wav) on the EEG experience page requires the file to be present in the same directory
- The resume link (resume.pdf) requires the PDF file to be present in the same directory
- External stylesheets (Font Awesome, Google Fonts) require an internet connection to load properly
- The site is fully responsive and can be tested using Chrome DevTools device emulation