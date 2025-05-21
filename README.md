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

## BUTTONS: TYPES, COLORS, AND SIZES

## ALERTS AND BADGES

## CARDS AND LIST GROUPS

## MODALS AND POPOVERS

## NAVBARS AND RESPONSIVE MENUS

## PAGINATION AND BREADCRUMBS

## COLLAPSE AND ACCORDIONS

## SPINNERS AND LOADERS

## PROGRESS BARS

## TYPOGRAPHY UTILITIES

## COLOR UTILITIES

## SPACING (MARGINS & PADDINGS)

## BORDERS, SHADOWS, AND RADIUS

## DISPLAY AND VISIBILITY UTILITIES

## RESPONSIVE UTILITIES

## CUSTOMIZING BOOTSTRAP WITH SASS

## USING BOOTSTRAP ICONS

## BUILDING RESPONSIVE LAYOUTS

## CENTERING CONTENT

## FIXED FOOTERS AND STICKY ELEMENTS

## OFFCANVAS AND SIDEBARS

## USING BOOTSTRAP JAVASCRIPT COMPONENTS

## TOOLTIPS, TOASTS, AND CAROUSELS

## DROPDOWNS AND COLLAPSIBLES

## DATA ATTRIBUTES VS MANUAL INIT

## HANDLING MODALS PROGRAMMATICALLY

## THEME CUSTOMIZATION WITH SASS VARIABLES

## CREATING A CUSTOM THEME

## OVERRIDING DEFAULT STYLES

## MIXING BOOTSTRAP WITH CUSTOM CSS

## USING BOOTSTRAP WITH TAILWIND

## MOBILE-FIRST DESIGN TIPS

## ACCESSIBILITY IN BOOTSTRAP

## PERFORMANCE OPTIMIZATION

## COMMON MISTAKES TO AVOID

## DEBUGGING LAYOUT ISSUES

## BOOTSTRAP NOT LOADING: COMMON CAUSES

## FRAMEWORK CONFLICTS

## MODAL Z-INDEX ISSUES

## LAYOUT BREAKS ON SMALL SCREENS

## FINAL CONSIDERATIONS

<footer align="center"> <img style="width:100%" src="https://capsule-render.vercel.app/api?type=soft&height=20&color=FFFFFF&fontSize=50&fontAlign=50&strokeWidth=0&descAlignY=80&stroke=000000&reversal=false&section=footer"> </footer>
