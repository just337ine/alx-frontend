# 0x01. Developer Tools

Developer Tools, also known as DevTools, are a set of web developer tools built directly into modern web browsers. They provide a wide range of functionalities to assist developers in debugging, analyzing, and optimizing websites and web applications.

### Opening Developer Tools

#### Google Chrome

1. **Keyboard Shortcut:** Press `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (Mac).
2. **Right-Click Menu:** Right-click on any element on the page and select "Inspect" from the context menu.
3. **Menu Option:** Click on the three dots in the top-right corner (`⋮`), go to "More tools," and select "Developer tools."

#### Mozilla Firefox

1. **Keyboard Shortcut:** Press `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (Mac).
2. **Right-Click Menu:** Right-click on any element on the page and select "Inspect Element" from the context menu.
3. **Menu Option:** Click on the three horizontal lines in the top-right corner, go to "Web Developer," and select "Inspector."

#### Safari

1. **Keyboard Shortcut:** Press `Option + Cmd + I`.
2. **Menu Option:** Go to "Develop" in the menu bar, then select "Show Web Inspector."

#### Microsoft Edge

1. **Keyboard Shortcut:** Press `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (Mac).
2. **Right-Click Menu:** Right-click on any element on the page and select "Inspect" from the context menu.
3. **Menu Option:** Click on the three dots in the top-right corner, go to "More tools," and select "Developer tools."

### Using the Elements Tab to Edit HTML and CSS

In the "Elements" tab of Developer Tools:

- **HTML:** Double-click on an HTML element to edit its content.
- **CSS:** Navigate to the "Styles" panel to modify CSS rules.

### Auditing a Page with Lighthouse

1. Open Developer Tools.
2. Go to the "Audits" tab.
3. Click on "Perform an audit" and select the categories you want to audit.
4. Click "Run audit."

### Creating and Running Snippets

1. Open Developer Tools.
2. Go to the "Sources" tab.
3. Navigate to the "Snippets" section.
4. Right-click and select "New snippet" to create.
5. Write your code and click "Ctrl + Enter" to run.

### Getting Information About Files and Server Configurations

Use the "Network" tab in Developer Tools to inspect network requests and responses, including file information and server configurations.

### Blocking Requests

In the "Network" tab, right-click on a request and select "Block request URL" to block specific requests.

### Knowing JavaScript/CSS Usage on a Page

Check the "Coverage" tab in Developer Tools to see how much of the JavaScript and CSS on a page is actually used.

### Detecting 404 Issues

In the "Network" tab, look for HTTP status code "404" in the list of network requests to identify 404 issues.

### Moving Elements on a Webpage

While in the "Elements" tab, click and hold on an HTML element, then drag it to the desired location to move it on the webpage.

For further details and examples, refer to [Chrome DevTools documentation](https://blittle.github.io/chrome-dev-tools/).
