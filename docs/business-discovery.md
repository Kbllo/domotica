# Business discovery

## Status and evidence policy

Initial discovery record, 2026-09-20. Founder statements below are self-reported experience and intentions, not independently verified market findings. Analytical hypotheses are proposals for discussion, not agreed commercial, technical, or spending decisions. Preserve the distinction when extending this record.

## Founder-reported experience

- Started developing home automation electronics approximately 15 years ago.
- More recently applied automation in a residential home and uses consumer systems in daily life.
- Reports substantial technical understanding across electronics, hardware, software, and multiple brands. The extent of paid installations, customer support work, and commercial sales has not yet been established.
- Has not yet experimented sufficiently with Home Assistant and sees it as a possible service opportunity.
- Is considering Matter as a potentially simpler basis for an offer with customer platform choice, including existing Alexa or Apple Home/HomeKit environments.
- Wants a good configuration manual to help customers configure or change platforms and is considering an optional router offering. Supported devices, migration scope, networking requirements, and cost remain undefined.
- Follow-up clarification on 2026-09-20: the founder wants to focus personally on design and configuration. Who performs or contracts physical installation, procurement, sales, and ongoing support is still to be established.

### Daily-use evidence — founder update, 2026-09-20

- Reports approximately 120 devices across two homes, with varying configurations and six months of daily use. Device distribution between homes, installation dates per device, and topology are not yet established. Do not interpret this as 120 devices on one Zigbee network.
- Describes roughly 90% of their experience as SONOFF with Zigbee. Do not assume every device, curtain motor, or other listed function uses that brand or protocol.
- Installed functions include lighting, curtains/blinds, presence sensors, motion sensors, smart locks, garden watering, LED strips, and smart outlets.
- Identifies lighting and blinds/curtains as the most convenient functions, particularly remotely switching off lights or closing blinds/curtains. The subsequent platform account below adds information about control interfaces; the exact path for each function remains unmapped.
- Troubleshooting time, maintenance frequency, and other household users' independence remain unknown. The subsequent platform account introduces a reliability hypothesis and identifies the main ecosystems in use.

The six-month daily-use period is distinct from the founder's approximately 15-year technical background. No failure rate, warranty performance, commercial customer count, or support-cost claim can be inferred from device count alone.

Analytical hypothesis: a limited lighting-and-curtain offer may be a useful first scope to discuss because the founder reports direct daily value and experience with these functions. This is not a selected catalog or proof of buyer demand. Other installed functions remain available for evaluation without automatically being included in the initial offer.

Use the existing installations as a reference when comparing a future Matter-based or Home Assistant-based configuration. Evaluate customer outcomes, commissioning effort, recovery, and ongoing intervention before selecting a commercial standard. No equipment replacement or additional purchase is authorized by this discovery update.

### Platforms, scenes, and voice control — founder update, 2026-09-20

Founder-reported observations and preferences:

- Initially described the SONOFF Zigbee hub as "u-bridge" and subsequently confirmed on 2026-09-20 that it is the ZBBridge-U / Zigbee Bridge Ultra. Firmware and distribution between homes remain unspecified; the model no longer needs clarification.
- Describes operation as mostly local, with many scenes and some that cannot run locally. Attributes this limitation to the number of scenes; the actual threshold and cause have not been verified.
- Uses Alexa and its scenes/routines. Perceives compatible Alexa speakers as inexpensive and broadly compatible; this is not a verified price comparison or universal compatibility claim.
- Uses HomePod mini and reports exposing the SONOFF hub through Matter to both Alexa and Apple Home, reaching approximately 90% of devices. The unsupported devices and missing functions have not been identified; do not treat this percentage as a commercial compatibility guarantee.
- Finds Apple Home most convenient because of Apple Watch integration. Reports that one HomePod suffices for their iPhone-based use, while placing voice-control speakers throughout a home can require substantial investment. Exact coverage and other occupants' needs are unknown.

