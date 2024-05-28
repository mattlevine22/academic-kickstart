---
# Display name
title: Matthew Levine

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: Postdoctoral Fellow

# Organizations/Affiliations
organizations:
- name: Eric and Wendy Schmidt Center
  url: "https://www.ericandwendyschmidtcenter.org"
- name: Broad Institute of MIT/Harvard
  url: "https://www.broadinstitute.org/ewsc"


# Short bio (displayed in user profile at end of posts)
bio:

interests:
- Dynamical Systems
- Machine Learning
- Data Assimilation
- Biomedicine

education:
  courses:
  - course: PhD in Computing + Mathematical Sciences
    institution: Caltech
    year: 2023
  - course: BA in Biophysics
    institution: Columbia University
    year: 2015

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: "mailto:mlevine@caltech.edu"  # For a direct email link, use "mailto:mlevine@caltech.edu".
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.com/citations?user=QUs08XEAAAAJ&hl=en&authuser=1
- icon: github
  icon_pack: fab
  link: https://github.com/mattlevine22
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
- icon: cv
  icon_pack: ai
  link: files/CV_MatthewLevine.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
#- Researchers
#- Visitors
---

Welcome! I am a Postdoctoral Fellow at the Broad Institute of MIT/Harvard in the Eric and Wendy Schmidt Center. My work focuses on improving the prediction and inference of biological and physical systems by blending machine learning, mechanistic modeling, and data assimilation techniques. I aim to build robust, unifying theory for these approaches, as well as develop concrete applications. I have worked substantially in the biomedical sciences, and enjoy collaborating on impactful applied projects.

I am always interested in developing new collaborations. If you think our work is complementary, please send me a message!

Updates:

- May 2023: New Jax repository, [CD_Dynamax](https://github.com/hd-UQ/cd_dynamax) (joint with [Iñigo Urteaga](http://iurteaga.github.io)) for learning dynamical systems from irregularly sampled, partially observed, noisy time-series data (extends discrete-time state-space approach in [Dynamax](https://github.com/probml/dynamax)). Flexible model implementation allows for user-specified combinations of mechanistic/physical and machine-learnt/data-driven terms. Autodifferentiable implementations of filtering/data-assimilation algorithms from [Särkkä 2006](https://aaltodoc.aalto.fi/server/api/core/bitstreams/f0fc3ccb-b2e6-4fd7-ba40-8ce6e096b303/content) for computing approximate likelihoods for non-linear systems. Stochastic Gradient Descent for approximate MLE; Hamiltonian Monte Carlo MCMC for uncertainty quantification.

- August 2023: I co-organized a [minisymposium on randomized machine learning at ICIAM 2023 in Tokyo](https://iciam2023.org/registered_data?id=00831) with Oliver Dunbar, Nick Nelsen, and Georg Gottwald. Thank you to our wonderful speakers, attendees, and co-organizers for such enriching sessions!

- July 2023: I visited Prof. Iñigo Urteaga at the Basque Center for Applied Mathematics (BCAM) in Bilbao, Spain. Thank you to Iñigo and BCAM for hosting me! I look forward to continuing our collaboration on [uncertainty quantification for hybrid dynamical models](https://www.bcamath.org/en/news-events/events/bcam-scientific-seminar-combining-data-assimilation-and-neural-odes-learning).

- May 2023: I defended my PhD thesis [Machine Learning and Data Assimilation for Blending Incomplete Models and Noisy Data](https://thesis.library.caltech.edu/15264/). I graduated with a PhD in computing and mathematical sciences at Caltech advised by Andrew Stuart. I am grateful to Andrew for his mentorship and support throughout my PhD. I am also grateful to my committee members, Yisong Yue, Houman Owhadi, and Katie Bouman for their insightful feedback and guidance.