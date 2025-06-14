# Phases of Web Dev:

    Learning to code is challenging due to unrealistic expectations and shifts in Resource Density and Scope of Knowledge.
    Key phases:
        Phase I: Hand-Holding Honeymoon: Joyful, high resources, narrow scope. Tip: Pick one resource.
        Phase II: Cliff of Confusion: Hand-holding ends, debugging difficult. Tip: Build constantly, work with others.
        Phase III: Desert of Despair: Lost, low resources, scope balloons. Tip: Strong goal, find a clear path.
        Phase IV: Upswing of Awesome: Apps work, but code brittle; self-doubt. Tip: Seek best practices, get feedback.
    Understanding phases aids navigating this journey successfully.

# History of Web Development:

    Web design involves skills for producing and maintaining websites, encompassing graphic design, UI/UX, and SEO. Its history began with text-only HTML (1991-1993), evolving with graphical browsers (Mosaic, 1993). The W3C established standards, influencing the "browser wars" (1996-1999) that introduced CSS, JavaScript, and Dynamic HTML. Since 2001, HTML5, CSS3, and mobile-first design (around 2012) became crucial.
        Key skills and techniques include:
        UX Design and ensuring web accessibility.
        Responsive web design to adapt to varying screen sizes.
    Maintaining quality of code through standards and validation.
    Websites are either static (unique files) or dynamic (server-generated, often database-driven). Primary occupations are web designer (visuals) and web developer. AI models like Chat GPT are increasingly used for faster creation.

# Web Development Summary:

    Front-end developers build the user interface using HTML, CSS, JS, and frameworks like ReactJS and Bootstrap. They ensure visual appeal and usability. Back-end developers manage the server, database, and application logic using Node.js, PHP, Python, and databases like MySQL or MongoDB. They handle data security, scalability, and APIs. Full stack developers work across both ends, mastering front-end and back-end skills, plus CMS tools (WordPress). Full stack offers flexibility but requires broad expertise.
    Salaries (US avg.): Front-end: ~$96K; Back-end: ~$164K; Full stack: ~$137K.
    Job outlook: ~16-17% growth (2022-2032).
    Soft skills: Problem-solving, adaptability, communication are key.
    Continuous learning is vital in this dynamic field.

Git basic commands CheatSheat: https://www.theodinproject.com/lessons/foundations-git-basics

# HTML vs CSS vs JS:

    HTML, CSS, and JavaScript are the three foundational coding languages for web development. HTML (Hypertext Markup Language) establishes the structure and content of a webpage, acting as its building blocks. CSS (Cascading Style Sheets) focuses on styling, determining the visual look, feel, layout, and responsive features of the HTML document. JavaScript is a robust language that adds interactivity to a website by enabling changes to HTML and CSS elements after the site loads, powering features like animations and interactive menus. Knowing these languages provides greater control over your website's appearance, functionality, and helps in diagnosing issues. Free resources like Codecademy are available for learning them.

# What is HTML

    HTML defines a webpage's structure and content, requiring explicit coding rather than menus found in word processors. You tell the browser what everything is using "elements," which are comprised of opening and closing "tags" (e.g., `<p>` and `</p>`). Content is placed between these tags, and line breaks or extra spaces in code are meaningless without explicit tags.

    HTML employs predefined, "semantic" elements, meaning their names convey their purpose (e.g., `<h1>` for heading, `<footer>` for footer). Using correct semantic HTML is crucial for web accessibility, enabling users with screen readers, keyboards, or other navigation methods to interact effectively with the site. It's best to learn essential, frequently used elements rather than attempting to memorize all existing tags.

# Links and Images Tutorial

This tutorial on **"Links and Images"** highlights several important topics for web development:

    1. **Attributes**  
    These add meaning to HTML elements, living inside the opening tag (e.g., `attribute='value'`).

    2. **Website Structure & File Organization**  
    Websites are collections of HTML files and folders. Organizing them into a main folder with subfolders (like `misc`, `images`) is crucial for web development.

    3. **Links (`<a>` element)**
    - Uses the `href` attribute to specify the destination.
    - **Absolute Links:** For different websites (e.g., `https://developer.mozilla.org/`).
    - **Relative Links:** For files within the same website, relative to the current file (e.g., `misc/extras.html` or `../links.html` to go up a directory).
    - **Root-Relative Links:** Relative to the website's root, starting with `/` (useful for larger sites but not testable locally).
    - The `target='_blank'` attribute opens links in a new tab/window.

    4. **Images (`<img>` element)**
    - An empty element; its `src` attribute points to the image file.
    - **Image Formats:**
        - **JPG:** Best for photos, no transparency.
        - **GIF:** Good for simple animations, limited color, binary transparency.
        - **PNG:** Excellent for icons, diagrams, logos, good opacity, no color limits (can be larger than JPG for photos).
        - **SVG:** Vector-based, scales without quality loss (ideal for responsive design, use whenever possible).
    - The `alt` attribute provides a text alternative for accessibility and search engines.
    - `width` and `height` attributes can set dimensions, but CSS is generally preferred for this.

    5. **Naming Conventions**  
    Use hyphens instead of spaces in file/folder names and consistently use lowercase to avoid URL issues (e.g., `%20` for spaces). This applies to all site files (HTML, CSS, JS, images).

    6. **Essential HTML Attributes**
    - `lang` attribute on `<html>` to define document language (e.g., `<html lang='en'>`).
    - `<meta charset='UTF-8' />` in the `<head>` to ensure correct display of international characters; UTF-8 is a universal standard.

    7. **HTML Entities**  
    Special characters in HTML documents, especially for "reserved characters" like `<`, `>`, and `&` (e.g., `&lt;`, `&gt;`, `&amp;`) or for typography like curly quotes.

    8. **Basic HTML Template**  
    Every page should start with a standard boilerplate defining doctype, language, character set, and title.
