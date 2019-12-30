- SOLID 原则
  - **S**ingle Responsibility Principle，单一职责原则
    - 在代码设计上，让一个类只处理一组相关的事情，控制了它的变化方向，后期也能更好的定位。如果引发变化的因素很多，会导致类的职责过多，难以维护，上帝类就是这么形成的。
  - **O**pen Close Principle，开闭原则
    - 在代码设计上，提倡对修改关闭，对扩展开放，你应该为你的服务调用者提供一个他需要的抽象、高层次的接口，后期你的服务有新的种类，你只需要新增一个实现该抽象、高层次接口具体服务，而不需要修改调用者的使用方式。
  - **L**iskov Substitution Principle，里氏替换原则
    - 在代码设计中，里氏替换原则对子类进行了约束，子类不要试图去重写父类的具体功能。对使用者来说，能够使用父类的地方，一定可以使用其子类，并且预期结果是一致的
  - **I**nterface Segregation Principle，接口隔离原则
    - 提倡不要将一个大而全的接口扔给使用者，而是将每个使用者关注的接口进行隔离
  - **D**ependency Inversion Principle，依赖倒置原则
    - 在代码设计中，使用者应该依赖一个抽象的服务接口，而不是去依赖一个具体的服务执行者，依赖关系从依赖具体实现到依赖抽象接口，从而倒置过来