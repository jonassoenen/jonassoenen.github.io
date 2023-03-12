---
# Leave the homepage title empty to use the site title
title:
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
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    id: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD in Machine Learning
          location: KU Leuven
          date_start: '2019-09-01'
          # date_end: '2023-09-01'
        - title: "Master in engineering: Computer Science"
          location: KU Leuven
          date_start: '2017-09-01'
          date_end: '2019-06-01'
        - title: "Bachelor in Computer Science"
          location: KU Leuven
          date_start: '2014-09-01'
          date_end: '2017-08-01'
        # - title: Professor of Semiconductor Physics
        #   company: University X
        #   company_url: ''
        #   company_logo: org-x
        #   location: California
        #   date_start: '2016-01-01'
        #   date_end: '2020-12-31'
        #   description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'

  - block: portfolio
    id: research
    content:
      title: Research Highlights
      filters:
        folders:
          - research
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Blogposts
      #     tag: blog
      #   - name: Presentations
      #     tag: presentation
      #   - name: Posters
      #     tag: poster
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  - block: markdown
    id: coaching
    content:
      title: Coaching
      subtitle: ''
      text: |-
        <table style = 'width:100%'> 
          <tr> <td> <h4> Master Thesis Supervision </h4> </td> <td style="text-align: right"> <em> 2019 - 2023 </em>  </td> </tr>
        </table>
        <p > I coached 8 master students to the succesfull completion of their thesis. <a data-toggle="collapse" data-target="#thesis-details"> <em style='font-size:0.8rem'>(expand details)</em> </a></p>

        <div id="thesis-details" class="collapse">
          <table class='table'> 
            <thead>
              <tr> <th> Student </th> <th> Thesis title </th> <th> Year </th> </tr>
            </thead>
            <tbody> 
              <tr> <td> <em> Clara De Smet </em> </td> <td>  Improving the initialisation of COBRAS </td> <td style='min-width: 6rem'>  2019-2020</td> 
              <tr> <td> <em>  Pablo Lopez Pantoja </em> </td> <td>  Active semi-supervised clustering with uncertain constraints </td> <td>  2019-2020</td> 
              <tr> <td> <em>  Nicholas Jankelevitch </em> </td> <td>  Oplossen van don’t-know beperkingen in actief semi-supervised clusteren </td> <td>  2020-2021</td> 
              <tr> <td> <em>  Elias Iblisdir </em> </td> <td>  Actief half-gesuperviseerd clusteren met ruis </td> <td>  2021-2022</td> 
              <tr> <td> <em>  Jonas Scheldeman </em> </td> <td> Het toevoegen van zwakke dependencies tussen attributen in dependency-based anomaliedetectie </td> <td>  2021-2022</td> 
              <tr> <td> <em>  Maarten Pyck </em> </td> <td>  Clustering with user feedback </td> <td>  2022-2023</td> 
              <tr> <td> <em>  Anthony Van Loon </em> </td> <td>   It is likely not to be so likely! Semi-supervised calibration of anomaly scores </td> <td> 2022-2023</td>
              <tr> <td> <em>  Jan Kranzen </em> </td> <td>  Generating residential electricity consumption scenarios with conditional generative neural networks </td> <td>  2022-2023 </td>  
            </tbody> 
          </table> 
        </div>
       
        <table style = 'width:100%'> 
          <tr> <td> <h4> Bachelor Thesis Supervision </h4> </td> <td style="text-align: right"> <em> 2019 - 2022 </em>  </td> </tr>
        </table>
        <p> I coached several teams of third year engineering and computer science students to design an implement a medium sized software application during the course "Probleemoplossen en ontwerpen: computerwetenschappen".   <a data-toggle="collapse" data-target="#PO-details"><em style='font-size:0.8rem'>(expand details)</em> </a></p>
        <div id="PO-details" class="collapse">
          <table class='table'> 
            <tbody> 
              <tr> 
                <td style='min-width: 6rem'> 2019-2020 </br> 2021-2022 </td> 
                <td> CatCaster, a game played on multiple computers with one or more screens and controlled with multiple mobile phones. After detecting the relative position and orientation of the screens using a picture taken by one of the mobile phones, each player controls a cat by moving his/her mobile phone. </td> 
              </tr>
              <tr> 
                <td> 2020-2021 </td> 
                <td> A chat app with some security guarentees, distributed architecture, and a virtual world where avatars walk around and interact with each other.  </td> 
              </tr>
            </tbody> 
          </table> 
        </div>
    design:
      columns: '2'
  - block: markdown
    id: teaching
    content:
      title: Teaching Assistant
      subtitle: ''
      text: |-
        <table style = 'width:100%'> 
          <tr> <td> <h4> Programming Fundamentals </h4> </td> <td style="text-align: right"> <em> 2017 - 2019 </em>  </td> </tr>
        </table>
        <p> As a master student, I taught Python to first year computer science students. </p>

        <table style = 'width:100%'> 
          <tr> <td> <h4> Proofs and Reasoning for Computer Scientists </h4> </td> <td style="text-align: right"> <em> 2019 - 2023 </em>  </td> </tr>
        </table>
        <p> During my PhD, I taught mathematical proofs basic mathematical concepts to first year computer science students.  </p>
    design:
      columns: '2'
  

  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        TODO list all my publications
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: features
    content:
      title: Activities
      subtitle: ''
      text: ''
      items:
        - name: Climbing
          description: Bouldering, Gym climbing
          icon: 🧗🏻‍♂️
          icon_pack: emoji
        - name: Cooking ...
          description: and eating 😋
          icon: 🍴
          icon_pack: emoji
        - name: Listening & Reading
          description: Music, Podcasts, Audiobooks </br> Sci-fi, Adventure, Informative books
          icon: 🎧📖
          icon_pack: emoji
        # - name: Reading
        #   description: Both Fiction and informative books
        #   icon: 📖
        #   icon_pack: emoji

---
