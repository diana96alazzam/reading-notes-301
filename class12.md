# Read 12

- EJS partials work like EJS layouts too in creating a single fix content on a web page.

- Unlike EJS Layouts, EJS partials can work without the express-ejs-layouts module. EJS partials apply in cases like creating objects like header, footer, div.

- For a web page to contain the partial, it must be connected to each partial via a line of code, unlike layouts which apply everywhere.

- Note: The `<%- %>` tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like `‘<’`, `‘>’`, etc…







