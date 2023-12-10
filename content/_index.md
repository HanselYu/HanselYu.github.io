---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: News
      text: <li><strong>Nov. 2023:</strong> Our paper UniKP&#58; a unified framework for the prediction of enzyme kinetic parameters has been accepted by Nature Communications! </li> <li><strong>Jul. 2023:</strong> I presented an academic speech titled "A Unified Framework For the Prediction of Enzyme Kinetic Parameters" at the Synthetic Biointelligent Manufacturing Conference in Shenzhen.</li> <li><strong>Dec. 2022:</strong> I was honored with the SIAT Dean's Scholarship and the Isynbio's Dean's Innovation Award! </li> <li><strong>Oct. 2022:</strong> Our paper <a href="https://academic.oup.com/bib/article/24/1/bbac476/6834141">IPPF-FE&#58; an integrated peptide and protein function prediction framework based on fused features and ensemble models</a> has been accepted by Briefings in Bioinformatics!</li>
    design:
      columns: '2'
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Intern
          company: Syneron Tech
          company_url: ''
          company_logo: org-gc
          location: Beijing
          date_start: '2022-08-01'
          date_end: '2022-11-01'
          description: Protein & peptide sequence analysis, working with Prof. [Xin Gao](https://cemse.kaust.edu.sa/sfb).
        - title: Summer School
          company: Tsinghua University
          company_url: ''
          company_logo: org-x
          location: Beijing
          date_start: '2022-07-01'
          date_end: '2020-08-31'
          description: The project of Mars Smart Cell Factory, working with Prof. [Tong Si](https://isynbio.siat.ac.cn/sitonglab/).
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: patents
    content:
      title: Patents
      text: <li><strong>May 2023:</strong> 酶动力学参数预测方法、电子设备及存储介质 </li> <li><strong>May 2023:</strong> 酶动力学参数预测模型训练与预测方法及相关设备 </li> <li><strong>May 2023:</strong> 蛋白质鉴定方法、电子设备及存储介质 </li> <li><strong>Apr. 2023:</strong> 一种酶动力学参数预测方法及装置 </li> <li><strong>Sep. 2022:</strong> 基于多序列比对的酶序列生成方法、装置、介质和设备 </li> <li><strong>Mar. 2022:</strong> 特征选择方法、特征选择装置、存储介质和设备 </li> <li><strong>Dec. 2021:</strong> 基于人工智能创制的高附加值代谢物底盘 </li> <li><strong>Nov. 2021:</strong> 基于自动化技术构建的高附加值代谢物智能细胞工厂 </li> <li><strong>Jun. 2021:</strong> 高热稳定性酶的蛋白序列生成方法、装置、介质和设备 </li>      
    design:
      columns: '2'
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2023-12-31'
          description: ''
          organization: Shenzhen Institute of Synthetic Biology Innovation
          organization_url: ''
          title: 优秀党务工作者
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2022-12-31'
          description: ''
          organization: Shenzhen Institute of Advanced Technology
          organization_url: ''
          title: SIAT Dean's Scholarship
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2022-12-31'
          description: ''
          organization: Shenzhen Institute of Synthetic Biology Innovation
          organization_url: ''
          title: Dean's Innovation Award
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2020-06-31'
          description: ''
          organization: Chongqing Municipal Education Commission
          organization_url: ''
          title: Excellent Graduates
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2019-09-01'
          description: ''
          organization: Ministry of Education, PRC
          organization_url: ''
          title: National Scholarship
          url: ''
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'  
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
