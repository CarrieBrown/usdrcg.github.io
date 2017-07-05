# Welcome to the refreshed USDRCG website!

### About This Site

## Templates

* There are many page templates available for use, should you need to add a new page. 
* Find them in the ALLTemplates folder. 
* Navigating to them in a browser allows you to see a live preview. Example: [http://usdrcg.github.io/AllTemplates/html/contact.html](http://usdrcg.github.io/AllTemplates/html/contact.html)

## Layouts (headers, footers, navs)
* Jekyll is used as a faux-server-side language that allows us to have headers, footers, and navigation sections seperate from each page.
* A configuration (`_config.yml`) file is needed that contains the following:

    baseurl: 
    exclude: ['README.md']

 *Note: the `baseurl` in our case is empty because we are working directly out of usdrcg.github.io. If we had a subfolder that contained another site, then we would list that subfolder there. This term allows us to create simple links to local documents.
 
 * At the top of each page, you must specify that you'd also like Jekyll to load your header, footer, and nav sections. This is done by including the following at the top of the page:

    `---`
    layout: default
    `---`

* The header, footer, and nav page must be located in the `_layouts` folder. This is where Jekyll knows how to find it.
* In the file `/_layouts/default.html`, you'll find the header and navigation code at the top, followed by `{{content}}` on the middle, then footer code at the bottom. The `{{content}}` code tells Jekyll where to include the page code.
 


Source of template: [here](https://wrapbootstrap.com/theme/bizwrap-elegant-bootstrap-4-template-WB07PT66X).
