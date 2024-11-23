<!DOCTYPE html>
<h1>HTML ELEMENTS BREAKDOWN</h1>
    <p>This chart categorizes commonly used HTML elements into different sections based on their purpose. Each element includes an explanation, an example of input (HTML code), and the output (how it would appear on a webpage).</p>
    <h2>1. DOCUMENT STRUCTURE ELEMENTS</h2>
    <p>These elements form the foundation of an HTML document.</p>
    <table border="1">
        <thead>
            <tr>
                <th>Element</th>
                <th>Explanation</th>
                <th>Example (Input)</th>
                <th>Output</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>&lt;!DOCTYPE html&gt;</td>
                <td>Declares the document type and version of HTML.</td>
                <td>&lt;!DOCTYPE html&gt;</td>
                <td>No visible output; informs browser of HTML5</td>
            </tr>
            <tr>
                <td>&lt;html&gt;</td>
                <td>The root element that contains all other elements.</td>
                <td>&lt;html lang="en"&gt; ... &lt;/html&gt;</td>
                <td>Wraps all content on the page.</td>
            </tr>
            <tr>
                <td>&lt;head&gt;</td>
                <td>Contains meta-information, links, and title.</td>
                <td>&lt;head&gt; &lt;meta charset="UTF-8"&gt; &lt;title&gt;My Page&lt;/title&gt; &lt;/head&gt;</td>
                <td>No visible output; sets up page metadata.</td>
            </tr>
            <tr>
                <td>&lt;body&gt;</td>
                <td>Contains the content displayed on the webpage.</td>
                <td>&lt;body&gt;&lt;h1&gt;Welcome&lt;/h1&gt;&lt;p&gt;This is a paragraph.&lt;/p&gt;&lt;/body&gt;</td>
                <td>Displays content on the page.</td>
            </tr>
        </tbody>
    </table>
    <h2>2. TEXT ELEMENTS</h2>
    <p>Used for adding text and formatting content.</p>
    <table border="1">
        <thead>
            <tr>
                <th>Element</th>
                <th>Explanation</th>
                <th>Example (Input)</th>
                <th>Output</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>&lt;h1&gt; to &lt;h6&gt;</td>
                <td>Defines HTML headings from largest to smallest.</td>
                <td>&lt;h1&gt;Big Heading&lt;/h1&gt;</td>
                <td><strong>Big Heading</strong> (Largest text)</td>
            </tr>
            <tr>
                <td>&lt;p&gt;</td>
                <td>Defines a paragraph of text.</td>
                <td>&lt;p&gt;This is a paragraph.&lt;/p&gt;</td>
                <td>This is a paragraph.</td>
            </tr>
            <tr>
                <td>&lt;strong&gt;</td>
                <td>Indicates strong emphasis (bold).</td>
                <td>&lt;strong&gt;Important text&lt;/strong&gt;</td>
                <td><strong>Important text</strong></td>
            </tr>
            <tr>
                <td>&lt;em&gt;</td>
                <td>Indicates emphasized text (italic).</td>
                <td>&lt;em&gt;Italicized text&lt;/em&gt;</td>
                <td><em>Italicized text</em></td>
            </tr>
        </tbody>
    </table>
    <h2>3. LINK & MEDIA ELEMENTS</h2>
    <p>Used for linking to other pages and embedding media.</p>
    <table border="1">
        <thead>
            <tr>
                <th>Element</th>
                <th>Explanation</th>
                <th>Example (Input)</th>
                <th>Output</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>&lt;a&gt;</td>
                <td>Defines a hyperlink to another webpage.</td>
                <td>&lt;a href="https://www.example.com"&gt;Visit Example&lt;/a&gt;</td>
                <td><a href="https://www.example.com">Visit Example</a> (clickable link)</td>
            </tr>
            <tr>
                <td>&lt;img&gt;</td>
                <td>Embeds an image on the webpage.</td>
                <td>&lt;img src="image.jpg" alt="A beautiful image"&gt;</td>
                <td>Displays image (if available)</td>
            </tr>
            <tr>
                <td>&lt;audio&gt;</td>
                <td>Embeds audio content on the webpage.</td>
                <td>&lt;audio controls&gt;&lt;source src="audio.mp3" type="audio/mp3"&gt;&lt;/audio&gt;</td>
                <td>Audio player controls with sound</td>
            </tr>
            <tr>
                <td>&lt;video&gt;</td>
                <td>Embeds video content on the webpage.</td>
                <td>&lt;video width="320" height="240" controls&gt;&lt;source src="movie.mp4" type="video/mp4"&gt;&lt;/video&gt;</td>
                <td>Video player with controls</td>
            </tr>
        </tbody>
    </table>
    <h2>4. FORM ELEMENTS</h2>
    <p>Used to create interactive forms for user input.</p>
    <table border="1">
        <thead>
            <tr>
                <th>Element</th>
                <th>Explanation</th>
                <th>Example (Input)</th>
                <th>Output</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>&lt;form&gt;</td>
                <td>Defines an HTML form for user input.</td>
                <td>&lt;form action="/submit" method="post"&gt; ... &lt;/form&gt;</td>
                <td>Creates form to collect data</td>
            </tr>
            <tr>
                <td>&lt;input&gt;</td>
                <td>Defines an input field in a form.</td>
                <td>&lt;input type="text" name="username"&gt;</td>
                <td>Text field for input</td>
            </tr>
            <tr>
                <td>&lt;button&gt;</td>
                <td>Defines a clickable button.</td>
                <td>&lt;button type="submit"&gt;Submit&lt;/button&gt;</td>
                <td>Button labeled "Submit"</td>
            </tr>
            <tr>
                <td>&lt;textarea&gt;</td>
                <td>Defines a multi-line text input field.</td>
                <td>&lt;textarea rows="4" cols="50"&gt;Enter text here&lt;/textarea&gt;</td>
                <td>Multi-line text area for input</td>
            </tr>
        </tbody>
    </table>
    <h2>5. LAYOUT ELEMENTS</h2>
    <p>Used for structuring the layout of content on a page.</p>
    <table border="1">
        <thead>
            <tr>
                <th>Element</th>
                <th>Explanation</th>
                <th>Example (Input)</th>
                <th>Output</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>&lt;div&gt;</td>
                <td>Defines a division or section in an HTML document.</td>
                <td>&lt;div class="container"&gt; &lt;p&gt;Content&lt;/p&gt; &lt;/div&gt;</td>
                <td>Used to group content together.</td>
            </tr>
            <tr>
                <td>&lt;span&gt;</td>
                <td>Defines a small section within text.</td>
                <td>&lt;span class="highlight"&gt;Highlighted text&lt;/span&gt;</td>
                <td>Inline text element with no line break.</td>
            </tr>
            <tr>
                <td>&lt;header&gt;</td>
                <td>Represents the header section of a page.</td>
                <td>&lt;header&gt;&lt;h1&gt;Page Title&lt;/h1&gt;&lt;/header&gt;</td>
                <td>Displays a header section</td>
            </tr>
            <tr>
                <td>&lt;footer&gt;</td>
                <td>Represents the footer section of a page.</td>
                <td>&lt;footer&gt;Footer content&lt;/footer&gt;</td>
                <td>Displays a footer section</td>
            </tr>
        </tbody>
    </table>
    <footer>
        <p>© 2024 HTML Elements Breakdown</p>
    </footer>
</body>
</html>
