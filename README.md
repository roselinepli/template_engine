## Simple Template Engine in Python

## Introduction
<p>This project is a simple template engine implemented in Python. Template engines are tools designed to handle text-heavy tasks where dynamic data needs to be combined with static textual data. The most common use case for template engines is generating HTML for web applications, but they can also be used to produce any textual output, such as plain-text email messages.</p>

## Implementation
<p>The template engine consists of two main phases: parsing the template and rendering the template.
<ol>
<li>Parsing the Template: In this phase, the template is analyzed to identify the dynamic and static parts. The dynamic parts are extracted and represented in a data structure that can be used during rendering.</li>

<li>Rendering the Template: During rendering, the template engine manages the dynamic context, which provides the data to be inserted into the template. It executes the logic elements, implements dot access and filter execution, and replaces the dynamic parts with the actual data to produce the final output.</li>
</ol>
</p>

Original from <a href="https://aosabook.org/en/500L/a-template-engine.html">500 lines or less</a>
