---
layout: home
title: "Building websites in GitHub"
author: "me"
---
  
{{ page.author }}  
[About](about.md)

# Description  
{{site.description}} 
{% assign lead = site.team_members | where:"role", "Head Writer" | first %}
This project is led by {{ lead.name }}.  
[See our full team]{about#team}

For questions, get in touch by email: [asankey@unb.ca](mailto: {{site.email}})
