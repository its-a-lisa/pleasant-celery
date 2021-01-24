---
title: About OpenControl
meta_title: ''
meta_description: ''
canonical_url: about
no_index: false
sections:
  - section_id: About OpenCtonrol
    title: Our Philosophy
    content: "## It’s a powerfully simple idea.\n\nTo improve the quality of our software development, we use continuous integration. To improve the reliability of our deployment, we use continuous delivery. To improve the security of our systems, we can use continuous authorization.\n\nSimply put, the tools that we use to develop and operate software, should also be used to generate and validate assessment and authorization packages.\n\nEvery commit runs the tests. Every passing build, updates the system security plan. Every deployment includes updates to continuous monitoring.\n\n> Software as Code.\n\n> Tests as Code.\n\n> Infrastructure as Code.\n\n> Compliance as Code.\n\n## It’s a schema.\n\nBy adopting a standard approach to documenting “controls” (whether Technical, Operational, or Management) we can rapidly build a community of vendors and operators. You can see\_[the current (and evolving) OpenControl schema here](https://github.com/opencontrol/schemas).\n\n## It’s a set of tools and best practices.\n\nRight now we’re excited about:\n\n*   [Compliance Masonry](https://github.com/opencontrol/compliance-masonry)\n\n*   [Concourse CI](https://concourse-ci.org/)\n\nMore\_[GitHub.com/opencontrol](https://github.com/opencontrol)\n\n## It’s a community.\n\nThis community includes vendors that provide documentation of controls in a standard schema, government agencies and other regulators that document certifications in another schema, and operators who use the OpenControl process to authorize their systems.\n\nInvite yourself to\_[OpenControl slack](https://join.slack.com/t/opencontrol/shared_invite/enQtNjM3NDY3NzQ3NjIwLTk2YTc0MmUwMjEyMmMxOTBhZTYwY2JhNDdiOTMwMDUzNjEyZGFlMGNjMDM3M2IyNjkyNzc0YmUxNGMzZWJhNWI)\_or join our\_[announcements mailing list](http://eepurl.com/cg0ZE1).\n\nYou can see the\_[full list of current members here.](https://open-control.org/members)\n"
    image_alt: lorem-ipsum
    background: gray
    actions: []
    type: section_content
  - section_id: members
    type: section_pricing
    background: gray
    title: OpenControl Members
    subtitle: You can have a separate pricing page or list everything on the home page.
    pricing_plans:
      - title: ''
        subtitle: ''
        price: Partners
        details: |-
          * Lorem ipsum dolor sit amet
          * Mauris a mi tincidunt
          * Suspendisse ut lacus
          * Etiam eget dui a augue
        actions:
          - label: Learn More
            url: /partners
            style: secondary
      - title: ''
        subtitle: ''
        price: Join!
        details: ''
        highlight: true
        actions:
          - label: Join Now
            url: /signup
            style: primary
      - title: ''
        subtitle: ''
        price: Contributors
        details: |-
          * Vestibulum non eros quis
          * Aenean iaculis lorem
          * Mauris eleifend sapien
          * Phasellus lobortis risus laoreet quam
        actions:
          - label: Learn More
            url: /contributors
            style: secondary
  - section_id: faq
    type: section_faq
    background: gray
    title: Frequently Asked Questions
    subtitle: 'Phasellus luctus laoreet arcu, vel porta metus imperdiet sit amet.'
    faq_items:
      - question: What license is this under?
        answer: "The code portions are all licensed under Apache 2.0, except what has been contributed directly by the US Government, which is in the public domain within the US. Internationally, the US Government licenses its code under\_[Creative Commons Zero 1.0](https://github.com/opencontrol/compliance-masonry/blob/master/LICENSE.md). All written content has been licensed as\_[Creative Commons Zero](https://creativecommons.org/publicdomain/zero/1.0/).\n"
      - question: What regulations can I use this for?
        answer: "The principles behind OpenControl can be applied to any regulatory environment, or in fact any operational environment with running systems and software. Currently, the community repositories include FedRAMP Low and Moderate definitions using the NIST 800-53 certification, as well as a newly defined\_[Lightweight Authority to Operate](https://gsablogs.gsa.gov/innovation/2014/12/10/it-security-security-in-an-agile-development-cloud-world-by-kurt-garbars/)\_(LATO) NIST 800-53 baseline from the\_[General Services Administration](http://gsa.gov/)\_(GSA).\n"
      - question: Why would I want this?
        answer: >
          For organizations in highly regulated environments, filling out
          compliance documentation is a huge commitment of time, staff, and
          resources. OpenControl will be a set of tools that will finall allow
          compliance to be directly incorporated to a continuous integration and
          deployment framework.
      - question: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        answer: >-
          ## Lorem ipsum


          Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.


          - Lorem ipsum

          - dolor sit amet
        type: faq_item
layout: landing
---
