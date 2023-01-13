---
title: Home
permalink: /
---

<div class='container'>
    <header class="masthead text-center">

      <img class='img-responsive center-block' src="" width="100%" height="100%" />

      <p>Research at the Music Cognition Lab seeks to understand the
way in which human <strong>listeners</strong> and
<strong>performers</strong> <strong>perceive</strong> and
<strong>appreciate</strong> <strong>music</strong>. This research
spans a wide range of <strong>psychological domains</strong>, from
<strong>low-level processes</strong> such as auditory stream
segregation to <strong>high-level musical experiences</strong> such as
aesthetic appreciation. The group makes use of a wide range of
research paradigms, including <strong>computational
modelling</strong>, <strong>neuroimaging</strong>, and
<strong>cognitive psychology</strong>.</p>

<p>The <strong>Music Cognition Lab </strong> is part of the <a
href="https://eecs.qmul.ac.uk/"><strong>School of Electronic
Engineering and Computer Science (EECS)</strong></a>, the <a
href="https://c4dm.eecs.qmul.ac.uk"><strong>Centre for Digital Music
(C4DM)</strong></a>, and the <strong><a
href="https://cogsci.eecs.qmul.ac.uk">Cognitive Science (CogSci)
Research Group</a></strong>, all institutions of <a
href="https://www.qmul.ac.uk/">Queen Mary University of
London</a>. The group is led by <strong><a
href="https://www.marcus-pearce.com"">Marcus Pearce</a></strong>.</p>

<!-- Collaborators --> 

      <div class="w3-container" style="   background: #f0f8ff; padding: 25px; border-radius:10px; border: 1px solid #5d8aa8">
        <div style="text-align:left">
          <h3> Recent News </h3>
          <span style="display: block; margin-bottom: 1em"></span>
          <div class="news">
              {% capture now %}{{'now' | date: '%s' | minus: 7776000 %}}{% endcapture %}
              <ul style="list-style-position:outside;padding:20px" >
                {% for new in site.data.news %}
                  {% capture date %}{{new.date | date: '%s' | plus: 0 %}}{% endcapture %}
                  {% if date > now %}
                    <li>
                      <span>
                        {{ new.details }}
                      </span>
                    </li>
                  {% endif %}
                {% endfor %}
              </ul>
          </div>
        </div >
      </div>

      <span style="display: block; margin-bottom: 3em"></span>
      School of Electronic Engineering and Computer Science, Queen Mary University of London, London E1 4NS, United Kingdom
      <span style="display: block; margin-bottom: 3em"></span>

      <hr>

    </header>