Founder hypothesis, not a diagnosis: cloud scenes may sometimes trigger unexpectedly when connectivity returns. In a follow-up on 2026-09-20, the founder stated that no specific example comes to mind, the issue is not repetitive enough to investigate now, and they consider the theory very strong. Respect that confidence as the founder's assessment while keeping causation unverified. No measured frequency, event log, timestamps, or root cause has been established. Do not assert that reconnection causes these events or that changing platform would fix them.

Current direction: defer investigation of this hypothesis and continue business discovery. Do not keep requesting examples, logs, or diagnostic work for it unless the founder reopens the topic. A future commercial acceptance test is a separate decision and is not authorized here.

Business implications proposed for discussion:

- Cost the basic control functions, the explicitly included scenes, and room-by-room voice access separately. This is a scoping hypothesis, not an approved package or a speaker purchase recommendation.
- Reuse a customer's suitable existing phone, watch, controller, or speakers when the agreed functions are supported. Verify any required home hub independently from how many voice listening points a customer wants.
- Record the execution platform, trigger, action, dependencies, and acceptance behavior for each included automation. Trace overlapping rules across platforms before attributing unexpected actions to the cloud.
- Compare local and cloud behavior for specific functions, including recovery, rather than labeling the whole installation "local" or "cloud." Passing devices through a Matter bridge does not establish where every automation executes.
- Base compatibility promises on a tested list of models and functions. Investigate the reported missing 10% only insofar as those devices affect the candidate lighting-and-curtain offer.

No scene changes, firmware updates, connectivity interruptions, diagnostics on live homes, or migration are authorized by this record.

## Local market and candidate segment — founder update, 2026-09-20

Founder-reported observations:

- Reactions to the installations vary: some people are enthusiastic and others attach little importance to them. No numbers, formal quotations, purchase commitments, or paid requests were reported in this account.
- Observes that people appreciate not having to get up at night to switch off lights after experiencing the convenience. Believes that experiencing the benefit matters more than an abstract explanation for people who are not already home automation enthusiasts.
- Proposes older people with high purchasing power in Lomas de Angelópolis as a target. Exact ages, household circumstances, decision makers, payers, existing technology, and sales access remain unspecified. Do not infer disability, technology aversion, or particular interface needs from age.
- Believes many people in this proposed segment are not involved in home automation. This is a local perception, not a measured adoption rate or verified demographic finding.

Founder brand perceptions, explicitly acknowledged by the founder as lacking substantiation:

- Aqara and SONOFF generally offer inexpensive, good-quality solutions.
- Philips Hue appears overpriced.
- Lutron may not make much sense in the local market.

Do not convert these perceptions into a brand ranking, procurement decision, or statement about Puebla demand. Any later comparison must use an actual customer outcome and comparable scope, including controls, physical finish, required infrastructure, installation/configuration effort, compatibility, support, warranty, replacement availability, and total cost. Higher price alone does not prove superior value; cheaper hardware alone does not prove a more profitable delivered service.

Business hypotheses for discussion:

1. Position a candidate offer around a specific experienced convenience, such as switching off lights and closing blinds from bed, with a control method comfortable for the intended user. Treat usability and household preferences as things to observe rather than assume.
2. A short hands-on demonstration may communicate this value better than a feature list. Validate whether interest progresses to a request for a defined proposal and acceptance of its actual price; enthusiasm alone is not a sale. No showroom, demonstration purchase, invitation, or access to either existing home is authorized.
3. Configuration, reliable operation, clear handover, and defined assistance may be part of what this customer pays for. Include their labor and support costs when pricing, even when equipment is inexpensive. Willingness to pay for that service is still untested.
4. Validate the handover method with the intended user: a concise guide, familiar controls, and an observed successful task may be more relevant than an extensive configuration manual. Customer self-configuration and migration remain optional hypotheses, not assumed preferences of this segment.

Relationship to the construction opportunity: the apartment project's location and buyer profile are unknown. The proposed Lomas segment does not automatically describe that builder's customers. Initially the first route was unresolved. In the subsequent 2026-09-20 clarification, the founder retained both new and occupied homes in the intended market and identified new construction through the builder as the easier initial route to explore. This establishes a discovery preference, not an approved launch or a claim that both routes have identical economics.

