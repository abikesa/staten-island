# Mode 🏝️

<style>
/* ╭━━━☆━━━╮  FLOAT FRAMES (Figure / Seealso) */
.float-frame {
    border: 1px solid #ccc;
    background-color: #f9f9f9;
    position: relative;
    padding: 10px 14px;
    margin: 15px;
    font-family: sans-serif;
    font-size: 14px;
    line-height: 1.5;
}

/* Floated figure (image/code block) */
.float-frame.figure-style {
    float: right;
    width: 35%;
    text-align: center;
}

/* Floated seealso (text-only callout) */
.float-frame.seealso-style {
    float: right;
    width: 45%;
    max-width: 400px;
    min-width: 200px;
    text-align: left;
    white-space: normal;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

/* Responsive override */
@media (max-width: 768px) {
    .float-frame {
        float: none !important;
        display: block;
        width: 95vw !important;
        max-width: 95vw !important;
        margin: 10px auto;
    }
}

/* ╭━━━☆━━━╮  BLOCKQUOTES */
blockquote {
    border-left: 2px solid #999;
    padding-left: 1em;
    margin-left: 0;
    margin-right: 0;
    color: #444;
    font-style: italic;
    background: none;
}

blockquote a {
    text-decoration: none;
    font-style: normal;
    color: #333;
    border-bottom: 1px dotted #aaa;
}

blockquote a:hover {
    color: #000;
    border-bottom: 1px solid #555;
}

/* ╭━━━☆━━━╮  COLLAPSIBLE <details> BLOCKS */
.custom-details summary {
    list-style: none;
    cursor: pointer;
    font-weight: normal;
    display: inline-block;
    padding: 5px 15px;
    border: 2px dotted black;
    border-radius: 20px;
    text-align: center;
    transition: color 0.3s ease-in-out;
}

.custom-details summary:hover {
    color: lightgray;
}

.custom-details summary::-webkit-details-marker {
    display: none;
}

/* ╭━━━☆━━━╮  NESTED QUOTES INSIDE DETAILS */
.quote-content {
    border-left: 4px solid #ccc;
    padding-left: 10px;
    color: #555;
    font-style: italic;
    margin-top: 15px;
}

.quote-content details {
    margin-top: 10px;
}

.quote-content summary {
    font-weight: bold;
    cursor: pointer;
}

/* so-so- def Container that floats right with image and caption */
.float-right {
    float: right;
    width: 35%;
    height: auto;
    margin-left: 15px;
    border: 1px solid #ccc;
    padding: 5px;
    text-align: center;
    font-size: 12px;
    background-color: #f9f9f9;
    position: relative;
}

/* Image itself */
.float-right img {
    width: 100%;
    height: auto;
    display: block;
}

/* Magnify icon overlay */
.image-bubble.layered-icon {
    position: absolute;
    bottom: 8px;
    right: 8px;
    width: 12px;
    height: 10px;
    background: none;
    padding: 0;
    cursor: pointer;
    z-index: 5;
}

/* Larger screen rectangle */
.large-icon {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #ddd;
    border: 1px solid #888;
    border-radius: 2px;
}

/* Smaller screen at 7 o'clock */
.small-icon {
    position: absolute;
    width: 50%;
    height: 50%;
    background-color: #aaa;
    border: 1px solid #666;
    border-radius: 2px;
    bottom: -1px;
    left: -1px;
}

.image-bubble.layered-icon:hover .large-icon {
    background-color: #007BFF;
    border-color: #0056b3;
}

.image-bubble.layered-icon:hover .small-icon {
    background-color: white;
    border-color: #007BFF;
}

/* Scoped variant for seealso boxes */
.float-frame.seealso-style {
    float: right; 
    display: inline-block;
    width: 190px;
    max-width: 190px;
    min-width: 100px;
    height: auto;
    border: 1px solid #ccc;
    padding: 6px 10px;
    font-size: 13px;
    background-color: #f9f9f9;
    position: relative;
    text-align: center;
    margin: 15px;
    white-space: nowrap;
}

/* Responsive fallback */
@media (max-width: 768px) {
    .float-frame.seealso-style {
        float: none !important;
        display: block;
        width: 95vw !important;
        max-width: 95vw !important;
        margin: 10px auto;
        white-space: normal;
    }
}
</style>

<details class="custom-details">
  <summary>+ Expand</summary>

  <iframe src="pdfs/ecosystem-nature.pdf" width="100%" height="1000px" style="border:none"></iframe>

  <blockquote class="quote-content">
    <details>
      <summary>Analysis</summary>
      <p>In designing the scenery and costumes...</p>
    </details>
    <p>-- <a href="https://www.gutenberg.org/cache/epub/887/pg887-images.html#page221">The Truth of Masks 🎭</a></p>
  </blockquote>
</details>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const details = document.querySelector(".custom-details");
    const summary = details.querySelector("summary");

    details.addEventListener("toggle", function() {
      summary.textContent = details.open ? "- Collapse" : "+ Expand";
    });
  });
</script>
<p></p>
<p></p> # flick 20250422034842-wLXd
# flick 20250422040656-jJeN
