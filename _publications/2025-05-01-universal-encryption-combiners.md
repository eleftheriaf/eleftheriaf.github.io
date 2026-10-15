---
title: "Universal Secret-Key and Public-Key Encryption Using Combiners"
collection: publications
category: other
permalink: /publication/2025-05-01-universal-encryption-combiners
excerpt: This thesis constructs universal secret-key and public-key encryption schemes using combiners, in the style of Levin's universal one-way function.
date: 2025-05-01
venue: 'M.S. Thesis, Cornell University'
slidesurl: 
paperurl: '/files/Cornell_University_Thesis_Template.pdf'
bibtexurl: 
citation: 
---
Abstract:

We construct universal secret-key and public-key encryption schemes using combiners, in the style of Levin's universal one-way
function. Given a finite list of candidate encryption schemes, our combiners produce a single scheme that is correct and
semantically secure if and only if at least one of the input schemes satisfies these properties. Our constructions are efficient
and require no assumptions beyond the existence of such a secure scheme within the list.

We develop and analyze these combiners for both the secret-key and public-key settings, establishing correctness and many-message
semantic security. We show that if there exists any encryption scheme that is efficiently computable and semantically secure, then
the output of our combiner is also secure and efficient. By enumerating all possible polynomial-time encryption schemes and applying
our construction, we obtain universal encryption schemes which are secure if and only if any such scheme exists.

See the full thesis [here](/files/Cornell_University_Thesis_Template.pdf).
