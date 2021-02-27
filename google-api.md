# Performing a search
- HTTP Request:
  https://www.googleapis.com/books/v1/volumes?q=search+terms
- You can specify your search by typing strings, such as:
  * intitle: Returns results where the text following this keyword is found in the title.
  * inauthor: Returns results where the text following this keyword is found in the author.
  * inpublisher: Returns results where the text following this keyword is found in the publisher.
  * subject: Returns results where the text following this keyword is listed in the category list of the volume.
  * isbn: Returns results where the text following this keyword is the ISBN number.
  * lccn: Returns results where the text following this keyword is the Library of Congress Control Number.
  * oclc: Returns results where the text following this keyword is the Online Computer Library Center number.
- HTTP Response:
If the request succeed, then the response will get the results as an array of data.
- You can use the filter parameter to restrict the returned results further by setting it the to one of the following values:
  * partial - Returns results where at least parts of the text are previewable.
  * full - Only returns results where all of the text is viewable.
  * free-ebooks - Only returns results that are free Google eBooks.
  * paid-ebooks - Only returns results that are Google eBooks with a price.
  * ebooks - Only returns results that are Google eBooks, paid or free.
- You can use the printType parameter to restrict the returned results to a specific print or publication type by setting it to one of the following values:
  * all - Does not restrict by print type (default).
  * books - Returns only results that are books.
  * magazines - Returns results that are magazines.
- You can use the projection parameter with one of the following values to specify a predefined set of Volume fields to return:
  * full - Returns all Volume fields.
  * lite - Returns only certain fields. See field descriptions marked with double asterisks in the Volume reference to find out which fields are included.
- You can change the ordering by setting the orderBy parameter to be one of these values:
  * relevance - Returns results in order of the relevance of search terms (this is the default).
  * newest - Returns results in order of most recently to least recently published.

# EGS
https://github.com/Aseel-Banna/reading-notes/blob/main/google-api

Performing a search
HTTP Request: https://www.googleapis.com/books/v1/volumes?q=search+terms
You can specify your search by typing strings, such as:
intitle: Returns results where the text following this keyword is found in the title.
inauthor: Returns results where the text following this keyword is found in the author.
inpublisher: Returns results where the text following this keyword is found in the publisher.
subject: Returns results where the text following this keyword is listed in the category list of the volume.
isbn: Returns results where the text following this keyword is the ISBN number.
lccn: Returns results where the text following this keyword is the Library of Congress Control Number.
oclc: Returns results where the text following this keyword is the Online Computer Library Center number.
HTTP Response: If the request succeed, then the response will get the results as an array of data.
You can use the filter parameter to restrict the returned results further by setting it the to one of the following values:
partial - Returns results where at least parts of the text are previewable.
full - Only returns results where all of the text is viewable.
free-ebooks - Only returns results that are free Google eBooks.
paid-ebooks - Only returns results that are Google eBooks with a price.
ebooks - Only returns results that are Google eBooks, paid or free.
You can use the printType parameter to restrict the returned results to a specific print or publication type by setting it to one of the following values:
all - Does not restrict by print type (default).
books - Returns only results that are books.
magazines - Returns results that are magazines.
You can use the projection parameter with one of the following values to specify a predefined set of Volume fields to return:
full - Returns all Volume fields.
lite - Returns only certain fields. See field descriptions marked with double asterisks in the Volume reference to find out which fields are included.
You can change the ordering by setting the orderBy parameter to be one of these values:
relevance - Returns results in order of the relevance of search terms (this is the default).
newest - Returns results in order of most recently to least recently published.

EGS
Options:
cache Compiled functions are cached, requires filename
filename Used by cache to key caches, and for includes
root Set project root for includes with an absolute path (e.g, /file.ejs). Can be array to try to resolve include from multiple directories.
views An array of paths to use when resolving includes with relative paths.
context Function execution context
compileDebug When false no debug instrumentation is compiled
client Returns standalone compiled function
delimiter Character to use for inner delimiter, by default '%'
openDelimiter Character to use for opening delimiter, by default '<'
closeDelimiter Character to use for closing delimiter, by default '>'
debug Outputs generated function body
strict When set to `true`, generated function is in strict mode
_with Whether or not to use with() {} constructs. If false then the locals will be stored in the locals object. (Implies `--strict`)
localsName Name to use for the object storing local variables when not using with Defaults to locals
rmWhitespace Remove all safe-to-remove whitespace, including leading and trailing whitespace. It also enables a safer version of -%> line slurping for all scriptlet tags (it does not strip new lines of tags in the middle of a line).
escape The escaping function used with <%= construct. It is used in rendering and is .toString()ed in the generation of client functions. (By default escapes XML).
outputFunctionName Set to a string (e.g., 'echo' or 'print') for a function to print output inside scriptlet tags.
async When true, EJS will use an async function for rendering. (Depends on async/await support in the JS runtime.




Tags:
<% 'Scriptlet' tag, for control-flow, no output
<%_ ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it
<%= Outputs the value into the template (HTML escaped)
<%- Outputs the unescaped value into the template
<%# Comment tag, no execution, no output
<%% Outputs a literal '<%'
%> Plain ending tag
-%> Trim-mode ('newline slurp') tag, trims following newline
_%> ‘Whitespace Slurping’ ending tag, removes all whitespace after it




CLI:
cache Compiled functions are cached, requires filename
-o / --output-file FILE Write the rendered output to FILE rather than stdout.
-f / --data-file FILE Must be JSON-formatted. Use parsed input from FILE as data for rendering.
-i / --data-input STRING Must be JSON-formatted and URI-encoded. Use parsed input from STRING as data for rendering.
-m / --delimiter CHARACTER Use CHARACTER with angle brackets for open/close (defaults to %).
-p / --open-delimiter CHARACTER Use CHARACTER instead of left angle bracket to open.
-c / --close-delimiter CHARACTER Use CHARACTER instead of right angle bracket to close.
-s / --strict When set to `true`, generated function is in strict mode
-n / --no-with Use 'locals' object for vars rather than using `with` (implies --strict).
-l / --locals-name Name to use for the object storing local variables when not using `with`.
-w / --rm-whitespace Remove all safe-to-remove whitespace, including leading and trailing whitespace.
-d / --debug Outputs generated function body
-h / --help Display this help message.
-V/v / --version Display the EJS version..


  
