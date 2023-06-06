# Hexagonal Architecture

Also known as the Ports and Adapters pattern, Hexagonal Architecture is a design principle coined by Alistair Cockburn. It aims to create loosely coupled application components that can be easily connected, swapped, and tested.

The central idea of Hexagonal Architecture is to allow an application to equally be driven by users, programs, automated tests, or batch scripts, and to be developed and tested in isolation from its eventual run-time devices and databases.

Here are the main goals of Hexagonal Architecture:

- Decouple the core logic of the application from the services it uses, allowing the services to be plugged into the application as interchangeable modules.
- Make the application easy to test by allowing the replacement of its outbound services with test doubles.
- Allow different configurations of the application’s inbound and outbound services to be assembled easily, enabling quick prototyping, testing, and deployment.

Explore the resources below to further your understanding of Hexagonal Architecture. And remember, if you come across a resource you think would benefit others, please add it to this list following our [contributing guidelines](link-to-your-CONTRIBUTING.md).

## Articles

- [Hexagonal Architecture, there are always two sides to every story](https://medium.com/ssense-tech/hexagonal-architecture-there-are-always-two-sides-to-every-story-bc0780ed7d9c)
