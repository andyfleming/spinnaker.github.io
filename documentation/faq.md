---
layout: toc-page
title: FAQ
id: faq
lang: en
---

* Table of contents. This line is required to start the list.
{:toc}

# Frequently Asked Questions

* [Where do I find `spinnaker-local.yml`?](#where-do-i-find-spinnaker-local-yml)
* [How do I set up Slack notificaitons for a pipeline?](#how-do-i-set-up-notificaitons-for-a-pipeline)

### Where do I find `spinnaker-local.yml`?

You can find it in `/opt/spinnaker/config/`.

### How do I set up Slack notificaitons for a pipeline?

1. Maker sure Spinnaker is up to date.
2. Add Slack credentials in `spinnaker-local.yml`.
3. Configure notifications
  * Option A) Add a notification to a single pipeline in the "configure" view.
  * Option B) Enable notifications for "any"/all pipelines for an applicaiton under `/#/applications/your-application/config` where it says "Add Notification Preferences".

