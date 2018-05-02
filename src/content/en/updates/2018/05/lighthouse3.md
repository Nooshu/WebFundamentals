project_path: /web/_project.yaml
book_path: /web/updates/_book.yaml
description: TODO

{# wf_updated_on: 2018-05-02 #}
{# wf_published_on: 2018-04-18 #}
{# wf_tags: lighthouse #}
{# wf_featured_image: /web/progressive-web-apps/images/pwa-lighthouse.png #}
{# wf_featured_snippet: TODO #}
{# wf_blink_components: Platform>DevTools #}

# Announcing Lighthouse 3.0 {: .page-title }

<img src="/web/progressive-web-apps/images/pwa-lighthouse.png"
     style="height:auto;width:50%;"
     class="lighthouse-logo attempt-right" alt="Lighthouse Logo">

Lighthouse 3.0 is out! New features include:

* TODO

Major changes include:

* TODO

## First Contentful Paint {: #fcp }

## New Report UI {: #ui }

## Throttling configuration {: #config } 

## 4G is the new default throttling level {: #4g } 

## New scoring model 

## JSON output changes 

## First Interactive renamed to First CPU Idle {: #fci }

## Perceptual Speed Index changed to Speed Index {: #speedindex }

## CSV output {: #csv }

New to 3.0, report results can now be output in CSV. Each row contains
the results for one audit, including:

* The name of the category that the audit belongs to.
* The name of the audit.
* A description of the audit.
* The score type used for the audit.
* The score value.

## Faster audits and less variability {: #lantern }

Thanks to a new internal auditing engine, codenamed Lantern, Lighthouse 3 completes your audits
faster, with less variability between runs.

Previously, Lighthouse would literally reload your page many times, in order to determine how the
page loaded under different conditions. Now, Lighthouse audits your page once, then uses Chrome's
trace data to estimate your score under different conditions.

## New Report UI {: #ui }

TODO don't like the sentence below...

The Lighthouse team conducted usability studies to learn how to improve the report UI, and
got a lot of useful feedback.

<figure>
  <img src="https://placeholder.com/500x500"
       alt="A screenshot of the new report UI."/>
  <figcaption>
    <b>Figure X</b>. A screenshot of the new report UI
  </figcaption>
</figure>

Thanks to [Jason](TODO) for conducting the user experience research, and to [Hwi](TODO) for
designing the new UI. And thanks to all of the research participants for your valuable feedback.
