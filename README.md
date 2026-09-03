# HTML Website Development Assignment

**Student Name:** Prince Chapuswike  
**Student ID (SIN#):** 2601317736  
**GitHub Repository:** [https://GitHub.com/princechapuswike/my_personal_website](https://GitHub.com/princechapuswike/my_personal_website)

---

## Question 1: Website Creation

**What type of website will you create and what content will it contain?**  
I created a personal portfolio/profile website. The content includes an "About Me" section describing my background, a "Personal Details" section containing a table with my contact information (email, phone, student ID, GitHub link), and a "Contact Me" section with a functional form that allows users to send me a message directly.

## Question 2: HTML Elements

**1. Which 5 elements did you find most challenging to implement and why?**  
1. `<table>`: Ensuring that `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` were correctly nested and structurally sound required careful attention.
2. `<form>`: Understanding how to properly configure the `action` and `method` attributes for email submission without a backend was a learning curve.
3. `<fieldset>` and `<legend>`: Grouping form elements structurally while maintaining visual clarity in plain HTML was initially confusing.
4. `<figure>` and `<figcaption>`: I had to make sure these were used semantically to wrap the image and its description, rather than just using a generic `div` or `p` tag.
5. `<blockquote>`: Deciding where to semantically place a quote without disrupting the flow of the document required some thought.

**2. How did you use semantic elements to structure your content?**  
I used `<header>` to contain the site's main title and navigation menu (`<nav>`). The core content is wrapped in `<main>`, which is further divided into thematic `<section>` blocks (About, Details, Contact). Within the About section, I used `<article>` to wrap self-contained content introducing myself. Finally, the `<footer>` is used at the bottom of the page to hold copyright and disclaimer text.

**3. Which element was most useful for organizing your layout and why?**  
The `<section>` element was the most useful. It allowed me to cleanly divide the page into distinct, logical parts (About, Details, Contact) that could each be navigated to using anchor links from the main navigation menu. It provided clear structure for both the code and the visual flow of the plain HTML.

## Question 3: HTML Attributes

**1. Which 3 attributes were essential for making your website functional?**  
1. `href` (in `<a>` tags): Essential for navigation, allowing links to different sections of the page, external websites, and `mailto:` / `tel:` links.
2. `action` (in `<form>` tag): Crucial for specifying where the form data should be sent (in this case, my email address).
3. `id` (in `<section>` tags): Necessary to create anchor points so the navigation links could jump to specific parts of the page.

**2. How did you use the class and id attributes differently?**  
I used the `id` attribute for unique identifiers on the page, specifically for linking navigation anchors to specific `<section>` tags and connecting `<label>` elements to `<input>` fields (using the `for` attribute). I used the `class` attribute to group similar elements (like `content-section`) so that if I were to add CSS later, I could style all sections consistently with a single rule.

**3. Which attribute helped improve user experience the most and why?**  
The `placeholder` attribute in the form inputs helped improve user experience the most. It provides an inline example of the expected input format before the user starts typing, reducing confusion and guiding them on how to fill out the form correctly.

## Question 4: Development Process

**1. How did you plan your website structure before coding?**  
I started by writing down the sections I wanted to include (Header/Nav, About, Details Table, Contact Form, Footer). I then mapped these sections to their appropriate semantic HTML5 tags to ensure the document outline was logical before writing any code.

**2. What was your approach to testing and debugging your HTML?**  
I used a web browser to continually preview the `index.html` file after making significant changes to ensure the layout rendered as expected. I also checked for unclosed tags or broken links by manually inspecting the code and clicking all navigation items.

**3. What challenges did you face and how did you overcome them?**  
A major challenge was making the website look organized and readable without using CSS. I overcame this by relying heavily on semantic HTML elements like `<hr>`, lists, headings of different levels (`<h1>`, `<h2>`, `<h3>`), and table attributes (`border`, `cellpadding`) to create natural visual hierarchy and separation.

## Question 5: Git & GitHub Implementation

**1. What Git commands did you use during development?**  
I used commands such as `git init` to start the repository, `git add .` to stage all new files, `git commit -m "..."` to save the changes, and `git push -u origin main` to upload the code to GitHub.

**2. How many commits did you make and what was your commit message strategy?**  
I made several commits to keep track of major milestones. My strategy was to use clear, descriptive messages like "Initial commit with semantic HTML structure", "Added personal details table", "Implemented contact form", and "Added README documentation".

**3. Why is version control important for web development projects?**  
Version control is crucial because it keeps a history of all changes made to the project. If a mistake is made, it's easy to revert to a previous working state. It also serves as a backup mechanism and allows for easy collaboration if I were to work with others.

## Question 6: Code Quality & Best Practices

**1. How did you ensure your HTML was valid and error-free?**  
I ensured validity by strictly following HTML5 syntax rules: including the correct `<!DOCTYPE html>`, properly nesting all elements, ensuring every opening tag had a corresponding closing tag, and providing necessary attributes like `alt` for images.

**2. What best practices did you follow for writing clean, readable code?**  
I used consistent indentation (using spaces/tabs) to visually represent the nesting of elements. I grouped related blocks of code together and separated major sections with blank lines to improve readability. I also used lowercase for all tag names and attributes.

**3. How would you improve your website if you had more time?**  
If I had more time and could use other technologies, I would add an external CSS file to greatly improve the aesthetics, colors, typography, and responsiveness of the layout. I would also use JavaScript to add client-side form validation and interactive elements.
