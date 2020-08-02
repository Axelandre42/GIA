Introduction
============

Internet services are constantly being created.
And most of the time, identification, authentification
and authorisation is implemented on their side meaning
those services needs to enforce their own security
guidelines. Otherwise, they could have security breaches.
And it has already happened.

Also, services end-users needs to have an authentification
mean that is, most of the time, a password. This implies
every users needs differents passwords for every services
they use. Or either two-factor authentication is not
widely spread.

This documents suggests a workflow based on OpenID Connect 1.0 [OIDC]_

.. index::
   single: scope

This document scope is to every organisation who needs
to deal with identification and authentication.

Definitions
-----------

.. index::
   pair: end user; user

end user
   A person using a service and who got an identity through an identification provider.

.. index::
   pair: identification provider; provider

identification provider
   An organisation that provides identity to end users trough this standard.

.. index::
   signle: relying party

relying party
   A service provider that relies on this standard to retrieve identity for an end user.

Requirement Notation
--------------------

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL
NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and
"OPTIONAL" in this document are to be interpreted as described in
[RFC2119]_