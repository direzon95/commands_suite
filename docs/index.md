---
layout: default
title: Команды бота
---
{% for cmd in site.data.commands.commands %}
- **{{ cmd.name }}**: {{ cmd.description }}  
  `{{ cmd.usage }}`
{% endfor %}
