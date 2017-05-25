====================
JSON Transformations
====================

Designed to transform existing RESTful API’s from the developer cornucopia
to digestible, tasty morsels for real-world practitioners; in other words,
improve the User Experience (UX) and shift the target audience for API
design from the custom software developer to the real-world data-consumer
and Subject Matter Experts (SME); through simple data transformations; SME’s
can then process data through the many existing tools already available for
analyzing, transforming, querying, aggregating and integrating with data
from other API’s.

A three (3) prong approach to RESTful API JSON data transformations:

1.  **A programmable JSON calculator**; simply JSON in, to JSON out, via
    JSON rules made from friendly Python tokens; fun and not too scary. 
    Record, rewind, fast-forward, pause and play.
2.  **Unix-like, command-line JSON tools via micro packages**; a slight
    twist on existing, traditional, JSON Unix-like tools to make accessing
    and transforming the JSON data both easy and fun.
3.  **A RESTful API transmorgification framework**; morph existing developer
    API’s into data-consumer focused, pragmatic, fun and scriptable
    command-line utensils.

Imagine if there was a programmable calculator designed to work with JSON
data. What if the transformations could be easily built, modified, tested
and debugged interactively via the terminal?  Want automation, simply record
the steps and replay.  It would allow the transformations to be done through
interactive configuration rather than custom code, allowing solutions to be
rolled out more quickly and with fewer errors.

The challenge: Today thousands of applications have RESTful API’s that are
designed by developers for developers.  Yet, the output of these API’s is
typically just JSON; aka. plain old structured data; therefore, is it really
necessary to develop custom code to make this data useful?  Or can we look
at these Restful API’s from a different perspective?  What if we were to
look at RESTful API’s through the data consumer lens, the data scientist
lens, or the User Experience (UX) lens rather than through the software
craftsmanship kaleidoscope?  Yes, well written custom code is a beautiful
thing, yet in production environments there is the overhead involved with
testing, documentation, development frameworks, orchestration, maintenance
and support.  Not to mention the willow-o-wisps tempting the creator to add
more features, to perfect their art, to beautify their code, etc.; all noble
causes, but nevertheless distractions from the pragmatist’s end-goal.
Programmable calculators traditionally remove these distractions, most
people who use calculators are focused on the end-results, the numbers,
problem-solving, the science, data analysis, etc.  Once the instructions are
programmed into the calculator and tested, the collection of instructions
simply become a script that can be scheduled.  The programmable calculator
supports a limited set of instructions and brings it a small step closer to
an embedded system and/or an industrial control system where stability and
reliability are prized.  It’s easy to imagine, but how do we make this a
reality while adhering to Occam’s Razor and leveraging existing standards
and guidelines; herein lies the great challenge and the impetus for this
community project; if you share this vision or some variation thereof, feel
free to join us here at JSON Transformations where we value your
contributions.

And, as it turns out this isn’t vaporware, parts of it are already being
used in production and are currently undergoing modifications for
distribution in the Open Source community under the MIT license.


Project Status
--------------

+---+-----+---------+-------------+--------------+-------------------------+
| P |  %  | Status  | Package     | Dependencies | Comments                |
+===+=====+=========+=============+==============+=========================+
| M | 4/5 | ACTIVE  | color-names |              | Curated list of color   |
|   |     |         |             |              | names to RGB hex string |
|   |     |         |             |              | values in JSON format   |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 4/5 | NEXT-UP | itemizer    | jsoncolor    | Enumerator/Sequencer    |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 1/5 | BACKLOG | jsoncalc    | jsonkeys     | Python RPN Calculator   |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 5/5 | DONE    | jsoncat     |              | PyPi: Registered        |
|   |     |         |             |              | Code Coverage: 95%      |
|   |     |         |             |              | TODO: Travis CI         |
|   |     |         |             |              | TODO: Coveralls         |
|   |     |         |             |              | Versions: PY2.6,7       |
|   |     |         |             |              | Versions: PY3.3+; pypy  |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 3/5 | ACTIVE  | jsoncolor   | jsoncat      | Human-readable or       |
|   |     |         |             |              | compressed format       |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 3/5 | NEXT-UP | jsonconfig  | itemizer     | CRUD operations for     |
|   |     |         |             |              | persistent user         |
|   |     |         |             |              | settings                |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 3/5 | NEXT-UP | jsoncount   | jsonkeys     | Count items in JSON     |
|   |     |         |             |              | arrays                  |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 4/5 | BACKLOG | jsoncut     | jsonkeys     | JSON pruning tool       |
|   |     |         |             |              | PyPi: Registered        |
|   |     |         |             |              | Versions: PY3.3+        |
|   |     |         |             |              | TODO: Split micro-pkgs  |
|   |     |         |             |              | TODO: Add more tests    |
|   |     |         |             |              | TODO: Better docs       |
+---+-----+---------+-------------+--------------+-------------------------+
| L | 0/5 | BACKLOG | jsongrep    | jsonkeys     | JSON search tool        |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 0/5 | BACKLOG | jsonbug     | jsoncalc     | JSON interactive debug  |
|   |     |         |             |              | aka. jitterbug          |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 4/5 | BACKLOG | jsonjoin    | jsonkeys     | Join JSON documents     |
|   |     |         |             |              | using SQL, set or       |
|   |     |         |             |              | symbol notation         |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 4/5 | BACKLOG | jsonkeys    | itemizer     | JSON key selectors      |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 0/5 | BACKLOG | jsonlookup  | jsonkeys     | Lookup & replace        |
|   |     |         |             |              | values from a JSON      |
|   |     |         |             |              | reference document      |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 1/5 | BACKLOG | jsonmap     | jsoncalc     |  Map JSON arrays        |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 0/5 | BACKLOG | jsonfilter  | jsoncalc     |  Filter JSON arrays     |
+---+-----+---------+-------------+--------------+-------------------------+
| L | 0/5 | BACKLOG | jsonreduce  | jsoncalc     |  Reduce JSON arrays     |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 4/5 | BACKLOG | jsontypes   | jsonkeys     |  Inspect JSON documents |
+---+-----+---------+-------------+--------------+-------------------------+
| M | 2/5 | BACKLOG | jsonbones   | jsoncalc     |  API transmogrification |
+---+-----+---------+-------------+--------------+-------------------------+
