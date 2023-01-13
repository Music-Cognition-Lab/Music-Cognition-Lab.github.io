---
title: Home
permalink: /home
---

<div class='container'>
    <header class="masthead text-left">

      <img class='img-responsive center-block' src="" width="100%" height="100%" />

      <p>Research at the Music Cognition Lab seeks to understand the
way in which human listeners and
performers perceive and
appreciate music. This research
spans a wide range of psychological domains, from
low-level processes such as auditory stream
segregation to high-level musical experiences such as
aesthetic appreciation. The group makes use of a wide range of
research paradigms, including computational
modelling, neuroimaging, and
cognitive psychology.</p>

<p>The Music Cognition Lab  is part of the <a
href="https://eecs.qmul.ac.uk/">School of Electronic
Engineering and Computer Science (EECS)</a>, the <a
href="https://c4dm.eecs.qmul.ac.uk">Centre for Digital Music
(C4DM)</a>, and the <a
href="https://cogsci.eecs.qmul.ac.uk">Cognitive Science (CogSci)
Research Group</a>, all institutions of <a
href="https://www.qmul.ac.uk/">Queen Mary University of
London</a>. The group is led by <a
href="https://www.marcus-pearce.com">Marcus Pearce</a>.</p>

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

    </header>


