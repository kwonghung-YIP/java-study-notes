1 | 2 | 3 | 4
--- | --- | --- | ---
Supplier<T> | T get() | gets a result | java.util.function
Callable<V> | V call() | computes a result, or throws an exception if unable to do so | java.util.conncurrent
Runnable | void run() |  | java.lang
Consumer<T> | void accept(T t) default Consumer<T> andThen(Comsumer<? super T> after) | | java.util.function
