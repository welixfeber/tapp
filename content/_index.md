+++
title = """Exploring <span class="block md:inline"> Digital Privacy <span class="block md:inline"><span class='test' data-words='Challenges,Attitudes,Perceptions,Trends,Issues' data-shuffle='true'></span>
with Influential <span class="block md:inline">Voices and <span class="block md:inline">Experts"""
sort_by = "weight"
extra.full_hero = true
extra.subtitle="An interdisciplinary research project conducted by a team of researchers in privacy, survey methodology, and complex sampling techniques at the Universities of Maryland and Munich."
+++

{% block_2c(bg="grey" left_text="The Transatlantic Privacy Perceptions Project (TAPP) is a fully funded, independent research initiative that provides an in-depth analysis of AI and digital privacy perceptions from experts in industry, law, NGOs, and academia across Europe and the USA.") %}
 We, based at the Universities of Maryland and Munich ([see Team](@/people/index.md)), provide survey infrastructure and methodology knowledge to give the experts opportunity to __raise awareness__ about the privacy issues they care about and contribute to scientific research that can __improve policymaking and technological design ([see DataViz](@/results/index.md)) and ([Findings](@/findings/index.md))__.    

Initiated in 2022, TAPP has completed four waves of quantitative surveys, a round of in-depth interviews, and is preparing to go into the field with waves 5 and 6 in 2024. With increasing interest in the survey and growing participation rates, we aim to expand our research scope to include regions with emerging privacy debates, such as Africa and Latin America. 
{% end %}

{{latest_news(
title="Latest News"
   data_path="news/news.toml"
    more_news="news/_index.md"
)}}

{% block_2c(title="Our mission" left_text="The Transatlantic Privacy Perceptions Project" bg="primary" color="white") %}
- gives **digital privacy** a voice in the AI era
 
- harvests and channels diverse perspectives

- creates data for public debate and __policy making__

- guides with best practices and identifies role models
{% end %}
{%slideshow(
title="Why participate"
   data_path="testimonies.toml"
)%}
By sharing your thoughts and outlook on current and emerging digital privacy issues, your participation will contribute to informing policymakers and companies internationally about digital privacy trends and concerns and how they can best be addressed in policy and technological design.\
Call for action: Join the survey! Become TAPP Participant or alike
{% end%}
{{ 
mailchimp_form(top_text="Subscribe to receive our latest research updates",subscribe_text="I would like to receive email communications from TAPP and agree with the data protection regulations and the described processing of personal data there.")
}}
