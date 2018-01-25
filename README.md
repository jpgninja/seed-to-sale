# seed-to-sale
Seed to sale software for LP's in Canada


##Architecture

(based off [ACMPR's record keeping regulations](http://laws.justice.gc.ca/eng/regulations/SOR-2016-230/page-20.html#h-27))

* `Transactions`
  * **Cannabis Received**
    a. the `name` of the person from whom it was received;
    a. the `address` of the site at which it was received;
    a. the `datetime` on which it was received; and
    a. an indication of `which substance` was received, as well as the following information:
      a. in the case of `fresh` or `dried marihuana` or `cannabis oil`:
        * the `quantity` and
        * `brand name`, where applicable
      a. in the case of cannabis `other` than cannabis referred to in subparagraph, its:
        * the `quantity`,
        * the `description`,
        * the `intended use` and,
        * if applicable, `brand name`.
