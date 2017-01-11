## Design Pattern
When you have footer links.

## Example
![Alt text](/FooterLinks/__example.png)

## Component Summary
The [footerLinks.hbs](/FooterLinks/footerLinks.hbs) component provides footer navigation

## Usage
```handlebars
{{> footerLinks data=footerLinks-data-page}}
```
(Optionally add a modifier for specific styling.)  
```handlebars
{{> footerLinks data=footerLinks-data-page modifier=mymodifier}}
```

## File Descriptions
* [footerLinks.hbs](/FooterLinks/footerLinks.hbs) (The Footer links list component)
* [footerLink.hbs](/FooterLinks/footerLink.hbs) (A Footer link item)
* [_footerLinks.scss](/FooterLinks/_footerLinks.scss) (SASS file for styling the FooterLinks component)
* [footerLinks-data-page.json](/FooterLinks/footerLinks-data-page.json) (Insert the footer links for your page here.)
