# Seedster ver 0.wtf

The basics premise is Seed to sale software for LP's in Canada. Easy to track, start-to-finish, and simple reporting. That's it (for now).


## Architecture

Here's a basic app structure based off [ACMPR's record keeping regulations](http://laws.justice.gc.ca/eng/regulations/SOR-2016-230/page-20.html#h-27).

1. `Transactions`
  * **Cannabis Received**
    - the `name` of the person from whom it was received;
    - the `address` of the site at which it was received;
    - the `datetime` on which it was received; and
    - an indication of `which substance` was received, as well as the following information:
      - in the case of `fresh` or `dried marihuana` or `cannabis oil`:
        * the `quantity` and
        * `brand name`, where applicable
      - in the case of cannabis `other` than cannabis referred to in subparagraph, its:
        * the `quantity`,
        * the `description`,
        * the `intended use` and,
        * if applicable, `brand name`.
  * **Imported substances**
    - imported marihuana (or a substance in paragraph _22(3)(c)_) must retain a copy of the `declaration` required by section 98 and of the `export permit` issued by a competent authority in the country of export.
  * **Exported substances**
    - exported marihuana (or a substance in paragraph _22(3)(c)_) must retain a copy of the `declaration` required by section 106 and of the `import permit` issued by a competent authority in the country of final destination.
  * **Record of verbal order**
    - A licensed producer who receives a **verbal order** referred to in subsection 143(3) must record the following information:
      * the `date` on which the order was placed and the order number;
      * the `information` referred to in paragraphs _143(2)(b)_ and _(c)_; and
      * the `name` of the individual recording the order.

  * **Filling of order from client**
    - A licensed producer who fills an order referred to in section 143 must record the following information:
      * the `given name`, `surname` and `date of birth` of the client for whom the order is placed;
      * the `given name` and `surname` of the individual placing the order;
      * the `quantity`, `brand name` and `lot number` of the fresh or dried marihuana, cannabis oil or marihuana plants or seeds sold or provided;
      * the `date` on which the order was received;
      * the `date` on which the substance was shipped; and
      * the `address` to which the substance was shipped.

  * **Retention of documents**
    - A licensed producer must retain a `written order` referred to in subsection 143(2) or a `written record` of a verbal order referred to in subsection 143(3).

  * **Refusal to fill an order**
    - A licensed producer who refuses to fill an order referred to in section 143 must retain a copy of the `written notice` referred to in subsection 145(3).

  * **Returned substance**
    - A licensed producer who receives fresh or dried marihuana, cannabis oil or marihuana plants or seeds that are returned under section 148 must record the following information:
      * the `given name` and `surname` of the client who returned the substance or on behalf of whom the substance was returned;
      * the `address` of the site at which it was received;
      * the `name` of the substance, its `quantity` and `brand name`; and
      * the `date` on which it was received.

  * **Order from person other than client**
    - A licensed producer who fills an order referred to in subsection 149(1) or (2) must record the following information:
      * the `name` of the person to whom the substance was sold or provided;
      * the `shipping address`;
      * an indication of `which substance` was ordered, as well as the following information:
        * in the case of fresh or dried marihuana or cannabis oil, its `quantity` and, if applicable, `brand name`, or
        * in the case of cannabis other than cannabis referred to in subparagraph (i), its `quantity`, `description` and, if applicable, `brand name`; and
      * the `date` on which the substance was shipped.

  * **Refusal to fill an order**
    - A licensed producer who refuses to fill an order referred to in subsection _149(1)_ or _(2)_ must retain a copy of the `written notice` referred to in subsection 151(2).

1. `Client Registrations`
  * **Information**
    - A licensed producer must record the following information:
      - details of the verifications performed under subsection _121(2)_, section 132, subsection _135(2)_ and paragraph _139(2)(b)_; and
      - what will serve as the unique identifier referred to in paragraph _133(2)(b)_ and the manner in which and the date on which it was communicated to the client.

  * **Documents**
    - A licensed producer must retain the following documents:
      - the `registration application` referred to in section 130;
      - the `medical document` referred to in section 130, or, if the document has been returned in accordance with subsection 136(3), a copy of it;
      - the copy of a `registration certificate` referred to in section 130;
      - a copy of a `registration document` referred to in paragraph 133(2)(a);
      - the `application` for the amendment of a registration referred to in section 137;
      - a copy of an `amended registration document` referred to in subsection 138(2); and
      - a copy of a `notice` referred to in section 136 or subsection 139(4) or (6).

1. `Security, Production and Inventory`
  * **Security**
    - A licensed producer must keep
      - the `visual recordings` referred to in sections 54 and 59;
      - the `records` referred to in subsections _56(2)_ and _62(2)_; and
      - the `record` referred to in subsection _57(3)_.

  * **Good production practices and packaging, labelling and shipping**
    - A licensed producer must keep
      - records demonstrating that each lot or batch of fresh or dried marihuana, cannabis oil or marihuana plants or seeds that they sold or provided under subsection 22(4) or (5) was `produced`, `packaged` and `labelled` in accordance with Subdivisions D and F of Division 1;
      - a list of all `brand names` of fresh or dried marihuana, cannabis oil or marihuana plants or seeds that they `produced`, `packaged` or `labelled`;
      - a copy of the `sanitation program` referred to in section 72 in use at their site;
      - a copy of the `standard operating procedures` referred to in section 73 in use at their site;
      - documentation concerning the system of control referred to in section 74 in use at their site;
      - a description of the qualifications of the quality assurance person in respect of the matters referred to in subparagraph 75(1)(a)(ii); and
      - records of every complaint referred to in paragraph 75(1)(b) and of any corrective action taken.

  * **Sale or provision**
    - A licensed producer who sells or provides fresh or dried marihuana, cannabis oil or marihuana plants or seeds must keep
      - records of any testing conducted by or on behalf of the licensed producer in respect of any lot or batch of the substance;
      - records of information necessary for the system of control referred to in section 74; and
      - a record of the information that the licensed producer is required by section 77 to provide to the Minister in respect of the recall of the substance.

  * **Dried marihuana equivalency factor**
    - A licensed producer must keep a record of the information concerning the method that they have used to determine the dried marihuana equivalency factor under section 79.

  * **Lot or batch — marihuana**
    - A licensed producer must keep a record of the following information concerning each lot or batch of marihuana that they propagate, sow, harvest, dry, package or destroy:
      - the `datetime` on which marihuana plants are propagated by means other than sowing seeds and the number of new plants propagated in this manner;
      - the `datetime` on which marihuana seeds are sown and their net weight on that date;
      - the `datetime` on which marihuana is harvested and its net weight on that date;
      - the `datetime` on which the drying process for marihuana is completed, if any, and its net weight on that date;
      - the `datetime` on which marihuana is packaged and its net weight on that date; and
      - the `datetime` on which marihuana is destroyed and its net weight on that date, before the destruction.
  * **Lot or batch — cannabis oil**
    - A licensed producer must keep a record of the following information concerning each lot or batch of cannabis oil that they produce, package or destroy:
      - the `datetime` on which the oil is produced and its `net weight` or `volume` on that date;
      - if applicable, the `datetime` on which the oil is put into a capsule or other similar dosage form and the number of capsules or `units` of that dosage form;
      - in respect of the cannabis that was used to produce the oil, its `description`, its `net weight` or `volume`, its `lot` or `batch number` and the `date` on which it was produced;
      - the `datetime` on which the oil is packaged and its `net weight` or `volume` on that date; and
      - the `datetime` on which the oil is destroyed and its `net weight` or `volume` on that date, before the destruction.

  * **Research and development**
    * Every licensed producer must keep a record of the following information concerning cannabis that they use in a research and development activity:
      * (a) its `description`, the `quantity` used, its `lot` or `batch number` and, if applicable, its `brand name`;
      * (b) the `date` on which it was used in that activity;
      * (c) the `purpose` and a brief `description` of that activity;
      * (d) in respect of any product or compound containing that cannabis that they have made or assembled in the course of that activity,
        * (i) its `description`,
        * (ii) the `datetime` on which it was made or assembled and the quantity made or assembled,
        * (iii) if applicable, the `datetime` on which it was used for testing and the quantity used, and
        * (iv) if applicable, the `datetime` on which it was placed in inventory and the quantity placed in inventory; and
      * (e) any other details permitting the reconciliation of the quantity of cannabis referred to in paragraph (a) and the quantities of products or compounds referred to in paragraph (d).

  * **Destroyed cannabis**
    * A licensed producer must keep, for each instance in which they destroy cannabis, a record of the following information:
      * (a) the `date` on which the cannabis was destroyed, the name of the substance destroyed and its net weight on that date, before the destruction;
      * (b) the `location` at which it was destroyed;
      * (c) a brief `description` of the method of destruction;
      * (d) the `names of the witnesses` to the destruction that are referred to in paragraph _30(1)(b)_ and the basis on which they are qualified to be witnesses under subsection _30(2)_; and
      * (e) if applicable, the `name` of the person who accompanied the cannabis in accordance with subsection 30(3).

  * **Statement by witnesses**
    * A licensed producer must keep, for each instance in which they destroy cannabis, a statement `signed` and `dated` by _each_ of the witnesses referred to in paragraph _30(1)(b)_ stating that they have witnessed the destruction and that the cannabis was destroyed in accordance with section 30.

  * **Inventory — marihuana**
    * A licensed producer must keep a record of the `net weight` of each of the following that are in inventory at their site at the end of each quarter of the calendar year:
      * (a) `marihuana seeds`, other than `marihuana seeds` referred to in paragraph (h);
      * (b) `harvested marihuana`, other than marihuana referred to in paragraphs (e) and (f), that is not to be subjected to a drying process;
      * (c) `harvested marihuana`, other than marihuana referred to in paragraphs (e) and (g), in respect of which the drying process has not been completed;
      * (d) `harvested marihuana`, other than marihuana referred to in paragraphs (e) and (g), in respect of which the drying process has been completed;
      * (e) `marihuana` that is destined for destruction;
      * (f) `packaged fresh marihuana`;
      * (g) `packaged dried marihuana`;
      * (h) `packaged marihuana seeds`; and
      * (i) `cannabis` other than marihuana or cannabis oil, with an indication of the `name` and `net weight` of each of the substances in question.

  * **Inventory — marihuana plants**
    * A licensed producer must keep a record of the number of marihuana plants destined to be sold or provided that are in inventory at their site at the end of each quarter of the calendar year.

  * **Inventory — cannabis oil**
    * A licensed producer must keep a record of the `net weight` of each of the following that are in inventory at their site at the end of each quarter of the calendar year:
      * (a) `cannabis oil` that has not been packaged, other than cannabis oil referred to in paragraph (c);
      * (b) packaged `cannabis oil`, other than cannabis oil referred to in paragraph (c); and
      * (c) `cannabis oil` that is destined for destruction.

1. `Notices to Local Authorities`
  * **Notices**
    * A licensed producer must keep a copy of
      * (a) each `notice` provided to local authorities under sections 48 to 50; and
      * (b) each copy of a `notice` provided to the Minister under section 50.

1. `Communications with Licensing Authorities`
  * **Documents**
    * A licensed producer must keep
      * (a) a copy of each `notice` provided to a licensing authority under section 51, as well a copy of the copy of the notice provided to the Minister under that section;
      * (b) for each `request` received from a licensing authority under subsection 123(1),
        * (i) a copy of `the request`, together with any supporting documentation received,
        * (ii) a record of the `date` on which the request and documentation were received,
        * (iii) a copy of the `information` that was provided in response to the request,
        * (iv) a record of the `date` on which the information was provided, and
        * (v) a record of `the steps that were taken` to ensure that the information was securely transmitted to the authority;
      * (c) a copy of any `request` or notice received from a licensing authority under section 124 and a record of the date on which it was received;
      * (d) for each instance in which they provide information to a licensing authority under section 124,
        * (i) a copy of `the information`,
        * (ii) a record of the `date` on which the information was provided, and
        * (iii) a record of `the steps that were taken` to ensure that the information was securely transmitted to the authority; and
      * (e) a copy of the `notice` sent under subsection 124(5).

---

## Retention information

As this is a software solution, retention isn't as much of an issue, but this could be built in, so I included it.

1. `General Obligations`
  * **Manner of keeping records**
    * A licensed producer must ensure that the records, documents and information referred to in this Division are kept in a manner that will enable an audit of them to be made in a timely manner and are available at their site.

  * **Retention period**
    * A licensed producer must retain the records, documents and information for the following periods:
      * (a) in the case of a notice that the producer is required to provide or send under this Part, for a period of two years after the day on which the notice is provided or sent;
      * (b) in the case of information that the producer is required to record under sections 152 and 155, subsection 156(1), section 157, subsections 158(1) and 159(1) and sections 163, 164 and 166, for a period of two years after the day on which the information is recorded;
      * (c) in the case of the documents referred to in sections 153 and 154, for a period of two years after the day on which the declaration referred to in section 98 or 106, as applicable, is sent to the Minister;
      * (d) in the case of the documents referred to in subsection 156(2) and paragraphs 159(2)(a) to (f), for a period of two years after the day on which the producer obtained them or, in the case of documents made by the producer, the day on which they were made;
      * (e) in the case of the visual recordings or the records referred to in section 160, for a period of two years after the day on which they were made;
      * (f) in the case of the records referred to in paragraphs _161(1)(a)_ and _(2)(b)_, for a period of two years after the date of the last sale or provision of any portion of the lot or batch of fresh or dried marihuana, cannabis oil or marihuana plants or seeds under subsection 22(4) or (5);
      * (g) in the case of a document referred to in any of paragraphs _161(1)(b)_ to (e), for the period during which it is current and for an additional period of two years after the day on which it is replaced by a new version;
      * (h) in the case of a document referred to in paragraph _161(1)(f)_, for the period during which the quality assurance person acts in that capacity and for an additional period of two years after the day on which the person ceases to do so;
      * (i) in the case of the records referred to in paragraph _161(1)(g)_, for a period of two years after the day on which the complaint was recorded;
      * (j) in the case of the records referred to in paragraph _161(2)(a)_, for a period of two years after the date of the last sale or provision of any portion of the lot or batch, other than a sale or provision for destruction;
      * (k) in the case of the records referred to in paragraph _161(2)(c)_, for a period of two years after the day on which the substance was recalled;
      * (l) in the case of the information concerning the method referred to in section 162, for a period of two years after the day on which the information is recorded;
      * (m) in the case of the records and documents referred to in section 165, for a period of two years after the day on which the cannabis was destroyed;
      * (n) in the case of a document or record referred to in paragraph 168(b), for a period of two years after the day on which the information was provided to the licensing authority;
      * (o) in the case of a request or notice referred to in paragraph 168(c), for a period of two years after the day on which it was received;
      * (p) in the case of a document or record referred to in paragraph 168(d), for a period of two years after the day by which the producer was required to provide the information; and
      * (q) in the case of a notice referred to in paragraph 168(e), for a period of two years after the end of the quarter to which the notice relates.

  * **Case reports and summary reports**
    * A licensed producer must retain the serious adverse reaction case reports and the summary reports referred to in subsections 78(1) and (2), respectively, for a period of 25 years after the day on which they were made.
