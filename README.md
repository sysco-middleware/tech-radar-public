# Rationale

The TechRadar is an asset which anyone at Sysco can use in order to visualize data corresponding to technological trends, relevance, adoption cycle and so on .

Technologies can move in and out of a radar and through the different rings depending on different factors, which can be both internal and external in reference to Sysco. 

When a technology appears / disappears from a radar or moves through the rings, we call it a "blip".

# Versioning

[CHANGELOG](CHANGELOG.md)

## Quadrants

Quadrants allow us to organize technologies in general categories that make sense to us and which are pretty much self-explaining. This dimension exists mainly for improved visualization purposes, and shouldn't have too much influence on the specific discussions related to one or more technologies. This means that we won't spend a lot of time defining these categories or trying to decide where to place technologies in cases where there is some ambiguity. Quadrants can also be customized and will vary between different radars.

### Architecture & Techniques

Examples: Domain Driven Design, Architectural Decision Records, Pair Programming, Service Mesh

### Data Management & Platform

Examples: Presto, Consul, Kafka, Apache Nifi

### Infrastructure & Tools

Examples: Bitbucket, Slack, Terraform, VMWare, Kubernetes

### Language & Frameworks

Examples: R, Kotlin, Scala, Go, Kafka-Streams

## Rings

The rings are the key dimension to a TechRadar as they represent the different stages of technology adoption, from becoming aware of a specific tech to actually putting it on production and eventually moving away from it.

Considering these rings while discussing technologies should allow us to focus the narratives around them and actually reach outcomes and conclusions which can drive decision making.

### Hold

Technologies on the "hold" ring have either just came to our attention or are on their last mile before being dropped from Sysco's portfolio.

### Assess

When technologies are on the "assess" ring, it means that there's movement around them and an on-going discussion within the organization. At this stage we're usually gathering evidence on why and how we should proceed with a specific tech, whether we're promoting it or phasing it out. Small PoCs delivered internally or at customers are quite relevant, as well as focused discussions happening within teams, competency groups, specialized channels, etc.

### Trial

Placing technologies on the "trial" ring involves committment, as we're effectively pushing them to the verge of either the production line or the retirement queue. This committment can mean building competency, looking for / hiring resources, engaging with vendors & customers, establishing partnerships and so on. The goal is always to be opportunistic while taking sound, smart decisions and avoiding being misled by hype-cycles.

### Adopt

Having technologies on this ring means that we're both confident and competent in them. Tech here has been battle tested and well documented through customer cases, success stories, internal deliveries, etc. 

Staying in the "adoption" phase means also that we're going to keep investing in this tech and trying to push it to both our customers and internal products.

## Technology framework

Radar(s) will tell the current story of the technology landscape, and
descriptions contain why a technology has reached a certain ring.

As technologies can potentially be mapped to different Radars, and
we need to know the full story, we will track documentation, changelogs, and use-cases about each technology.

New technology can be documented without being added to a Radar yet.

