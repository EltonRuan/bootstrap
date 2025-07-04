<div align='center'>
 <img style="width:100%" src="https://capsule-render.vercel.app/api?type=soft&height=200&color=FFFFFF&text=Bootstrap%20Guide&fontSize=40&fontAlign=50&strokeWidth=0&descAlignY=80&stroke=000000">
</div>

<nav align="center">
  <h2>🔗 NAVIGATION</h2>
  <p>
    <a href="#about-this-guide">ABOUT THIS GUIDE</a> |
    <a href="#what-is-bootstrap">WHAT IS BOOTSTRAP?</a> |
    <a href="#why-choose-bootstrap-for-web-development">WHY CHOOSE BOOTSTRAP FOR WEB DEVELOPMENT?</a> |
    <a href="#bootstrap-vs-other-frameworks">BOOTSTRAP VS OTHER FRAMEWORKS</a> |
    <a href="#installing-bootstrap-cdn-local-and-npm">INSTALLING BOOTSTRAP (CDN, LOCAL, AND NPM)</a> |
    <a href="#bootstrap-file-structure">BOOTSTRAP FILE STRUCTURE</a> |
    <a href="#linking-bootstrap-with-html">LINKING BOOTSTRAP WITH HTML</a> |
    <a href="#using-bootstrap-with-vite-webpack-or-laravel">USING BOOTSTRAP WITH VITE, WEBPACK, OR LARAVEL</a> |
    <a href="#bootstrap-grid-system">BOOTSTRAP GRID SYSTEM</a> |
    <a href="#breakpoints-and-responsive-design">BREAKPOINTS AND RESPONSIVE DESIGN</a> |
    <a href="#containers-rows-and-columns">CONTAINERS, ROWS, AND COLUMNS</a> |
    <a href="#flexbox-in-bootstrap">FLEXBOX IN BOOTSTRAP</a> |
    <a href="#buttons-types-colors-and-sizes">BUTTONS: TYPES, COLORS, AND SIZES</a> |
    <a href="#alerts-and-badges">ALERTS AND BADGES</a> |
    <a href="#cards-and-list-groups">CARDS AND LIST GROUPS</a> |
    <a href="#modals-and-popovers">MODALS AND POPOVERS</a> |
    <a href="#navbars-and-responsive-menus">NAVBARS AND RESPONSIVE MENUS</a> |
    <a href="#pagination-and-breadcrumbs">PAGINATION AND BREADCRUMBS</a> |
    <a href="#collapse-and-accordions">COLLAPSE AND ACCORDIONS</a> |
    <a href="#spinners-and-loaders">SPINNERS AND LOADERS</a> |
    <a href="#progress-bars">PROGRESS BARS</a> |
    <a href="#typography-utilities">TYPOGRAPHY UTILITIES</a> |
    <a href="#color-utilities">COLOR UTILITIES</a> |
    <a href="#spacing-margins--paddings">SPACING (MARGINS & PADDINGS)</a> |
    <a href="#borders-shadows-and-radius">BORDERS, SHADOWS, AND RADIUS</a> |
    <a href="#display-and-visibility-utilities">DISPLAY AND VISIBILITY UTILITIES</a> |
    <a href="#responsive-utilities">RESPONSIVE UTILITIES</a> |
    <a href="#customizing-bootstrap-with-sass">CUSTOMIZING BOOTSTRAP WITH SASS</a> |
    <a href="#using-bootstrap-icons">USING BOOTSTRAP ICONS</a> |
    <a href="#building-responsive-layouts">BUILDING RESPONSIVE LAYOUTS</a> |
    <a href="#centering-content">CENTERING CONTENT</a> |
    <a href="#fixed-footers-and-sticky-elements">FIXED FOOTERS AND STICKY ELEMENTS</a> |
    <a href="#offcanvas-and-sidebars">OFFCANVAS AND SIDEBARS</a> |
    <a href="#using-bootstrap-javascript-components">USING BOOTSTRAP JAVASCRIPT COMPONENTS</a> |
    <a href="#tooltips-toasts-and-carousels">TOOLTIPS, TOASTS, AND CAROUSELS</a> |
    <a href="#dropdowns-and-collapsibles">DROPDOWNS AND COLLAPSIBLES</a> |
    <a href="#data-attributes-vs-manual-init">DATA ATTRIBUTES VS MANUAL INIT</a> |
    <a href="#handling-modals-programmatically">HANDLING MODALS PROGRAMMATICALLY</a> |
    <a href="#theme-customization-with-sass-variables">THEME CUSTOMIZATION WITH SASS VARIABLES</a> |
    <a href="#creating-a-custom-theme">CREATING A CUSTOM THEME</a> |
    <a href="#overriding-default-styles">OVERRIDING DEFAULT STYLES</a> |
    <a href="#mixing-bootstrap-with-custom-css">MIXING BOOTSTRAP WITH CUSTOM CSS</a> |
    <a href="#using-bootstrap-with-tailwind">USING BOOTSTRAP WITH TAILWIND</a> |
    <a href="#mobile-first-design-tips">MOBILE-FIRST DESIGN TIPS</a> |
    <a href="#accessibility-in-bootstrap">ACCESSIBILITY IN BOOTSTRAP</a> |
    <a href="#performance-optimization">PERFORMANCE OPTIMIZATION</a> |
    <a href="#common-mistakes-to-avoid">COMMON MISTAKES TO AVOID</a> |
    <a href="#debugging-layout-issues">DEBUGGING LAYOUT ISSUES</a> |
    <a href="#bootstrap-not-loading-common-causes">BOOTSTRAP NOT LOADING: COMMON CAUSES</a> |
    <a href="#framework-conflicts">FRAMEWORK CONFLICTS</a> |
    <a href="#modal-z-index-issues">MODAL Z-INDEX ISSUES</a> |
    <a href="#layout-breaks-on-small-screens">LAYOUT BREAKS ON SMALL SCREENS</a> |
    <a href="#final-considerations">FINAL CONSIDERATIONS</a>
  </p>
</nav>

## ABOUT THIS GUIDE

<p>This guide was created to serve as a complete and practical manual for developers of all levels who want to master <strong>Bootstrap</strong>, one of the most widely used front-end frameworks in the world.</p>

<p>Whether you're just starting out in web development or are an experienced professional, this guide provides a structured, hands-on approach to building responsive, modern, and visually appealing websites using Bootstrap.</p>

<p>You'll find instructions on how to install and configure Bootstrap, explore its grid system, components, utilities, and learn best practices to optimize performance and maintain code readability. We'll also cover custom themes, troubleshooting tips, and real-world implementation examples.</p>

<p>By the end of this guide, you will be able to:</p>

<ul>
  <li>Understand what Bootstrap is and how it works.</li>
  <li>Set up Bootstrap using CDN, local files, or npm.</li>
  <li>Utilize the grid system and layout tools effectively.</li>
  <li>Style your projects using Bootstrap’s built-in components and utilities.</li>
  <li>Customize Bootstrap themes using Sass.</li>
  <li>Implement responsive design principles easily.</li>
  <li>Troubleshoot common layout and rendering issues.</li>
  <li>Build professional and scalable web interfaces faster.</li>
</ul>

## WHAT IS BOOTSTRAP?

<p><strong>Bootstrap</strong> is a popular open-source front-end framework originally developed by Twitter. It provides developers with a collection of pre-designed components, responsive grid systems, and utility classes to quickly and efficiently build modern, mobile-first web interfaces.</p>

<p>Its goal is to simplify the process of creating visually appealing and fully responsive web applications without having to write extensive custom CSS from scratch. Whether you're building a personal website, a product landing page, or a full dashboard interface, Bootstrap offers the tools to do it faster and more consistently.</p>

<p>Some key characteristics of Bootstrap include:</p>

<ul>
  <li>Mobile-first approach</li>
  <li>Pre-built responsive grid system</li>
  <li>Components like buttons, navbars, cards, modals, etc.</li>
  <li>Utility classes for margin, padding, colors, and typography</li>
  <li>Easily customizable with Sass variables and built-in themes</li>
  <li>Compatibility with all modern browsers</li>
</ul>

<p>Bootstrap is ideal for both beginners and experienced developers who want to streamline their UI development process.</p>

## WHY CHOOSE BOOTSTRAP FOR WEB DEVELOPMENT?

<p>Choosing <strong>Bootstrap</strong> for web development offers numerous benefits that streamline the design process and improve development efficiency. It's widely adopted by both beginners and professionals due to its versatility, ease of use, and strong community support.</p>

<p>Here are some key reasons to choose Bootstrap for your projects:</p>

<ul>
  <li><strong>Quick Prototyping:</strong> Bootstrap provides pre-styled components and layout utilities that allow developers to rapidly prototype websites without starting from scratch.</li>
  <li><strong>Responsive Design:</strong> Built with a mobile-first approach, Bootstrap ensures your projects are responsive by default and adapt seamlessly to different screen sizes.</li>
  <li><strong>Cross-Browser Compatibility:</strong> Bootstrap is tested and compatible with all major browsers, saving time on manual adjustments and fixes.</li>
  <li><strong>Customization:</strong> Developers can easily customize Bootstrap using Sass variables and theming options to match the branding or specific design guidelines of a project.</li>
  <li><strong>Component-Rich:</strong> From modals and carousels to buttons and alerts, Bootstrap includes a wide variety of reusable UI components that are fully integrated and accessible.</li>
  <li><strong>Extensive Documentation:</strong> Bootstrap offers comprehensive and well-organized documentation, making it easy to learn and implement even for beginners.</li>
  <li><strong>Large Community:</strong> With millions of users worldwide, Bootstrap has a vibrant community that contributes to plugins, tutorials, templates, and ongoing support.</li>
</ul>

<p>Overall, Bootstrap is a reliable and time-saving tool for building modern, clean, and professional web interfaces with minimal effort.</p>

## BOOTSTRAP VS OTHER FRAMEWORKS

<p>While <strong>Bootstrap</strong> is one of the most popular front-end frameworks, it’s important to understand how it compares with other alternatives in the web development ecosystem. Each framework has its own strengths and use cases.</p>

<ul>
  <li><strong>Bootstrap vs Tailwind CSS:</strong> 
    Bootstrap comes with pre-designed components and layout utilities, which helps in building UIs quickly. Tailwind, on the other hand, uses a utility-first approach, offering greater flexibility and control over the design at the cost of a steeper learning curve for some developers.
  </li>

  <li><strong>Bootstrap vs Foundation:</strong> 
    Foundation, by Zurb, is another responsive front-end framework with a focus on accessibility and customization. While both offer mobile-first grids and UI components, Bootstrap’s larger community and more frequent updates make it more beginner-friendly and widely adopted.
  </li>

  <li><strong>Bootstrap vs Bulma:</strong> 
    Bulma is a lightweight and modern CSS framework based entirely on Flexbox. It’s known for simplicity and elegant syntax, but lacks built-in JavaScript components, which Bootstrap includes by default.
  </li>

  <li><strong>Bootstrap vs Materialize:</strong> 
    Materialize is based on Google’s Material Design principles, offering beautiful components out of the box. Bootstrap is more neutral and flexible in design, giving developers more freedom to style according to brand identity.
  </li>
</ul>

<p><strong>Conclusion:</strong> While all frameworks have their place, Bootstrap stands out for its balance between ease of use, component variety, responsiveness, and support. It's ideal for both rapid prototyping and production-ready development.</p>

## INSTALLING BOOTSTRAP (CDN, LOCAL, AND NPM)

<p>There are multiple ways to install and use Bootstrap in your web projects, depending on your setup and preferences. Below are the most common methods:</p>

<h3>1. CDN (Content Delivery Network)</h3>
<p>This is the quickest and easiest way to get started with Bootstrap. Simply add the following lines to your HTML file:</p>

<pre><code>&lt;!-- Bootstrap CSS --&gt;
&lt;link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet"&gt;

&lt;!-- Bootstrap JS (with Popper) --&gt;
&lt;script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"&gt;&lt;/script&gt;
</code></pre>

