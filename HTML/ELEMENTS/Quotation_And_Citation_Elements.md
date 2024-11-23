<!DOCTYPE html>
<h1>HTML QUOTATION AND CITATION ELEMENTS</h1>
<p>Elements used for quotations and citations: <code>&lt;blockquote&gt;</code>, <code>&lt;q&gt;</code>, <code>&lt;abbr&gt;</code>, <code>&lt;address&gt;</code>, <code>&lt;cite&gt;</code>, and <code>&lt;bdo&gt;</code>.</p>
<br>

<h2><b>QUOTED SECTIONS: &lt;blockquote&gt;</b></h2>
<p>Defines a section that is quoted from another source. Browsers usually render this element as an indented block.</p>
<p class="input-label"><b>INPUT:</b></p>
<pre>
  &lt;p&gt;Here is a quote from WWF's website:&lt;/p&gt;
  &lt;blockquote cite="http://www.worldwildlife.org/who/index.html"&gt;
  For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries.At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
  &lt;/blockquote&gt;
  </pre>
  <p class="output-label"><b>OUTPUT:</b></p>
  <blockquote>
    For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
    </blockquote>
    <br>

   
   <h2><b>SHORT QUOTATIONS: </b> &lt;q&gt;</h2>
    <p>Defines a short inline quotation. Browsers usually add quotation marks around the text.</p>
    <p class="input-label"><b>INPUT:</b></p>
    <pre>
      &lt;p&gt;WWF's goal is to: &lt;q&gt;Build a future where people live in harmony with nature.&lt;/q&gt;&lt;/p&gt;
      </pre>
      <p class="output-label"><b>OUTPUT:</b></p>
      <blockquote>
      <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
      </blockquote>
      <br>
      
  <h2><b>ABBREVIATIONS: </b> &lt;abbr&gt;</h2>
      <p>Defines an abbreviation or acronym, providing additional information through the <code>title</code> attribute. Useful for accessibility and SEO.</p>
      <p class="input-label"><b>INPUT:</b></p>
      <pre>
        &lt;p&gt;The &lt;abbr title="World Health Organization"&gt;WHO&lt;/abbr&gt; was founded in 1948.&lt;/p&gt;
        </pre>
        <p class="output-label"><b>OUTPUT:</b></p>
        <blockquote>
        <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
        </blockquote>
        <br>
    
  <h2>CONTACT INFORMATION: &lt;address&gt;</h2>
        <p>Defines contact information for the author or owner of a document. Typically rendered in italics, with line breaks before and after.</p>
        <p class="input-label"><b>INPUT:</b></p>
        <pre>
          &lt;address&gt;
          Written by John Doe.&lt;br&gt;
          Visit us at:&lt;br&gt;
        Example.com&lt;br&gt;
          Box 564, Disneyland&lt;br&gt;
          USA
          &lt;/address&gt;
    </pre>
    <p class="output-label"><b>OUTPUT:</b></p>
    <blockquote>
    <address>
        Written by John Doe.<br>
        Visit us at:<br>
        Example.com<br>
        Box 564, Disneyland<br>
        USA
      </address>
      </blockquote>
      <br>

  <h2>TITLE OF A WORK: &lt;cite&gt; </h2>
      <p>Defines the title of a creative work, such as a book, song, or painting. Usually rendered in italics.</p>
      <p class="input-label"><b>INPUT:</b></p>
      <pre>
        &lt;p&gt;&lt;cite&gt;The Scream&lt;/cite&gt; by Edvard Munch. Painted in 1893.&lt;/p&gt;
        </pre>
        <p class="output-label"><b>OUTPUT:</b></p>
        <blockquote>
        <p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
          </blockquote>
        <br>
        
  <h2>BI-DIRECTIONAL OVERRIDE: &lt;bdo&gt;</h2>
        <p>Overrides the text direction for bidirectional languages like Arabic or Hebrew.</p>
        <p class="input-label"><b>INPUT:</b></p>
        <pre>
          &lt;bdo dir="rtl"&gt;This text will be written from right to left&lt;/bdo&gt;
          </pre>
          <p class="output-label"><b>OUTPUT:</b></p>
          <blockquote>
          <bdo dir="rtl">This text will be written from right to left</bdo>
            </blockquote>
          </body>
          </html>
