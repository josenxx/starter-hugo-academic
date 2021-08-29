---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Rresearch Assistant
    company: AutoIC Lab
    company_url: 'https://polytechnic.purdue.edu/autoic-lab'
    company_logo: autoic
    location: West Lafayette, Indiana
    date_start: '2019-01-01'
    date_end: ''
    description: |2-
        Research Project Participation:
        PFI-RP: Automating Building Code Compliance Checking and Modular Construction Through Interoperable Building Information Modeling Technology (Award Number: 1827733)  
        * Investigated Part-of-Speech (POS) tagging of building codes using Natural Language Processing (NLP) techniques
        * Collected POS tagging results of different POS taggers and human annotators on building codes
        * Created a database of POS-tagged building codes, called Part-of-Speech Tagged Building Codes Dataset (PTBC)
        * Resolved the problem that POS taggers that were developed on general English have under-desired performance on building codes by developing a technique called error-driven transformational rule
        * Adapted deep learning models and combined them with error-driven transformational rule to develop a POS tagger that is tailored for building codes
        * Expanded range of checkable building codes of automated code compliance checking system with minimal marginal effort by adding new rules to existing ruleset
        * Implemented a rule-based method to extract cross-references and hierarchical structure in building


  - title: Teaching Assistant
    company: Purdue University
    company_url: 'https://www.purdue.edu/'
    company_logo: university
    location: West Lafayette, Indiana
    date_start: '2019-01-01'
    date_end: ''
    description: |2-
        Class:
        CM 200 Intermediate Pre-Construction Management
        * Prepare question sheets for lab
        * Prepare questions for exam
        * Lead lab section
        * Oversee exams
        * Grade laboratory exercises and exams
        * Manage electronic class management system (BrightSpace, Blackboard, and Gradescope)

design:
  columns: '2'
---
