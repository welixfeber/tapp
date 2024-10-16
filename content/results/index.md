+++
title = "DataViz"
weight = 4
extra.full_hero = false
extra.main_nav = true
+++
{% padded_block(bg="accent") %}
Here you can explore TAPP data visualized, both by waves and through our trend analysis. 
{% end %}
{{
shiny_app(url="https://tapp-shiny-app.blackisland-fad2c1bc.germanywestcentral.azurecontainerapps.io/",id="shiny1")
}}
{{gototop()}}
