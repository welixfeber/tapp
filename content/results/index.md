+++
title = "DataVis"
weight = 4
extra.full_hero = false
extra.main_nav = true
+++
{% padded_block(bg="accent") %}
Below you can read the results of our 4 waves survey.
{% end %}
{{
shiny_app(url="https://tapp-shiny-app.blackisland-fad2c1bc.germanywestcentral.azurecontainerapps.io/",id="shiny1")
}}
{{gototop()}}