# Muneeb Riaz

Backend engineer in Berlin.

I work at Invatech Health on a pharmacy platform that is used in production. My part is
the integrations: connecting it to supplier and wholesaler systems over REST, SOAP and
FTP, in C# and .NET. Most of the interesting problems there are not about writing code
but about what happens when the other side is slow, sends something unexpected or is
simply down for an hour. Retries, idempotent handlers, making sure an order is placed
exactly once.

Before Berlin I spent almost two years at Nanosoft Technologies in Karachi, building
REST and gRPC services, data pipelines and background jobs with RabbitMQ, Docker and
CI/CD.

I am also finishing an MSc in Artificial Intelligence at BTU Cottbus-Senftenberg. My
thesis starts in October and is about deepfakes.

Mostly working with: C#/.NET, Python, Java, SQL, TypeScript, PostgreSQL, SQL Server,
MongoDB, RabbitMQ, Docker, React

## Papers

Two papers I co-authored at AHFE International 2026, from my work as a research
assistant at TU Berlin. Both are about how people, not machines, enter and read data
for the EU Digital Product Passport:

- [Designing Human-Centric Interfaces for the Digital Product Passport in SMEs](https://doi.org/10.54941/ahfe1007782)
- [Designing Error-Resilient Human-in-the-Loop Interfaces for Battery Passport Compliance](https://doi.org/10.54941/ahfe1007781)

## Some things I built

**Multi-scale blob detection for object counting on a Raspberry Pi.** My research
project at the Chair of Graphical Systems, supervised by N. Pschipsch and
Prof. D. W. Cunningham. The existing pipeline used edge detection and fell apart when
the lighting changed or objects touched each other, so I rebuilt it around Hessian-based
Difference-of-Gaussian blob detection, with a variational Bayesian mixture model to
throw out false detections. Counting accuracy went from 59.3% to 74.1%. Python, and the
results ended up on a research poster.

Two others I cannot put here, because they are work projects and one of them touches
unreleased standards. A JSON Schema validator that sorts violations into three severity
groups instead of just telling you the file is invalid, and an offline tool that
compares two PDF versions of a standards draft. The second one matches paragraphs by
what they say rather than where they sit on the page and rates every difference by how
much it actually matters, so a changed requirement does not get lost among moved commas.
It runs locally, so confidential drafts stay on the machine, and it catches every real
change that Adobe Acrobat's compare finds while flagging less than half as many items.
Python, FastAPI, React, tested with pytest and Hypothesis. I am happy to talk through
either of them.

The rest of the repositories here are university work in Java and C#.

Reach me at muneebriaz19@gmail.com or on
[LinkedIn](https://linkedin.com/in/muneeb-riaz-91a225154).


- ⚡ Fun fact: ...
-->
