## Hei 👋

I'm Nicolai, a master's student in software engineering and systems architecture
at the University of Oslo. My thesis is on detecting malware hidden in deep
neural networks a model's weights can carry a payload much the same way a
binary can, and finding it is a stranger problem than it first sounds.

I also teach: TA in Project in Programming (IN2031) and Operating Systems
(IN3000/IN4000) at UiO. Explaining paging to twenty people who are each stuck in
a slightly different place will teach you the material properly.

Away from coursework I mostly build things around markets, because I follow
finance closely enough to keep wanting tools that don't exist yet.

### Things I've built

**[Ticker](https://github.com/NicoSik/StockApp)** A stock watcher and
multi-broker portfolio aggregator. Java 17, Javalin, PostgreSQL, and a front end
with no build step. It pulls holdings from eToro, Nordnet and DNB into a single
NOK total with live pricing and currency conversion.

The interesting work was all in the unglamorous half: writing parsers for two
undocumented export formats (UTF-16LE tab-separated CSV, and XLSX read straight
out of the zip as XML, no library), resolving securities against market data by
checking the price the export itself states rather than trusting a name match,
and reconciling every import against the file's own total so a partially read
file gets rejected instead of quietly being wrong.

**A minimal operating system** in x86 assembly and C paging, memory
management, process scheduling, basic file handling. Written for IN3000, the
course I now TA.

**[Inspector Chalmers](https://github.com/NicoSik/Chalmers)** A DHIS2 app for
digital school inspections in the Gambia, built as a team project. Collection,
analysis and visualisation of inspection data, with offline support because the
connection can't be relied on. A prototype from a course, not something running
in production.


### Tools I reach for

Python, Java, C, x86 assembly. PyTorch, scikit-learn, pandas, NumPy.
PostgreSQL, Docker, Linux, Git. React or plain JS.

### Otherwise

Based in Oslo. Norwegian, English and Polish. Before university I served with
His Majesty The King's Guard as an S6 assistant, looking after comms and helping
keep the camp's IT running.
