## Design Pattern
When you have social media icon links.  Usually in the footer of a page.

## Example
![Alt text](/SocialMediaLinks/__example.png)

## Component Summary
The [socialMediaLinks.hbs](/SocialMediaLinks/socialMediaLinks.hbs) component provides a set of social media icon links.

## Usage
```handlebars
{{> socialMediaLinks data=socialMediaLinks-data}}
```
(Optionally add a modifier for specific styling.  For example, a case where you have two socialMediaLinks components, and you want the second one styled differently)
```handlebars
{{> socialMediaLinks data=socialMediaLinks-data modifier=mymodifier}}
```

## File Descriptions
* [socialMediaLinks.hbs](/SocialMediaLinks/socialMediaLinks.hbs) (The Social Media list component)
* [socialMediaLink.hbs](/SocialMediaLinks/socialMediaLink.hbs) (A Social Media Link item)
* [_socialMediaLinks.scss](/SocialMediaLinks/_socialMediaLinks.scss) (SASS file for styling the SocialMediaLinks component)
* [socialMediaLinks-data.json](/SocialMediaLinks/socialMediaLinks-data.json) (Insert your question and answers here)
