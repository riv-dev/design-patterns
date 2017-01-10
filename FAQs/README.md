## Synopsis
A basic component for Question and Answer section on web pages.

## Example
![Alt text](/FAQs/example.png)

## Usage
```handlebars
{{> faqs data=faqs-data}}
```
(Optionally add a modifier for specific styling)
```handlebars
{{> faqs data=faqs-data modifier=mymodifier}}
```

## File Descriptions
*faqs.hbs (The FAQ list component)
*faq.hbs (A FAQ item)
*faqs.scss (SASS file for styling the FAQs component)
*faqs-data.scss (Insert your question and answers here)
