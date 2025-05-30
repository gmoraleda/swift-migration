---
title: Home
layout: home
nav_order: 1
description: 'This is a site to help you migrate your Swift code to Swift 6.'
permalink: /
---

# Swift 6 Migration Resources

Swift 6 was introduced the _16th of September 2024_. This site is a collection of resources to help you migrate your Swift code to Swift 6.
{: .fs-6 .fw-300 }

---

{: .important }

This is a collection of resources to help you migrate your Swift code to Swift 6. This site is a work in progress and will be updated as more resources become available. The resources are not exhaustive and may not cover all aspects of the migration process. I'm not affiliated with Apple or the Swift team. This site is not an official resource for Swift 6 migration.

## Getting started

Read the Swift 6 [release notes](https://www.swift.org/blog/announcing-swift-6/) to learn about the new features and changes in Swift 6.

### Books[^1]

- [Modern Concurrency in Swift (Second Edition)](https://amzn.to/48wIoDI): Introducing Async/Await, Task Groups & Actors by _Marin Todorov_.
- [Modern Concurrency on Apple Platforms](https://amzn.to/3C5AVPQ): Using async/await with Swift by _Andrés Ibañez Kautsch_.

### Official migration guide

A great point to start is to read the official migration guide for Swift Concurrency. You can find it [here](https://www.swift.org/migration/documentation/migrationguide/). It covers the most important changes and how to migrate your code to the new concurrency model.

### Articles

- [Sendable and @Sendable closures explained with code examples](https://www.avanderlee.com/swift/sendable-protocol-closures/), by SwiftLee
- [Sendable and @Sendable closures](https://www.hackingwithswift.com/swift/5.5/sendable), by Paul Hudson
- [Understanding Concurrency in Swift 6 with Sendable protocol, MainActor, and async-await](https://medium.com/@egzonpllana/understanding-concurrency-in-swift-6-with-sendable-protocol-mainactor-and-async-await-5ccfdc0ca2b6), by Egzon Pllana
- [Thread Safety with Mutex in Swift 6](https://medium.rip/@noahlittle199/thread-safety-with-mutex-in-swift-6-575e79f14386), by Noah Little
- [Swift 6 Incomplete Migration Guide for Dummies](https://brightdigit.com/tutorials/swift-6-async-await-actors-fixes/), by brightdigit
- [ Migrating to Swift 6](https://apiumhub.com/tech-blog-barcelona/migrating-to-swift-6/), by Apium

## Contributing

If you have a resource you would like to share, please [open an issue](https://github.com/gmoraleda/swift-migration/issues/new/) or submit a pull request. You can also reach out to me on [🦋](https://bsky.app/profile/gmoraleda.bsky.social).

## Get Help

If you or your team need help migrating your Swift code to Swift 6, I can help. I have experience migrating Swift codebases to the latest Swift versions. You can reach out to me [per e-mail](mailto:swift.migration@gmx.net).

---

[^1]: These are affiliate links. If you buy a book using these links, I may earn a small commission. This helps me maintain this site and keep it free of ads. Thank you for your support!
