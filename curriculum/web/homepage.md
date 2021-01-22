# Homepage

Build a simple homepage using HTML, CSS, and JavaScript.

## Background

The internet has enabled incredible things: we can use a search engine to research anything imaginable, communicate with friends and family members around the globe, play games, take courses, and so much more. But it turns out that nearly all pages we may visit are built on three core languages, each of which serves a slightly different purpose:

1. HTML, or <em>HyperText Markup Language</em>, which is used to describe the content of websites;
1. CSS, <em>Cascading Style Sheets</em>, which is used to describe the aesthetics of websites; and
1. JavaScript, which is used to make websites interactive and dynamic.

Create a simple homepage that introduces yourself, your favorite hobby or extracurricular, or anything else of interest to you.

## Getting Started

<p>Here’s how to download this problem’s “distribution code” (i.e., starter code) into your own CS50 IDE. Log into <a href="https://ide.cs50.io/">CS50 IDE</a> and then, in a terminal window, execute each of the below.</p>

<ol>
  <li>Execute <code class="language-plaintext highlighter-rouge">cd</code> to ensure that you’re in <code class="language-plaintext highlighter-rouge">~/</code> (i.e., your home directory).</li>
  <li>Execute <code class="language-plaintext highlighter-rouge">mkdir pset8</code> to make (i.e., create) a directory called <code class="language-plaintext highlighter-rouge">pset8</code> in your home directory.</li>
  <li>Execute <code class="language-plaintext highlighter-rouge">cd pset8</code> to change into (i.e., open) that directory.</li>
  <li>Execute <code class="language-plaintext highlighter-rouge">wget https://cdn.cs50.net/2019/fall/tracks/web/homepage/homepage.zip</code> to download a (compressed) ZIP file with this problem’s distribution.</li>
  <li>Execute <code class="language-plaintext highlighter-rouge">unzip homepage.zip</code> to uncompress that file.</li>
  <li>Execute <code class="language-plaintext highlighter-rouge">rm homepage.zip</code> followed by <code class="language-plaintext highlighter-rouge">yes</code> or <code class="language-plaintext highlighter-rouge">y</code> to delete that ZIP file.</li>
  <li>Execute <code class="language-plaintext highlighter-rouge">ls</code>. You should see a directory called <code class="language-plaintext highlighter-rouge">homepage</code>, which was inside of that ZIP file.</li>
  <li>Execute <code class="language-plaintext highlighter-rouge">cd homepage</code> to change into that directory.</li>
  <li>Execute <code class="language-plaintext highlighter-rouge">ls</code>. You should see this problem’s distribution, including <code class="language-plaintext highlighter-rouge">index.html</code> and <code class="language-plaintext highlighter-rouge">styles.css</code>.</li>
  <li>You can immediately start a server to view the site by running</li>
</ol>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ http-server
</code></pre></div></div>

<p>in the terminal window and clicking on the link that appears.</p>

## Specification

<p>Implement in your <code class="language-plaintext highlighter-rouge">homepage</code> directory a website that must:</p>

<ul>
  <li data-marker="*">Contain at least four different <code class="language-plaintext highlighter-rouge">.html</code> pages, at least one of which is <code class="language-plaintext highlighter-rouge">index.html</code> (the main page of your website), and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.</li>
  <li data-marker="*">Use at least ten (10) distinct HTML tags besides <code class="language-plaintext highlighter-rouge">&lt;html&gt;</code>, <code class="language-plaintext highlighter-rouge">&lt;head&gt;</code>, <code class="language-plaintext highlighter-rouge">&lt;body&gt;</code>, and <code class="language-plaintext highlighter-rouge">&lt;title&gt;</code>. Using some tag (e.g., <code class="language-plaintext highlighter-rouge">&lt;p&gt;</code>) multiple times still counts as just one (1) of those ten!</li>
  <li data-marker="*">Integrate one or more features from Bootstrap into your site. Bootstrap is a popular library (that comes with lots of CSS classes and more) via which you can beautify your site. See <a href="https://getbootstrap.com/docs/4.1/getting-started/introduction/">Bootstrap’s documentation</a> to get started. To add Bootstrap to your site, it suffices to include</li>
</ul>

<div class="language-html highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nt">&lt;link</span> <span class="na">rel=</span><span class="s">"stylesheet"</span> <span class="na">href=</span><span class="s">"https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"</span><span class="nt">&gt;</span>

</code></pre></div></div>

<p>in your pages’ <code class="language-plaintext highlighter-rouge">&lt;head&gt;</code>, below which you can also include</p>

<div class="language-html highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nt">&lt;link</span> <span class="na">href=</span><span class="s">"styles.css"</span> <span class="na">rel=</span><span class="s">"stylesheet"</span><span class="nt">&gt;</span>
</code></pre></div></div>

<p>to link your own CSS.</p>
<ul>
  <li data-marker="*">Have at least one stylesheet file of your own creation, <code class="language-plaintext highlighter-rouge">styles.css</code>, which uses at least five (5) different CSS selectors (e.g. tag (<code class="language-plaintext highlighter-rouge">example</code>), class (<code class="language-plaintext highlighter-rouge">.example</code>), or ID (<code class="language-plaintext highlighter-rouge">#example</code>)), and within which you use a total of at least five (5) different CSS properties, such as <code class="language-plaintext highlighter-rouge">font-size</code>, or <code class="language-plaintext highlighter-rouge">margin</code>; and</li>
  <li data-marker="*">Integrate one or more features of JavaScript into your site to make your site more interactive. For example, you can use JavaScript to add alerts, to have an effect at a recurring interval, or to add interactivity to buttons, dropdowns, or forms. Feel free to be creative!</li>
  <li data-marker="*">Ensure that your site looks nice on browsers both on mobile devices as well as laptops and desktops.</li>
</ul>

## Testing


## Assessment


## Hints


## How to Submit