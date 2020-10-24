## EJS


- Like a lot of the applications we build, there will be a lot of code that is reused. We’ll call those partials and define three files we’ll use across all of our site: head.ejs, header.ejs, and footer.ejs. Let’s make those files now.

- We have our partials defined now. All we have to do is include them in our views. Let’s go into index.ejs and about.ejs and use the include syntax to add the partials.

__Syntax for including an EJS Partial__; 
 - Use `<%- include('RELATIVE/PATH/TO/FILE') %>` to embed an EJS partial in another file.

    - The hyphen <%- instead of just <% to tell EJS to render raw HTML.
    - The path to the partial is relative to the current file.

- `cache` Compiled functions are cached, requires filename
- `-o / --output-file FILE` Write the rendered output to FILE rather than stdout.
- `-f / --data-file FILE` Must be JSON-formatted. Use parsed input from FILE as data for rendering.
- `-i / --data-input STRING` Must be JSON-formatted and URI-encoded. Use parsed input from STRING as data for rendering.
- `-m / --delimiter CHARACTER` Use CHARACTER with angle brackets for open/close (defaults to %).
- `-p / --open-delimiter CHARACTER` Use CHARACTER instead of left angle bracket to open.- 
- `-c / --close-delimiter CHARACTER` Use CHARACTER instead of right angle bracket to close.
- `-s / --strict` When set to `true`, generated function is in strict mode
- `-n / --no-with` Use 'locals' object for vars rather than using `with` (implies --strict).
- `-l / --locals-name` Name to use for the object storing local variables when not using `with`.
- `-w / --rm-whitespace` Remove all safe-to-remove whitespace, including leading and trailing whitespace.
- `-d / --debug` Outputs generated function body
- `-h / --help` Display this help message.
- `-V/v / --version` Display the EJS version


[<===BACK](README.MD)
