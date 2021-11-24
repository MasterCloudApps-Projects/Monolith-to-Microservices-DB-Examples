# Monolith-to-Microservices-DB-Examples

## What Are Microservices?

Microservices are independently deployable services modeled around a business domain. They communicate with each other via networks, and as an architecture choice offer many options for solving the problems you may face. It follows that a microservice architecture is based on multiple collaborating microservices.

## What Advantages Can Microservices Bring?

The advantages of microservices are many and varied. The independent nature of the deployments opens up new models for improving the scale and robustness of systems, and allows you to mix and match technology. As services can be worked on in parallel, you can bring more developers to bear on a problem without them getting in each other’s way. It can also be easier for those developers to understand their part of the system, as they can focus their attention on just one part of it. Process isolation also makes it possible for us to vary the technology choices we make, perhaps mixing different programming languages, programming styles, deployment platforms, or databases to find the right mix.

Perhaps, above all, microservice architectures give you flexibility. They open up many more options regarding how you can solve problems in the future.

However, it’s important to note that none of these advantages come for free. There are many ways you can approach system decomposition, and fundamentally what you are trying to achieve will drive this decomposition in different directions. Understanding what you are trying to get from your microservice architecture therefore becomes important.

## Our work

In this work we have tried to focus into the database decomposition patterns to transform architectures from a monolith to microservices. For this work, we have relied on the publication [Monolith to Microservices](https://samnewman.io/books/monolith-to-microservices/) specifically in chapter 4 (Chapter 4. Decomposing the Database). This book presents examples at a high level, which we have implemented at a low level.

We are implement these database patterns:

- Database view
- Database as a service
- Aggregate Exponsing Monolith
- Split Table

The academic work associated with this repository can be found at this [link](memoria/memoriaTFM.docx)