### Builder route and flexible scope — founder clarification, 2026-09-20

- Believes selling to a builder is easier because one buyer can purchase the offer for a development.
- Believes describing apartments as smart can be a powerful real-estate sales/rental message. The known contact still builds for sale; mentioning rentals as a possible benefit does not change that confirmed business model.
- Sees automation scope as flexible across different levels. Exact price tiers, included functions, supported combinations, and buyer segments remain undefined; do not translate this into unlimited customization or suitability for every budget.

Business interpretation for discussion: one commercial negotiation may cover multiple homes, but configuration, acceptance, ownership handover, and support must still be costed per unit. The builder as purchaser and the eventual resident as user are distinct roles. Their respective responsibilities and support arrangements require explicit agreement.

An offer could distinguish construction preparation, a defined functioning base, and separately scoped extensions. Describe preparation as preparation; identify the actual functions delivered when using a smart-home claim. Keep variants within tested combinations and account for extra design, installation coordination, and support work. No package or quantity is selected here.

Revenue-model question to resolve next: whether the business supplies only design/configuration while the builder purchases specified equipment, or also sells equipment and manages procurement. Compare founder cash exposure, procurement labor, quality control, margin, and warranty responsibilities. Deposits, pricing, and supplier terms have not been agreed.

On 2026-09-20, the founder requested the benefits and risks of both models. See [commercial model comparison](commercial-model-comparison.md) for the analysis, illustrative economics, risk controls, and a provisional services-first recommendation. The founder has not chosen a model; do not treat the recommendation or illustrative figures as accepted decisions or a quotation.

The founder subsequently supplied a small-apartment package estimate: one ZBBridge-U at 1,500 MXN, 5–8 smart switches/modules at 200 each, three presence sensors at 500 each, two motion sensors at 300 each, and approximately ten everyday scenes. The described areas are a kitchen, living room, bedroom, bathroom, and garden. Equipment arithmetic is 4,600–5,200 MXN; tax inclusion, complete accessory costs, module/sensor models, and labor remain unconfirmed. The founder considers larger boxes and neutral conductors a likely small construction increment and describes very broad lighting compatibility; both are hypotheses to verify for the actual project.

See [basic apartment pricing](basic-apartment-pricing.md) for percentage calculations, explicit cost assumptions, provisional prototype/repeat service fees, and an advisory growth path. The proposed package adds concrete lighting/sensing scope but does not include curtain hardware. The founder asked how to price and grow, not to execute a pilot or approve these fees. The percentage denominator, IVA treatment, actual workload, and hourly objective remain to be clarified.

### Lean builder offer and earnings scale — later clarification, 2026-09-20

- The hardware prices are approximate recollections, possibly somewhat high. The founder expects to compare suppliers later and does not have the tax basis or measured delivery hours available now. Do not make those inputs a prerequisite for an explicitly hypothetical earnings comparison.
- The immediate request is the order of magnitude of earnings from designing/configuring one small home versus a tower of twenty small apartments. Twenty is a comparison scenario, not a confirmed project quantity or order.
- The founder understands this builder's objective as attractive, inexpensive homes for sale, with minimum additional spending and maintenance to market a smart-home feature. This is the founder's interpretation; the builder has not confirmed it here. It does not replace the separately proposed affluent end-customer segment.
- The founder proposes lighting, curtains, and a screen with Alexa as sufficient candidates for a visible demonstration during a sales visit or video. Counts, models, scene scope, buyer value, and the screen's incremental selling effect remain unvalidated. The screen and curtain hardware were absent from the earlier equipment subtotal.
- Irrigation, water-leak detection, and gas detection are suggested optional additions, not approved baseline functions. Low device price does not establish low delivery cost or low consequence of failure.

See [lean offer earnings](lean-offer-earnings.md) for transparent service-only illustrations and their downside. The working comparison includes design, configuration, testing, and a bounded handover/support allowance; it is not a design-drawing-only quote. Builder-funded equipment and qualified physical installation are analytical assumptions, not agreed responsibility assignments. No rates, twenty-unit project, scope, supplier, or commercial model have been accepted.

