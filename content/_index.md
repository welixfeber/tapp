+++
title = """Exploring <span class="block md:inline"> AI and Privacy <span class="block md:inline"><span class='test' data-words='Challenges,Attitudes,Perceptions,Trends,Issues' data-shuffle='true'></span>
with Influential <span class="block md:inline">Voices and <span class="block md:inline">Experts"""
sort_by = "weight"
extra.full_hero = true
+++

{% block_2c(bg="grey" left_text="The Transatlantic Privacy Perceptions Project (TAPP) is a fully funded, independent research initiative that provides in-depth analysis of AI and digital privacy perceptions from experts in industry, law, NGOs, and academia across Europe and the USA.") %}
 We ([→ Team](@/people/index.md)) provide survey infrastructure and methodology knowledge to give experts opportunities to __raise awareness__ about the privacy issues they care about, thereby contributing to public debate and enhancing scientific research that can __improve policymaking and technological design ([→ DataViz](@/results/index.md) and [→ Findings](@/findings/index.md))__.  

Initiated in 2022, TAPP has completed five waves of quantitative surveys, a round of in-depth interviews, and is preparing to go into the field with wave 6 in 2024. With increasing interest in the survey and growing participation rates, we aim to expand our research scope to include regions with emerging privacy debates, such as Africa and Latin America. 
{% end %}

{{latest_news(
title="Latest News"
   data_path="news/news.toml"
    more_news="news/_index.md"
)}}

{%slideshow(
title="Why participate"
   data_path="testimonies.toml"
)%}
By sharing your thoughts and outlook on current and emerging digital privacy issues, your participation will contribute to informing policymakers and companies internationally about digital privacy trends and concerns and how they can best be addressed in policy and technological design.\
As a panel participant, you will get exclusive, tailored updates about our findings via email.
{% end%}
{{ 
mailchimp_form(top_text="Subscribe to receive our latest research updates",subscribe_text="I would like to receive email communications from TAPP and agree with the data protection regulations and the described processing of personal data there.")
}}
