## Design Pattern
When you have breadcrumb links on a page to show where you currently are, and navigation to previous pages in the path.

## Example
![Alt text](/BreadCrumbLinks/__example.png)

## Component Summary
The [breadcrumbLinks.hbs](/BreadCrumbLinks/breadcrumbLinks.hbs) component provides breadcrumb navigation

## Usage
```handlebars
{{> breadcrumbLinks data=breadcrumbLinks-data-page}}
```
(Optionally add a modifier for specific styling.)  
```handlebars
{{> breadcrumbLinks data=breadcrumbLinks-data-page modifier=mymodifier}}
```

## File Descriptions
* [breadcrumbLinks.hbs](/BreadCrumbLinks/breadcrumbLinks.hbs) (The BreadCrumb list component)
* [breadcrumbLink.hbs](/BreadCrumbLinks/breadcrumbLink.hbs) (A BreadCrumb item)
* [_breadcrumbLinks.scss](/BreadCrumbLinks/_breadcrumbLinks.scss) (SASS file for styling the BreadCrumbLinks component)
* [breadcrumbLinks-data-page.json](/BreadCrumbLinks/breadcrumbLinks-data-page.json) (Insert the breadcrumb links for your page here.)
