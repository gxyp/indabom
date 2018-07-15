# indabom
A simple bill of materials web app using [django-bom](https://github.com/mpkasp/django-bom).

- Master parts list with indented bill of materials
- Octopart price matching
- BOM Cost reporting, with sourcing recommendations

# Note
Base on mpkasp's two project, plan to re-write django-bom to meet myself requirement. 

- Change django-bom to apps not package for easy modificaiton
- Change part number to match current material part number. only size and glue method change
- Also need change import code to import current p/n
- Add reference in the subparts for PCBA level needed reference number
- 


