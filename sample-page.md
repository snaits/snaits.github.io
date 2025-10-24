---
layout: default
title: Sample Page
---

<section class="intro">
    <p>This is a sample page created using Jekyll and Markdown.</p>
</section>

<section class="content">
    ## Main Content

    Your main content goes here. You can write in **Markdown** and it will be automatically converted to HTML.

    ### Subsection

    - You can use lists
    - With multiple items
    - Very easily in Markdown

    You can also include [links](https://github.com/snaits) and other Markdown features.

    ### Code Examples

    ```javascript
    // You can even include code blocks
    function hello() {
        console.log("Hello, world!");
    }
    ```
</section>

<section class="additional">
    ## Additional Information

    Any additional content can be written in Markdown format:

    1. Numbered lists work too
    2. They're automatically formatted
    3. No need to write HTML

    > You can also use blockquotes for emphasis
</section>

<section class="links">
    ## Related Links
    
    <ul>
        <li><a href="{{ '/' | relative_url }}">Back to Home</a></li>
        <li><a href="https://github.com/snaits" target="_blank">GitHub Profile</a></li>
    </ul>
</section>