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


  