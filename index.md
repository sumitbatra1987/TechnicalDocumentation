---
employeename: Sumit
employeecode: 987
---


This is the first page of my website with {{page.employeename}}. The unique {{page.employeecode}} is doing his bit.

- Editing this file for practicing. 
- Done some changes. 

These changes are done on Sunday, 31st Jan 2021.

Watch out for more updates in near future.

Show the code: {{site.code}}

Data file contents:

{% for item in site.data.demo %}

The country needs {{item.plant}} was created with employee {{item.breed}}

{% endfor %}

Common text is used in: {%include common2.txt%}
