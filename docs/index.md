---
tags:
  - plugin
resource_link: "https://www.redguides.com/community/resources/mq2kisstemplate.328/"
support_link: "https://www.redguides.com/community/threads/mq2kisstemplate.67314/"
repository: "https://github.com/RedGuides/MQ2KissTemplate"
config: "Kissassist_Level_ClassShortName.ini"
authors: "ChatWithThisName"
tagline: "Makes a template of your current characters KissAssist INI."
---

# MQ2KissTemplate

<!--desc-start-->
Convert a character's KissAssist INI to a shareable template file.
<!--desc-end-->
It will also convert old conditions from KissAssist 10 to the new KissAssist 11+ format.

Output file is `Kissassist_Level_ClassShortName.ini` e.g. `Kissassist_105_WAR.ini`

You can then share the INI without a bunch of copy/pasting.

MQ2KissTemplate will upgrade to the new KA11 Conditions automatically.


## Commands

<a href="cmd-maketemplate/">
{% 
  include-markdown "projects/mq2kisstemplate/cmd-maketemplate.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "projects/mq2kisstemplate/cmd-maketemplate.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('projects/mq2kisstemplate/cmd-maketemplate.md') }}
