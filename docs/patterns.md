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
- [Clean Architecture by Robert C. Martin](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164?&linkCode=ll1&tag=soneaca-20&linkId=fb2f76f0b846a8b61d98f09dd40d798e&language=en_US&ref_=as_li_ss_tl)
- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/B0C625HRLL?dib=eyJ2IjoiMSJ9.yI8BkTYntjHysk8RF1dYTW6IvmMwVSp8t8h_Cs5aen2hLWQFdK7nonmU_VDrjrpMtkU9rI8p-jcgVxdfMW_88xclv6jq90NAukRZ3-jJ1a-qfNROoGB7U9xHPecSgwnU33aeSPtZxypTU8kbjXOcNtnu6WxbywZM1rS80vZDKbWP6OsKoLrIAPGvinJkNAlW_8wu_Hr-Oyl1umgjikIfXmHlglSB8A92HjF6Pyb3ckE.E4Xcdf_2I5vvFk12phlsKiEajNkqu-tcvZ3WI13OPAc&dib_tag=se&keywords=Design+Patterns%3A+Elements+of+Reusable+Object-Oriented+Software&qid=1735831891&sr=8-4&linkCode=ll1&tag=soneaca-20&linkId=687c8ca592a447cab1edee1b53d5c22c&language=en_US&ref_=as_li_ss_tl)

## AI Collaboration Considerations
- Validate AI-generated patterns
- Ensure architectural integrity
- Maintain code readability
- Critically review generated solutions
