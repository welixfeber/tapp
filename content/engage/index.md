+++
title="Engage"
weight = 2
extra.full_hero = false
extra.main_nav = false
+++
{% block_2c(left_text="Want to be a part of it?" bg="accent") %}
Below you can find how to become involved in this project.
{% end %}

{{ block_2c(
left_text="Join"
bg="primary"
color="white"
) }}

{{ big_cards(
    
    bg="grey"
    card_bg="primary"
    color="white"
    title_color="accent" 
    data_path="engage/join.toml"
    
)}}
{{ block_2c(
 left_text="Interact"
 bg="white") }}
{{ big_cards(
    
    bg="grey"
    card_bg="primary"
    color="white"
    title_color="white" 
    data_path="engage/engage_1.toml"
    
)}}
{{ block_2c(left_text="Or simply" bg="accent") }}
{{ 
mailchimp_form(top_text="Subscribe to receive our latest research updates",subscribe_text="I would like to receive email communications from TAPP and agree with the data protection regulations and the described processing of personal data there.")
}}