### External examples of local marketing — checked 2026-09-20

- Ideabitat's own website promotes smart residences in Lomas de Angelópolis with voice or smartphone control of lighting and other listed functions. [Ideabitat](https://www.ideabitat.mx/).
- ValorCity's HEM development page in Lomas includes a home automation offering described as a digital entrance lock and an Alexa system. [ValorCity — HEM](https://www.valorcity.mx/departamentos-almenare-hem).

These are primary-source examples of advertised positioning. They do not establish installed performance, current availability, buyer demographics, higher achieved prices, faster sales, rental uplift, or willingness to pay for this business's offer. They show that smart-home language is already present locally; the label alone is not an established competitive advantage. No advertised property price was adopted as a valuation benchmark.

## Founder-reported construction opportunity

The founder believes three provisions can add installation flexibility with limited construction changes:

1. Elevated AC power points for motorized curtains.
2. Deeper electrical boxes for smart devices or modules.
3. Neutral conductors at lighting switch locations, which the founder reports are often absent in the installations they encounter.

These are candidate preparation requirements, not a complete electrical design or a statement about all Puebla housing. Exact motor power requirements and location, usable box space, load compatibility, wiring, network coverage, and applicable installation requirements must be established for an actual project by the responsible qualified parties. No technical specification, construction cost, or quantified saving has been approved.

## Contacts and actual commercial status

| Alias | Founder-reported relationship | Current status | Decision-relevant unknowns |
| --- | --- | --- | --- |
| Residential builder | Acquaintance who builds apartments and houses for sale, clarified by the founder on 2026-09-20; previously recorded as Apartment builder | Contact only; no outreach, interest, order, or partnership confirmed in this work | Current construction stage, number of units, buyer profile, decision maker, budget, and who would purchase automation services |
| Residential architect | Architect who built the referenced house and participated in its implementation | Existing working familiarity; no commercial agreement confirmed | Current projects, client access, desired responsibilities, willingness to recommend or buy the service, and commercial terms |

No names, contact details, property addresses, or access information are recorded. No authorization to contact either person has been given.

### Possible apartment project — founder update, 2026-09-20

The founder reports that some apartments may be at the point when installation decisions can be made. This is a possible near-term opportunity, not a verified construction stage or an interested customer. Whether electrical routes and boxes remain accessible, the decision deadline, unit count, layout repetition, intended sale price, and builder interest remain unknown. No site visit, design work, installation, or expenditure has been committed.

Discovery implication: establish the remaining construction decision window and basic project characteristics before drafting a priced offer. A representative apartment could be a bounded basis for scoping, subject to actual layout differences and the builder's interest; this is a proposed discussion approach, not an approved pilot.

## Initial business hypotheses — not accepted decisions

The founder's technical breadth and construction experience may support a repeatable service that specifies, verifies, commissions, and documents a limited set of automation outcomes. Whether either contact or their customers will pay for this remains untested.

Discuss three potentially separate paid scopes:

| Candidate scope | Possible deliverable | Potential payer to verify | Economic condition to validate |
| --- | --- | --- | --- |
| Construction preparation | Agreed preparation specification, coordination with the architect/electrician, and defined verification visits before closure and handover | Builder, architect commissioning the work, or property owner | Preparation fees cover design, coordination, travel, and revisions without depending on a later equipment sale |
| Device selection and commissioning | Agreed device specification, configuration, tested functions, customer-owned accounts, and handover documentation; physical installation assigned separately | Builder including automation in the property, or final owner buying an upgrade | Price covers all contracted responsibilities and expected after-sales costs; procurement and physical installation must have explicit payer and responsibility assignments |
| Later service | Defined changes, troubleshooting, or maintenance with explicit coverage | Property owner or operator | Service price covers actual workload and commitments; recurring billing requires a recurring service customers value |

