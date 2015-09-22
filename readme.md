#NSX RAML

This repository holds a RAML specification of the NSX for vSphere 6.x API.
For more details on RAML, please visit http://raml.org.

This RAML file has been generated from information that can be found in the "NSX vSphere API Guide" documenation that is  available in PDF format at vmware.com.

The purpose of this package is to be used as the basis in building dynamic API clients for the NSX for vSphere API and for the automatic generation of API documentation.

An example of one such dynamic client that uses the NSX RAML specification is the Python 'nsxramlclient' that can be found at:
http://github.com/vmware/nsxramlclient

In addition to the RAML file itself, three artifacts are provided that are generated by the tools raml2html, raml2md and raml2postman:
- In /html-version/ there is a HTML file generated by raml2html that can be viewed in a browser.
- Likewise, /md-version/ contains a markdown file generated by raml2md.
- Finally, in /postman-collection/ there are postman collection and postman environments files generated by raml2postman

You can find more information on the raml2html and raml2md tools on Kevin Renkser's Github 
https://github.com/kevinrenskers

Details on raml2postman can be found on postmanlabs github
https://github.com/postmanlabs/raml2postman 


#Credits
Special credits and thanks go to Conner Mullaney. Dilligently he has created more than 80% of the content in the RAML File out of the NSX-v 6.1.4 API Documentation available as PDF, and with this brought this project forward significantly


#License
Copyright © 2015 VMware, Inc. All Rights Reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and
to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions
of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED
TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.

