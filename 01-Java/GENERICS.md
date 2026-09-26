# Java Generics

## 1. Why Generics Exist

Generics provide compile-time type safety and allow reusable code without pervasive casts.

They are broader than collections, although collections are a major use case.

---

## 2. Generic Classes

```java
class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```

Usage:

```java
Box<String> box = new Box<>();
box.set("hello");

String value = box.get();
```

`T` is a type parameter chosen at compile time.

Production example:

```java
class ServiceResult<T> {
    private boolean success;
    private String errorCode;
    private String message;
    private T data;
}
```

`ServiceResult<Account>` means the variable part is the data payload, not every field.

---

## 3. Generic Interfaces

```java
interface Repository<T, ID> {
    T findById(ID id);
}
```

Implementation:

```java
class AccountRepository implements Repository<Account, Long> {
    @Override
    public Account findById(Long id) {
        // ...
        return null;
    }
}
```

Mental model:
- `T` = entity type
- `ID` = identifier type

---

## 4. Generic Methods

```java
public static <T> T findFirst(List<T> items) {
    return items.isEmpty() ? null : items.get(0);
}
```

Important distinction:

```text
<T>          declares the method type variable
T            is the return type
List<T>      connects the input type to the return type
```

Example:

```java
List<String> names = List.of("Gopal", "Ravi", "John");
String name = findFirst(names);

List<Integer> numbers = List.of(10, 20, 30);
Integer number = findFirst(numbers);
```

Java infers:
- `T = String`
- `T = Integer`

Explicit type arguments are possible:

```java
GenericMethodDemo.<Integer>findFirst(numbers);
```

but normally inference makes this unnecessary.

---

## 5. Multiple Type Parameters

```java
public static <T, R> R convert(
        T input,
        Function<T, R> converter) {
    return converter.apply(input);
}
```

Example:

```java
String text = "123";

Integer number =
        convert(text, Integer::parseInt);
```

Java infers:
- `T = String`
- `R = Integer`

Mental model:

```text
T  →  Function<T,R>  →  R
```

`Function<T,R>` is a functional interface whose `apply(T)` accepts T and returns R.

This differs from:

```java
<T> T
```

where the same type relationship is usually maintained.

---

## 6. Next: Bounds

### Type parameter bound

```java
<T extends Number>
```

This restricts T to `Number` or a subtype.

Example:

```java
public static <T extends Number> double toDouble(T value) {
    return value.doubleValue();
}
```

This is the next topic to study in detail.

---

## Interview mental models

### Generic class
The class is parameterized.

### Generic interface
The contract is parameterized.

### Generic method
The method introduces its own type variables.

### Multiple type parameters
Use them when different type roles need independent types.

### Generic return relationship
`<T> T` often means input and output share a type relationship.

### Transformation relationship
`<T,R> R` allows input and output to be different types.

---

## Interview traps to revisit

- Compile-time safety vs runtime type safety
- Type inference
- Type erasure
- Why primitives cannot be generic type arguments
- Wildcards vs type parameters
- `? extends` vs `? super`
- PECS
- Raw types
- Heap pollution
- Bridge methods
