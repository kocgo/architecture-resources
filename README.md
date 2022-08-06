## Layered Architecture

### State Machine ?

## Pipeline Architecture
Monolithic, simple architecture style which is consisting of two elements: pipes and filters.

### Pipes
Unidirectional connections between filters.

### Filters
Filters do not know about each other. Each filter does a specific task.

1) Producers (Starting point)
2) Transformers (Input, proccess, output)
3) Testers (input, discard or pass output)
4) Consumers

### Pipeline vs Event Driven Architecture
They are not the same thing even with a messaging system.

Pipeline is all about synchronous data filtering. Always unidirectional. Usually monolithic.
Event driven architecture is about async data proccessing. Can be request/reply. Usually microservices.

## Architecture Patterns Books
https://learning.oreilly.com/library/view/software-architecture-patterns

## Folder Structure For API's
https://www.youtube.com/watch?v=oNlMrpnUSFE
