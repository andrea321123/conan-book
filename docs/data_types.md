## Data types

All variables in Conan are either objects or primitive data types. There are 11 primitive data types in Conan:

| Primitive type | Example | Description |
| --- | --- | --- |
| u8 | 23 | Unsigned 8-bit integer |
| i8 | -23 | Signed 8-bit integer |
| u16 | 2365 | Unsigned 16-bit integer |
| i16 | -147 | Signed 16-bit integer |
| u32 | 62658 | Unsigned 32-bit integer |
| i32 | -149 | Signed 32-bit integer |
| u64 | 1254365 | Unsigned 64-bit integer |
| i64 | -1578 | Signed 64-bit integer |
| f32 | 23 | 32-bit decimal number |
| f64 | -23 | 64-bit decimale number |
| char| a | Character |

### Integer types
Each integer type has its own range.
Unsigned numbers can store values from 0 to 2^n -1, where n is the number of bits used to store the value.
On the other hand, signed numbers can store values from -2^(n -1) to 2^(n -1) -1. Signed types use two's complement representation. Here is a table with ranges for all integer types

| Type | From | To (inclusive) |
| --- | --- | --- |
| u8 | 0 | 255 |
| i8 | -128 | 127
| u16 | 0 | 65,535 |
| i16 | -32,768 | 32,767
| u32 | 0 | 4,294,967,295
| i32 | -2,147,483,648 | 2,147,483,647
| u64 | 0 | 18,446,744,073,709,551,615
| i64 | -9,223,372,036,854,775,808 | 9,223,372,036,854,775,807