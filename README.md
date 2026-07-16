Product leader and three-time founder. I work in industries where being wrong is expensive. These are the problems I've spent the last decade on.

### How do you let an LLM touch data an auditor will read?

Have it emit SQL, not answers. A query is something a human can read before it runs, and re-run against any data snapshot afterward. That property — not accuracy — is what let the model stand up to an audit.

The eval regime followed from it. Every deployment was tracked against a fuzzed dataset built from a real study, with a 75% floor to ship. That floor was a release gate, not what customers saw: any query classified high risk went to a human before it ran.

**studyOS**, 2022–2025. Started as reporting for biotechs; discovery showed that was a commodity, so we pivoted to analytics for pharma, which is what won the enterprise accounts. Alcon, Bausch + Lomb, and GSK ran it across 8 studies, 3 of them registrational, on a $3.5M seed. Acquired.

### How do you deliver lab capabilities anywhere, to anyone?

You build the logistics yourself, because nobody sells them. Contracted networks supply phlebotomist contact details and nothing else — no dispatch, no routing, no chain of custody. All of that had to exist before a single draw could happen.

Kits were assembled just-in-time, shipped to whatever address the patient gave, timed to the draw window and the specimen's stability limits, and routed back to the lab intact. Miss any one of those and the sample is worthless on arrival.

**Butterfly Labs**, 2021–2022. 300+ contracted phlebotomists, nationwide coverage, 2,000+ draws a month. Acquired.

### How do you get a PDF paid?

Out-of-network claims arrive as paper. We ran OCR over the PDFs, built connectors to the payors, submitted the claims electronically, and automated the follow-up — because the submission is not the hard part. Getting a payor to actually respond is.

**Get Franklin**, 2020–2021. Bootstrapped, no outside capital, $10M+ in claims through the pipeline. I shut it down after concluding the model wouldn't reach venture scale, and started studyOS instead.

### Before that

Product manager at Microsoft, 2016–2020. Azure SQL Data Warehouse, then the launch of Azure Synapse Analytics — which became the foundation of Microsoft Fabric after I left.

---

Right now I'm building personal tools for AI development.

Email is in my profile and DMs are open. [hirokibutterfield.com](https://hirokibutterfield.com) is where I write about the work.

I'm a product person, so most of what I've shipped isn't code with my name on it — and regulated software doesn't get open-sourced.