<h3>2. Local Installation</h3>
<p>If you prefer to keep all dependencies locally, download Bootstrap from the official website ( https://getbootstrap.com/docs/5.3/getting-started/download/ ) and include the CSS and JS files:</p>

<pre><code>&lt;link rel="stylesheet" href="path/to/bootstrap.min.css"&gt;
&lt;script src="path/to/bootstrap.bundle.min.js"&gt;&lt;/script&gt;
</code></pre>

<h3>3. NPM (Node Package Manager)</h3>
<p>If you're using a build system like Webpack, Vite, or Parcel, you can install Bootstrap via NPM:</p>

<pre><code>npm install bootstrap</code></pre>

<p>Then, import Bootstrap into your JavaScript or SCSS files:</p>

<pre><code>// JavaScript
import 'bootstrap';

// SCSS
@import "bootstrap/scss/bootstrap";
</code></pre>

<p><strong>Note:</strong> When using the NPM method, make sure you configure your bundler to compile SCSS or bundle the required JS correctly.</p>

<h2 id="bootstrap-file-structure">BOOTSTRAP FILE STRUCTURE</h2>

<p>When you download Bootstrap locally, the extracted folder typically contains two main directories: <code>css/</code> and <code>js/</code>. These folders include various versions of compiled CSS and JavaScript files, both minified and unminified, as well as source maps and RTL (right-to-left) support files.</p>

<h3>Directory Overview:</h3>

<pre><code>bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── bootstrap.rtl.css
│   ├── bootstrap.rtl.css.map
│   ├── bootstrap.rtl.min.css
│   ├── bootstrap.rtl.min.css.map
│   ├── bootstrap-grid.css
│   ├── bootstrap-grid.css.map
│   ├── bootstrap-grid.min.css
│   ├── bootstrap-grid.min.css.map
│   ├── bootstrap-grid.rtl.css
│   ├── bootstrap-grid.rtl.css.map
│   ├── bootstrap-grid.rtl.min.css
│   ├── bootstrap-grid.rtl.min.css.map
│   ├── bootstrap-reboot.css
│   ├── bootstrap-reboot.css.map
│   ├── bootstrap-reboot.min.css
│   ├── bootstrap-reboot.min.css.map
│   ├── bootstrap-reboot.rtl.css
│   ├── bootstrap-reboot.rtl.css.map
│   ├── bootstrap-reboot.rtl.min.css
│   ├── bootstrap-reboot.rtl.min.css.map
│   ├── bootstrap-utilities.css
│   ├── bootstrap-utilities.css.map
│   ├── bootstrap-utilities.min.css
│   ├── bootstrap-utilities.min.css.map
│   ├── bootstrap-utilities.rtl.css
│   ├── bootstrap-utilities.rtl.css.map
│   ├── bootstrap-utilities.rtl.min.css
│   └── bootstrap-utilities.rtl.min.css.map
└── js/
    ├── bootstrap.bundle.js
    ├── bootstrap.bundle.js.map
    ├── bootstrap.bundle.min.js
    ├── bootstrap.bundle.min.js.map
    ├── bootstrap.esm.js
    ├── bootstrap.esm.js.map
    ├── bootstrap.esm.min.js
    ├── bootstrap.esm.min.js.map
    ├── bootstrap.js
    ├── bootstrap.js.map
    ├── bootstrap.min.js
    └── bootstrap.min.js.map
</code></pre>

<h3>Description of Key Files:</h3>

<ul>
  <li><strong>bootstrap.css / bootstrap.min.css</strong>: The core Bootstrap CSS (normal and minified).</li>
  <li><strong>bootstrap.rtl.css</strong>: CSS with support for right-to-left languages.</li>
  <li><strong>bootstrap-grid.css</strong>: Grid system only, useful if you don’t need the full Bootstrap bundle.</li>
  <li><strong>bootstrap-reboot.css</strong>: Resets and normalizes styles across browsers.</li>
  <li><strong>bootstrap-utilities.css</strong>: Contains Bootstrap’s utility classes only.</li>
  <li><strong>.map files</strong>: Source maps for debugging and development tools.</li>
  <li><strong>bootstrap.bundle.js</strong>: Includes Bootstrap’s JavaScript and Popper (necessary for dropdowns, tooltips, etc).</li>
  <li><strong>bootstrap.esm.js</strong>: JavaScript in ECMAScript module format for modern bundlers.</li>
  <li><strong>bootstrap.js</strong>: The standard JavaScript without dependencies bundled.</li>
</ul>

<p>This file structure offers flexibility to only include what your project really needs, helping reduce load times and improving maintainability.</p>

## LINKING BOOTSTRAP WITH HTML

<p>To start using Bootstrap in your web projects, you need to link the Bootstrap CSS and JavaScript files within your HTML documents. There are multiple ways to do this, including using a CDN (Content Delivery Network) or hosting the files locally.</p>

<h3>1. Using Bootstrap via CDN</h3>
<p>Linking via CDN is the fastest and easiest way to get started without downloading any files. Simply add the following <code>&lt;link&gt;</code> and <code>&lt;script&gt;</code> tags inside the <code>&lt;head&gt;</code> and before the closing <code>&lt;/body&gt;</code> tag respectively:</p>

<pre><code>&lt;!-- Bootstrap CSS --&gt;
&lt;link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-..." crossorigin="anonymous"&gt;

&lt;!-- Bootstrap JS Bundle (includes Popper) --&gt;
&lt;script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-..." crossorigin="anonymous"&gt;&lt;/script&gt;
</code></pre>

<p>Make sure to replace the version number (here, <code>5.3.0</code>) with the latest stable version.</p>

<h3>2. Using Bootstrap Locally</h3>
<p>If you prefer to download Bootstrap and serve the files from your own server or project folder, link the CSS and JS files like this:</p>

<pre><code>&lt;!-- Bootstrap CSS --&gt;
&lt;link href="path/to/bootstrap/css/bootstrap.min.css" rel="stylesheet"&gt;

&lt;!-- Bootstrap JS Bundle --&gt;
&lt;script src="path/to/bootstrap/js/bootstrap.bundle.min.js"&gt;&lt;/script&gt;
</code></pre>

<p>Replace <code>path/to/bootstrap/</code> with the actual path to where you placed the Bootstrap files.</p>

<h3>3. Important Notes</h3>
<ul>
  <li>Always include the Bootstrap CSS file in the <code>&lt;head&gt;</code> section so the styles load before the content is rendered.</li>
  <li>Place the Bootstrap JS bundle right before the closing <code>&lt;/body&gt;</code> tag to improve page load speed.</li>
  <li>The Bootstrap JS bundle includes Popper.js, which is required for tooltips, popovers, and dropdowns.</li>
  <li>If you need to customize Bootstrap extensively, consider using the source SCSS files and compiling them yourself.</li>
</ul>

<p>Once linked, you can start using Bootstrap's classes and components right away in your HTML!</p>

## USING BOOTSTRAP WITH VITE, WEBPACK, OR LARAVEL

<p>For modern development workflows and larger applications, it's common to use build tools like <strong>Vite</strong>, <strong>Webpack</strong>, or full-stack frameworks like <strong>Laravel</strong> (which often includes Vite by default). Below is how you can integrate Bootstrap with each of these tools efficiently.</p>

<h3>Vite</h3>
<ol>
  <li>Install Bootstrap via NPM:
    <pre><code>npm install bootstrap</code></pre>
  </li>
  <li>Import Bootstrap into your main JavaScript or SCSS file:
    <pre><code>// main.js
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap';</code></pre>
  </li>
  <li>Start your development server:
    <pre><code>npm run dev</code></pre>
  </li>
</ol>

<h3>Webpack</h3>
<ol>
  <li>Install Bootstrap and dependencies:
    <pre><code>npm install bootstrap</code></pre>
  </li>
  <li>Include Bootstrap in your entry file:
    <pre><code>// index.js
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap';</code></pre>
  </li>
  <li>Make sure your Webpack config handles CSS and JS bundling correctly.</li>
</ol>

<h3>Laravel (with Vite)</h3>
<ol>
  <li>Install Bootstrap:
    <pre><code>npm install bootstrap</code></pre>
  </li>
  <li>Edit <code>resources/js/app.js</code> to include:
    <pre><code>import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap';</code></pre>
  </li>
  <li>Edit <code>vite.config.js</code> if necessary (Laravel 10+ usually has it preconfigured).</li>
  <li>Compile assets:
    <pre><code>npm run dev</code></pre>
  </li>
</ol>

<h3>Pro Tips</h3>
<ul>
  <li>Always restart the dev server after changing configuration files.</li>
  <li>Using SCSS? Import <code>bootstrap/scss/bootstrap.scss</code> instead and customize variables before compiling.</li>
  <li>Use <code>@import</code> or <code>require()</code> based on your bundler's support.</li>
</ul>

## BOOTSTRAP GRID SYSTEM

<p>The <strong>Bootstrap Grid System</strong> is a powerful and flexible way to create responsive layouts. It’s based on a 12-column system and uses containers, rows, and columns to align content across various screen sizes and devices.</p>

<h3>Key Concepts</h3>
<ul>
  <li><strong>Container</strong>: Wraps the content and provides horizontal padding. Use <code>.container</code> or <code>.container-fluid</code>.</li>
  <li><strong>Row</strong>: Used to create a horizontal group of columns.</li>
  <li><strong>Columns</strong>: Use <code>.col</code>, <code>.col-*</code>, or responsive variations like <code>.col-md-6</code>.</li>
</ul>

<h3>12-Column System</h3>
<p>The grid divides the screen into 12 columns. You can combine columns to span the width you need. For example:</p>

<pre><code>
&lt;div class="container"&gt;
  &lt;div class="row"&gt;
    &lt;div class="col-6"&gt;Column 1 (6/12)&lt;/div&gt;
    &lt;div class="col-6"&gt;Column 2 (6/12)&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Responsive Breakpoints</h3>
<p>Bootstrap includes classes for different device sizes:</p>
<ul>
  <li><code>.col-sm-*</code>: ≥576px</li>
  <li><code>.col-md-*</code>: ≥768px</li>
  <li><code>.col-lg-*</code>: ≥992px</li>
  <li><code>.col-xl-*</code>: ≥1200px</li>
  <li><code>.col-xxl-*</code>: ≥1400px</li>
</ul>

<h3>Auto Layout Columns</h3>
<p>Let columns automatically adjust to fit their content or space:</p>

<pre><code>
&lt;div class="row"&gt;
  &lt;div class="col"&gt;Auto 1&lt;/div&gt;
  &lt;div class="col"&gt;Auto 2&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Nesting</h3>
<p>You can nest rows and columns for complex layouts:</p>

<pre><code>
&lt;div class="row"&gt;
  &lt;div class="col-8"&gt;
    &lt;div class="row"&gt;
      &lt;div class="col-6"&gt;Nested 1&lt;/div&gt;
      &lt;div class="col-6"&gt;Nested 2&lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Tips</h3>
<ul>
  <li>Use <code>.g-*</code> classes for spacing between columns (gutter).</li>
  <li>Combine different breakpoint classes for adaptive designs.</li>
  <li>Always wrap columns inside a row to avoid unexpected behavior.</li>
</ul>

## BREAKPOINTS AND RESPONSIVE DESIGN

<p>
  Bootstrap is built with a mobile-first approach and provides predefined <strong>breakpoints</strong> that make it easy to build responsive web layouts. These breakpoints allow you to apply different styles depending on the screen size of the user’s device.
</p>

<h3>Default Breakpoints</h3>
<p>Bootstrap includes the following responsive breakpoints:</p>
<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Breakpoint</th>
      <th>Class Prefix</th>
      <th>Dimensions</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Extra small</td>
      <td><code>none</code></td>
      <td>&lt; 576px</td>
    </tr>
    <tr>
      <td>Small</td>
      <td><code>sm</code></td>
      <td>≥ 576px</td>
    </tr>
    <tr>
      <td>Medium</td>
      <td><code>md</code></td>
      <td>≥ 768px</td>
    </tr>
    <tr>
      <td>Large</td>
      <td><code>lg</code></td>
      <td>≥ 992px</td>
    </tr>
    <tr>
      <td>Extra Large</td>
      <td><code>xl</code></td>
      <td>≥ 1200px</td>
    </tr>
    <tr>
      <td>Extra Extra Large</td>
      <td><code>xxl</code></td>
      <td>≥ 1400px</td>
    </tr>
  </tbody>
</table>

<h3>How to Use Breakpoints</h3>
<p>
  Combine breakpoint prefixes with utilities and grid classes. For example:
</p>

<pre><code>
&lt;div class="d-none d-md-block"&gt;
  This content is hidden on small screens and visible on medium and larger.
&lt;/div&gt;

&lt;div class="col-12 col-sm-6 col-lg-4"&gt;
  Responsive column that adjusts width based on screen size.
&lt;/div&gt;
</code></pre>

<h3>Responsive Utility Classes</h3>
<p>Bootstrap provides many responsive utility classes, such as:</p>
<ul>
  <li><code>.d-none</code>, <code>.d-sm-block</code> (Display utilities)</li>
  <li><code>.text-center</code>, <code>.text-md-start</code> (Text alignment)</li>
  <li><code>.m-0</code>, <code>.p-lg-5</code> (Spacing utilities)</li>
</ul>

<h3>Best Practices</h3>
<ul>
  <li>Start with mobile styles, then add enhancements for larger screens using breakpoints.</li>
  <li>Use containers and grid classes wisely to create fluid and adaptable layouts.</li>
  <li>Test your design on multiple devices or with browser developer tools.</li>
</ul>

## CONTAINERS, ROWS, AND COLUMNS

<p>
  The foundation of the Bootstrap grid system is built on three key elements: <strong>containers</strong>, <strong>rows</strong>, and <strong>columns</strong>. Understanding how these elements work together is essential for building responsive layouts.
</p>

<h3>1. Containers</h3>
<p>
  Containers are used to wrap the site content and provide proper alignment and padding. Bootstrap provides two types:
</p>
<ul>
  <li><code>.container</code> – A fixed-width container that responds to screen sizes.</li>
  <li><code>.container-fluid</code> – A full-width container spanning the entire width of the viewport.</li>
</ul>

<pre><code>
&lt;div class="container"&gt;
  Fixed-width content
&lt;/div&gt;

&lt;div class="container-fluid"&gt;
  Full-width content
&lt;/div&gt;
</code></pre>

<h3>2. Rows</h3>
<p>
  Rows are used to create horizontal groups of columns. They ensure proper alignment and spacing.
</p>

<pre><code>
&lt;div class="row"&gt;
  &lt;div class="col"&gt;Column 1&lt;/div&gt;
  &lt;div class="col"&gt;Column 2&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>3. Columns</h3>
<p>
  Columns are flex containers within a row. Bootstrap uses a 12-column grid, allowing for flexible layouts by specifying how many columns each element should span.
</p>

<pre><code>
&lt;div class="row"&gt;
  &lt;div class="col-6"&gt;Half Width&lt;/div&gt;
  &lt;div class="col-6"&gt;Half Width&lt;/div&gt;
&lt;/div&gt;

&lt;div class="row"&gt;
  &lt;div class="col-sm-4 col-md-6 col-lg-3"&gt;
    Responsive Column
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Tips</h3>
<ul>
  <li>Always place <code>.col-*</code> inside a <code>.row</code> inside a <code>.container</code>.</li>
  <li>Use responsive column classes like <code>.col-md-4</code> for adaptable designs.</li>
  <li>You can nest rows and columns to build complex layouts.</li>
</ul>

## FLEXBOX IN BOOTSTRAP

<p>
  Bootstrap 5 is built entirely with <strong>Flexbox</strong>, a powerful layout module that allows you to design flexible and responsive layout structures without using float or positioning hacks.
</p>

<h3>Why Flexbox?</h3>
<ul>
  <li>Easy vertical and horizontal alignment.</li>
  <li>Responsive layouts with less CSS.</li>
  <li>Flexible resizing of elements.</li>
  <li>Dynamic space distribution between items.</li>
</ul>

<h3>Basic Flex Utilities in Bootstrap</h3>
<p>
  Bootstrap provides a wide range of utility classes to apply Flexbox directly in your HTML without writing custom CSS.
</p>

<h4>1. <code>.d-flex</code></h4>
<p>Makes an element a flex container.</p>
<pre><code>
&lt;div class="d-flex"&gt;
  &lt;div&gt;Item 1&lt;/div&gt;
  &lt;div&gt;Item 2&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h4>2. <code>.justify-content-*</code></h4>
<p>Aligns children horizontally.</p>
<ul>
  <li><code>.justify-content-start</code></li>
  <li><code>.justify-content-center</code></li>
  <li><code>.justify-content-end</code></li>
  <li><code>.justify-content-between</code></li>
  <li><code>.justify-content-around</code></li>
  <li><code>.justify-content-evenly</code></li>
</ul>

<h4>3. <code>.align-items-*</code></h4>
<p>Aligns children vertically.</p>
<ul>
  <li><code>.align-items-start</code></li>
  <li><code>.align-items-center</code></li>
  <li><code>.align-items-end</code></li>
</ul>

<h4>4. <code>.flex-column</code> and <code>.flex-row</code></h4>
<p>Changes the direction of the flex container.</p>
<pre><code>
&lt;div class="d-flex flex-column"&gt;
  &lt;div&gt;Top&lt;/div&gt;
  &lt;div&gt;Bottom&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h4>5. Responsive Flex</h4>
<p>
  You can make flex utilities responsive using breakpoints:
</p>
<pre><code>
&lt;div class="d-flex flex-md-row flex-column"&gt;
  &lt;div&gt;Item 1&lt;/div&gt;
  &lt;div&gt;Item 2&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li>Use <code>.d-flex</code> to initiate flex context.</li>
  <li>Combine with <code>.justify-content-</code> and <code>.align-items-</code> for precise control.</li>
  <li>Leverage responsive flex utilities to create adaptable layouts.</li>
</ul>

## BUTTONS: TYPES, COLORS, AND SIZES

<p>
  Buttons in Bootstrap are highly customizable and easy to implement. They can be used to trigger actions, submit forms, navigate, and more.
</p>

<h3>Button Types</h3>
<p>Bootstrap provides several button types using classes:</p>
<ul>
  <li><code>btn</code> - Required base class for all buttons.</li>
  <li><code>btn-primary</code> - Used for primary actions.</li>
  <li><code>btn-secondary</code> - Used for secondary actions.</li>
  <li><code>btn-success</code> - Indicates a successful or positive action.</li>
  <li><code>btn-danger</code> - Indicates a dangerous or potentially negative action.</li>
  <li><code>btn-warning</code> - Indicates caution should be taken.</li>
  <li><code>btn-info</code> - Represents neutral informative actions.</li>
  <li><code>btn-light</code> and <code>btn-dark</code> - Alternate styles for dark/light themes.</li>
  <li><code>btn-link</code> - Appears like a link.</li>
</ul>

<pre><code>
&lt;button class="btn btn-primary"&gt;Primary&lt;/button&gt;
&lt;button class="btn btn-danger"&gt;Danger&lt;/button&gt;
&lt;button class="btn btn-link"&gt;Link&lt;/button&gt;
</code></pre>

<h3>Button Colors</h3>
<p>Colors are applied using contextual classes mentioned above. You can also customize buttons using your own CSS if needed.</p>

<h3>Button Sizes</h3>
<p>Use these classes to adjust button size:</p>
<ul>
  <li><code>btn-lg</code> - Large button</li>
  <li><code>btn-sm</code> - Small button</li>
</ul>

<pre><code>
&lt;button class="btn btn-success btn-lg"&gt;Large Button&lt;/button&gt;
&lt;button class="btn btn-warning btn-sm"&gt;Small Button&lt;/button&gt;
</code></pre>

<h3>Additional Options</h3>
<ul>
  <li><code>btn-block</code> (v4) or <code>d-grid gap-2</code> + <code>w-100</code> (v5) for full-width buttons.</li>
  <li><code>disabled</code> attribute for disabling buttons.</li>
  <li>Use button tags or anchor tags interchangeably.</li>
</ul>

<pre><code>
&lt;button class="btn btn-primary" disabled&gt;Disabled&lt;/button&gt;
&lt;a href="#" class="btn btn-info"&gt;Anchor Button&lt;/a&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li>Use <code>.btn</code> with a contextual class like <code>.btn-primary</code>.</li>
  <li>Control size with <code>.btn-sm</code> and <code>.btn-lg</code>.</li>
  <li>Use utility classes for responsiveness and spacing.</li>
</ul>

## ALERTS AND BADGES

<p>
  Alerts and badges are two essential components in Bootstrap used for feedback messages and displaying counts, statuses, or labels in a compact form.
</p>

<h3>Alerts</h3>
<p>
  Alerts provide contextual feedback messages for typical user actions. They come in several predefined colors and can be dismissible.
</p>

<h4>Basic Alert</h4>
<pre><code>
&lt;div class="alert alert-primary" role="alert"&gt;
  This is a primary alert—check it out!
&lt;/div&gt;
</code></pre>

<h4>Alert Contextual Classes</h4>
<ul>
  <li><code>alert-primary</code></li>
  <li><code>alert-secondary</code></li>
  <li><code>alert-success</code></li>
  <li><code>alert-danger</code></li>
  <li><code>alert-warning</code></li>
  <li><code>alert-info</code></li>
  <li><code>alert-light</code></li>
  <li><code>alert-dark</code></li>
</ul>

<h4>Dismissible Alert</h4>
<pre><code>
&lt;div class="alert alert-warning alert-dismissible fade show" role="alert"&gt;
  This is a dismissible alert!
  &lt;button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"&gt;&lt;/button&gt;
&lt;/div&gt;
</code></pre>

<h3>Badges</h3>
<p>
  Badges are used to highlight new or unread items, counters, or labels.
</p>

<h4>Basic Badge</h4>
<pre><code>
&lt;span class="badge bg-primary"&gt;New&lt;/span&gt;
</code></pre>

<h4>Badge Contextual Classes</h4>
<ul>
  <li><code>bg-primary</code></li>
  <li><code>bg-secondary</code></li>
  <li><code>bg-success</code></li>
  <li><code>bg-danger</code></li>
  <li><code>bg-warning text-dark</code></li>
  <li><code>bg-info</code></li>
  <li><code>bg-light text-dark</code></li>
  <li><code>bg-dark</code></li>
</ul>

<h4>Badge in Buttons</h4>
<pre><code>
&lt;button type="button" class="btn btn-primary"&gt;
  Notifications &lt;span class="badge bg-light text-dark"&gt;4&lt;/span&gt;
&lt;/button&gt;
</code></pre>

<h4>Pill Badges</h4>
<pre><code>
&lt;span class="badge rounded-pill bg-success"&gt;Success&lt;/span&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li>Use alerts for messages and notifications with dismiss functionality if needed.</li>
  <li>Use badges for counts, labels, or statuses inside buttons, links, or text.</li>
</ul>

## CARDS AND LIST GROUPS

<p>
  Cards and list groups are versatile UI components in Bootstrap used for displaying content, links, and grouped information in a visually structured way.
</p>

<h3>Cards</h3>
<p>
  Cards are flexible and extensible content containers with multiple variants and options.
</p>

<h4>Basic Card</h4>
<pre><code>
&lt;div class="card" style="width: 18rem;"&gt;
  &lt;img src="image.jpg" class="card-img-top" alt="..."&gt;
  &lt;div class="card-body"&gt;
    &lt;h5 class="card-title"&gt;Card Title&lt;/h5&gt;
    &lt;p class="card-text"&gt;Some quick example text to build on the card title.&lt;/p&gt;
    &lt;a href="#" class="btn btn-primary"&gt;Go somewhere&lt;/a&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h4>Card Variations</h4>
<ul>
  <li>Cards with headers and footers</li>
  <li>Horizontal cards using <code>.row</code> and <code>.col</code></li>
  <li>Cards with background variants using <code>.bg-*</code> and text variants with <code>.text-*</code></li>
</ul>

<h3>List Groups</h3>
<p>
  List groups are great for displaying a series of content or navigation items.
</p>

<h4>Basic List Group</h4>
<pre><code>
&lt;ul class="list-group"&gt;
  &lt;li class="list-group-item"&gt;First item&lt;/li&gt;
  &lt;li class="list-group-item"&gt;Second item&lt;/li&gt;
  &lt;li class="list-group-item"&gt;Third item&lt;/li&gt;
&lt;/ul&gt;
</code></pre>

<h4>List Group with Links</h4>
<pre><code>
&lt;div class="list-group"&gt;
  &lt;a href="#" class="list-group-item list-group-item-action active"&gt;Active item&lt;/a&gt;
  &lt;a href="#" class="list-group-item list-group-item-action"&gt;Another item&lt;/a&gt;
&lt;/div&gt;
</code></pre>

<h4>List Group with Badges</h4>
<pre><code>
&lt;ul class="list-group"&gt;
  &lt;li class="list-group-item d-flex justify-content-between align-items-center"&gt;
    Messages
    &lt;span class="badge bg-primary rounded-pill"&gt;14&lt;/span&gt;
  &lt;/li&gt;
&lt;/ul&gt;
</code></pre>

<h4>Cards with List Groups</h4>
<pre><code>
&lt;div class="card" style="width: 18rem;"&gt;
  &lt;div class="card-header"&gt;
    Featured
  &lt;/div&gt;
  &lt;ul class="list-group list-group-flush"&gt;
    &lt;li class="list-group-item"&gt;Item 1&lt;/li&gt;
    &lt;li class="list-group-item"&gt;Item 2&lt;/li&gt;
    &lt;li class="list-group-item"&gt;Item 3&lt;/li&gt;
  &lt;/ul&gt;
&lt;/div&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li>Cards are used for content blocks with images, text, and actions.</li>
  <li>List groups are ideal for structured lists, navigation, or content grouping.</li>
  <li>They can be combined for more powerful UI elements.</li>
</ul>

## MODALS AND POPOVERS

<p>
  Modals and popovers are interactive components in Bootstrap used to present content or actions in a focused overlay without navigating away from the current page.
</p>

<h3>Modals</h3>
<p>
  A modal is a dialog box/popup window that is displayed on top of the current page.
</p>

<h4>Basic Modal Structure</h4>
<pre><code>
&lt;!-- Button to trigger modal --&gt;
&lt;button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal"&gt;
  Launch demo modal
&lt;/button&gt;

&lt;!-- Modal --&gt;
&lt;div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"&gt;
  &lt;div class="modal-dialog"&gt;
    &lt;div class="modal-content"&gt;
      &lt;div class="modal-header"&gt;
        &lt;h5 class="modal-title" id="exampleModalLabel"&gt;Modal Title&lt;/h5&gt;
        &lt;button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"&gt;&lt;/button&gt;
      &lt;/div&gt;
      &lt;div class="modal-body"&gt;
        Modal body content goes here.
      &lt;/div&gt;
      &lt;div class="modal-footer"&gt;
        &lt;button type="button" class="btn btn-secondary" data-bs-dismiss="modal"&gt;Close&lt;/button&gt;
        &lt;button type="button" class="btn btn-primary"&gt;Save changes&lt;/button&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h4>Modal Options</h4>
<ul>
  <li><code>data-bs-backdrop="static"</code> – Prevents closing on click outside</li>
  <li><code>data-bs-keyboard="false"</code> – Prevents closing with Esc key</li>
  <li>Sizes: <code>modal-sm</code>, <code>modal-lg</code>, <code>modal-xl</code></li>
</ul>

<h3>Popovers</h3>
<p>
  Popovers are small overlays that appear upon user interaction, usually over buttons or links.
</p>

<h4>Enabling Popovers</h4>
<p>
  Make sure Popper and Bootstrap JS are properly included, then enable popovers using JavaScript.
</p>

<pre><code>
// Enable popover globally
const popoverTriggerList = document.querySelectorAll('[data-bs-toggle="popover"]');
const popoverList = [...popoverTriggerList].map(popoverTriggerEl =&gt; new bootstrap.Popover(popoverTriggerEl));
</code></pre>

<h4>Example Popover</h4>
<pre><code>
&lt;button type="button" class="btn btn-secondary" data-bs-toggle="popover" title="Popover title" data-bs-content="Popover body content is here."&gt;
  Click me
&lt;/button&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li><strong>Modals</strong> are ideal for forms, alerts, or confirmations.</li>
  <li><strong>Popovers</strong> are useful for hints or additional information on interaction.</li>
  <li>Both components enhance interactivity and UX.</li>
</ul>

## NAVBARS AND RESPONSIVE MENUS

<p>
  Bootstrap provides powerful navigation components like navbars that are fully responsive and customizable. They adapt to different screen sizes and can include brand names, links, dropdowns, forms, and togglers.
</p>

<h3>Basic Navbar Structure</h3>

<pre><code>
&lt;nav class="navbar navbar-expand-lg navbar-light bg-light"&gt;
  &lt;div class="container-fluid"&gt;
    &lt;a class="navbar-brand" href="#"&gt;BrandName&lt;/a&gt;
    &lt;button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" 
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation"&gt;
      &lt;span class="navbar-toggler-icon"&gt;&lt;/span&gt;
    &lt;/button&gt;
    &lt;div class="collapse navbar-collapse" id="navbarNav"&gt;
      &lt;ul class="navbar-nav"&gt;
        &lt;li class="nav-item"&gt;
          &lt;a class="nav-link active" aria-current="page" href="#"&gt;Home&lt;/a&gt;
        &lt;/li&gt;
        &lt;li class="nav-item"&gt;
          &lt;a class="nav-link" href="#"&gt;Features&lt;/a&gt;
        &lt;/li&gt;
        &lt;li class="nav-item"&gt;
          &lt;a class="nav-link" href="#"&gt;Pricing&lt;/a&gt;
        &lt;/li&gt;
      &lt;/ul&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/nav&gt;
</code></pre>

<h3>Color Schemes</h3>
<ul>
  <li><code>navbar-light bg-light</code> – Light text on light background</li>
  <li><code>navbar-dark bg-dark</code> – Light text on dark background</li>
  <li>Custom colors can be used with Bootstrap utility classes or custom CSS</li>
</ul>

<h3>Responsiveness</h3>
<ul>
  <li><code>navbar-expand-lg</code> – Expands the navbar on large screens and collapses on smaller ones</li>
  <li>Change the breakpoint with: <code>navbar-expand-sm</code>, <code>navbar-expand-md</code>, <code>navbar-expand-xl</code></li>
</ul>

<h3>Dropdown Menus</h3>

<pre><code>
&lt;li class="nav-item dropdown"&gt;
  &lt;a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false"&gt;
    Dropdown
  &lt;/a&gt;
  &lt;ul class="dropdown-menu" aria-labelledby="navbarDropdown"&gt;
    &lt;li&gt;&lt;a class="dropdown-item" href="#"&gt;Action&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a class="dropdown-item" href="#"&gt;Another action&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;hr class="dropdown-divider"&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a class="dropdown-item" href="#"&gt;Something else here&lt;/a&gt;&lt;/li&gt;
  &lt;/ul&gt;
&lt;/li&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li>Use navbars to create site-wide navigation</li>
  <li>Responsive and collapsible by default</li>
  <li>Fully customizable with Bootstrap classes and utility styles</li>
</ul>

## PAGINATION AND BREADCRUMBS

<p>
  Bootstrap provides built-in components for handling navigation within your website, such as pagination and breadcrumbs. These elements help users move through content and understand their location within the site.
</p>

<h3>Pagination</h3>
<p>
  Pagination is used to divide content into multiple pages, commonly used in lists, tables, or search results.
</p>

<pre><code>
&lt;nav aria-label="Page navigation example"&gt;
  &lt;ul class="pagination"&gt;
    &lt;li class="page-item"&gt;&lt;a class="page-link" href="#"&gt;Previous&lt;/a&gt;&lt;/li&gt;
    &lt;li class="page-item"&gt;&lt;a class="page-link" href="#"&gt;1&lt;/a&gt;&lt;/li&gt;
    &lt;li class="page-item"&gt;&lt;a class="page-link" href="#"&gt;2&lt;/a&gt;&lt;/li&gt;
    &lt;li class="page-item"&gt;&lt;a class="page-link" href="#"&gt;3&lt;/a&gt;&lt;/li&gt;
    &lt;li class="page-item"&gt;&lt;a class="page-link" href="#"&gt;Next&lt;/a&gt;&lt;/li&gt;
  &lt;/ul&gt;
&lt;/nav&gt;
</code></pre>

<h4>Customization Options</h4>
<ul>
  <li><code>.pagination-lg</code> or <code>.pagination-sm</code> for size variations</li>
  <li><code>.disabled</code> and <code>.active</code> classes for state control</li>
</ul>

<h3>Breadcrumbs</h3>
<p>
  Breadcrumbs provide a trail for the user to navigate back to previously visited sections or higher levels in the hierarchy.
</p>

<pre><code>
&lt;nav aria-label="breadcrumb"&gt;
  &lt;ol class="breadcrumb"&gt;
    &lt;li class="breadcrumb-item"&gt;&lt;a href="#"&gt;Home&lt;/a&gt;&lt;/li&gt;
    &lt;li class="breadcrumb-item"&gt;&lt;a href="#"&gt;Library&lt;/a&gt;&lt;/li&gt;
    &lt;li class="breadcrumb-item active" aria-current="page"&gt;Data&lt;/li&gt;
  &lt;/ol&gt;
&lt;/nav&gt;
</code></pre>

<h4>Styling</h4>
<ul>
  <li>Uses ordered list <code>&lt;ol&gt;</code> with <code>.breadcrumb</code> class</li>
  <li>Each breadcrumb item is a list element with the <code>.breadcrumb-item</code> class</li>
  <li>The last item typically has <code>.active</code> and <code>aria-current="page"</code></li>
</ul>

<h3>Summary</h3>
<ul>
  <li>Use pagination to handle large datasets or multiple pages</li>
  <li>Use breadcrumbs to enhance navigation and user orientation</li>
  <li>Both components are highly customizable and responsive</li>
</ul>

## COLLAPSE AND ACCORDIONS

<p>
  Bootstrap offers interactive UI components like Collapse and Accordions that allow you to show or hide content dynamically. These components are especially useful for FAQs, toggle menus, and compact content displays.
</p>

<h3>Collapse</h3>
<p>
  The <code>.collapse</code> class is used to toggle visibility of content using JavaScript triggers.
</p>

<pre><code>
&lt;p&gt;
  &lt;a class="btn btn-primary" data-bs-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample"&gt;
    Toggle Content
  &lt;/a&gt;
&lt;/p&gt;
&lt;div class="collapse" id="collapseExample"&gt;
  &lt;div class="card card-body"&gt;
    This content is hidden by default and revealed when the button is clicked.
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Accordions</h3>
<p>
  Accordions are collections of collapsible items that work together so that only one item is shown at a time.
</p>

<pre><code>
&lt;div class="accordion" id="accordionExample"&gt;
  &lt;div class="accordion-item"&gt;
    &lt;h2 class="accordion-header" id="headingOne"&gt;
      &lt;button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne"&gt;
        Accordion Item #1
      &lt;/button&gt;
    &lt;/h2&gt;
    &lt;div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample"&gt;
      &lt;div class="accordion-body"&gt;
        This is the first item's accordion body.
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt>

  &lt;div class="accordion-item"&gt;
    &lt;h2 class="accordion-header" id="headingTwo"&gt;
      &lt;button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo"&gt;
        Accordion Item #2
      &lt;/button&gt;
    &lt;/h2&gt;
    &lt;div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample"&gt;
      &lt;div class="accordion-body"&gt;
        This is the second item's accordion body.
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h4>Key Notes</h4>
<ul>
  <li>Use <code>data-bs-toggle="collapse"</code> to link a trigger with a target element.</li>
  <li><code>.accordion</code> component controls the visibility of only one section at a time.</li>
  <li>Accessibility attributes like <code>aria-expanded</code> and <code>aria-controls</code> are important for screen readers.</li>
</ul>

<h3>Summary</h3>
<ul>
  <li><strong>Collapse:</strong> Great for toggling sections independently.</li>
  <li><strong>Accordion:</strong> Perfect for grouped, exclusive content sections.</li>
  <li>Both rely on Bootstrap JavaScript and data attributes for interactivity.</li>
</ul>

## SPINNERS AND LOADERS

<p>
  Bootstrap provides lightweight loading indicators—called <strong>spinners</strong>—to visually show that a process is ongoing or loading. These are customizable and can be used for buttons, sections, or entire pages.
</p>

<h3>Basic Spinner</h3>
<p>Use the <code>.spinner-border</code> class for a border-style spinner:</p>

<pre><code>
&lt;div class="spinner-border text-primary" role="status"&gt;
  &lt;span class="visually-hidden"&gt;Loading...&lt;/span&gt;
&lt;/div&gt;
</code></pre>

<h3>Growing Spinner</h3>
<p>The <code>.spinner-grow</code> class creates a growing-style spinner:</p>

<pre><code>
&lt;div class="spinner-grow text-success" role="status"&gt;
  &lt;span class="visually-hidden"&gt;Loading...&lt;/span&gt;
&lt;/div&gt;
</code></pre>

<h3>Color Variants</h3>
<p>Spinners support contextual color classes like:</p>
<ul>
  <li><code>.text-primary</code></li>
  <li><code>.text-secondary</code></li>
  <li><code>.text-success</code></li>
  <li><code>.text-danger</code></li>
  <li><code>.text-warning</code></li>
  <li><code>.text-info</code></li>
  <li><code>.text-light</code></li>
  <li><code>.text-dark</code></li>
</ul>

<h3>Spinners in Buttons</h3>
<p>Combine spinners with buttons to indicate loading states:</p>

<pre><code>
&lt;button class="btn btn-primary" type="button" disabled&gt;
  &lt;span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"&gt;&lt;/span&gt;
  Loading...
&lt;/button&gt;
</code></pre>

<h3>Accessibility</h3>
<ul>
  <li>Always use <code>&lt;span class="visually-hidden"&gt;Loading...&lt;/span&gt;</code> for screen readers.</li>
  <li>Spinners are purely visual, so provide textual fallback when needed.</li>
</ul>

<h3>Summary</h3>
<ul>
  <li><strong>spinner-border</strong> = circular outline spinner</li>
  <li><strong>spinner-grow</strong> = expanding spinner</li>
  <li>Customize size using <code>.spinner-border-sm</code></li>
  <li>Useful inside buttons, modals, or full screens</li>
</ul>

## PROGRESS BARS

<p>
  Bootstrap provides a flexible and customizable <strong>progress bar</strong> component to visually represent the progress of a task or process. These are often used in uploads, form completions, or loading sequences.
</p>

<h3>Basic Progress Bar</h3>
<p>Use the <code>.progress</code> container with <code>.progress-bar</code> inside:</p>

<pre><code>
&lt;div class="progress"&gt;
  &lt;div class="progress-bar" role="progressbar" style="width: 50%;" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"&gt;
    50%
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Colored Progress Bars</h3>
<p>Use contextual classes like:</p>
<ul>
  <li><code>.bg-success</code></li>
  <li><code>.bg-info</code></li>
  <li><code>.bg-warning</code></li>
  <li><code>.bg-danger</code></li>
</ul>

<pre><code>
&lt;div class="progress"&gt;
  &lt;div class="progress-bar bg-success" style="width: 75%;"&gt;75%&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>📐 Striped Progress Bar</h3>
<p>Add <code>.progress-bar-striped</code> for stripes:</p>

<pre><code>
&lt;div class="progress"&gt;
  &lt;div class="progress-bar progress-bar-striped" style="width: 60%;"&gt;60%&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Animated Stripes</h3>
<p>Add <code>.progress-bar-animated</code> to make stripes move:</p>

<pre><code>
&lt;div class="progress"&gt;
  &lt;div class="progress-bar progress-bar-striped progress-bar-animated bg-info" style="width: 80%;"&gt;80%&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Multiple Bars</h3>
<p>Place multiple <code>.progress-bar</code> elements inside a single <code>.progress</code>:</p>

<pre><code>
&lt;div class="progress"&gt;
  &lt;div class="progress-bar bg-success" style="width: 40%"&gt;40%&lt;/div&gt;
  &lt;div class="progress-bar bg-warning" style="width: 20%"&gt;20%&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Height Customization</h3>
<p>Control the height of the progress bar using inline style:</p>

<pre><code>
&lt;div class="progress" style="height: 30px;"&gt;
  &lt;div class="progress-bar" style="width: 70%;"&gt;70%&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li><strong>.progress</strong>: Container element</li>
  <li><strong>.progress-bar</strong>: Fills the bar</li>
  <li>Use <code>style="width: %"</code> to set progress</li>
  <li>Supports striping, animation, and color variations</li>
</ul>

## TYPOGRAPHY UTILITIES

<p>
  Bootstrap provides a rich set of typography utility classes that help you easily style and align text elements. These utilities are responsive, customizable, and essential for creating well-structured, readable content.
</p>

<h3>Font Size</h3>
<p>Use responsive font sizing with classes like:</p>
<ul>
  <li><code>.fs-1</code> (largest)</li>
  <li><code>.fs-2</code></li>
  <li><code>.fs-3</code></li>
  <li><code>.fs-4</code></li>
  <li><code>.fs-5</code></li>
  <li><code>.fs-6</code> (smallest)</li>
</ul>

<pre><code>
&lt;p class="fs-1"&gt;Huge Text&lt;/p&gt;
&lt;p class="fs-6"&gt;Tiny Text&lt;/p&gt;
</code></pre>

<h3>Font Weight and Style</h3>
<p>Control boldness and style using:</p>
<ul>
  <li><code>.fw-bold</code></li>
  <li><code>.fw-semibold</code></li>
  <li><code>.fw-normal</code></li>
  <li><code>.fw-light</code></li>
  <li><code>.fst-italic</code></li>
  <li><code>.fst-normal</code></li>
</ul>

<pre><code>
&lt;p class="fw-bold fst-italic"&gt;Bold and Italic Text&lt;/p&gt;
</code></pre>

<h3>Text Alignment</h3>
<ul>
  <li><code>.text-start</code></li>
  <li><code>.text-center</code></li>
  <li><code>.text-end</code></li>
</ul>

<pre><code>
&lt;p class="text-center"&gt;Centered Text&lt;/p&gt;
</code></pre>

<h3>Text Color and Background</h3>
<p>Use contextual classes like:</p>
<ul>
  <li><code>.text-primary</code></li>
  <li><code>.text-success</code></li>
  <li><code>.text-danger</code></li>
  <li><code>.bg-light</code>, <code>.bg-dark</code>, etc.</li>
</ul>

<pre><code>
&lt;p class="text-success bg-light"&gt;Success message!&lt;/p&gt;
</code></pre>

<h3>Text Transform</h3>
<ul>
  <li><code>.text-lowercase</code></li>
  <li><code>.text-uppercase</code></li>
  <li><code>.text-capitalize</code></li>
</ul>

<pre><code>
&lt;p class="text-uppercase"&gt;uppercase text&lt;/p&gt;
</code></pre>

<h3>Line Height and Truncation</h3>
<ul>
  <li><code>.lh-1</code>, <code>.lh-sm</code>, <code>.lh-base</code>, <code>.lh-lg</code></li>
  <li><code>.text-truncate</code> (for ellipsis)</li>
</ul>

<pre><code>
&lt;p class="lh-lg"&gt;This text has larger line height.&lt;/p&gt;
&lt;p class="text-truncate" style="max-width: 150px;"&gt;Very long text that will be truncated.&lt;/p&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li>Use <strong>.fs-*</strong> for font sizes</li>
  <li><strong>.fw-*</strong> and <strong>.fst-*</strong> for weight and style</li>
  <li><strong>.text-*</strong> for alignment, transform, and color</li>
  <li>Background and spacing classes enhance readability</li>
</ul>

## COLOR UTILITIES

<p>
  Bootstrap provides a wide range of color utility classes that let you quickly apply text, background, and border colors without writing custom CSS. These utilities follow Bootstrap’s design system, ensuring visual consistency across your project.
</p>

<h3>Text</h3>
<p>You can change text color using classes like:</p>
<ul>
  <li><code>.text-primary</code></li>
  <li><code>.text-secondary</code></li>
  <li><code>.text-success</code></li>
  <li><code>.text-danger</code></li>
  <li><code>.text-warning</code></li>
  <li><code>.text-info</code></li>
  <li><code>.text-light</code></li>
  <li><code>.text-dark</code></li>
  <li><code>.text-muted</code></li>
  <li><code>.text-white</code></li>
</ul>

<pre><code>
&lt;p class="text-success"&gt;Green success text&lt;/p&gt;
&lt;p class="text-danger"&gt;Red error text&lt;/p&gt;
</code></pre>

<h3>Background</h3>
<p>Background color classes work in a similar way:</p>
<ul>
  <li><code>.bg-primary</code></li>
  <li><code>.bg-secondary</code></li>
  <li><code>.bg-success</code></li>
  <li><code>.bg-danger</code></li>
  <li><code>.bg-warning</code></li>
  <li><code>.bg-info</code></li>
  <li><code>.bg-light</code></li>
  <li><code>.bg-dark</code></li>
  <li><code>.bg-white</code></li>
  <li><code>.bg-transparent</code></li>
</ul>

<pre><code>
&lt;div class="bg-warning text-dark p-3"&gt;Yellow background with dark text&lt;/div&gt;
</code></pre>

<h3>Borders</h3>
<p>You can apply color to borders with classes like:</p>
<ul>
  <li><code>.border</code> + <code>.border-primary</code></li>
  <li><code>.border-success</code>, <code>.border-danger</code>, etc.</li>
</ul>

<pre><code>
&lt;div class="border border-info p-2"&gt;Box with light blue border&lt;/div&gt;
</code></pre>

<h3>Customization</h3>
<p>You can combine these colors with other utilities like spacing and shadows to build visually appealing components:</p>

<pre><code>
&lt;div class="bg-primary text-white p-4 rounded shadow"&gt;
  Card with blue background and white text
&lt;/div&gt;
</code></pre>

<h3>Summary</h3>
<ul>
  <li>Use <code>.text-*</code> to change text color</li>
  <li>Use <code>.bg-*</code> to set background color</li>
  <li>Use <code>.border-*</code> for colored borders</li>
  <li>Classes are responsive and follow the Bootstrap theme</li>
</ul>

## SPACING (MARGINS & PADDINGS)

<p>
  Bootstrap includes a powerful spacing utility system for managing margins (<code>m</code>) and paddings (<code>p</code>) on all sides of an element. This system follows a scale from <code>0</code> to <code>5</code> (and sometimes auto), allowing precise control over layout spacing.
</p>

<h3>Syntax</h3>
<p>
  The general syntax for spacing classes is:
</p>
<pre><code>
{property}{side}-{breakpoint?}-{size}
</code></pre>

<ul>
  <li><strong>Property:</strong> <code>m</code> (margin), <code>p</code> (padding)</li>
  <li><strong>Side:</strong> <code>t</code> (top), <code>b</code> (bottom), <code>s</code> (start/left), <code>e</code> (end/right), <code>x</code> (left & right), <code>y</code> (top & bottom), blank (all sides)</li>
  <li><strong>Breakpoint (optional):</strong> e.g., <code>sm</code>, <code>md</code></li>
  <li><strong>Size:</strong> <code>0</code> to <code>5</code>, or <code>auto</code> for margin</li>
</ul>

<h3>Examples</h3>

<pre><code>
&lt;div class="m-3"&gt;Margin on all sides&lt;/div&gt;
&lt;div class="pt-4"&gt;Padding on top&lt;/div&gt;
&lt;div class="mx-auto"&gt;Horizontal margin auto (centered)&lt;/div&gt;
&lt;div class="p-0"&gt;No padding&lt;/div&gt;
</code></pre>

<h3>Notes</h3>
<ul>
  <li>All classes are mobile-first and responsive-friendly</li>
  <li>Combine with flex and grid utilities to build layout spacing easily</li>
  <li>Spacing scale represents multiples of <code>.25rem</code> (e.g., <code>m-1</code> = <code>.25rem</code>)</li>
</ul>

<h3>Summary</h3>
<ul>
  <li><code>.m*</code> and <code>.p*</code> handle margins and paddings</li>
  <li>Use directional classes like <code>.mt-3</code>, <code>.px-2</code>, etc.</li>
  <li>Responsive spacing can be set using breakpoints (e.g., <code>.mb-md-5</code>)</li>
  <li><code>auto</code> is only valid for margins</li>
</ul>

## BORDERS, SHADOWS, AND RADIUS

<p>
  Bootstrap provides utility classes to style borders, apply shadows, and control border-radius on elements, helping developers create sleek and modern UI components.
</p>

<h3>Border Utilities</h3>
<p>
  Add or remove borders using simple utility classes.
</p>

<pre><code>
&lt;div class="border"&gt;All borders&lt;/div&gt;
&lt;div class="border-top"&gt;Top border only&lt;/div&gt;
&lt;div class="border-0"&gt;No border&lt;/div&gt;
&lt;div class="border-primary"&gt;Primary colored border&lt;/div&gt;
</code></pre>

<h4>Available Classes:</h4>
<ul>
  <li><code>.border</code>, <code>.border-top</code>, <code>.border-end</code>, <code>.border-bottom</code>, <code>.border-start</code></li>
  <li><code>.border-0</code>, <code>.border-top-0</code>, etc. for removing specific borders</li>
  <li>Color variants: <code>.border-primary</code>, <code>.border-success</code>, <code>.border-danger</code>, etc.</li>
  <li>Width variants: <code>.border-1</code> to <code>.border-5</code></li>
</ul>

<h3>Shadow Utilities</h3>
<p>
  Apply shadow effects for depth and emphasis.
</p>

<pre><code>
&lt;div class="shadow-none"&gt;No shadow&lt;/div&gt;
&lt;div class="shadow-sm"&gt;Small shadow&lt;/div&gt;
&lt;div class="shadow"&gt;Regular shadow&lt;/div&gt;
&lt;div class="shadow-lg"&gt;Large shadow&lt;/div&gt;
</code></pre>

<h3>Border Radius (Rounded Corners)</h3>
<p>
  Create rounded corners with predefined radius classes.
</p>

<pre><code>
&lt;div class="rounded"&gt;Slightly rounded corners&lt;/div&gt;
&lt;div class="rounded-circle"&gt;Perfect circle (for equal width and height)&lt;/div&gt;
&lt;div class="rounded-pill"&gt;Pill-shaped corners&lt;/div&gt;
&lt;div class="rounded-0"&gt;No rounding&lt;/div&gt;
</code></pre>

<h4>Directional Radius Classes:</h4>
<ul>
  <li><code>.rounded-top</code>, <code>.rounded-end</code>, <code>.rounded-bottom</code>, <code>.rounded-start</code></li>
</ul>

<h3>Summary</h3>
<ul>
  <li>Use <code>.border</code> classes to control visibility, color, and width</li>
  <li>Use <code>.shadow</code> classes to add elevation effects</li>
  <li>Use <code>.rounded</code> classes to apply different levels and directions of border-radius</li>
</ul>

## DISPLAY AND VISIBILITY UTILITIES

<p>
  Bootstrap offers a powerful set of utility classes to control how elements are displayed and whether they are visible or hidden — all without writing custom CSS.
</p>

<h3>Display Classes</h3>
<p>
  Use the <code>.d-*</code> classes to control an element’s display property.
</p>

<pre><code>
&lt;div class="d-none"&gt;Hidden&lt;/div&gt;
&lt;div class="d-block"&gt;Displayed as block&lt;/div&gt;
&lt;div class="d-inline"&gt;Displayed inline&lt;/div&gt;
&lt;div class="d-inline-block"&gt;Displayed as inline-block&lt;/div&gt;
</code></pre>

<h4>Responsive Display Variants:</h4>
<p>
  You can combine display classes with breakpoints:
</p>

<pre><code>
&lt;div class="d-none d-md-block"&gt;Hidden on small, visible on medium and up&lt;/div&gt;
&lt;div class="d-sm-inline d-lg-none"&gt;Inline on small, hidden on large and up&lt;/div&gt;
</code></pre>

<h3>Visibility Classes</h3>
<p>
  Use visibility utilities to toggle the visibility of elements without changing the layout (unlike display).
</p>

<pre><code>
&lt;div class="visible"&gt;Visible (default)&lt;/div&gt;
&lt;div class="invisible"&gt;Invisible but still takes up space&lt;/div&gt;
</code></pre>

<h3>Utility for Responsive Visibility</h3>
<p>
  You can also use the combination of display and visibility classes to handle responsiveness and hide/show content depending on the screen size.
</p>

<h3>Summary</h3>
<ul>
  <li><code>.d-none</code>, <code>.d-block</code>, <code>.d-flex</code>, etc., control layout display</li>
  <li>Combine with breakpoints: <code>.d-md-none</code>, <code>.d-lg-block</code>, etc.</li>
  <li><code>.invisible</code> hides elements visually but keeps layout space</li>
  <li>Ideal for responsive designs and toggling UI elements dynamically</li>
</ul>

## RESPONSIVE UTILITIES

<p>
  Bootstrap’s responsive utilities provide powerful tools to show or hide content depending on the screen size. These classes are essential for building mobile-first, responsive layouts.
</p>

<h3>Responsive Display Classes</h3>
<p>
  Use classes like <code>.d-none</code>, <code>.d-sm-block</code>, <code>.d-md-inline</code>, etc., to change how elements appear at specific breakpoints.
</p>

<pre><code>
&lt;div class="d-none d-md-block"&gt;Visible on medium and larger screens&lt;/div&gt;
&lt;div class="d-sm-none d-lg-block"&gt;Hidden on small, visible on large&lt;/div&gt;
</code></pre>

<h3>Breakpoint Options</h3>
<ul>
  <li><code>sm</code> — ≥576px</li>
  <li><code>md</code> — ≥768px</li>
  <li><code>lg</code> — ≥992px</li>
  <li><code>xl</code> — ≥1200px</li>
  <li><code>xxl</code> — ≥1400px</li>
</ul>

<h3>Visibility vs Display</h3>
<p>
  Remember: <code>.invisible</code> hides elements visually but keeps layout space. <code>.d-none</code> removes the element from layout entirely.
</p>

<h3>Use Cases</h3>
<ul>
  <li>Show mobile-only or desktop-only content</li>
  <li>Toggle layout components responsively</li>
  <li>Enhance UX across screen sizes</li>
</ul>

<p>
  Combine with other utilities like spacing, borders, and flexbox to create adaptive, user-friendly designs.
</p>

## CUSTOMIZING BOOTSTRAP WITH SASS

<p>
  Bootstrap is built with Sass, a powerful CSS preprocessor that allows you to customize Bootstrap's styles by modifying its variables, using mixins, functions, and more.
</p>

<h3>Setting Up Bootstrap with Sass</h3>
<p>To start customizing Bootstrap with Sass, you need a Sass environment (like Vite, Webpack, or Laravel Mix):</p>

<pre><code>
// Install Bootstrap and Sass via npm
npm install bootstrap sass
</code></pre>

<h3>Import Only What You Need</h3>
<p>
  Instead of importing the full Bootstrap CSS, import just the parts you want in your <code>custom.scss</code> file:
</p>

<pre><code>
// custom.scss
@import "node_modules/bootstrap/scss/functions";
@import "node_modules/bootstrap/scss/variables";
@import "node_modules/bootstrap/scss/mixins";

// Import selected components
@import "node_modules/bootstrap/scss/root";
@import "node_modules/bootstrap/scss/reboot";
@import "node_modules/bootstrap/scss/buttons";
@import "node_modules/bootstrap/scss/utilities";
</code></pre>

<h3>Customizing Variables</h3>
<p>
  Override Bootstrap's default Sass variables <strong>before</strong> importing Bootstrap’s Sass files:
</p>

<pre><code>
// custom.scss
$primary: #6f42c1;
$font-family-base: 'Segoe UI', sans-serif;

@import "bootstrap";
</code></pre>

<h3>Why Customize with Sass?</h3>
<ul>
  <li>Define your own color palette</li>
  <li>Set custom breakpoints, spacing, shadows, and more</li>
  <li>Reduce CSS size by only importing what you need</li>
</ul>

<h3>Rebuilding Bootstrap</h3>
<p>
  After modifying your Sass files, compile them to CSS using a Sass compiler:
</p>

<pre><code>
sass custom.scss custom.css
</code></pre>

<p>
  Using Sass with Bootstrap gives you full control over the design system, enabling more maintainable and scalable front-end development.
</p>

## USING BOOTSTRAP ICONS

<p>
  <strong>Bootstrap Icons</strong> is a free, open-source icon library officially maintained by the Bootstrap team. It provides over 1,800 scalable vector icons that are easy to use with Bootstrap components.
</p>

<h3>📦 Installing Bootstrap Icons</h3>

<p>You can include Bootstrap Icons in your project via CDN or by installing them locally using npm:</p>

<h4>🔗 CDN</h4>
<pre><code>&lt;link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css"&gt;</code></pre>

<h4>📥 NPM</h4>
<pre><code>npm install bootstrap-icons</code></pre>

<p>Then, include it in your CSS or JS entry file:</p>
<pre><code>@import "bootstrap-icons/font/bootstrap-icons.css";</code></pre>

<h3>🔧 Using Icons in HTML</h3>

<p>To use an icon, simply add the <code>bi</code> class and the specific icon name class to an inline element like <code>&lt;i&gt;</code> or <code>&lt;span&gt;</code>:</p>

<pre><code>&lt;i class="bi bi-alarm"&gt;&lt;/i&gt;
&lt;span class="bi bi-heart-fill"&gt;&lt;/span&gt;
</code></pre>

<h3>🎨 Styling Icons</h3>
<ul>
  <li>Change size with Bootstrap’s utility classes: <code>.fs-1</code>, <code>.fs-2</code>, etc.</li>
  <li>Change color with <code>.text-primary</code>, <code>.text-danger</code>, etc.</li>
</ul>

<pre><code>&lt;i class="bi bi-battery-full fs-3 text-success"&gt;&lt;/i&gt;</code></pre>

<h3>📚 Icon Library Reference</h3>
<p>Browse the full list of icons at <a href="https://icons.getbootstrap.com/" target="_blank">icons.getbootstrap.com</a>.</p>

<p>
  Bootstrap Icons make it quick and easy to add professional vector graphics to your UI without relying on external image files or SVGs.
</p>

## BUILDING RESPONSIVE LAYOUTS

<p>
  One of Bootstrap’s greatest strengths is its powerful grid system and utility classes that make building responsive layouts both intuitive and flexible. With just a few lines of code, you can create interfaces that look great on any screen size — from mobile devices to large desktops.
</p>

<h3>Responsive Grid System</h3>

<p>
  Bootstrap’s grid is based on a 12-column layout with five default breakpoints: <code>xs</code>, <code>sm</code>, <code>md</code>, <code>lg</code>, and <code>xl</code>. You can combine these classes to create dynamic and adaptable layouts.
</p>

<pre><code>
&lt;div class="container"&gt;
  &lt;div class="row"&gt;
    &lt;div class="col-12 col-md-6 col-lg-4"&gt;Column 1&lt;/div&gt;
    &lt;div class="col-12 col-md-6 col-lg-4"&gt;Column 2&lt;/div&gt;
    &lt;div class="col-12 col-lg-4"&gt;Column 3&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Containers and Rows</h3>

<ul>
  <li><code>.container</code>: Provides a fixed-width responsive container.</li>
  <li><code>.container-fluid</code>: Expands to 100% of the width of the viewport.</li>
  <li><code>.row</code>: Wrapper for columns with automatic negative margins for spacing.</li>
</ul>

<h3>Responsive Classes</h3>

<p>
  Bootstrap includes a variety of responsive utility classes for visibility, spacing, alignment, flex behaviors, and more. These can adapt elements' behavior based on screen size.
</p>

<pre><code>
&lt;div class="d-none d-md-block"&gt;Visible on md and larger screens&lt;/div&gt;
&lt;div class="text-center text-lg-start"&gt;Text alignment changes with screen size&lt;/div&gt;
</code></pre>

<h3>Mobile-First Approach</h3>

<p>
  Bootstrap is designed with a mobile-first philosophy, meaning styles are applied first to smaller devices and scale up as needed.
</p>

<h3>Combining Layout Components</h3>

<p>
  You can combine rows, columns, cards, navbars, and modals to construct complete pages that scale beautifully across all devices. Try nesting rows, adjusting breakpoints, and mixing grid sizes to suit your design.
</p>

<p>
  With a few utility classes and a solid understanding of the grid, you’ll be able to build any responsive layout you need.
</p>

## CENTERING CONTENT

<p>
  Centering elements is a common requirement in web design, and Bootstrap provides several utilities to make this task straightforward—whether you're centering text, blocks, or entire sections both vertically and horizontally.
</p>

<h3>Centering Text Horizontally</h3>

<p>Use the <code>.text-center</code> class to horizontally align text:</p>

<pre><code>&lt;div class="text-center"&gt;
  This text is centered horizontally.
&lt;/div&gt;
</code></pre>

<h3>Centering Block Elements Horizontally</h3>

<p>To center block-level elements, use the combination of <code>mx-auto</code> and a defined width (or <code>col-*</code> in the grid):</p>

<pre><code>&lt;div class="w-50 mx-auto"&gt;
  This block is horizontally centered.
&lt;/div&gt;
</code></pre>

<h3>Centering Vertically with Flexbox</h3>

<p>
  For vertical alignment, Bootstrap uses Flexbox utilities. Use <code>d-flex</code>, <code>align-items-center</code>, and <code>justify-content-center</code>:
</p>

<pre><code>&lt;div class="d-flex align-items-center justify-content-center" style="height: 200px;"&gt;
  &lt;div&gt;Centered both vertically and horizontally&lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Centering in Grid Layouts</h3>

<p>Use Bootstrap's grid system to center columns with auto margins:</p>

<pre><code>&lt;div class="row"&gt;
  &lt;div class="col-6 mx-auto"&gt;
    This column is centered.
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Text and Content Alignment Utilities</h3>

<ul>
  <li><code>.text-start</code>, <code>.text-center</code>, <code>.text-end</code> for horizontal text alignment.</li>
  <li><code>.justify-content-</code> and <code>.align-items-</code> for Flexbox containers.</li>
  <li><code>.mx-auto</code> and <code>.my-auto</code> for margin-based centering.</li>
</ul>

<p>
  Whether you are working on small components or full-page layouts, Bootstrap's centering utilities allow you to position content easily and responsively.
</p>

## FIXED FOOTERS AND STICKY ELEMENTS


<p>
  Bootstrap provides utility classes and layout strategies to help you create fixed footers and sticky elements that remain visible while scrolling. These features are useful for navigation bars, action buttons, footers, and more.
</p>

<h3>Fixed Footer</h3>

<p>
  To keep a footer fixed at the bottom of the viewport, use the <code>fixed-bottom</code> class:
</p>

<pre><code>&lt;footer class="bg-dark text-white text-center py-3 fixed-bottom"&gt;
  This is a fixed footer.
&lt;/footer&gt;
</code></pre>

<p>
  Make sure that your page content doesn't overlap with the fixed footer. Add bottom padding to the main content if necessary.
</p>

<h3>Sticky Top Element</h3>

<p>
  To make an element stay at the top of the page when scrolling, use the <code>sticky-top</code> class:
</p>

<pre><code>&lt;div class="sticky-top bg-warning p-3"&gt;
  I stick to the top when you scroll!
&lt;/div&gt;
</code></pre>

<h3>Sticky Sidebar or Section</h3>

<p>
  You can also apply <code>position: sticky</code> to other elements like sidebars:
</p>

<pre><code>&lt;aside class="position-sticky top-0" style="height: 100vh;"&gt;
  &lt;!-- Sidebar content --&gt;
&lt;/aside&gt;
</code></pre>

<p>
  Sticky elements require a parent with relative or static positioning and sufficient height to allow scrolling behavior.
</p>

<h3>Additional Tips</h3>

<ul>
  <li>Use utility classes like <code>.top-0</code>, <code>.bottom-0</code>, <code>.start-0</code>, and <code>.end-0</code> for precise placement.</li>
  <li>Combine <code>position-fixed</code> with <code>z-index</code> utilities to control layering.</li>
  <li>For mobile responsiveness, test sticky and fixed elements in different viewports.</li>
</ul>

<p>
  These layout tools improve navigation and accessibility by keeping essential elements visible as users interact with your page.
</p>

## OFFCANVAS AND SIDEBARS

<p>
  The <strong>Offcanvas</strong> component in Bootstrap allows you to create hidden panels (like sidebars or menus) that slide into view from the side of the screen. It's a powerful tool for responsive and mobile-friendly UI design.
</p>

<h3>Basic Offcanvas Example</h3>

<p>Here’s how to create a simple offcanvas sidebar that opens from the left:</p>

<pre><code>&lt;button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasExample"&gt;
  Open Sidebar
&lt;/button&gt;

&lt;div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasExample" aria-labelledby="offcanvasExampleLabel"&gt;
  &lt;div class="offcanvas-header"&gt;
    &lt;h5 class="offcanvas-title" id="offcanvasExampleLabel"&gt;Sidebar Menu&lt;/h5&gt;
    &lt;button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"&gt;&lt;/button&gt;
  &lt;/div&gt;
  &lt;div class="offcanvas-body"&gt;
    &lt;p&gt;You can place navigation links or additional content here.&lt;/p&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Offcanvas Positioning</h3>

<ul>
  <li><code>.offcanvas-start</code> – slides in from the left (default)</li>
  <li><code>.offcanvas-end</code> – slides in from the right</li>
  <li><code>.offcanvas-top</code> – slides down from the top</li>
  <li><code>.offcanvas-bottom</code> – slides up from the bottom</li>
</ul>

<h3>Customization Tips</h3>

<ul>
  <li>Use utility classes like <code>bg-dark</code>, <code>text-light</code>, <code>p-4</code> to style your offcanvas content.</li>
  <li>Control width and height using custom CSS or Bootstrap’s sizing utilities.</li>
  <li>Combine offcanvas with navigation menus for responsive mobile views.</li>
</ul>

<h3>When to Use Offcanvas</h3>

<ul>
  <li>Mobile navigation menus</li>
  <li>Filters and search panels</li>
  <li>Account or user profile settings</li>
  <li>Custom slide-in forms</li>
</ul>

<p>
  Bootstrap's offcanvas component is built with accessibility and responsiveness in mind, making it a great tool for modern interface design.
</p>

## USING BOOTSTRAP JAVASCRIPT COMPONENTS

<p>
  Bootstrap includes a suite of powerful JavaScript components to enhance interactivity and user experience. These components are built using modern JavaScript and can be easily integrated without needing external libraries like jQuery (from Bootstrap 5 onward).
</p>

<h3>How to Use</h3>
<p>
  To use Bootstrap JS components, make sure you’ve included the Bootstrap JavaScript file either via CDN or your local setup:
</p>

<pre><code>&lt;script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"&gt;&lt;/script&gt;
</code></pre>

<p>
  Alternatively, if you're using a bundler like Vite, Webpack, or Laravel Mix, you can import only the components you need.
</p>

<h3>Common JavaScript Components</h3>
<ul>
  <li><strong>Modal</strong> – Pop-up overlays for dialogs and content.</li>
  <li><strong>Tooltip</strong> – Small hover-based informational boxes.</li>
  <li><strong>Popover</strong> – Similar to tooltips but with more content.</li>
  <li><strong>Toast</strong> – Lightweight notifications that slide into view.</li>
  <li><strong>Collapse</strong> – Toggle visibility of content sections.</li>
  <li><strong>Dropdown</strong> – Menus for navigation or actions.</li>
  <li><strong>Carousel</strong> – Slideshows for images or custom content.</li>
  <li><strong>Scrollspy</strong> – Automatically update navs based on scroll position.</li>
</ul>

<h3>Example: Modal</h3>

<pre><code>&lt;!-- Button to trigger --&gt;
&lt;button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal"&gt;
  Launch Modal
&lt;/button&gt;

&lt;!-- Modal HTML --&gt;
&lt;div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"&gt;
  &lt;div class="modal-dialog"&gt;
    &lt;div class="modal-content"&gt;
      &lt;div class="modal-header"&gt;
        &lt;h5 class="modal-title" id="exampleModalLabel"&gt;Modal Title&lt;/h5&gt;
        &lt;button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"&gt;&lt;/button&gt;
      &lt;/div&gt;
      &lt;div class="modal-body"&gt;
        This is the modal body content.
      &lt;/div&gt;
      &lt;div class="modal-footer"&gt;
        &lt;button type="button" class="btn btn-secondary" data-bs-dismiss="modal"&gt;Close&lt;/button&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<h3>Tips</h3>
<ul>
  <li>Use <code>data-bs-toggle</code> and <code>data-bs-target</code> attributes for declarative control.</li>
  <li>For more control, use JavaScript API methods like <code>Modal.show()</code> or <code>Tooltip.enable()</code>.</li>
  <li>Most components emit events like <code>shown.bs.modal</code> and <code>hidden.bs.toast</code> for custom scripting.</li>
</ul>

<p>
  Bootstrap’s JavaScript components are designed for flexibility, modularity, and accessibility, providing essential functionality without heavy scripting.
</p>

## TOOLTIPS, TOASTS, AND CAROUSELS

<p>
  Bootstrap offers dynamic UI components such as tooltips, toasts, and carousels, which enhance user interaction with subtle yet effective visual feedback. Each one can be initialized via data attributes or JavaScript.
</p>

<h3>Tooltips</h3>
<p>
  Tooltips are small, hover-activated text popups commonly used to describe a UI element.
</p>

<pre><code>&lt;button type="button" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="top" title="Tooltip text"&gt;
  Hover me
&lt;/button&gt;

&lt;script&gt;
  // Initialize all tooltips on the page
  const tooltipTriggerList = document.querySelectorAll('[data-bs-toggle="tooltip"]')
  const tooltipList = [...tooltipTriggerList].map(tooltipTriggerEl =&gt; new bootstrap.Tooltip(tooltipTriggerEl))
&lt;/script&gt;
</code></pre>

<h3>Toasts</h3>
<p>
  Toasts are lightweight notifications that slide into view. They’re perfect for non-intrusive feedback.
</p>

<pre><code>&lt;div class="toast show" role="alert" aria-live="assertive" aria-atomic="true"&gt;
  &lt;div class="toast-header"&gt;
    &lt;strong class="me-auto"&gt;Bootstrap&lt;/strong&gt;
    &lt;small&gt;Just now&lt;/small&gt;
    &lt;button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"&gt;&lt;/button&gt;
  &lt;/div&gt;
  &lt;div class="toast-body"&gt;
    Hello, this is a toast message!
  &lt;/div&gt;
&lt;/div&gt;

&lt;script&gt;
  // Optionally initialize manually
  const toastEl = document.querySelector('.toast');
  const toast = new bootstrap.Toast(toastEl);
  toast.show();
&lt;/script&gt;
</code></pre>

<h3>Carousels</h3>
<p>
  Carousels are useful for showcasing images, content sliders, or highlights.
</p>

<pre><code>&lt;div id="carouselExample" class="carousel slide" data-bs-ride="carousel"&gt;
  &lt;div class="carousel-inner"&gt;
    &lt;div class="carousel-item active"&gt;
      &lt;img src="img1.jpg" class="d-block w-100" alt="..."&gt;
    &lt;/div&gt;
    &lt;div class="carousel-item"&gt;
      &lt;img src="img2.jpg" class="d-block w-100" alt="..."&gt;
    &lt;/div&gt;
    &lt;div class="carousel-item"&gt;
      &lt;img src="img3.jpg" class="d-block w-100" alt="..."&gt;
    &lt;/div&gt;
  &lt;/div&gt;
  &lt;button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev"&gt;
    &lt;span class="carousel-control-prev-icon" aria-hidden="true"&gt;&lt;/span&gt;
    &lt;span class="visually-hidden"&gt;Previous&lt;/span&gt;
  &lt;/button&gt;
  &lt;button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next"&gt;
    &lt;span class="carousel-control-next-icon" aria-hidden="true"&gt;&lt;/span&gt;
    &lt;span class="visually-hidden"&gt;Next&lt;/span&gt;
  &lt;/button&gt;
&lt;/div&gt;
</code></pre>

<p>
  These components add a polished and modern layer to your web interface and are fully customizable through Bootstrap's API and classes.
</p>

## DROPDOWNS AND COLLAPSIBLES

<p>
  Bootstrap provides interactive elements like <strong>dropdowns</strong> and <strong>collapsibles</strong> to create dynamic and user-friendly interfaces without requiring external JavaScript libraries.
</p>

<h3>Dropdowns</h3>
<p>
  Dropdowns are toggleable menus used for navigation or to group actions in a compact way.
</p>

<pre><code>&lt;div class="dropdown"&gt;
  &lt;button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-bs-toggle="dropdown" aria-expanded="false"&gt;
    Dropdown button
  &lt;/button&gt;
  &lt;ul class="dropdown-menu" aria-labelledby="dropdownMenuButton"&gt;
    &lt;li&gt;&lt;a class="dropdown-item" href="#"&gt;Action&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a class="dropdown-item" href="#"&gt;Another action&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a class="dropdown-item" href="#"&gt;Something else here&lt;/a&gt;&lt;/li&gt;
  &lt;/ul&gt;
&lt;/div&gt;
</code></pre>

<p>
  You can align the dropdown menu, add headers, dividers, and make it responsive using utility classes.
</p>

<h3>Collapsibles</h3>
<p>
  Collapsibles allow you to hide and show content using a simple toggle. Ideal for FAQs, expandable panels, or minimizing clutter.
</p>

<pre><code>&lt;p&gt;
  &lt;a class="btn btn-primary" data-bs-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample"&gt;
    Toggle Collapse
  &lt;/a&gt;
&lt;/p&gt;
&lt;div class="collapse" id="collapseExample"&gt;
  &lt;div class="card card-body"&gt;
    This content is hidden by default and shown when triggered.
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<p>
  Bootstrap’s collapse feature can also be used with navigation menus, accordions, and more. You can control its behavior programmatically using the <code>Collapse</code> JavaScript API.
</p>

## DATA ATTRIBUTES VS MANUAL INIT

<p>
  Bootstrap provides two main ways to activate its JavaScript-powered components: using <strong>data attributes</strong> or initializing them <strong>manually with JavaScript</strong>. Both approaches achieve the same effect, but choosing one depends on your project complexity and control needs.
</p>

<h3>Using Data Attributes</h3>
<p>
  The easiest and most declarative way to use Bootstrap components. You add special <code>data-bs-*</code> attributes directly in your HTML.
</p>

<pre><code>&lt;button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal"&gt;
  Launch Modal
&lt;/button&gt;
</code></pre>

<p>
  This automatically enables the component without any JavaScript. It's simple and ideal for basic UI elements.
</p>

<h3>Manual Initialization with JavaScript</h3>
<p>
  For dynamic or more complex behavior, you can manually initialize components via JavaScript. This provides greater control and customization.
</p>

<pre><code>&lt;button id="modalBtn" class="btn btn-primary"&gt;Open Modal&lt;/button&gt;

&lt;script&gt;
  const modalElement = document.getElementById('exampleModal');
  const modal = new bootstrap.Modal(modalElement);
  document.getElementById('modalBtn').addEventListener('click', () =&gt; {
    modal.show();
  });
&lt;/script&gt;
</code></pre>

<h3>When to Use Each</h3>
<ul>
  <li><strong>Data attributes:</strong> Great for simple, static pages or quick prototyping.</li>
  <li><strong>Manual init:</strong> Ideal when components are created dynamically, require event listeners, or need conditional logic.</li>
</ul>

<p>
  You can even combine both methods, though it's usually better to stick with one for consistency.
</p>

## HANDLING MODALS PROGRAMMATICALLY

<p>
  Bootstrap allows you to control modals not only through data attributes but also programmatically using JavaScript. This is especially useful when you need to show, hide, or toggle a modal based on specific logic or events in your application.
</p>

<h3>Showing a Modal with JavaScript</h3>
<pre><code>&lt;button id="openModalBtn" class="btn btn-primary"&gt;Open Modal&lt;/button&gt;

&lt;div class="modal fade" id="myModal" tabindex="-1" aria-hidden="true"&gt;
  &lt;div class="modal-dialog"&gt;
    &lt;div class="modal-content"&gt;
      &lt;div class="modal-header"&gt;
        &lt;h5 class="modal-title"&gt;Modal Title&lt;/h5&gt;
        &lt;button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"&gt;&lt;/button&gt;
      &lt;/div&gt;
      &lt;div class="modal-body"&gt;
        This modal was opened programmatically!
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;

&lt;script&gt;
  const modalElement = document.getElementById('myModal');
  const modalInstance = new bootstrap.Modal(modalElement);
  
  document.getElementById('openModalBtn').addEventListener('click', () =&gt; {
    modalInstance.show();
  });
&lt;/script&gt;
</code></pre>

<h3>Hiding a Modal</h3>
<pre><code>modalInstance.hide();</code></pre>

<h3>Toggling a Modal</h3>
<p>
  Bootstrap doesn't provide a native <code>toggle()</code> method for modals, so you need to manage the state manually:
</p>
<pre><code>
if (modalElement.classList.contains('show')) {
  modalInstance.hide();
} else {
  modalInstance.show();
}
</code></pre>

<h3>Listening to Modal Events</h3>
<p>
  You can hook into modal lifecycle events to run custom logic:
</p>
<pre><code>
modalElement.addEventListener('show.bs.modal', () =&gt; {
  console.log('Modal is about to be shown');
});

modalElement.addEventListener('hidden.bs.modal', () =&gt; {
  console.log('Modal was hidden');
});
</code></pre>

<p>
  Programmatically managing modals gives you full control over the user experience, making your application more dynamic and responsive to user actions.
</p>

## THEME CUSTOMIZATION WITH SASS VARIABLES

<p>
  Bootstrap was built with Sass, which makes it extremely customizable. Instead of overwriting classes with additional CSS, you can modify Bootstrap’s core design system by redefining its Sass variables before compiling.
</p>

<h3>Why Use Sass Variables?</h3>
<ul>
  <li>Change colors, spacings, fonts, and more without writing additional CSS.</li>
  <li>Maintain consistency across components.</li>
  <li>Easily adapt Bootstrap to your brand’s visual identity.</li>
</ul>

<h3>Sass Files Structure (Example)</h3>
<pre><code>
/custom-bootstrap/
├── scss/
│   ├── _custom-variables.scss   // Your overrides go here
│   └── custom-bootstrap.scss    // Main Sass entry file
</code></pre>

<h3>Example of Overriding Variables</h3>
<p>Create a file like <code>_custom-variables.scss</code>:</p>
<pre><code>
// Change the primary color
$primary: #ff5722;

// Change font family
$font-family-base: 'Poppins', sans-serif;

// Spacing scale
$spacer: 1rem;
</code></pre>

<h3>Main SCSS File (custom-bootstrap.scss)</h3>
<p>Import Bootstrap’s source files after your custom variables:</p>
<pre><code>
// Override variables first
@import 'custom-variables';

// Then import Bootstrap
@import '~bootstrap/scss/bootstrap';
</code></pre>

<h3>Compiling with a Tool (e.g., Vite, Webpack, Laravel Mix)</h3>
<p>You’ll need a Sass compiler to generate the final CSS. Example with <code>npm</code>:</p>
<pre><code>npm install sass bootstrap</code></pre>

<p>Then compile:</p>
<pre><code>sass scss/custom-bootstrap.scss css/bootstrap-custom.css</code></pre>

<h3>Tips</h3>
<ul>
  <li>Refer to <code>_variables.scss</code> in Bootstrap’s source to see all customizable options.</li>
  <li>Only import what you need using partials like <code>_buttons.scss</code> or <code>_navbar.scss</code>.</li>
</ul>

<p>
  Customizing Bootstrap with Sass variables allows you to create a unique design system that stays consistent, clean, and maintainable without relying heavily on custom CSS overrides.
</p>

## CREATING A CUSTOM THEME

<p>
  Creating a custom Bootstrap theme involves modifying the default design tokens (Sass variables), importing only the components you need, and compiling everything into your own stylesheet. This gives you full control over the look and feel of your application while maintaining the consistency and responsiveness of Bootstrap.
</p>

<h3>Steps to Create a Custom Theme</h3>

<ol>
  <li>
    <strong>Install Bootstrap via NPM</strong><br>
    <code>npm install bootstrap</code><br>
    Or use <code>yarn add bootstrap</code>.
  </li>

  <li>
    <strong>Create a Custom SCSS File</strong><br>
    Create a file named <code>custom.scss</code> in your project:
<pre><code>// 1. Override Bootstrap default variables before importing
$primary: #ff6600;
$font-family-base: 'Poppins', sans-serif;
$body-bg: #fefefe;
$border-radius: .75rem;

// 2. Optionally import only the components you use
@import "node_modules/bootstrap/scss/functions";
@import "node_modules/bootstrap/scss/variables";
@import "node_modules/bootstrap/scss/mixins";
@import "node_modules/bootstrap/scss/reboot";
@import "node_modules/bootstrap/scss/buttons";
@import "node_modules/bootstrap/scss/cards";
// Or import the full Bootstrap framework:
@import "node_modules/bootstrap/scss/bootstrap";
</code></pre>
  </li>

  <li>
    <strong>Compile Your SCSS</strong><br>
    Use a compiler like <code>sass</code>, <code>webpack</code>, <code>Vite</code>, or <code>Laravel Mix</code> to convert SCSS to CSS:
    <br>
    <code>sass custom.scss custom.css</code>
  </li>

  <li>
    <strong>Link Your Custom CSS in HTML</strong><br>
<pre><code>&lt;link href="path/to/custom.css" rel="stylesheet"&gt;
</code></pre>
  </li>
</ol>

<h3>Folder Example</h3>
<pre><code>project/
├── scss/
│   └── custom.scss
├── css/
│   └── custom.css
├── index.html
</code></pre>

<h3>Tips for Theming</h3>
<ul>
  <li>Start by changing primary colors and fonts for the fastest brand adaptation.</li>
  <li>Use the <code>:root</code> selector with CSS variables if you plan to swap themes dynamically.</li>
  <li>Always keep Bootstrap's structure in mind to avoid conflicts with default styles.</li>
</ul>

<p>
  With a custom theme, your Bootstrap-based website or app will not only look unique but will also reflect your brand identity and design principles—without sacrificing performance or responsiveness.
</p>

## OVERRIDING DEFAULT STYLES

<p>
  While Bootstrap provides a powerful default theme, you may often need to override specific styles to better fit your design requirements. There are several methods for overriding Bootstrap’s styles, each suitable for different situations.
</p>

<h3>Common Methods to Override Styles</h3>

<ol>
  <li>
    <strong>Using Your Own CSS File</strong><br>
    The simplest method is to include your own stylesheet after Bootstrap's CSS in your HTML. This ensures your rules take precedence.
<pre><code>&lt;link href="bootstrap.min.css" rel="stylesheet"&gt;
&lt;link href="custom.css" rel="stylesheet"&gt;</code></pre>
  </li>

  <li>
    <strong>Using More Specific Selectors</strong><br>
    Bootstrap uses general class names, so you can override them with more specific CSS selectors.
<pre><code>.navbar.navbar-dark {
  background-color: #ff6600 !important;
}</code></pre>
  </li>

  <li>
    <strong>Using <code>!important</code> (Cautiously)</strong><br>
    As a last resort, you can use <code>!important</code> to force your styles to override Bootstrap’s. Use it sparingly to avoid maintenance issues.
<pre><code>.btn-primary {
  background-color: #ff6600 !important;
  border-color: #ff6600 !important;
}</code></pre>
  </li>

  <li>
    <strong>Overriding with Sass Variables</strong><br>
    If you’re compiling Bootstrap with Sass, override the variables before importing Bootstrap's SCSS:
<pre><code>// custom.scss
$primary: #ff6600;
@import "bootstrap";</code></pre>
  </li>
</ol>

<h3>Best Practices</h3>
<ul>
  <li>Minimize the use of <code>!important</code> where possible.</li>
  <li>Keep overrides in a dedicated file (e.g., <code>custom.css</code> or <code>overrides.scss</code>).</li>
  <li>Use developer tools to inspect which classes are being applied and where conflicts occur.</li>
  <li>Document your overrides for better collaboration and maintenance.</li>
</ul>

<p>
  Overriding Bootstrap styles gives you the flexibility to make any design your own, while still taking advantage of the framework’s responsiveness and utility classes.
</p>

## MIXING BOOTSTRAP WITH CUSTOM CSS

<p>
  One of Bootstrap’s strengths is its flexibility—allowing you to combine its powerful prebuilt components with your own custom styles. This hybrid approach helps you achieve unique designs without starting from scratch.
</p>

<h3>Why Mix Bootstrap with Custom CSS?</h3>
<ul>
  <li>To apply your brand's identity and unique design elements.</li>
  <li>To create features not directly available in Bootstrap.</li>
  <li>To override or adjust default Bootstrap behavior.</li>
  <li>To improve maintainability by separating custom styles from framework code.</li>
</ul>

<h3>How to Organize Custom CSS with Bootstrap</h3>

<ol>
  <li>
    <strong>Create a separate custom CSS file</strong><br>
    Save your custom styles in a file like <code>custom.css</code> and include it after the Bootstrap CSS.
<pre><code>&lt;link href="bootstrap.min.css" rel="stylesheet"&gt;
&lt;link href="custom.css" rel="stylesheet"&gt;</code></pre>
  </li>

  <li>
    <strong>Use semantic class names for custom styles</strong><br>
    Avoid naming conflicts with Bootstrap by using unique class names.
<pre><code>.custom-header {
  font-family: 'Poppins', sans-serif;
  background-color: #fff3e0;
  border-bottom: 2px solid #ffa726;
}</code></pre>
  </li>

  <li>
    <strong>Utilize Bootstrap utility classes where possible</strong><br>
    You can still use Bootstrap spacing, layout, and typography classes alongside your own.
<pre><code>&lt;div class="custom-header p-3 text-center"&gt;Welcome!&lt;/div&gt;</code></pre>
  </li>

  <li>
    <strong>Structure your CSS for maintainability</strong><br>
    Organize your custom CSS into logical sections (e.g., typography, layout, components) and add comments.
<pre><code>/* Typography */
.custom-heading {
  font-weight: 700;
  color: #ff6600;
}

/* Buttons */
.btn-orange {
  background-color: #ff6600;
  color: white;
}</code></pre>
  </li>
</ol>

<h3>Tips</h3>
<ul>
  <li>Use browser dev tools to inspect and experiment with your styles.</li>
  <li>Stick to a naming convention for your custom classes (e.g., <code>.custom-</code> or <code>.myapp-</code>).</li>
  <li>If you're using Sass, separate overrides and custom styles into different files for better clarity.</li>
</ul>

<p>
  Mixing Bootstrap with your own CSS allows for full creative control while still leveraging the power and reliability of the framework. With careful organization and best practices, your project will remain scalable and maintainable.
</p>

## USING BOOTSTRAP WITH TAILWIND

<p>
  Although <strong>Bootstrap</strong> and <strong>Tailwind CSS</strong> are two very different CSS frameworks—one component-based and the other utility-first—there may be cases where you want to use both in the same project. This section explains how to integrate them carefully and effectively.
</p>

<h3>Why Combine Bootstrap and Tailwind?</h3>
<ul>
  <li>Leverage Bootstrap’s prebuilt components and Tailwind’s utility classes simultaneously.</li>
  <li>Gradually migrate from one framework to another.</li>
  <li>Add more granular styling to Bootstrap components using Tailwind utilities.</li>
</ul>

<h3>⚠Key Considerations Before Mixing</h3>
<ul>
  <li><strong>Class Conflicts:</strong> Both frameworks define some common class names like <code>container</code> or <code>btn</code>. Tailwind may override Bootstrap or vice versa.</li>
  <li><strong>Bundle Size:</strong> Including both frameworks can significantly increase the size of your CSS output.</li>
  <li><strong>Maintenance Complexity:</strong> Mixing approaches may confuse new developers or make the codebase harder to maintain.</li>
</ul>

<h3>How to Use Bootstrap with Tailwind</h3>

<ol>
  <li>
    <strong>Install Both Frameworks</strong><br>
    You can install via CDN or using a bundler like Vite or Webpack.
<pre><code>// Tailwind via npm
npm install -D tailwindcss

// Bootstrap via npm
npm install bootstrap</code></pre>
  </li>

  <li>
    <strong>Import Both in Your CSS</strong><br>
    If using a custom <code>main.css</code> or <code>app.scss</code>:
<pre><code>@import "tailwindcss/base";
@import "tailwindcss/components";
@import "tailwindcss/utilities";

@import "bootstrap/scss/bootstrap";</code></pre>
    <p>Tip: Import Bootstrap <strong>after</strong> Tailwind if you want Bootstrap styles to take precedence.</p>
  </li>

  <li>
    <strong>Use Tailwind and Bootstrap Separately</strong><br>
    You can use Tailwind for layout and spacing while keeping Bootstrap for components:
<pre><code>&lt;div class="container mx-auto mt-10"&gt;
  &lt;button class="btn btn-primary"&gt;Bootstrap Button&lt;/button&gt;
  &lt;p class="text-center text-gray-600 mt-4"&gt;This is styled with Tailwind.&lt;/p&gt;
&lt;/div&gt;</code></pre>
  </li>
</ol>

<h3>Best Practices</h3>
<ul>
  <li>Avoid mixing classes from both frameworks in the same element.</li>
  <li>Use clear comments or conventions to separate Tailwind and Bootstrap components.</li>
  <li>If possible, choose one framework as primary and the other as secondary.</li>
</ul>

<p>
  While not always recommended for production-scale projects, combining Bootstrap with Tailwind can be useful for experimentation, migration, or specific hybrid needs. Just make sure to plan and document your structure for future maintainability.
</p>


## MOBILE-FIRST DESIGN TIPS

<p>
  Bootstrap follows a <strong>mobile-first</strong> approach, meaning styles are applied to mobile devices by default and then enhanced for larger screens using media queries. This philosophy improves performance, responsiveness, and accessibility.
</p>

<h3>Why Mobile-First?</h3>
<ul>
  <li>Majority of users browse from mobile devices.</li>
  <li>Performance is better on smaller, limited-bandwidth devices.</li>
  <li>It’s easier to progressively enhance than to scale down.</li>
</ul>

<h3>Best Practices for Mobile-First Design</h3>

<ul>
  <li>
    <strong>Start with the Smallest Screen</strong><br>
    Design and test your layout using the default (mobile) styles first, then add responsiveness for tablets and desktops.
  </li>

  <li>
    <strong>Use Bootstrap’s Grid Breakpoints</strong><br>
    Utilize responsive classes like <code>.col-12</code>, <code>.col-md-6</code>, <code>.col-lg-4</code> to change layout based on screen size.
<pre><code>&lt;div class="row"&gt;
  &lt;div class="col-12 col-md-6 col-lg-4"&gt;Responsive Column&lt;/div&gt;
&lt;/div&gt;</code></pre>
  </li>

  <li>
    <strong>Use Utility Classes Responsively</strong><br>
    Tailor spacing, alignment, and visibility with responsive utility classes like:
<pre><code>.d-none d-md-block
.mt-2 mt-lg-5
.text-center text-sm-start</code></pre>
  </li>

  <li>
    <strong>Test on Real Devices or Emulators</strong><br>
    Use browser dev tools and device emulators to check how your layout adapts at each breakpoint.
  </li>

  <li>
    <strong>Avoid Fixed Widths</strong><br>
    Use percentages, viewport units (<code>vw</code>, <code>vh</code>), and Bootstrap’s fluid containers to ensure adaptability.
  </li>

  <li>
    <strong>Prioritize Touch-Friendly Elements</strong><br>
    Ensure buttons are large enough and spaced well for touch interaction.
  </li>

  <li>
    <strong>Optimize Content Hierarchy</strong><br>
    On smaller screens, place the most important information first. Hide or collapse less critical content.
  </li>
</ul>

<h3>Bonus Tip</h3>
<p>
  Combine <code>order</code> and <code>flex</code> classes to reorder elements visually without changing the HTML structure:
<pre><code>&lt;div class="d-flex flex-column flex-md-row"&gt;
  &lt;div class="order-2 order-md-1"&gt;Main Content&lt;/div&gt;
  &lt;div class="order-1 order-md-2"&gt;Sidebar&lt;/div&gt;
&lt;/div&gt;</code></pre>
</p>

<p>
  Applying mobile-first principles ensures your website is inclusive, performant, and user-friendly across all devices. It's not just about shrinking things down—it's about delivering a better experience, everywhere.
</p>

## ACCESSIBILITY IN BOOTSTRAP

<p>
  <strong>Accessibility (a11y)</strong> is a fundamental aspect of web development, ensuring that applications can be used by as many people as possible, including those with disabilities. Bootstrap comes with built-in support for accessible components, but developers must follow best practices to maintain and enhance usability.
</p>

<h3>Built-in Accessibility Features</h3>
<ul>
  <li><strong>ARIA attributes:</strong> Many Bootstrap components include default <code>aria-*</code> attributes to communicate behavior and state to assistive technologies.</li>
  <li><strong>Keyboard support:</strong> Components like modals, dropdowns, and carousels are designed to be navigable using the keyboard.</li>
  <li><strong>Semantic HTML:</strong> Bootstrap encourages the use of semantic elements such as <code>&lt;nav&gt;</code>, <code>&lt;button&gt;</code>, <code>&lt;form&gt;</code>, and <code>&lt;label&gt;</code>.</li>
</ul>

<h3>Developer Best Practices</h3>
<ul>
  <li><strong>Use Labels and Placeholders:</strong> Always associate <code>&lt;label&gt;</code> elements with form controls using the <code>for</code> attribute.</li>
  <li><strong>Ensure Color Contrast:</strong> Check that text and background combinations meet WCAG standards. Tools like <a href="https://webaim.org/resources/contrastchecker/" target="_blank">WebAIM</a> can help.</li>
  <li><strong>Don't Rely on Color Alone:</strong> Use text or icons to reinforce meaning for buttons, alerts, or status indicators.</li>
  <li><strong>Test with a Screen Reader:</strong> Tools like NVDA or VoiceOver help validate if your app is usable without a visual interface.</li>
  <li><strong>Provide Focus Indicators:</strong> Don't remove the default focus outline unless you’re providing a clear alternative.</li>
</ul>

<h3>ARIA Roles and Attributes</h3>
<p>Bootstrap uses and supports ARIA roles and properties. You can also enhance components manually if needed:</p>
<pre><code>&lt;button aria-label="Close" class="btn-close"&gt;&lt;/button&gt;
&lt;div role="alert"&gt;This is an alert message.&lt;/div&gt;
</code></pre>

<h3>Tools for Accessibility Testing</h3>
<ul>
  <li><a href="https://wave.webaim.org/" target="_blank">WAVE – Web Accessibility Evaluation Tool</a></li>
  <li><a href="https://developer.chrome.com/docs/lighthouse/accessibility/" target="_blank">Lighthouse (Chrome DevTools)</a></li>
  <li><a href="https://axe.dev/" target="_blank">axe DevTools</a></li>
</ul>

<p>
  Accessibility is not an optional feature—it's a responsibility. Bootstrap gives you a solid foundation, but your markup and logic determine the final experience. Always test with real tools and users whenever possible.
</p>

## PERFORMANCE OPTIMIZATION

<p>
  Ensuring fast load times and responsive interactions is key to delivering a high-quality user experience. While Bootstrap offers a lot of features out of the box, optimizing your use of it can significantly improve the performance of your website or application.
</p>

<h3>Use Only What You Need</h3>
<ul>
  <li>
    <strong>Custom Builds:</strong> Don’t include the entire Bootstrap bundle if you're only using specific components. Use tools like <a href="https://getbootstrap.com/docs/5.3/customize/overview/" target="_blank">Bootstrap's Customizer</a> or import specific SCSS modules.
  </li>
  <li>
    <strong>Tree Shaking:</strong> If you're using Bootstrap via Webpack, Vite, or another bundler, configure it to remove unused code.
  </li>
</ul>

<h3>Minify CSS and JavaScript</h3>
<ul>
  <li>
    Use the <code>.min.css</code> and <code>.min.js</code> versions of Bootstrap to reduce file size.
  </li>
  <li>
    Tools like <a href="https://cssnano.co/" target="_blank">CSSNano</a> and <a href="https://terser.org/" target="_blank">Terser</a> can help you further minify your custom code.
  </li>
</ul>

<h3>Optimize Assets</h3>
<ul>
  <li><strong>Use Lazy Loading:</strong> Apply <code>loading="lazy"</code> to images and iframes.</li>
  <li><strong>Compress Images:</strong> Use optimized formats like WebP and compress images with tools like TinyPNG or Squoosh.</li>
  <li><strong>Use SVG Icons:</strong> Lightweight and scalable for most UI elements.</li>
</ul>

<h3>Leverage CDN</h3>
<ul>
  <li>
    Load Bootstrap via a CDN like jsDelivr or BootstrapCDN for faster delivery and better caching.
<pre><code>&lt;link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet"&gt;</code></pre>
  </li>
</ul>

<h3>Audit Performance</h3>
<ul>
  <li>Use <a href="https://pagespeed.web.dev/" target="_blank">PageSpeed Insights</a> or <a href="https://developer.chrome.com/docs/lighthouse/overview/" target="_blank">Lighthouse</a> to identify performance bottlenecks.</li>
  <li>Regularly profile your site using browser dev tools to catch memory leaks and slow rendering elements.</li>
</ul>

<h3>Best Practices Summary</h3>
<ul>
  <li>Use only necessary Bootstrap features</li>
  <li>Defer or async non-critical scripts</li>
  <li>Use <code>&lt;link rel="preload"&gt;</code> for critical assets</li>
  <li>Minimize DOM complexity</li>
</ul>

<p>
  With these strategies, your Bootstrap project can be lightweight, fast, and highly optimized for performance across all devices and networks.
</p>

## COMMON MISTAKES TO AVOID

<p>
  When working with Bootstrap, especially for beginners, it's easy to fall into a few common traps that can affect maintainability, performance, and responsiveness. This section highlights frequent mistakes and how to prevent them.
</p>

<h3>Overwriting Instead of Extending</h3>
<ul>
  <li>
    Avoid constantly overriding Bootstrap classes in your custom CSS. Instead, use utility classes or extend Bootstrap with SASS variables when needed.
  </li>
</ul>

<h3>Misusing the Grid System</h3>
<ul>
  <li>
    Not wrapping columns with <code>.row</code> or forgetting <code>.container</code> can break layouts. Always follow the proper structure: <code>container > row > col</code>.
  </li>
</ul>

<h3>Ignoring Breakpoints</h3>
<ul>
  <li>
    Bootstrap is mobile-first. Avoid hardcoding widths or assuming layouts will look the same on all devices. Use responsive utility classes and test across viewports.
  </li>
</ul>

<h3>Adding Inline Styles</h3>
<ul>
  <li>
    Inline styles override Bootstrap and make the code harder to maintain. Use Bootstrap utility classes or external CSS files instead.
  </li>
</ul>

<h3>Loading Duplicate Bootstrap Files</h3>
<ul>
  <li>
    Ensure you’re not loading both the CDN and local Bootstrap files simultaneously. This can cause unpredictable behavior and style conflicts.
  </li>
</ul>

<h3>Overcomplicating Customizations</h3>
<ul>
  <li>
    For advanced customization, use Bootstrap’s SASS version. Avoid editing Bootstrap’s core files directly—this makes upgrades difficult.
  </li>
</ul>

<h3>Forgetting JavaScript Dependencies</h3>
<ul>
  <li>
    Many components (e.g., modals, dropdowns) require Bootstrap’s JavaScript and Popper.js. If components don’t work, check that these scripts are correctly included.
  </li>
</ul>

<h3>Disabling Focus Outlines</h3>
<ul>
  <li>
    Removing <code>outline: none</code> without a proper alternative reduces accessibility. Always provide clear focus indicators for keyboard users.
  </li>
</ul>

<h3>Not Validating Forms</h3>
<ul>
  <li>
    Bootstrap provides basic validation styles, but you need to implement real validation logic. Don’t rely on appearance alone.
  </li>
</ul>

<p>
  By avoiding these mistakes, you’ll ensure your Bootstrap projects are clean, responsive, accessible, and easier to maintain over time.
</p>

## DEBUGGING LAYOUT ISSUES

<p>
  Layout problems are common when working with any front-end framework, including Bootstrap. Thankfully, Bootstrap provides a structured system that makes troubleshooting easier when you know what to look for.
</p>

<h3>Check Your Grid Structure</h3>
<ul>
  <li>Ensure you are using the correct hierarchy: <code>.container</code> → <code>.row</code> → <code>.col</code>.</li>
  <li>Make sure columns are properly closed and that rows are nested correctly inside containers.</li>
  <li>Avoid placing <code>.col-*</code> directly inside a <code>.container</code> without a <code>.row</code>.</li>
</ul>

<h3>Use DevTools to Inspect Layout</h3>
<ul>
  <li>Open your browser's Developer Tools (usually F12) to inspect the layout.</li>
  <li>Check for unintended margins, paddings, or overrides affecting alignment.</li>
  <li>Use the “Elements” and “Computed” panels to trace styles and box models.</li>
</ul>

<h3>Missing or Conflicting CSS</h3>
<ul>
  <li>Make sure the Bootstrap CSS file is properly loaded before any custom CSS.</li>
  <li>Look out for conflicting styles that might override Bootstrap defaults.</li>
</ul>

<h3>Verify Responsive Classes</h3>
<ul>
  <li>Double-check your use of responsive classes like <code>col-md-6</code>, <code>col-lg-4</code>, etc.</li>
  <li>If something breaks at a specific screen size, check if the appropriate breakpoint is used.</li>
</ul>

<h3>Use Debug Utilities</h3>
<ul>
  <li>Bootstrap offers classes like <code>.d-none</code>, <code>.d-block</code>, and <code>.border</code> to help visualize and control layout behavior during development.</li>
  <li>You can add borders to rows or columns temporarily to see how they behave: <code>.border</code>, <code>.bg-light</code>, etc.</li>
</ul>

<h3>Overflow and Fixed Elements</h3>
<ul>
  <li>Unexpected horizontal scroll? Check for elements with fixed widths or large content that break the layout.</li>
  <li>Use <code>overflow-hidden</code> cautiously and only when necessary.</li>
</ul>

<h3>Reset Styles and Test Isolated</h3>
<ul>
  <li>If layout is broken, isolate the problem by removing components one by one or recreating the section in a clean file.</li>
  <li>Try a “reset” of styles or temporarily disable custom CSS to identify the culprit.</li>
</ul>

<p>
  Debugging layout issues takes patience and a methodical approach. Leverage browser tools, inspect your structure carefully, and remember that Bootstrap works best when its patterns are followed closely.
</p>

## BOOTSTRAP NOT LOADING: COMMON CAUSES

<p>
  If Bootstrap styles or components are not working as expected, it's usually due to a few common setup issues. This section helps identify and resolve the most frequent causes.
</p>

<h3>1. Incorrect CSS or JS File Paths</h3>
<ul>
  <li>Double-check that the paths to your <code>.css</code> and <code>.js</code> files are correct.</li>
  <li>Use browser DevTools (F12) to verify the files are being loaded in the “Network” tab.</li>
</ul>

<h3>2. No Internet Connection (for CDN)</h3>
<ul>
  <li>If you're using CDN links (like from jsDelivr or BootstrapCDN), an internet connection is required.</li>
  <li>Make sure your internet is active, or switch to local hosting.</li>
</ul>

<h3>3. JavaScript File Missing or Improperly Ordered</h3>
<ul>
  <li>Ensure that Bootstrap’s JavaScript file is loaded after its dependencies (e.g., Popper.js if needed).</li>
  <li>Incorrect ordering of <code>&lt;script&gt;</code> tags can break interactive components like modals and dropdowns.</li>
</ul>

<h3>4. Missing Popper.js (for Tooltips, Dropdowns, etc.)</h3>
<ul>
  <li>Some Bootstrap components require <strong>Popper.js</strong> to function properly (e.g., tooltips, popovers, dropdowns).</li>
  <li>Include Popper either from the CDN or via a bundler like Vite or Webpack.</li>
</ul>

<h3>5. Conflicting or Overriding Styles</h3>
<ul>
  <li>Another CSS file might be overriding Bootstrap styles.</li>
  <li>Ensure your custom CSS is loaded after Bootstrap, and avoid overusing <code>!important</code>.</li>
</ul>

<h3>6. Using the Wrong Bootstrap Version</h3>
<ul>
  <li>Make sure the documentation you're following matches the Bootstrap version you’ve included (v4, v5, etc.).</li>
  <li>Different versions have different class names and component structures.</li>
</ul>

<h3>7. File Caching in the Browser</h3>
<ul>
  <li>Sometimes, changes aren’t visible due to caching.</li>
  <li>Try clearing the browser cache or performing a hard refresh (Ctrl + F5).</li>
</ul>

<h3>8. Using Incomplete Bootstrap Packages</h3>
<ul>
  <li>If installing via npm, make sure all dependencies (like <code>bootstrap</code> and <code>popper.js</code>) are correctly installed.</li>
  <li>Run <code>npm install bootstrap @popperjs/core</code> for full functionality.</li>
</ul>

<p>
  Most Bootstrap loading issues come down to small oversights in linking or ordering. Reviewing your file paths, order of scripts, and dependencies will typically solve the problem quickly.
</p>

## FRAMEWORK CONFLICTS


<p>
  When using Bootstrap alongside other frameworks or libraries, conflicts can arise that affect styling, layout, or JavaScript behavior. Identifying and managing these conflicts early can help ensure smooth integration and functionality.
</p>

<h3>CSS Conflicts</h3>
<ul>
  <li><strong>Global Styles:</strong> Bootstrap applies global styles (e.g., resets, box-sizing), which can override or be overridden by other frameworks like Tailwind CSS or Foundation.</li>
  <li><strong>Utility Class Collisions:</strong> Class names like <code>.container</code>, <code>.row</code>, or <code>.btn</code> are common and might exist in other CSS frameworks, causing unexpected results.</li>
  <li><strong>Specificity Issues:</strong> More specific selectors from other stylesheets can override Bootstrap's styles unless managed carefully with proper ordering and scoping.</li>
</ul>

<h3>JavaScript Conflicts</h3>
<ul>
  <li><strong>Library Interference:</strong> If multiple libraries manipulate the DOM (like jQuery, Alpine.js, or Vue), interactions with Bootstrap's JavaScript can break components like modals or tooltips.</li>
  <li><strong>Double Initialization:</strong> Components might be initialized by two libraries at once, leading to unpredictable behavior (e.g., two modals open or stuck states).</li>
  <li><strong>Event Handling Conflicts:</strong> Some frameworks listen or emit conflicting events, which can disrupt Bootstrap’s UI logic.</li>
</ul>

<h3>How to Avoid Conflicts</h3>
<ul>
  <li><strong>Namespace your styles:</strong> Use unique class names or wrap your custom styles in containers to limit overlap.</li>
  <li><strong>Load order carefully:</strong> Always load Bootstrap CSS before custom or conflicting stylesheets, and load JavaScript libraries in the correct sequence.</li>
  <li><strong>Use component scopes:</strong> When combining frameworks, isolate each component’s logic using <code>shadow DOM</code>, scoped styles, or different view components (e.g., Vue SFCs).</li>
  <li><strong>Test in isolation:</strong> Before integrating with other frameworks, test each Bootstrap component independently.</li>
</ul>

<h3>Frameworks Known to Conflict with Bootstrap</h3>
<ul>
  <li><strong>Tailwind CSS:</strong> Utility classes overlap; requires careful ordering or using Tailwind’s prefixing system.</li>
  <li><strong>Material UI / Foundation:</strong> Similar class and component names; keep their scopes separated.</li>
  <li><strong>jQuery UI:</strong> May conflict with Bootstrap’s use of jQuery in older versions.</li>
</ul>

<p>
  Managing framework conflicts requires planning and structure. Understand the strengths and structure of each framework and ensure they are not stepping on each other's toes in your project.
</p>

## MODAL Z-INDEX ISSUES

<p>
  One of the most common layout bugs when working with Bootstrap modals is related to <strong>z-index stacking</strong>. Modals may appear behind other elements, be partially hidden, or fail to display correctly. These issues are usually caused by conflicting z-index values in your layout or improperly positioned elements.
</p>

<h3>Common Causes</h3>
<ul>
  <li><strong>Custom Styles:</strong> Other elements (like headers, sidebars, or overlays) with high <code>z-index</code> may overlap the modal unintentionally.</li>
  <li><strong>Nested Positioning:</strong> Modals placed inside relatively positioned elements can inherit stacking contexts that limit their visibility.</li>
  <li><strong>Missing Backdrop:</strong> If the modal backdrop is not rendered or has a lower <code>z-index</code>, it can affect the layering of the modal itself.</li>
</ul>

<h3>Solutions</h3>
<ul>
  <li>Ensure the modal is placed outside of elements with <code>position: relative</code> or <code>z-index</code> manipulation.</li>
  <li>Use the default Bootstrap structure — place the modal component directly in the <code>&lt;body&gt;</code> tag.</li>
  <li>Inspect with DevTools and compare z-index values of overlapping elements.</li>
  <li>If needed, override Bootstrap’s default modal z-index (e.g., <code>z-index: 1055</code>) using custom CSS with care:</li>
</ul>

.modal {
  z-index: 9999 !important;
}
.modal-backdrop {
  z-index: 9998 !important;
}

## LAYOUT BREAKS ON SMALL SCREENS

<p>
  One of the most common issues in responsive design is when layouts break or look unorganized on smaller screens, such as smartphones. This usually happens due to improper use of Bootstrap’s grid system, fixed widths, or non-responsive components.
</p>

<h3>Common Causes</h3>
<ul>
  <li><strong>Missing responsive classes:</strong> Forgetting to use responsive grid classes like <code>.col-sm-</code>, <code>.col-md-</code>, etc.</li>
  <li><strong>Fixed widths or heights:</strong> Using hardcoded <code>px</code> values instead of relative units like <code>%</code>, <code>vh</code>, or <code>vw</code>.</li>
  <li><strong>Overflowing content:</strong> Images, long text strings, or tables that don't adjust to smaller screens.</li>
  <li><strong>Improper nesting:</strong> Placing columns outside of a <code>.row</code> or placing rows outside of a <code>.container</code>.</li>
</ul>

<h3>Solutions</h3>
<ul>
  <li>Always use the Bootstrap grid correctly: <code>.container</code> → <code>.row</code> → <code>.col-*</code>.</li>
  <li>Use fluid layouts with <code>container-fluid</code> when needed.</li>
  <li>Make use of utility classes like <code>.img-fluid</code>, <code>.text-wrap</code>, <code>.table-responsive</code>, and responsive padding/margin helpers.</li>
  <li>Test your layout on different screen sizes using browser dev tools (Device Mode).</li>
</ul>

<h3>Best Practices</h3>
<ul>
  <li>Follow the mobile-first principle: start designing for smaller screens first, then expand for larger ones.</li>
  <li>Use relative sizing units like <code>em</code>, <code>rem</code>, <code>%</code> to improve flexibility.</li>
  <li>Don't forget to set the viewport meta tag in your HTML.</li>
</ul>

## FINAL CONSIDERATIONS

<p>
  This documentation was created to summarize and organize the key concepts of the Bootstrap framework. Inspired by the official <a href="https://getbootstrap.com/" target="_blank">Bootstrap documentation</a>, its main goal is to provide a more accessible and centralized reference for study, quick consultation, and real-world application.
</p>

<p>
  Whether you are just beginning your journey in frontend development or reinforcing your knowledge, this guide aims to simplify your learning experience by offering structured content, practical examples, and clear explanations.
</p>

<p>
  Feel free to use this material to boost your productivity, improve your understanding of responsive design, and accelerate your workflow with one of the most popular CSS frameworks in the world.
</p>

<br><br>
<p><strong>© 2025 EltonRuan. All rights reserved.</strong></p>

<footer align="center"> <img style="width:100%" src="https://capsule-render.vercel.app/api?type=soft&height=20&color=FFFFFF&fontSize=50&fontAlign=50&strokeWidth=0&descAlignY=80&stroke=000000&reversal=false&section=footer"> </footer>
