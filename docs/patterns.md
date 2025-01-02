# Common Patterns and Anti-patterns in Software Architecture

## Design Patterns
### Creational Patterns
- **Factory Method**: [Gang of Four Design Patterns](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633610)
  - Flexible object creation
  - [Martin Fowler's Explanation](https://martinfowler.com/articles/creationalPatterns.html)

- **Singleton**: 
  - Controlled global instance
  - [Refactoring Guru - Singleton](https://refactoring.guru/design-patterns/singleton)

- **Builder**: 
  - Complex object construction
  - [Source Making - Builder Pattern](https://sourcemaking.com/design_patterns/builder)

### Structural Patterns
- **Adapter**: 
  - Interface compatibility
  - [Adapter Pattern Explained](https://www.baeldung.com/java-adapter-pattern)

- **Decorator**: 
  - Dynamic functionality extension
  - [Design Patterns - Decorator](https://www.tutorialspoint.com/design_pattern/decorator_pattern.htm)

- **Composite**: 
  - Hierarchical object composition
  - [Composite Pattern Overview](https://www.geeksforgeeks.org/composite-design-pattern/)

### Behavioral Patterns
- **Observer**: 
  - Event-driven communication
  - [Observer Pattern Tutorial](https://www.journaldev.com/1739/observer-design-pattern-in-java)

- **Strategy**: 
  - Interchangeable algorithms
  - [Strategy Pattern Explained](https://www.baeldung.com/java-strategy-pattern)

## Anti-patterns
### Architectural Anti-patterns
- **Monolithic Architecture**: 
  - Rigid, hard to scale
  - [Microservices Guide](https://microservices.io/post/microservices/2022/02/08/thats-not-microservices.html)

- **God Object**: 
  - Oversized, multi-responsibility class
  - [Code Smells - God Object](https://sourcemaking.com/refactoring/smells/large-class)

- **Spaghetti Code**: 
  - Tangled, unstructured implementation
  - [Preventing Spaghetti Code](https://www.toptal.com/software/predicting-spaghetti-code)

## Best Practices
- Favour composition over inheritance
- Keep components small and focused
- Design for testability
- Minimize external dependencies

## Learning Resources
- [Martin Fowler's Architecture Blog](https://martinfowler.com/architecture/)
- [Clean Architecture by Robert C. Martin](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164)
- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633610)

## AI Collaboration Considerations
- Validate AI-generated patterns
- Ensure architectural integrity
- Maintain code readability
- Critically review generated solutions