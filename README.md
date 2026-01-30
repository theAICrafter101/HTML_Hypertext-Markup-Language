# HTML_Hypertext-Markup-Language

## HTML Essentials
- Defines the structure and content of web pages.
- Elements are the building blocks; most have opening + closing tags.
- Void elements have no closing tag (e.g., img, meta).
- Attributes provide extra info or behavior (attribute="value").
- Boolean attributes: true when present (e.g., disabled, required).
- Comments allow developer notes, not shown in the browser.

## Common Elements
- Headings: h1–h6 (importance decreases downward).
- Paragraphs: p for text blocks.
- Images: img uses src and alt (text description).
- Body: Contains all visible page content.
- Sectioning: section for thematic blocks; div as a non-semantic container.
- Links: a uses href to navigate.
- Lists: ul (bulleted) and ol (numbered), each with li items.
- Text emphasis: em (emphasis), strong (strong importance).
- figure + figcaption: groups media with a caption.
- main: primary content area.
- footer: bottom area for site info and links.

## Identifiers & Grouping
- ID: Unique per page; no spaces; use hyphens for multiple words.
- Class: Reusable grouping identifier; elements may have multiple classes.

## Special Characters & Linking
- HTML entities: Escape reserved characters (e.g., &amp;, &lt;).
- link element: Connects external stylesheets or icons.
- script element: Embeds JavaScript or references external JS via src.

## Boilerplate & Encoding
- DOCTYPE: Declares the HTML standard.
- html: Root element; lang defines page language.
- head: Metadata for browsers/search engines.
- meta: Defines metadata (character encoding, previews, etc.).
- title: Browser tab title.
- UTF‑8: Universal character encoding set via meta charset.

## SEO & Social Sharing
- SEO: Improving visibility on search engines.
- Meta description: Short page summary.
- Open Graph (OG) tags: Control how pages appear on social media (title, type, image, URL).

## Media Elements & Optimization
- Replaced elements: Content from external sources (e.g., iframe, video).
- Images: Optimize size, format, compression. Prefer WEBP or AVIF.
- Licenses: Check copyright/Creative Commons before use.
- SVG: Scales without losing quality.

## Multimedia Integration
- audio/video: Supports multiple formats (audio: mp3/wav/ogg; video: mp4/webm).
- controls: Shows playback UI.
- loop/muted: Boolean attributes for behavior.
- source elements: Provide multiple file types for browser compatibility.
- poster: Image shown before the video plays.

## Target Attribute Types
- _self: current tab (default)
- _blank: new tab
- _parent: parent frame
- _top: top-most browsing context

## Paths
- Path basics: / (separator), . (current), .. (parent).
- Absolute path: Full URL including protocol + domain.
- Relative path: Based on current file location; ideal for internal links.

## Link States
- :link – unvisited link
- :visited – visited link
- :hover – mouse pointer over link
- :focus – keyboard or programmatic focus
- :active – during click/activation

## Semantic HTML
- Semantic HTML gives meaning and structure to content, making pages more accessible, SEO‑friendly, and easier to maintain.
- Correct heading levels (<h1> to <h6>) define the logical outline of the page.
<h1> = main title
<h6> = smallest subheading
This helps both users and search engines understand content structure.
- Old elements that only control appearance and should not be used today.
Examples: <center>, <font>, <big>.

### Main Semantic Elements
- Elements that describe purpose and meaning instead of appearance.
- <header>
Defines the introductory section of a page or content block, typically featuring logos, titles, or navigation elements.
- <main>
Holds the central, unique content of the page (only one <main> per document).
- <section>
Represents a logical grouping of related content within a document.
- <nav>
Contains major navigation links such as menus, tables of contents, or page pathways.
- <figure>
Wraps visual content like images, diagrams, or code snippets, often used with <figcaption>.

### Text-Level Semantic Elements
- <em>
Marks text with emphasis or stress, typically rendered in italics.
- <i>
Indicates text with an alternate tone or meaning (foreign words, technical terms, moods).
Not used to show importance.
Use lang="" when indicating another language.
- <strong>
Indicates strong importance or seriousness; typically displayed in bold.
- <b>
Highlights text that needs attention (keywords, product names) without implying importance.

### Description Lists
- <dl>
A container for a list of terms and their descriptions.
- <dt>
The term is being defined.
- <dd>
The explanation or description of the term.

### Quotation Elements
- <blockquote>
Represents long, block-level quotations.
Supports cite="" for the source URL.
- <cite>
Indicates the title or name of a referenced work.
- <q>
Represents short, inline quotations within text.

### Additional
- <abbr>
Defines an abbreviation or acronym.
Use title="" to show its full form.
- <address>
Displays contact information (physical address, email, phone).
- <time>
Represents dates and/or times.
Use datetime="" for machine-readable ISO 8601 timestamps.
- ISO 8601 datetime Attribute
Standardized date‑time format:
YYYY-MM-DDThh:mm:ss
(“T” separates date and time.)

### Numeric Elements
- <sup>
Displays superscript characters.
Used for exponents, ordinal numbers, etc.
- <sub>
Displays subscript characters.
Used for chemical formulas, variable indices, etc.

### Code & Preformatted Text
- <code>
Marks inline fragments of computer code.
- <pre>
Displays preformatted text, preserving spacing and line breaks.

### Specialized Text Markup
- <u>
Marks text with a non-textual annotation (not for emphasis).
- <ruby>
Used for phonetic guides or annotations in East Asian typography.
- <rt>
Provides the ruby annotation text (pronunciation/translation).
- <rp>
Fallback parentheses for older browsers that don’t support ruby text.
- <s>
Represents text that is no longer correct or relevant.


## The following are the simple web pages that I created using HTML.

### 1. Built a simple web app to show details about the cat (the lovely animal).
### 2. Built a recipe web page made with different ingredients.
What I gained from this:
- Understand the boilerplate of HTML.
- Come to know about the different sections of an HTML document:  html, head, body, etc.
- Grasp the attributes and tags used in the HTML head and body.
- Learn how to convert an image or text into a link.
- and learn how to attach an image or a link to HTML.

### 3. Built a simple bookstore page.
What I understood:
- How to use div elements.
- Why to use div elements (CSS-styling).
- What are id and class attributes?
- How to use id and class in HTML.

### 4. Travel Agency Page
Important concepts I grasped from it (I was stuck on this for an hour):
- How to add a meta description for SEO.
- How to convert a text into an anchor using the <a> tag.
- How to convert an image into an anchor using the <a> tag (I was really stuck here).
- How to use the figure element and figcaption for images.

### 5. Audio and Video Player
### 6. Video Player Web App
Key skills acquired from building this:
- How to add audio and video elements to an HTML file.
- how to add attributes, e.g., controls, loop, src, muted, etc.
- How to add source elements depending upon the browser.
- usage and function of the width and poster attributes.
- learn about different MIME types, video/mp4, video/webm, video/ogg, video/quicktime

### 7. Built an SVG heart shape
Knowledge acquired from the workshop:
- understand three tools for images: size, format, and compression
- Learn about image licenses and how to use them
- how to use SVG attributes to build different shapes

### 8. iframe Elements
Insights from the workshop:
- what replaced elements are and how to use them
- different replaced elements, <img>, <video>, <embed>
- How to use iframe elements
- different attributes of the iframe element

### 9. iframe Video
Understanding developed on:
- How to embed any video in an HTML page using the iframe element
- key attributes of iframe elements, e.g., title, width, height
- How to allow the user to use full-screen mode
