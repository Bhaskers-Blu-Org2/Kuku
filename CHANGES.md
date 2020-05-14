# List of Changes

## Version 2.1

### 2.1.0
- Changed name `KukuDotNet` to `KukuNet`.
- Improved `README.md`.
- Added NuGet package.

## Version 2.0

### 2.0.0
- Switched to using faster non-cryptographic hash functions and a faster insertion method.
- Created .NET Standard wrappers for the public API.
- Kuku is not a CMake project (with a top-level CMake file)

## Version 1.1

### 1.1.1
- Added `table_size_type` to use instead of `std::size_t` to be compatible with `location_type`.

### 1.1.0
- Enabled interoperability between 32-bit and 64-bit versions by limiting location size to 32 bits.