# Class and object diagrams

[Architecture overview](index.html)

* TOC
{:toc}

---

The application was developed according to the MVC software design pattern.

There are multiple GoF patterns implemented in the code. For example, constant (over)usage of interfaces implements **template method** pattern, `Transfer` is a **facade** for `Transaction`.

## Class diagrams

The system is too big to fit in one class diagram.

![](images/class.svg)

Class diagrams below provide an overview of classes under the respective components.

### Domain

![](images/class_domain.svg)

### Integration

![](images/class_integration.svg)

### Repository

![](images/class_repository.svg)

## Object diagram

![](images/object.svg)

---

[Previous (Component diagram)](component.html)

[Next (Sequence diagram)](sequence.html)
