README:
Author: John Drake
Contact: jdrake@uoregon.edu
Description: A simple web server that returns 403 errors if prohibited characters are in the url/filename,
or the url does not end in .html or .css. If the file/page is not found whatsoever, a 404 error is returned. Should the file
specified in the url be present, the page will be transmitted to the client/browser by the server and displayed.