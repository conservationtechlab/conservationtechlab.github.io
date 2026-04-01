---
layout: default
title: People
description: Meet the Conservation Tech Lab team
---

<div class="container">
  <h2 class="section-title">People</h2>
  <p style="text-align: center; color: #666; margin-bottom: 2rem;">
    Meet the people who make the Conservation Technology Lab possible: staff, fellows, volunteers, partners, and alumni.
  </p>

  {% comment %}
    For each group below we call the include that renders a responsive grid of cards.
    Adjust ordering by editing _data/people.yml
  {% endcomment %}

  {% comment %} Render the lead (Ian Ingram) on its own row {% endcomment %}
  {% assign head1 = site.data.people.lab | where: "id", "mtobler" %}
  {% assign head2 = site.data.people.lab | where: "id", "iingram" %}
  {% assign head = head1 | concat: head2 %}
  {% include people-cards.html collection=head title="Lab" %}

  {% comment %} Render the rest of the lab members {% endcomment %}
  {% assign lab_others = site.data.people.lab | where_exp: "person", "person.id != 'iingram'" %}
  {% include people-cards.html collection=lab_others title="" %}

  {% include people-cards.html collection=site.data.people.fellows title="Fellows" %}
  {% include people-cards.html collection=site.data.people.volunteers title="Volunteers" %}
  {% include people-cards.html collection=site.data.people.partners title="Partners" %}
  {% include people-cards.html collection=site.data.people.former_members title="Former Members" %}
</div>