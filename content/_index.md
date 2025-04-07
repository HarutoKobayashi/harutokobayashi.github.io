---
title: 'Haruto Kobayashi'
date: 2025-02-12
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: edu_and_work
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true

  # 少なくともこのテンプレートでは、 blockとして自由な名称を指定できない
  # username は自由に指定できる
  # 以上2点から、新たに publication dir を作成し、Publication に関わる情報は publication/_index.md 内の awards に記載することにした
  - block: awards
    content:
      title: Domestic Conferences / Symposium
      username: publication

  - block: awards
    content:
      title: Awards
      username: awards

  - block: experience
    content:
      title: Activities
      username: activities
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
---
