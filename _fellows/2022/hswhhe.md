---
layout: fellow
pagetype: fellow
shortname: hswhhe
permalink: /fellows/hswhhe.html
fellow-name: Haoran Sun
title: Haoran Sun - IRIS-HEP Fellow
active: false
dates:
  start: 2022-06-20
  end: 2022-09-21
photo: /assets/images/team/fellows-2022/Haoran-Sun.jpg
institution: University of Washington
e-mail: hsun3@uw.edu
project_title: Enabling support for MiniAOD Transformer for ServiceX Data Delivery
  Service
project_goal: >
  The func_adl data query language has two backends that are currently part of ServiceX
  - one based on C++ for ATLAS data and CMS data, and one based on columnar processing
  using uproot and awkward arrays. The C++ backend currently runs only on the ATLAS
  binary format (xAOD) and CMS binary format (CMS AOD). This project aims to create
  an interface similar to the existing func_adl_xAOD repository, where both CMS AOD
  and ATLAS xAOD backends are available, such that the user can send hierarchical
  SQL-like queries to a MiniAOD backend. The project also includes the required modifications
  of the C++ ServiceX backend to allow processing the publicly available CMS MiniAOD
  binary files.
mentors:
- Gordon Watts (University of Washington)
- Benjamin Galewsky (NCSA)
- Oksana Shadura (University of Nebraska - Lincoln)
- Mason Proffitt (University of Washington)
- Alexander Held (New York University)
proposal: /assets/pdf/fellows-2022/071-proposal-Haoran-Sun.pdf
github-username: hswhhe
presentations:
- title: Support for MiniAOD Transformer for ServiceX
  date: 2022-10-19
  url: https://indico.cern.ch/event/1199559/contributions/5097282/
  meeting: IRIS-HEP Fellows Presentations 2022
  meetingurl: https://indico.cern.ch/event/1199559/
  recordingurl: https://youtu.be/gEaqn7C9ipY?t=2994
  location: Virtual
  focus-area: as
  project:
current_status:
linkedin-profile: https://www.linkedin.com/in/haoran-sun-3712ba211/
focus-area:
challenge-area:
funding-source: nsf
---