---
layout: default
title: "About"
---

## Project  
The purpose of this project is to learn how to set up a website on GitHub.

## Cite us  
Cite this as "ha ha..."  
- Email: [asankey@unb.ca](mailto: {{ site.email }})
- GitHub: [https://github.com/sankeyad/]({{ site.git }})

## Team  
The following:
{% for team_member in site.team_members %}
- {{ team_member.name}}, role: {{team_member.role }}
{% endfor %}
