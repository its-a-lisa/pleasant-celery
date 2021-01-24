---
title: About OpenControl
meta_title: ''
meta_description: ''
canonical_url: about
no_index: false
sections:
  - section_id: About OpenCtonrol
    title: Our Philosophy
    content: >
      This is a place where folks who are doing cybersecurity compliance work
      can come together to help improve the process to free up time to focus on
      security. 
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
      - question: Why did you use Concourse?
        answer: >
          There are a lot of great continuous integration tools out there,
          including Jenkins, Travis, Bamboo, Wercker, and more. OpenControl
          pipelines can be defined using any CI tool. We felt that the
          “dependency-injection” style of job and resource declaration in
          Concourse made it a good fit for the semantics of OpenControl.
        type: faq_item
      - question: Why didn’t you use OpenSCAP?
        answer: "The Security Content Automation Protocol (SCAP) is developed by the US Government to check for the presence of common vulnerabilities, or secure configurations on common technologies. OpenSCAP and OpenControl are extremely complementary - they are solving different problems. As the name implies,\_[OpenSCAP](https://github.com/OpenSCAP), a collection of open source SCAP tools provided by Red Hat, is about\_*automating*\_whether or not technologies with SCAP profiles in fact possess the security claims or “benchmarks” provided by\_[NIST](https://web.nvd.nist.gov/view/ncp/repository)\_or have common vulnerabilities in\_[MITRE’s database](https://cve.mitre.org/).\n\nIf your organization already uses SCAP, OpenSCAP may be a great solution to run those tests, and then output the results to\_[Compliance Masonry](https://github.com/opencontrol/compliance-masonry), an OpenControl tool. You use Compliance Masonry to map and automation of the\_*results*\_of those tests to the actual compliance documentation, which was always the missing piece from SCAP based systems. SCAP systems still required humans to manually entire information into static documentation. Via Compliance Masonry, OpenControl is\_[agnostic as to the source of your test results](https://github.com/opencontrol/compliance-masonry#long-term-plan-diagram)\_and whether not any compliance control is in fact implemented. It maps those controls to tests, and also renders the final compliance documentation.\n\nAlso of note is that the SCAP standard is\_[extremely verbose and complex XML](http://scap.nist.gov/schema/scap/1.2/scap-source-data-stream\\_1.2.xsd). Developers of net-new technologies have usually not written benchmarks in SCAP, and as a result, benchmarks significantly lag behind technological development. By using YAML and creating a more developer focused framework, we hope that secure baselines evolve more quickly in parallel with SCAP enabled enterprise benchmarks provided by NIST.\n"
        type: faq_item
      - question: Who came up with this concept?
        answer: "The ideas of continuous authorization have been around for a long time. The term ‘OpenControl’ was coined by Joshua McKenty, and first used in\_[a keynote presentation at All Things Open 2015](https://speakerdeck.com/joshuamckenty/all-things-open-opencontrol)\_in Raleigh, North Carolina. The presentation includes some history, and explicit thanks to key originators at both 18F and Pivotal, as well as the creators of Cloud Audit. Special thanks goes to Diego Lapiduz and Noah Kunin.\n"
        type: faq_item
layout: landing
---
