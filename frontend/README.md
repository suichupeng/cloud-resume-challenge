# Frontend Technical Specification

Create a static website that servers HTML resume

## Resume Format Consideration

[Jack's resume template](https://www.overleaf.com/latex/templates/jakes-resume/syzfjbzwjncs)

### Jack's resume 

Use GenAI to generate HTML and CSS if possible, them refactor it for better performance

Prompt to GPT

```
Convert this to HTML
Don't use css framework
Please use least amount of CSS tag
```

Image provided to LLM
![](./docs/jack%20_resume_template.jpeg)

HTML I am going to refactor:
[generated_output](./docs/inital_generate.html)

## HTML Adjustment

- UTF-8 to support most languages
- width