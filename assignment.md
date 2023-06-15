#WHAT IS JSX?
ANS:-
JSX (JavaScript XML) is an extension syntax used in JavaScript to write HTML-like code within JavaScript code. It is primarily associated with React, a popular JavaScript library for building user interfaces. JSX allows developers to define the structure and appearance of UI components in a more declarative and intuitive manner.
With JSX, you can write HTML-like markup directly in your JavaScript code. This allows you to describe the structure and content of UI components using familiar HTML tags, attributes, and nested elements. JSX is not a separate template language but rather a syntax extension that can be transformed into regular JavaScript using a transpiler, such as Babel.

#WHAT IS JSX SUPERPOWERS?
ANS:-
Declarative Syntax: JSX allows developers to write UI code in a declarative manner, meaning you describe what the UI should look like based on its state, rather than imperatively defining each step to update the UI. This makes the code easier to read, understand, and maintain.
HTML-Like Syntax: JSX resembles HTML syntax, making it familiar and intuitive for web developers. It allows you to use HTML tags, attributes, and nested elements to define the structure of UI components. This makes it easier to transition from HTML-based development to building components in React.
JavaScript Integration: JSX allows embedding JavaScript expressions within curly braces {}. This enables you to dynamically generate content, use variables, perform calculations, and invoke functions directly within the JSX code. This tight integration with JavaScript makes JSX flexible and powerful.
Component-Based Structure: JSX enables the creation of reusable UI components in React. You can define custom components by composing JSX elements together, creating a modular and hierarchical structure. Components can encapsulate their own state, behavior, and rendering logic, allowing for efficient code organization and reusability.
Static Type Checking: JSX supports static type checking through tools like TypeScript or Flow. By adding type annotations to JSX code, you can catch type errors during development, improving code reliability and reducing runtime errors.
Optimized Rendering: JSX allows React to efficiently update the user interface. React uses a virtual DOM (a lightweight copy of the actual DOM) to determine the minimal set of changes needed to update the UI based on JSX component updates. This approach reduces the number of DOM manipulations, resulting in better performance.
Ecosystem and Tooling: JSX is widely supported in the React ecosystem, with a rich set of tools, libraries, and frameworks available for building UI components. Various IDEs and code editors provide syntax highlighting, autocompletion, and linting for JSX code, making development easier and more efficient.
These superpowers make JSX a valuable asset for building dynamic and interactive user interfaces in React, enhancing developer productivity and enabling the creation of complex UI structures with ease.


#ROLE OF TYPE ATTRIBUTE IN SCRIPT TAG?WHAT OPTION CAN I USE THERE?
ANS:-
The type attribute in the <script> tag is used to specify the MIME type of the content within the script block. It helps the browser understand how to interpret and execute the script code. The type attribute is optional, and if it is not provided, the default value is assumed to be "text/javascript".

Here are some common values for the type attribute:

"text/javascript": This is the most common and widely supported value for the type attribute. It indicates that the content within the <script> block is JavaScript code.

"module": This value is used to indicate that the script is an ECMAScript module. Modules are used to encapsulate and organize JavaScript code, allowing for better code organization and reusability. When using "module", the script file is fetched with CORS and executes in strict mode.


#TITLE COMPONENT VS <TITLE COMPONENT/>VS <TITLE COMPONENT> VS </TITLE COMPONENET> IN JSX?
ANS:-
In JSX, the usage of angle brackets < > and self-closing tags / determines how components are represented and rendered.

 1.Title component: This refers to a JSX component named Title that is used without opening or closing tags. It could be a custom component or a built-in React component. 
 2.<Title component/>: This syntax represents a self-closing tag for the Title component. It is equivalent to the previous example but uses self-closing syntax. 
 3.<Title component>: This syntax without a closing tag represents an opening tag for the Title component. It is used when you want to include content within the component.
 4.</Title component>: This syntax with a closing tag is not valid in JSX. The closing tag is used to denote the end of a JSX component, but it should match the opening tag of the same component. 