First commercial discussion should explore collaboration on a defined project. It does not require deciding company ownership or an equity partnership. The founder's meaning of "associate" is still open.

Following the 2026-09-20 clarification, the initial offer to explore is design and configuration for a builder selling homes. An illustrative structure is a separately priced design/preparation scope and configuration/acceptance scope, with site visits and revisions defined. Whether the builder would buy either scope, include working automation in the sale, or offer upgrades to the buyer remains unvalidated. Selling homes does not establish demand for automation or a higher achievable property price.

Potential advantages to validate include preventing avoidable construction rework, selecting combinations already tested in real use, clear customer handover, and repeatable delivery through the builder's or architect's existing teams. No sales premium, shorter property sale time, or local demand level is established.

Risks to evaluate include unpaid design work, repeated site visits, construction changes outside the agreed scope, financing equipment before collection, unclear responsibility between trades, and becoming responsible for every future network or platform problem. A future equipment sale should not be assumed to recover an unpriced preparation service.

## Technical facts checked on 2026-09-20

- Home Assistant can act as a Matter controller, so the two can coexist. Some native integrations expose functions not available through Matter. [Home Assistant Matter documentation](https://www.home-assistant.io/integrations/matter/).
- Matter supports customer-authorized access from multiple platforms through multi-admin. This supports platform choice; it does not establish a tested migration procedure for our future offer. [Connectivity Standards Alliance Matter FAQ](https://csa-iot.org/all-solutions/matter/matter-faq/).
- Thread connectivity requires a compatible border router; this capability can be built into another device. An ordinary Wi-Fi router upgrade and a Thread border router are distinct requirements. [Home Assistant Thread documentation](https://www.home-assistant.io/integrations/thread/).
- SONOFF documents the ZBBridge-U as a Zigbee gateway with Matter bridging. Its newer V1.13.0 article describes broader bridging capabilities than the original manual. Exact supported models/functions and the installed firmware therefore need checking before applying either document to the founder's system. The consulted sources did not establish the founder's local-scene limit or reconnection hypothesis. [SONOFF manual](https://support.sonoff.tech/zbbridge-u-usermanual/), [SONOFF V1.13.0 capabilities](https://sonoff.tech/en-uk/blogs/news/sonoff-ultra-matter-bridge-bring-whole-home-devices-into-matter-ecosystem).
- Apple documents Siri accessory control from compatible Apple devices and home-hub support for remote access. Voice use is not limited to a speaker in each room; suitability depends on the user's devices and intended interaction. [Apple Siri home-control guidance](https://support.apple.com/en-au/105027), [Apple HomePod home-control guidance](https://support.apple.com/guide/homepod/control-your-home-and-apple-tv-4k-apd8085c1032/homepod).

Business interpretation: evaluate a small set of tested device/controller/network combinations before making compatibility promises. A manual should describe those combinations, ownership transfer, recovery, and supported changes. Do not promise automatic transfer of scenes, routines, or every manufacturer feature without testing the exact path.

Home Assistant profitability versus a simpler supported configuration is unmeasured. Assess learning time, setup, maintenance, repeat visits, hardware costs, and the additional outcome a customer would pay for. No platform or router purchase is selected by this record.

## Next discovery priorities

1. Clarify services-only versus equipment resale/procurement scope, then the financial and time limits relevant to that model. The founder wants both new and occupied homes and sees new construction through a builder as the easier initial route; do not ask them to choose between the routes again.
2. Establish the specific builder's interest, actual project location and buyer profile, remaining construction decision window, unit count, and repeated layouts before producing an offer. Do not assume the project is in Lomas or matches the proposed older customer segment.
3. Establish included functions, expected user interaction and handover, physical installation and support responsibilities, and willingness to pay for a defined scope. Mixed reactions, experienced convenience, the founder's design/configuration preference, and the hub model are known; the scene investigation remains deferred.

No pricing, margins, budget, loss limit, pilot commitment, platform standard, supplier, or partnership has been agreed. These inputs are needed progressively before commitments or a quotation; they do not block the founder's requested order-of-magnitude discussion.
