---
layout: colab-page
permalink: /news
---
<br>
This page overviews resources and community groups to follow for the latest DH news and job boards to find career opportunities in DH. There’s naturally overlap between news sources and job boards in the broad field of digital humanities (DH), so we have included sources that promote announcements, workshops, calls for proposals, and job postings in the following lists.

## Current Opportunities
<div class="flex-inner">
{% for post in site.posts %}
<div class="card">
  <img src="{{ post.img }}" style="width:100%">
  <div class="card-container">
     <a href="{{ post.url }}">{{ post.title }}</a>
     <div class="categories">
      {% for category in post.categories %}
        <a href="/category/{{ category }}">category: {{ category }}</a>
      {% endfor %}
     </div>
  </div>
</div>
{% endfor %}
</div>


## Finding Opportunities
Careers in digital humanities span several fields and can be based in many settings: cultural heritage institutions like galleries, libraries, archives and museums (GLAM institutions), research positions in academic and educational institutions, community and nonprofit organizations, data and information technology settings, and many more. As such, some of these sources may promote some job types over others.

### Job boards and DH news listservs
- Association for Computers and the Humanities news
- Critical Digital Humanities Initiative and Digital Humanities Network newsletter from the University of Toronto
- The Digital Classicist communities
- Digital Library Federation Job board and Digital Library Federation email lists
- Digital Humanities Slack Space (which has a “jobs” channel)
- DH+Lib job board
- DH Now
- Digital Humanities Summer Institute List, hosted by the University of Victoria
- HathiTrust Digital Library and Research Center newsletter
- LifexCode and Black Beyond Data joint listserv
- Teaching with Primary Sources (TPS) Collective

### Cornell University listservs

Cornell University Library’s Digital Humanities listserv has been a longstanding source for local news and announcements. The Digital Humanities Initiative (DHI) listserv features relevant events facilitated by the DHI steering team.

We also highlight news and opportunities related to digital scholarship from communities around Cornell, including (but not limited to):

- Cornell Center for Social Sciences (workshops page)
- Cornell Data Services newsletter
- Cornell Bowers College of Computing and Information Science newsletter
- Media Studies Program listserv (MEDIA-STUDIES-L). Follow the directions at this link to subscribe.
- Society for the Humanities newsletter

### Fellowships for graduating Master’s or PhD students

- CLIR Postdoctoral Fellowship Program: “Offers recent Ph.D. graduates the chance to develop research tools, resources, and services while exploring new career opportunities.”
- Kluge Fellowships in Digital Studies
- Library of Congress online internships and fellowships
- Residency Interest Group of the Association for College and Research Libraries: Find opportunities for residencies and term-limited fellowships for library and information science (LIS) professionals.

### Additional support

If you’d like additional support in your job search, contact Cornell Career Services. Services are available to students, staff, faculty, alumni, parents and families.