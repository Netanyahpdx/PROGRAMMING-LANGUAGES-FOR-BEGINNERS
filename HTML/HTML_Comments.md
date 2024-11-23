<!DOCTYPE html>
<h1>HTML COMMENTS</h1>
<p>HTML comments are not displayed in the browser but are useful for documenting your source code.</p>
<br>
<h2><b> HTML COMMENT SYNTAX </b></h2>
<p>Comments in HTML use the following syntax:</p>
<p class="input-label"><b>INPUT:</b></p>
<pre>
  &lt;!-- Write your comments here --&gt;
  </pre>
  <p><i>Comments are ignored by the browser and do not appear on the page.</i></p>
<br>

  <h2><b> ADDING COMMENTS </b></h2>
  <p>Comments can be used to add notes or reminders in your HTML code.</p>
  <p class="input-label"><b>INPUT:</b></p>
  <pre>
    &lt;!-- This is a comment --&gt;
    &lt;p&gt;This is a paragraph.&lt;/p&gt;

  &lt;!-- Remember to add more information here --&gt;
  </pre>
  <p class="output-label"><b>OUTPUT:</b></p>
  <blockquote>
  <p>This is a paragraph.</p>
    </blockquote>
  <br>
  
  <h2> <b> HIDING CONTENT</b></h2>
  <p>Comments can be used to hide parts of the content, such as temporarily removing sections:</p>
  <p class="input-label"><b>INPUT:</b></p>
  <pre>
    &lt;p&gt;This is a paragraph.&lt;/p&gt;

  &lt;!-- &lt;p&gt;This is another paragraph&lt;/p&gt; --&gt;

  &lt;p&gt;This is a paragraph too.&lt;/p&gt;
  </pre> 
  <p class="output-label"><b>OUTPUT:</b></p>
  <blockquote>
  <p>This is a paragraph.</p>
  <p>This is a paragraph too.</p>
  </blockquote>
<br>

  <h2><b> HIDING MULTIPLE LINES</b></h2>
  <p>Comments can hide multiple lines of code. Everything between <code>&lt;!--</code> and <code>--&gt;</code> will be ignored by the browser.</p>
  <p class="input-label"><b>INPUT:</b></p>
  <pre>
    &lt;p&gt;This is a paragraph.&lt;/p&gt;
    &lt;!--
    &lt;p&gt;Look at this cool image:&lt;/p&gt;
    &lt;img border="0" src="pic_trulli.jpg" alt="Trulli"&gt;
    --&gt;
    &lt;p&gt;This is a paragraph too.&lt;/p&gt;
  </pre>
  <p class="output-label"><b>OUTPUT:</b></p>
  <blockquote>
  <p>This is a paragraph.</p>
  <p>This is a paragraph too.</p>
  </blockquote>
  <br>
  
  <h2><b>HIDING INLINE CONTENT</b></h2>
  <p>Comments can also be used to hide parts of a single line within an HTML element:</p>
  <p class="input-label"><b>INPUT:</b></p>
  <pre>
    &lt;p&gt;This &lt;!-- great text --&gt; is a paragraph.&lt;/p&gt;
  </pre>
  <p class="output-label"><b>OUTPUT:</b></p>
  <blockquote>
  <p>This is a paragraph.</p>
  </blockquote>
  </body>
  </html>
