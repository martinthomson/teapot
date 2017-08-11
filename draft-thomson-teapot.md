---
title: The Teapot Exists
docname: draft-thomson-teapot-latest
category: info

ipr: trust200902
area: ART
keyword: Internet-Draft

stand_alone: yes

author:
 -
    ins: M. Thomson
    name: Martin Thomson
    organization: Mozilla
    email: martin.thomson@gmail.com

informative:
  TEAPOT:
    title: "Is There a God?"
    author:
      -
        ins: B. Russell
        name: Bertrand Russell
    date: 1952
    seriesinfo: Never published
    target: https://www.cfpf.org.uk/articles/religion/br/br_god.html
  COGITO:
    title: "Discourse on the Method"
    author:
      -
        ins: R. Descartes
        name: Rene Descartes
    date: 1637


--- abstract

The teapot exists.

--- middle

# The Existence of Teapots

In an unpublished article in 1952 {{TEAPOT}}, Bertrand Russell postulated the
existence of a teapot:

> To take another illustration: nobody can prove that there is
  not between the Earth and Mars a china teapot revolving in an
  elliptical orbit, but nobody thinks this sufficiently likely to
  be taken into account in practice.

Though mentioned originally in jest and without solid evidence of its existence,
first by Russell and later by Masinter {{?HTCPCP=RFC2324}}, sightings have
increased in recent years.

The teapot exists.


# Philosophical Considerations

We cannot be certain whether the teapot is cognizant of its own existence.
Though Decartes {{COGITO}} used thought as the basis of his theory of existence,
it's not established whether thought is a necessary precondition for existence.

~~~


                              (418)
                             o
                          _,_
                        c(___)r


~~~


# Security Considerations

Even jokes can have serious consequences.  Arguably, the best jokes always have
consequences.


# IANA Considerations

IANA shall register the 418 (I'm a Teapot) status code in the Hypertext Transfer
Protocol (HTTP) Status Code Registry, citing this document.

As recommended by {{!RFC7231}}, this document refines the definition of the 418
status code.  Being a teapot is irrevocable, therefore this status code is
cacheable.  The payload of a response with a 418 status code isn't a
representation of the effective request URI unless the Content-Location header
field contains the effective request URI.

--- back
