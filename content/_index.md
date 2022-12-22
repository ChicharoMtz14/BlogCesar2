---
# Leave the homepage title empty to use the site title
title: The Great B Project
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: FAQ
      items:
        - name: How often do you post?
          description: At least once a week (depends on mood + agenda)
          icon: file-circle-plus
          icon_pack: fas
        - name: LinkedIn and now this?
          description: You will have more fun over here, trust me.
          icon: linkedin-in
          icon_pack: fab
        - name: Just... why?
          description: Felt like giving blogging a try. 
          icon: question
          icon_pack: fas
          
  - block: experience
    content:
      title: Academic Background
      subtitle: Alright, this bit is actually kind of what you see at LinkedIn...
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Economics Major
          company: Tecnológico de Monterrey
          company_url: https://tec.mx/es
          company_logo: tec
          location: Monterrey, Mexico
          date_start: '2022-08-01'
          date_end: ''
          description: |2-
              Aug-Dec '22 Final Grade: 99.8/100 
              
              Key Academic Courses:
              * Political Philosophy (Score: 100/100)
              * Programming Principles for Social Sciences (100/100)
              * Contemporary Transformation of Mexico (99/100)
              
              Extracurricular Activities:
              * Logistics Director for Tec's 41st International Economics Symposium
              * Finalist at Tec's 20th "ExpoIngenierías" Engineering Exposition
              
        - title: International Baccaulaureate (Diploma Program)
          company: International Baccaulaureate - Tecnológico de Monterrey
          company_url: https://ibo.org/
          company_logo: LogoIB
          location: Monterrey, Mexico
          date_start: '2019-08-01'
          date_end: '2021-05-31'
          description: |2-
              Final IB Score: 39/45 
              
              Key Academic Courses:
              * Mathematics Higher Level (Score: 7/7)
              * Computer Science Standard Level (7/7)
              * Global Politics Higher Level (6/7)
              
              Extracurricular Activities:
              * Best Delegate at The English School's TESMUN XVII (2021)
              * Selected Candidate at Wellington Leadership Institute's Global Social Leaders event (2021)   
              * FGA's Best Delegate at Markham College's 2020 International MUN
              * Keyboardist for Tec's "JAM 17" musical event (2019) 
          
        - title: Multicultural High School Diploma
          company: Tecnológico de Monterrey
          company_url: https://tec.mx/es
          company_logo: tec
          location: Monterrey, Mexico
          date_start: '2018-08-01'
          date_end: '2021-05-10'
          description: |2-
              Overall High School Grade: 98.4/100
              
              Key Academic Courses:
              * World History (Score: 98/100)
              * Spanish and Latin American Literature (99/100)
              * Digital Expression and Design (100/100)
              
              Extracurricular Activities:
              * Member of PrepaTec EGL Campus's Representative Soccer Team (2019-2021)
              * Finance staff member at Tec's BELIEVE Youth Congress (2018)

    design:
      columns: '2'
      
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading (Accomplish&shy;ments).
      title: 'Courses and Certificates'
      subtitle: Perfect complements for the standard academic upbringing and professional excellence
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://educacionfinanciera.condusef.gob.mx/CertificadoCondusef/FinPersonales/verifify_certificate.php?token=8ee36250-bebf-49b4-a9ae-125ffa20b3a5
          date_end: '2022-05-01'
          date_start: '2022-04-25'
          description: '* Fundamental principles about budgeting, investing, and identyfing potential frauds'
          organization: CONDUSEF
          organization_url: https://www.gob.mx/condusef
          title: Financial Education for Everyone
          url: 'https://cursoenlinea.condusef.gob.mx/'
        - certificate_url: https://educacionfinanciera.condusef.gob.mx/DiplomadoSeguros/customcert/verifify_certificate.php?token=66867xe2afceac9c51a3cd751b87eaf4cf0236x69881185b9fa72580cd21c2e83ee63924574b357
          date_end: ''
          date_start: '2022-05-01'
          description: |2-
            * Studied the history and intricacies of contemporary insurance policies' bureaucratic structure
            * Learned how to select convenient commercial insurance options based on their description
          organization: CONDUSEF
          organization_url: https://www.gob.mx/condusef
          title: Certificate on Insurance Policies
          url: https://educacionfinanciera.condusef.gob.mx/DiplomadoSeguros/
        - certificate_url: https://drive.google.com/file/d/1fjMg1vi7yvYLWgfl-wdNrdQLWmVax3lx/view?usp=sharing
          date_end: '2022-08-21'
          date_start: '2021-08-01'
          description: |2-
            * Learned about 23 different investment options within the Mexican and the international financial markets
            * Practiced with theoretical scenarios using the aforementioned financial instruments
            * Realized specialized research on the subject alongside other participants 
          organization: MorisDieck
          organization_url: https://morisdieck.com/
          title: '23 Investments in 1 Year'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: |2-
        This is where the oversharing part starts. 
        
        <strong>Disclaimer</strong>: Multilinguism lies ahead. Translations are on their way, be patient. Thanks :)
        
        Click <strong>[here](./categories/)</strong> to see all content categories. 
      text:
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        folders:
          - post
        author:
        category:
        tag:
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: experiences
    content:
      title: Experiences
      subtitle: Some of the projects and adventures that I've enjoyed the most in recent times.
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Volunteering
          tag: volunteering
        # - name: Other
        #  tag: Demo
        - name: Tec
          tag: Tec
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: markdown
    content:
      title: Gallery
      subtitle: 'There are moments with people and by yourself that just need to be captured forever.'
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: publicationsandresearch
    content:
      title: Featured [Publications & Research](./publication/)
      subtitle: You may review some of my recent works within the global academic field. Click on the title above to see all the available documents. 
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
  - block: collection
    id: languagecorner
    content:
      title: L[anguage Corner](./event/)
      subtitle: Buckle up, people, 'cause it's about to get international in here.
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Whether that is feedback, networking or advertising offers, don't be shy, I am more than happy to get in touch with all of you. 
      # Contact (add or remove contact options as necessary)
      email: cesar14martinez2021@gmail.com
      phone: +52 81 8473 8642
      # appointment_url: 'https://calendly.com'
      address:
        street: 2501 Eugenio Garza Sada Ave.
        city: Monterrey
        region: Nuevo León
        postcode: '64849'
        country: Mexico
        country_code: MX
      directions: I spend most of my time at Campus' library. Come by to say hi!
      office_hours:
        - 'Monday - Friday 09:00 to 17:00'
        - 'Saturday 09:00 to 14:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/messages/compose?recipient_id=1066151540891766784&text=Hello%20there!%20I’ve%20got%20a%20message%20for%20you…'
        # - icon: skype
          # icon_pack: fab
          # name: Skype Me
          # link: 'skype:echo123?call'
        # - icon: video
          # icon_pack: fas
          # name: Zoom Me
          # link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: gmail
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
