## Welcome!

Hi, my name is Jared Yankee!

I am a Software Developer specializing in system integrations. I work with
enterprise business platforms like HubSpot, NetSuite, Stripe and BigCommerce,
creating the pipelines that keep them all in sync: qualifying leads from form
submissions, live syncing all e-commerce orders, and reconciling records with
source of truth data.

Currently working on Seyona.ai, an AI-powered FAQ generator that renders content
directly to all live pages across a website. It scrapes the content from a
webpage and runs it through a three-model AI workflow, creating:

1. **Brand Profile** a master document for the whole site: brand voice, the
   business's offerings, and reference links to key pages that FAQs elsewhere on
   the site can point to.
2. **Trend Analysis** the highest-opportunity search trends addressed by each
   page's content, with rationale for each choice, URL citations, and a
   confidence score per term.
3. **Generated FAQs** SEO/AEO-optimized question and answer couplets built from
   the high-confidence trends, the page content, and the sitewide brand profile,
   ready to be delivered to live webpages.

I am not a vibecoder; I miss writing code by hand, but love that my design choices
can be brought to life much quicker. Some engineering highlights:

- Created dynamic form-generation workflow in Remedy to track progress of conditions
- Refactored Seyona's request pipeline to store requests in the database and
  process them through scheduled functions.
- Built a two-way HubSpot–NetSuite order sync with loop prevention so syncs don't
  start endless webhook loops.
- Wrote a lead qualifier that assesses form type and country of origin on HubSpot
  form submissions, rejecting them before they enter NetSuite.
- Ran headless Chromium inside a Netlify function for server-side PDF invoice
  generation for BigCommerce subscription orders, which aren't created
  automatically.
