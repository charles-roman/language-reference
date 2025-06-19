# Language / Language Support

## Table of Contents

- [Directives](#directives)
- [Comments](https://cppreference.com/w/cpp/comments.html)
- [ASCII Chart](https://cppreference.com/w/cpp/language/ascii.html)
- [Basic Concepts](https://cppreference.com/w/cpp/language/basics.html)
    - [Keywords](https://cppreference.com/w/cpp/keywords.html)
    - [Identifiers](https://cppreference.com/w/cpp/language/name.html)
    - [Types](#types)
        - [Fundamental](https://cppreference.com/w/cpp/language/types.html)
            - [Modifiers](https://cppreference.com/w/cpp/language/types.html#Modifiers)
            - [Range](https://cppreference.com/w/cpp/language/types.html#Range_of_values)
        - Compound
            - [User-Defined](../../user-defined-types/README.md)
            - [Derived](#derived)
        - Type Support
            - [Numeric Limits](https://cppreference.com/w/cpp/types/numeric_limits.html)
            - [Additional Basic Types / RTTI](https://cppreference.com/w/cpp/utility/rtti.html)
                - size_t
                - ptrdiff_t
                - nullptr_t / NULL
                - fixed-width integers
    - [The main function](https://cppreference.com/w/cpp/language/main_function.html)

- [Expressions](https://cppreference.com/w/cpp/language/expressions.html)
    - [Value Categories](https://cppreference.com/w/cpp/language/value_category.html)
    - [Evaluation Order](https://cppreference.com/w/cpp/language/eval_order.html)
    - [Conversions](#conversions)
        - type safety
        - [Order of Conversions](https://cppreference.com/w/cpp/language/implicit_cast.html#Order_of_the_conversions)
        - [Contextual Conversions](https://cppreference.com/w/cpp/language/implicit_cast.html#Contextual_conversions)
        - [Value Transformations](https://cppreference.com/w/cpp/language/implicit_cast.html#Value_transformations)
        - [Array-to-pointer decay](../memory-management/README.md#arrays)
        - [Function-to-pointer](https://cppreference.com/w/cpp/language/implicit_cast.html#Function-to-pointer_conversion)
        - [Numeric Conversions](https://cppreference.com/w/cpp/language/implicit_cast.html#Numeric_conversions)
            - integral
            - floating point
            - pointer
            - boolean
        - Narrowing
        - [Qualification Conversions](https://cppreference.com/w/cpp/language/implicit_cast.html#Qualification_conversions)
            - [Ordering](https://cppreference.com/w/cpp/language/cv.html#Conversions)
        - [Promotions](#promotions)
            - integral
            - floating point
        - [Casting](#casting)
            - c-style cast
            - const_cast
            - static_cast
            - dynamic_cast
            - reinterpret_cast
            - user-defined
    - [Literals](https://cppreference.com/w/cpp/language/expressions.html#Literals)
        - integral
        - character
        - floating point
        - string
        - boolean
        - nullptr
        - user-defined
    - [Operators](https://cppreference.com/w/cpp/language/expressions.html#Operators)
        - [Precedence](https://cppreference.com/w/cpp/language/operator_precedence.html)
        - Special Operators
            - [sizeof](https://cppreference.com/w/cpp/language/sizeof.html)
            - [typeid](https://cppreference.com/w/cpp/language/typeid.html)
            - [noexcept](https://cppreference.com/w/cpp/language/noexcept.html)
            - [casting operators](#casting)
            - [new, delete](../memory-management/README.md#dynamic-memory-allocation)
        - [Overflow](https://cppreference.com/w/cpp/language/operator_arithmetic.html#Overflows)
        - [Overloading](../../classes/README.md#operator-overloading)

- [Statements](https://cppreference.com/w/cpp/language/statements.html)
    - Control Statements
        - [Conditionals](#conditionals)
        - [Loops](#loops)

- (Attribute) Declarations / Initialization
    - Declarations vs Definitions
    - Attribute Declaration and Initialization
    - [cv Type Qualifiers](#cv-type-qualifiers)
        - [mutable specifier](../../classes/README.md#attribute-specifiers)
    - [Specifiers](#specifiers)
        - typedef

        - constexpr

        - [Storage Class Specifiers](#storage-class-specifiers)
            - auto
            - register
            - static
            - thread_local
            - extern
            - mutable

        - decltype
        - auto
