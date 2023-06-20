# Structure Web Pages with HTML

## Welcome to the HTML FAQ

Please see below for answers to your most pressing questions!

### Q: What is HTML and why do we use it?

A: HTML or HyperText Markup Language is a markup language (it's in the name!). As Wikipedia states, a markup language is *a text-encoding system consisting of a set of symbols inserted in a text document to control its structure, formatting, or the relationship between its parts.*

- This code is used to structure a website. For a basic layout (without style or sizing) you can use this to make the beginnings of a website.

- Think of it as the bare bones or basic structure of house. You have a foundation, walls, and a roof. You will still need to paint the house, furnish it, and include utilities. But at least you got the house started! That's what HTML accomplishes.

- Adding in CSS and Javascript will refine, furnish, and bring functionality to your home, but you need to start with a basic structure to then build off of.

### Q: What are the 3 main parts of an HTML element?

A: The entirety of parts is called an element. The 3 main parts of an element is an opening tag, the content within, and a closing tag.

- An example of this is `<h1>Content</h1>`.
- Note: there are self-closing tags which will not include a closing tag, only an opening tag and content.

### Q: What is it called when you give an element extra information?

A: **Attribute.**

- This provides extra information that will not be seen on the website. It allows us to give an identifier that can be used to adjust or provide information to an element.

- Attributes that set a value will include:
  - (1) a space between the element/previous attribute.
  - (2) The attribute will be followed by an equal sign.
  - (3) The value will be wrapped in quotation marks.
    - Quotations are not always required. However, it is best practices to include them.

### Q: What is a semantic element?

A: Semantics = Meaning. Think about the purpose of this code, and what role it plays. Instead of thinking about the appearance, when talking about semantics, we are thinking about why it is there and what its effect is.

### **Additional Notes**

#### [*Wireframing and Design*](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)

6 Steps to make a wireframe

1. Do your research.
2. Prepare your research for quick reference.
3. Make sure you have your user flow mapped out.
4. Draft, don’t draw. Sketch, don’t illustrate.
5. Add some detail and get testing.
6. Start turning your wireframes into prototypes.

Tools

- Pen and Paper
- [*in*vision](https://www.invisionapp.com/)
- [balsamiq](https://balsamiq.com/)
- [UXPin](https://www.uxpin.com/) (free trial)
- [wireframe](https://wireframe.cc/) (free trial)

Inspiration

- [9 Inspiring Website and App Wireframe Examples](https://careerfoundry.com/en/blog/ux-design/website-app-wireframe-examples/)

Tutorial

- [How To Create Your First Wireframe (A UX Tutorial)](https://www.youtube.com/watch?v=qpH7-KFWZRI)

Miscellaneous Resourses

- [How to Conduct User Experience Research Like a Professional](https://careerfoundry.com/en/blog/ux-design/how-to-conduct-user-experience-research-like-a-professional/)
- [An Excellent Beginner’s Guide to Information Architecture](https://careerfoundry.com/en/blog/ux-design/a-beginners-guide-to-information-architecture/)

How to make your wireframe good: Three key principles

1. **Clarity**
    - What is the site page?
    - What can user can do there?
    - Does this satisfies the users needs?

2. **Confidence**
    - Is there ease of navigation through your site?
    - Are there clear calls-to-action?
    - Are you increasing user confidence?

3. **Simplicity**
    - Is there too much information, copy, or links?
    - Is this detrimental or productive in achieving the user's goals?
    - Is it constructed in an intuitive and natural way?

#### [*Mozilla HTML Basics*](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

Notes taken directly from the site:

`<html></html>` — the `<html>` element. Sets the language. Also known as the root element.

`<head></head>` — the `<head>` element. A container that sets all the info not shown on the page: Keywords, Page descriptions, CSS style, etc.

`<meta charset="utf-8">` — includes most characters from the vast majority of written languages.

`<meta name="viewport" content="width=device-width">` — the viewpoint element renders at the width of the viewpoint so on mobile devices, the site won't get shrunk down.

`<title></title>` — the `<title>` element. This is the title that appears in the browser tab the page is loaded in.

`<body></body>` — the `<body>` element. This contains all the content that you want to show to web users

#### [*Semantics*](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

Notes taken directly from the site:

Use proper HTML Semantics to reap the most benefits, which incllude:

- Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)

- Screen readers can use it as a signpost to help visually impaired users navigate a page

- Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes

- Suggests to the developer the type of data that will be populated

- Semantic naming mirrors proper custom element/component naming
