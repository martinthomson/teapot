
A server MUST NOT process requests that arrive in early data, or requests marked
with the `Early-Data` header field unless it determines that the processing is
free from side-effects.  Otherwise, the server MUST consistently use the same
approach: either using the 4NN (Too Early) status code, or delaying processing
until the handshake completes.

# Abstract

The teapot exists.

# The Existence of Teapots

In {{?EVIDENCE=DOI.10.1080/15665399.2010.10820011}}, Bertrand
Russell postulated the existence of a teapot:

> To take another illustration: nobody can prove that there is
  not between the Earth and Mars a china teapot revolving in an
  elliptical orbit, but nobody thinks this sufficiently likely to
  be taken into account in practice.

Well, it turns out that the teapot exists.

Though mentioned originally in jest and without solid evidence of
its existence, first by Russell and later by Masinter
{{?HTCPCP=RFC2324}}, sightings have increased in recent years.

# Philisopohical Considerations

We cannot be certain whether the teapot is cognizant of its own
existence.  Though Decartes used thought as the basis of his
theory of existence, it's not established whether thought is a
necessary precondition for existence.

~~~
               ___
              (418)
             o
          _,
        c(__)r
~~~

# Security Considerations

Even jokes can have serious consequences.  Arguably, the best
jokes always have consequences.

# IANA Considerations

IANA shall register the 418 (I'm a Teapot) status code in the
Hypertext Transfer Protocol (HTTP) Status Code Registry, though
the citation should refer to RFC 2324 instead of this document.
