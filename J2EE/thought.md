1. 如果有同一个业务流程，只是流程和参数有一些不同，可以抽象一个类，定义业务方法。
  然后不同的流程新建类继承父类并重写业务方法，需要的时候在每个子类重写的方法中都
  去调用父类的方法来实现一些需要对这类方法进行统一的过滤等的操作。