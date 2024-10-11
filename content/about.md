---
# Leave the homepage title empty to use the site title
title:
date: 2023-03-10
type: landing

sections:
  - block: hero
    content:
      title: ABOUT ME
      # text: |2-
      #   I'm a fifth year Ph.D. student in Statistics at the University of Michigan and I am originally from Montreal, Canada. I previously worked as a Data Science intern at the Ubisoft Montreal User Research Lab on online skill rating algorithms using approximate Bayesian inference. I did a master’s thesis at the University of Montreal on an adaptive Multiple-Try Metropolis algorithm aimed at sampling from complex distributions. 

      #   My current research projects

      #   * Latent variable models using variational inference for node attribute imputation in network data (with [Prof. Ji Zhu](http://dept.stat.lsa.umich.edu/~jizhu/))
      #   * Bayesian functional factor models for EEG-based brain-computer interfaces (with [Prof. Jian Kang](http://www-personal.umich.edu/~jiankang/) and [Prof. Ji Zhu](http://dept.stat.lsa.umich.edu/~jizhu/))
      #   * Microbiome data analysis (with [Prof. Gen Li](https://sites.google.com/view/ligen) and [Prof. Ji Zhu](http://dept.stat.lsa.umich.edu/~jizhu/))
    design:
      columns: 2
      background:
        gradient_start: '#c31432'
        gradient_end: '#240b36'
        gradient_angle: 180
        text_color_light: true
        # image:
        #   filename: "stella_ai2.png"
        #   size: cover
        #   filters:
        #     brightness: 0.4
        #   parallax: false
  - block: experience
    content:
      title: EDUCATION
      date_format: Jan 2006
      items:
        - title: PhD in Statistics
          company: University of Michigan
          company_url: 'https://sites.lsa.umich.edu/'
          company_logo: um
          location: Ann Arbor, MI, USA
          date_end: 
          date_start: '2019-09-01'
          description: |2-
              Thesis: *Statistical models for dependent data*, supervised by [Prof. Ji Zhu](https://dept.stat.lsa.umich.edu/~jizhu/) and [Prof. Jian Kang](https://public.websites.umich.edu/~jiankang/)
        - title: MSc in Statistics
          company: University of Montreal
          company_url: 'https://dms.umontreal.ca/en/'
          company_logo: udem
          location: Montreal, Quebec, Canada
          date_start: '2016-09-01'
          date_end: '2019-05-01'
          description: |2-
              Thesis: *MCMC adaptatifs à essais multiples*, supervised by [Prof. Mylène Bédard](https://dms.umontreal.ca/~bedard/)
        - title: BSc in Probability & Statistics
          company: McGill University
          company_url: 'https://www.mcgill.ca/mathstat/'
          company_logo: mcgill
          location: Montreal, Quebec, Canada
          date_start: '2013-01-01'
          date_end: '2016-05-01'
          description: 
    design:
      columns: '2'
  - block: experience
    content:
      title: EXPERIENCE
      date_format: Jan 2006
      items:
        - title: Postdoctoral Scholar
          company: Pennsylvania State University
          company_url: 'https://www.psu.edu/'
          company_logo: psu
          location: University Park, PA, USA
          date_start: '2024-08-01'
          date_end: 
          description: |2-
              * Supervised by [Prof. Lingzhou Xue](https://sites.psu.edu/lingzhouxue/)
        - title: Graduate Student Research Assistant
          company: University of Michigan Medical School
          company_url: 'https://medicine.umich.edu/medschool/home'
          company_logo: um
          location: Ann Arbor, MI, USA
          date_start: '2021-09-01'
          date_end: '2022-12-31'
          description: |2-
              * Project: *Harnessing Opportunities to Screen for Esophageal Adenocarcinoma* (HOSEA)
              * In collaboration with researchers at the US Veterans Affairs Ann Arbor Healthcare System (VAAAHS)
              * Development of a predictive tool for early cancer detection ([K-ECAN](https://osf.io/tvu8z/))
              * Results published in [*Gastroenterology*](/publication/rubenstein-predicting-2023)
        - title: Graduate Student Instructor
          company: University of Michigan
          company_url: 'https://umich.edu'
          company_logo: um
          location: Ann Arbor, MI, USA
          date_start: '2020-01-01'
          date_end: '2022-08-30'
          description: 
        - title: Data Science Intern
          company: Ubisoft Montreal User Research Lab
          company_url: 'https://montreal.ubisoft.com/en/'
          company_logo: ubisoft
          location: Montreal, Quebec, Canada
          date_start: '2019-01-01'
          date_end: '2019-08-08'
          description: |2-
              * Project on online skill rating algorithms for online video games
              * Development, implementation and experimentation of various models to include additional information in the currently used algorithm
              * Development of solutions tailored to specific games
        - title: Teaching Assistant
          company: University of Montreal
          company_url: 'https://www.umontreal.ca/en/'
          company_logo: udem
          location: Montreal, Quebec, Canada
          date_start: '2017-01-01'
          date_end: '2018-12-31'
          description:
        - title: Grader
          company: McGill University
          company_url: 'https://www.mcgill.ca/'
          company_logo: mcgill
          location: Montreal, Quebec, Canada
          date_start: '2014-01-01'
          date_end: '2016-05-01'
          description: 
    design:
      columns: '2'
  - block: experience
    content:
      title: SERVICE
      date_format: Jan 2006
      items:
        - title: 2022 Organizer & 2023 Mentor
          company: Michigan Student Symposium for Interdisciplinary Statistical Sciences
          company_url: 'https://sites.lsa.umich.edu/mssiss/'
          company_logo: um
          location: Ann Arbor, MI, USA
          date_end: '2023-03-10'
          date_start: '2021-10-08'
          description: 
        - title: Reviewer
          company: Various journals
          company_url: 
          company_logo: 
          location: 
          date_end: 
          date_start: '2022-03-10'
          description: |2-
            * [Annals of Applied Statistics](https://imstat.org/journals-and-publications/annals-of-applied-statistics/) (4x)
            * [Journal of Computational and Graphical Statistics](https://www.tandfonline.com/journals/ucgs20) (1x)
            * [Biometrics](https://onlinelibrary.wiley.com/journal/15410420) (2x)
            * [Statistics in Medicine](https://onlinelibrary.wiley.com/journal/10970258) (2x)
    design:
      columns: '2'
  - block: accomplishments
    content:
      title: AWARDS
      subtitle:
      date_format: Jan 2006
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ""
          date_end: ""
          date_start: "2023-06-01"
          description: ""
          organization: Fond de Recherche du Québec -- Nature et Technologies
          company_logo: frq
          organization_url: https://frq.gouv.qc.ca/en/
          title: Doctoral Training Scholarship
          url: https://frq.gouv.qc.ca/en/program/frqnt-doctoral-training-scholarships/
        - certificate_url: ""
          date_end: ""
          date_start: "2022-05-01"
          description: ""
          organization: Department of Statistics, University of Michigan
          company_logo: um
          organization_url: https://lsa.umich.edu/stats
          title: Ph.D. Student Service Award
          url: ""
        - certificate_url: ""
          date_end: ""
          date_start: "2021-05-01"
          description: ""
          organization: Rackham Graduate School, University of Michigan
          organization_logo: um
          organization_url: https://rackham.umich.edu
          title: Rackham International Student Fellowship
          url: "https://rackham.umich.edu/funding/funding-types/rackham-international-student-fellowship-and-the-chia-lun-lo-fellowship/"
        - certificate_url: ""
          date_end: ""
          date_start: "2021-05-01"
          description: ""
          organization: Department of Statistics, University of Michigan
          organization_logo: um
          organization_url: https://lsa.umich.edu/stats
          title: Outstanding Graduate Student Instructor Award
          url: ""
        - certificate_url: ""
          date_end: ""
          date_start: "2020-05-01"
          description: ""
          organization: Department of Statistics, University of Michigan
          organization_logo: um
          organization_url: https://lsa.umich.edu/stats
          title: Outstanding First-year Student Award
          url: ""
        - certificate_url: ""
          date_end: ""
          date_start: "2019-05-01"
          description: ""
          organization: University of Montreal
          organization_logo: udem
          organization_url: https://www.umontreal.ca/
          title: Dean's Honor List
          url: "https://esp.umontreal.ca/a-propos/liste-dhonneur-du-recteur/#c179273"
        - certificate_url: ""
          date_end: ""
          date_start: "2018-05-01"
          description: ""
          organization: Department of Mathematics and Statistics, University of Montreal
          organization_logo: udem
          organization_url: https://dms.umontreal.ca/en/
          title: Serge-Tardif Fellowship
          url: "https://dms.umontreal.ca/en/resources/financial-support"
    design:
      columns: '2'
---
