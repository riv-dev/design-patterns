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
* [faqs.hbs](/FAQs/faqs.hbs) (The FAQ list component)
* [faq.hbs](/FAQs/faq.hbs) (A FAQ item)
* [_faqs.scss](/FAQs/_faqs.scss) (SASS file for styling the FAQs component)
* [faqs-data.json](/FAQs/faqs-data.json) (Insert your question and answers here)
