# Portable C/C++ Source Code Libraries

A collection of C/C++ source code libraries written by David Lafreniere for cross-platform embedded and PC-based software development.

# GitHub Repositories

GitHub source code repositories categorized by library type.

## State Machines

| Repository | Language | Description |
|------------|----------|-------------|
| [C_StateMachine](https://github.com/endurodave/C_StateMachine) | C | C-language state machine. |
| [StateMachine](https://github.com/endurodave/StateMachine) | C++ | Object-oriented state machine. 

## State Machines with Threads

| Repository | Language | Description |
| :--- | :--- | :--- |
| [C_StateMachineWithThreads](https://github.com/endurodave/C_StateMachineWithThreads) | C | A C-language implementation of the Active Object pattern, featuring a thread-safe state machine with an integrated message queue. |
| [StateMachineWithThreads](https://github.com/endurodave/StateMachineWithThreads) | C++ | A thread-safe C++ state machine utilizing `std::thread` to execute state transitions on a dedicated worker thread. |
| [cpp-signal-slot-fsm](https://github.com/endurodave/cpp-signal-slot-fsm) | C++ | A thread-safe C++ state machine demonstrating **Signal-Slot communication** and RAII-managed asynchronous event marshaling via DelegateMQ. |
| [AsyncStateMachine](https://github.com/endurodave/AsyncStateMachine) | C++ | A **native asynchronous state machine** implemented as an active object, where every transition is dispatched and executed within its own thread of control. |

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
| [IntegrationTestFramework](https://github.com/endurodave/IntegrationTestFramework) | C++ | Integration test framework using Google Test and C++ delegates. |
| [IntegrationTestFrameworkCppUTest](https://github.com/endurodave/IntegrationTestFrameworkCppUTest) | C++ | Integration test framework using CppUTest and C++ delegates. |
| [IntegrationTestFrameworkDoctest](https://github.com/endurodave/IntegrationTestFrameworkDoctest) | C++ | Integration test framework using doctest and C++ delegates. |

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
