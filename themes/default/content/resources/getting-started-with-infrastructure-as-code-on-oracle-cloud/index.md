---
# Name of the webinar.
title: "Getting started with Infrastructure as Code on Oracle Cloud"
meta_desc: "Learn the fundamentals of Infrastructure as Code (IaC) through guided exercises using Pulumi on Oracle Cloud Infrastructure."
meta_image: "/images/resources/getting-started-oracle-josh-eli.png"

# A featured webinar will display first in the list.
featured: false

# If the video is pre-recorded or live.
pre_recorded: false

# If the video is part of the PulumiTV series. Setting this value to true will list the video in the "PulumiTV" section.
pulumi_tv: false

# The preview image will be shown on the list page.
preview_image: ""

# Webinars with unlisted as true will not be shown on the webinar list
unlisted: false

# Gated webinars will have a registration form and the user will need
# to fill out the form before viewing.
gated: true

# The layout of the landing page.
type: webinars

# External webinars will link to an external page instead of a webinar
# landing/registration page. If the webinar is external you will need
# set the 'block_external_search_index' flag to true so Google does not index
# the webinar page created.
external: false
block_external_search_index: false

# The url slug for the webinar landing page. If this is an external
# webinar, use the external URL as the value here.
url_slug: "getting-started-with-infrastructure-as-code-on-oracle-cloud"

# The content of the hero section.
hero:
    # The title text in the hero. This also serves as the pages H1.
    title: "Getting started with Infrastructure as Code on Oracle Cloud"
    # The image the appears on the right hand side of the hero.
    image: "/icons/containers.svg"

# Webinar pages support multiple session via the 'multiple' property.
# multiple:
#   - datetime: 2020-02-05T10:00:00-07:00
#     hubspot_form_id: ""
#     gotowebinar_key: ""

# Content for the left hand side section of the page.
main:
    # Webinar title.
    title: "Getting started with Infrastructure as Code on Oracle Cloud"
    # URL for embedding a URL for ungated webinars.
    youtube_url: #"https://www.youtube.com/embed/oDVSN0uwJTg"
    # Sortable date. The datetime Hugo will use to sort the webinars in date order.
    sortable_date: 2024-02-22T09:00:00-08:00
    # Duration of the webinar.
    duration: "90 minutes"
    # Datetime of the webinar.
    datetime: ""
    # Description of the webinar.
    description: |
        With Pulumi’s new Oracle Cloud integration you can define, deploy, and manage OCI resources using your favorite programming languages including JavaScript/TypeScript, Python, C#/.NET, and Golang.

        In this workshop, you will learn the fundamentals of Infrastructure as Code through a guided exercise using Pulumi’s infrastructure as code platform, where you can use familiar programming languages to provision infrastructure on any cloud.

    # The webinar presenters
    presenters:
            - name: Josh Kodroff
              role: Sr. Solutions Architect, Pulumi
            - name: Eli Schilling
              role: Developer Advocate, Cloud Native and DevOps @ Oracle

    # A bullet point list containing what the user will learn during the webinar.
    learn:
        - "The basics of Pulumi Programming Model"
        - "How to provision, update and destroy OCI resources using Pulumi"

# The right hand side form section.
form:
    # HubSpot form id.
    hubspot_form_id: 53f62fbc-252b-4407-813e-4d0462b119e7
    salesforce_campaign_id: 701Du000000Bu34IAC
---
