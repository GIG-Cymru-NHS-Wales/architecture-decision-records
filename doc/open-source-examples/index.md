# Open source examples

!!! info

    **Status**: Proposed
    
    **Level**: 2

    **Updated**: 2025-06-27

## Summary

I've created a bunch of free open source examples of software engineering, and I
intend to use with our staff for teaching and training, such as for test automation. 

Some organizations have some people who have questions about open source, so
this ADR is to help describe how it works, and the specifics that I'm doing with
staff, so any stakeholder can ask questions, add advice, and participate.

## Drivers

Right now I need qto teach and train our operations testers in how to do test
automation. A specific example is how to use Selenium browser automation to
visit a web URL, inspect what the page shows, and report success or failure.

I intend to use my pre-existing free open source software to help with this,
because I've done this before with other organizations. I have free open source
repositories that demonstrate how to use Selenium for browser testing, and that
provide simple web services that Selenium can query.

The specifics include these free open source repositories to start...

Demonstrations of how to use Selenium with JavaScript, Python, etc.

* https://github.com/joelparkerhenderson/demo-selenium-javascript

Web service examples that are targets that Selenium can test, such as this web
service that prints the current time in unix epoch format:

* https://github.com/joelparkerhenderson/web-service-epoch-axum

Testing examples that are web pages with testable user interfaces, such as with testable HTML tags, CSS styles, etc.

* https://github.com/testingexamples

All of these are my own free open source projects, so I'm confident they work.

## Options

* Yes, good, right

* Maybe, needs improvement

* No, bad, wrong
  
A successful outcome (IMHO) looks like what many of my clients do, which is "We like
using open source. These projects have clear licenses that we know such as MIT
or BSD or GPL. Use the projects. Don't incorporate any of the projects' source
code into our core software without first getting governance clearance."

An unsuccessful outcome (IMHO) looks like what one of my client did, which was
banning the use of external open source projects, in favor of building
internally and buying externally, because those are easier to control legally
for high-stakes auditing.

I'm currently chatting about this with:

* our organization's risk registry manager
* our CISO and deputy
* OUR Client Services staff

## Options Analysis

### Yes, good, right

**Pro:**

* Easy
* Friendly
* Fast

**Con:**

* No commerical support
* No commercial maintenance
* No commercial indemnification

### Maybe, needs improvement

**Pros:**

* Could turn up unknown unknowns for learning opportunites
* Might be helpful for creating organization change
* Potentially surfaces ideas for feature improvements

**Cons:**

* Time & money, such as if our org wants legal audits.

### No, bad, wrong

**Pros:**

* Clear
* Direct
* Certain

**Cons:**

* Snowballs into future build-vs-buy investigations

## Recommendation

Yes, good, right.

I choose this because I need to teach our operations testers starting near-immediatly.

### Consequences

TODO?

{This section is **optional**.}

{Now that a decision has been made what are the expected outcomes and impacts,
both positive and negative? What known limitations, costs, or risks are being
accepted by making this decision? How will this decision affect different
stakeholders, other systems, development practices, operational procedures,
or user experience?}

* Pro: {A specific positive outcome or benefit expected from this decision.}

* Con: {A specific accepted downside, cost, or risk resulting from this
    decision. }

* Other: {A consequence that isn't strictly a pro or con.}

### Confirmation

TODO?

{This section is **optional**.}

{Outline how the implementation of this decision will be verified and how
ongoing compliance will be ensured. This helps demonstrate that the decision
isn't just theoretical but will be actively put into practice and monitored.

How will you check that the decision has been correctly implemented?
(e.g., code reviews, specific tests, demonstrations, peer review).

How will adherence to this decision be maintained over time? (e.g., automated
checks, periodic audits, updates to team guidelines, training).

Are there specific metrics or indicators that will show the decision is
achieving its intended positive outcomes? (e.g., performance benchmarks,
adoption rates, reduction in specific errors, user feedback scores).

Who is responsible for overseeing this, and what happens if the decision is
not followed?}
