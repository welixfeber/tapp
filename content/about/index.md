+++
title = "People"
weight = 5
extra.full_hero = false
extra.main_nav = true
#extra.hide_title= true
extra.sub_nav =["Team","Topic Partner"]
+++

{% block_1c(title="Who's behind the work" bg="accent") %}
Our team comprises experts from the most diverse areas and Universities and Institutes.
{% end %}

{{ anchor(title="Team")}}
{{
  gallery_person(
    data_path="people/members.toml"
    image_path="people/"
  )
}}
{{ anchor(title="Topic Partner")}}
{% block_1c(title="Topic Partner" bg="accent") %}
We are excited to introduce the upcoming Topic Partner Program, an initiative designed to enhance the preparation of our annual survey. Individuals from different disciplines can join us as Topic Partners for a one-year term, where they will have the unique opportunity to propose topics and participate in the decision-making process regarding topic submissions.

This collaborative approach ensures that TAPP remains relevant and comprehensive, reflecting a diverse range of perspectives and ideas. By involving Topic Partners, we aim to foster a deeper engagement with our community and enhance the overall quality and impact of our work.

If you are passionate about contributing to meaningful discussions and have expertise in areas relevant to our survey (anyone who is actively engaged in the AI and privacy debate), we encourage you to consider becoming a Topic Partner. Together, we can make a significant difference in gathering and analyzing data that matters.

{% end %}
