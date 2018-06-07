# jukkalepisto.com
Source of code of simple static responsive "business card"-type website

## About implemention
- Update <meta> tags at head of index.html: Such as title, description, og-tags, url etc..
- Body of index.html itself is pretty self-explanatory and it constructs of numerous div-sections with each having its own class (css class).
- I have used Material Design Icons: Please find them here in case you want to replace or add any: https://material.io/tools/icons/?style=baseline
- If you update menu ( inside <header> tag ), remember to update element id's as well. For example link 'a href="#experience" class="menu">Experience' takes user to element with id "experience"
- Remove or add any "experience cards" (div class="card card-1") as you wish
- Notice the divider that is hidden by default (div id="hiddenExperience" class="hidden"). Every experience card inside that div are hidden on page load and those will be set visible only after user clicks "Show more" button.
  
Enjoy!
