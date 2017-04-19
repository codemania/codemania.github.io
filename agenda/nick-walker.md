---
layout: speaker2017
speakerName: Nick Walker
title: Nick Walker
speakerTwitter: nz_walker
speakerBio: |
    Nick works on the Platform team at Vend, responsible for ensuring that the system architecture scales for their rapid growth in customers and developer team size.<br/><br/>
    Over the past 4 years he's been working on everything from internal tooling for microservices, Kafka-based databuses and routing layers for datacenter migrations.<br/><br/>
    His passions include providing Vend developers with GIFs for all occasions, where he is summoned on Slack by his handle "@needagif".
speakerImage: 2017/nick.jpg
talkTitle: Making Microservices Durable
talkBlurb: |
    <p>Much ado has been made about service orientated architecture and how it can speed up development and improve application resilience. However, passing data between services remains a challenging problem. Common recommendations such as message queues and RPC often choose availability instead of durability/consistency - a tradeoff which is unacceptable for some systems.</p>
    <p>This talk introduces the concept of Change Data Capture and how it can be used to provide durable event passing between services. At its core, this is achieved by transforming a database replication log into a stream of row changes emitted to a Kafka cluster. Individual services can then consume this stream of events, removing any need for direct service-to-service RPC or queues.</p>
    <p>After this talk you will understand the basics of implementation, the tradeoffs involved and failure modes / recovery mechanisms.</p>
---
