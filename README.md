# Building REST services with Spring

https://spring.io/guides/tutorials/rest/

Throughout this tutorial, you have engaged in various tactics to build REST APIs. As it turns out, REST isn’t just about pretty URIs and returning JSON instead of XML.

Instead, the following tactics help make your services less likely to break existing clients you may or may not control:

+ Don’t remove old fields. Instead, support them.

+ Use rel-based links so clients don’t have to hard code URIs.

+ Retain old links as long as possible. Even if you have to change the URI, keep the rels so older clients have a path onto the newer features.

+ Use links, not payload data, to instruct clients when various state-driving operations are available.
