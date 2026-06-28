# MBio — Digital Analyst (Retail) · Targeting Note

This audit was built with the inside view in mind, even though it was conducted
from outside.

The Retail team at MBio owns the data foundation behind dealer websites and
customer journeys — exactly the funnel this audit maps. The configurator
observation across five brands documents the same journey a Digital Analyst
on that team would instrument: session start, model selection, configurator
completion, end CTA, lead submission. The ten-checkpoint fieldwork checklist
is a manual version of the event tracking schema that a properly instrumented
GA4 implementation would capture automatically.

The GA4 proxy work (BigQuery, SQL, session-depth analysis) demonstrates the
analytical pattern — not the conclusion. With access to mercedes-benz.pt's
actual GA4 property, the three questions this audit cannot answer become the
first measurement framework I would propose: configurator session completion
rate by model, lead submission rate at 7/14/30 days post-completion, and
return visit rate segmented by save mechanism type. These are the KPIs that
connect the structural gap identified here to a decision a product team can act on.

The audit is the work sample. The questions it cannot answer are the job.
