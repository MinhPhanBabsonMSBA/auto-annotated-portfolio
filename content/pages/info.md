---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      #### Hi, I’m Mike Phan, a Master’s student in Business Analytics at Babson
      College with a passion for solving real-world problems through data. I
      specialize in turning raw data into clear, actionable insights using tools
      like Python, R, SQL, and BI platforms like Tableau and Power BI. My
      interests lie at the intersection of analytics, machine learning, and
      strategy—and I love building projects that combine technical rigor with
      real impact. Whether it’s predicting stock prices, segmenting customers,
      or tackling unexpected challenges like flight delays, I’m always looking
      for new ways to turn data into decisions.

    media:
      type: ImageBlock
      url: /images/IMG_8525-2.jpg
      altText: Hero image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: right
        flexDirection: row
    type: HeroSection
    actions: []
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: ''
    items:
      - type: Label
        label: SQL
      - type: Label
        label: 'Python (NumPy, Pandas, Matplotlib) '
      - type: Label
        label: 'R (Statistics, Machine Learning) '
      - type: Label
        label: ' Alteryx'
      - type: Label
        label: SAS Analytics
      - type: Label
        label: Jira Project Management
      - type: Label
        label: 'Visualization Tools: Tableau | Power BI | Google Looker Studio'
      - type: Label
        label: >-
          Cloud: AWS (S3, EC2, Crawler, CloudWatch, Glue, Athena, Lambda,
          Redshift) | GCP (Bucket, Mage Compute Engine,Big query)
    title: My Skills
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |+
          **Jun 2022 - August 2022**

          *   Technology Consultant - Pyramid Software and Consulting











        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        subtitle: 'Education:'
        text: "**2024-2025**\n\n*   M.S. in Business Analytics Candidate at BABSON COLLEGE, F.W. OLIN GRADUATE SCHOOL OF BUSINESS, Wellesley, MA\_\n\n\n\n\n\n**2021 - 2024**\n\n*   Bachelor of Science, Information Technology at NORTHEASTERN UNIVERSITY, Boston, MA\_\n\n    GPA: 3.65 / 4.0 (Cum Laude)\n\n"
        styles:
          self:
            textAlign: left
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
