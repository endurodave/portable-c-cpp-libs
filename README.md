# Portable C/C++ Source Code Libraries

A collection of C/C++ source code libraries for cross-platform embedded and PC-based software development.

# GitHub Repositories

GitHub source code repositories categorized by library type.

## State Machines

| Repository | Language | Description |
|------------|----------|-------------|
| [C_StateMachine](https://github.com/endurodave/C_StateMachine) | C | C-language state machine. |
| [StateMachine](https://github.com/endurodave/StateMachine) | C++ | Object-oriented state machine. 

## State Machines with Threads

| Repository | Language | Description |
|------------|----------|-------------|
| [C_StateMachineWithThreads](https://github.com/endurodave/C_StateMachineWithThreads) | C | C-language state machine with threads. |
| [StateMachineWithThreads](https://github.com/endurodave/StateMachineWithThreads) | C++ | C++ state machine with `std::thread`. |
| [StateMachineWithModernDelegates](https://github.com/endurodave/StateMachineWithModernDelegates) | C++ | C++ state machine with C++ delegates. |
| [AsyncStateMachine](https://github.com/endurodave/AsyncStateMachine) | C++ | Asynchronous C++ state machine implemented using C++ delegates. |

## Threads

| Repository | Language | Description |
|------------|----------|-------------|
| [StdWorkerThread](https://github.com/endurodave/StdWorkerThread) | C++ | C++ `std::thread` event loop with message queue and timer. |
| [ThreadWin](https://github.com/endurodave/ThreadWin) | C++ | Win32 `CreateThread()` C++ wrapper with synchronized thread startup. |

## Fixed-Block Memory Allocators

| Repository | Language | Description |
|------------|----------|-------------|
| [C_Allocator](https://github.com/endurodave/C_Allocator) | C |  C-language fixed-block memory allocator. |
| [Allocator](https://github.com/endurodave/Allocator) | C++| C++ fixed-block memory allocator. |
| [xallocator](https://github.com/endurodave/xallocator) | C++ | A fixed-block allocator `malloc`/`free` replacement. |
| [stl_allocator](https://github.com/endurodave/stl_allocator) | C++ | A `std::allocator` compatible fixed-block memory allocator for the C++ Standard Library. |
| [pmr_allocator](https://github.com/endurodave/pmr_allocator) | C++ | A C++ Polymorphic Memory Resource (PMR) fixed-block memory allocator. |
  
## Callbacks

| Repository | Language | Description |
|------------|----------|-------------|
| [MulticastCallback](https://github.com/endurodave/MulticastCallback) | C |Type-safe multicast callbacks in C. |
| [C_AsyncCallback](https://github.com/endurodave/C_AsyncCallback) | C | Asynchronous callbacks in C. |
| [AsyncCallback](https://github.com/endurodave/AsyncCallback) | C++ | Asynchronous callbacks in C++. |
| [DelegateMQ](https://github.com/endurodave/DelegateMQ) | C++ | Invoke any callable synchronously or asynchronously using C++ delegates. |

## Communications

| Repository | Language | Description |
|------------|----------|-------------|
| [SimpleSocketProtocol](https://github.com/endurodave/SimpleSocketProtocol) | C | A C-language socket-based communication transport protocol for Windows, Linux, Arduino and embedded systems. |
| [DelegateMQ](https://github.com/endurodave/DelegateMQ) | C++ | Invoke any remote function located in a separate process or processor using C++ delegates. |

## Serialization

| Repository | Language | Description |
|------------|----------|-------------|
| [MessageSerialize](https://github.com/endurodave/MessageSerialize) | C++ | C++ object binary serialize and deserialize. |

## Fault Handling

| Repository | Language | Description |
|------------|----------|-------------|
| [CoreDump](https://github.com/endurodave/CoreDump) | C | Universal embedded systems core dump framework. |

## Testing

| Repository | Language | Description |
|------------|----------|-------------|
| [IntegrationTestFramework](https://github.com/endurodave/IntegrationTestFramework ) | C++ | Integration test framework using Google Test and C++ delegates. |

## Miscellaneous

| Repository | Language | Description |
|------------|----------|-------------|
| [OBDII-Adapter-Software](https://github.com/endurodave/OBDII-Adapter-Software) | C | OBDII adapter source code and schematic for automotive diagnostic vehicle communication. |
| [Async-SQLite](https://github.com/endurodave/Async-SQLite) | C++ | Asynchronous SQLite API using C++ delegates. |

## Deprecated

The current C++ delegate implementation is [DelegateMQ](https://github.com/endurodave/DelegateMQ). The following delegate-related repositories offer prior implementations.

| Repository | Language | Description |
|------------|----------|-------------|
| [AsyncMulticastDelegateCpp17](https://github.com/endurodave/AsyncMulticastDelegateCpp17) | C++ | C++ delegates using C++17. |
| [AsyncMulticastDelegateCpp11](https://github.com/endurodave/AsyncMulticastDelegateCpp11) | C++ | C++ delegates using C++11. |
| [AsyncMulticastDelegate](https://github.com/endurodave/AsyncMulticastDelegate) | C++ | C++ delegates using C++03. |

# License

All libraries are licensed under the MIT License.
