## Design Pattern
When you have a Question and Answer list, usually on the "FAQ" page.

## Example
![Alt text](/FAQs/example.png)

## Component Summary
The [faqs.hbs](/FAQs/faqs.hbs) component provides a list of question and answers.

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
