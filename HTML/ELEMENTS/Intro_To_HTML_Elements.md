<!DOCTYPE html>
<body>
    <header>
        <h1>INTRO TO HTML ELEMENTS</h1>
    </header>
    <section>
        <h2>WHAT ARE HTML ELEMENTS?</h2>
        <p>HTML (Hypertext Markup Language) is the standard language used to create web pages. In HTML, <strong>elements</strong> are the building blocks used to structure the content of a web page. Each element is defined using HTML tags and can contain text, attributes, and other nested elements.</p>
    </section>
    <section>
        <h2>Structure of an HTML Element</h2>
        <p>An HTML element generally consists of three parts:</p>
        <ul>
            <li><strong>Start tag</strong>: Marks the beginning of an element (e.g., <code>&lt;p&gt;</code> for a paragraph).</li>
            <li><strong>Content</strong>: The actual content inside the element (e.g., text, images, or links).</li>
            <li><strong>End tag</strong>: Marks the end of the element (e.g., <code>&lt;/p&gt;</code> for a paragraph).</li>
        </ul>
        <p>Example of a paragraph element:</p>
        <pre><code>&lt;p&gt;This is a paragraph&lt;/p&gt;</code></pre>
    </section>
    <section>
        <h2>Common HTML Elements</h2>
        <p>Below are a few common HTML elements:</p>
        <ul>
            <li><strong>&lt;h1&gt; - &lt;h6&gt;</strong>: Heading tags used to define headings. <em>&lt;h1&gt;</em> is the largest, and <em>&lt;h6&gt;</em> is the smallest.</li>
            <li><strong>&lt;p&gt;</strong>: The paragraph tag, used to define blocks of text.</li>
            <li><strong>&lt;a&gt;</strong>: The anchor tag, used to create links.</li>
            <li><strong>&lt;img&gt;</strong>: The image tag, used to embed images on a web page.</li>
            <li><strong>&lt;div&gt;</strong>: A block-level container element, commonly used for structuring content.</li>
        </ul>
    </section>
    <section>
        <h2>Attributes in HTML Elements</h2>
        <p>HTML elements can also contain attributes that provide additional information about the element. Attributes are always written in the start tag and consist of a name and value.</p>
        <p>Example of an element with an attribute:</p>
        <pre><code>&lt;a href="https://www.example.com"&gt;Visit Example&lt;/a&gt;</code></pre>
        <p>In this example, <code>href</code> is the attribute, and <code>"https://www.example.com"</code> is its value.</p>
    </section>
    <section>
        <h2>Self-Closing Elements</h2>
        <p>Some HTML elements do not have an end tag. These are called self-closing elements. For example:</p>
        <pre><code>&lt;br /&gt;  <!-- Line break --></code></pre>
        <p>In this case, the <code>&lt;br /&gt;</code> tag inserts a line break and does not require a closing tag.</p>
    </section>
    <footer>
        <p>For more information, check out the official <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">MDN Web Docs on HTML</a>.</p>
    </footer>

</body>
</html>
