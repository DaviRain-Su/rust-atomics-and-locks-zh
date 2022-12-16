# index

A
AArch64 (see ARM64)
ABA problem, Compare-and-Exchange Operations
aborting the process, Example: ID Allocation
AcqRel, Release and Acquire Ordering
(see also release and acquire memory ordering)
acquire memory ordering (see release and acquire memory ordering)
add instruction (ARM), Processor Instructions
add instruction (x86), Processor Instructions
address-based waiting (Windows), Address-Based Waiting
(see also futex)
air, out of thin, Relaxed Ordering
alignment, Impact on Performance
allocating IDs (see ID allocation)
AMD processors, Understanding the Processor
and instruction (x86), x86 lock prefix
Arc, Reference Counting
building our own, Building Our Own "Arc"-Summary
cyclic structures, Weak Pointers
get_mut, Mutation
memory ordering, Basic Reference Counting, Mutation, Optimizing, Optimizing
naming clones, Reference Counting
using for channel state, Safety Through Types
weak pointers, Weak Pointers
performance cost, Optimizing
arguments, consuming, Safety Through Types
ARM64 (processor architecture), Understanding the Processor
aarch64-unknown-linux-musl target, Processor Instructions
other-multi-copy atomic, Memory Ordering
weakly ordered, ARM64: Weakly Ordered-ARM64: Weakly Ordered
ARM64 instructions
add, Processor Instructions
ARMv8.1 atomic instructions, ARM load-exclusive and store-exclusive, ARM64: Weakly Ordered
b.ne (branch if not equal), Compare-and-exchange on ARM
cbnz (compare and branch on nonzero), ARM load-exclusive and store-exclusive
clrex (clear exclusive), ARM load-exclusive and store-exclusive
cmp (compare), Compare-and-exchange on ARM
dmb (data memory barrier), Memory Fences
ldar (load-acquire register), ARM64: Weakly Ordered
ldaxr (load-acquire exclusive register), ARM64: Weakly Ordered
ldr (load register), Processor Instructions
ldxr (load exclusive register), ARM load-exclusive and store-exclusive
load-linked and store-conditional instructions, ARM load-exclusive and store-exclusive
mov (move), Compare-and-exchange on ARM
overview, Summary
ret (return), Processor Instructions
stlr (store-release register), ARM64: Weakly Ordered
stlxr (store-release exclusive register), ARM64: Weakly Ordered
str (store register), Processor Instructions
stxr (store exclusive register), ARM load-exclusive and store-exclusive
ARMv8 (see ARM64)
ARMv8.1 atomic instructions, ARM load-exclusive and store-exclusive, ARM64: Weakly Ordered
overview, Summary
array::from_fn, Fences
assembler, Processor Instructions
assembly, Processor Instructions
inspecting compiler output, Processor Instructions
atomic, Atomics-Summary
compare-and-exchange operations, Compare-and-Exchange Operations-Example: Lazy One-Time Initialization
caching, effect on, Impact on Performance
compiler optimization, Compare-and-exchange on ARM
example, ID allocation, Example: ID Allocation Without Overflow
example, lazy initialization, Example: Lazy One-Time Initialization, Example: Lazy Initialization with Indirection-Example: Lazy Initialization with Indirection
memory ordering, Example: Locking
using for channel state, Safety Through Runtime Checks
using for mutex state, Avoiding Syscalls
using for reader-writer lock state, Reader-Writer Lock
using on AtomicPtr, Example: Lazy Initialization with Indirection
using to lock reference counter, Optimizing
weak, Compare-and-Exchange Operations
fetch-and-modify operations, Fetch-and-Modify Operations-Example: ID Allocation
example, ID allocation, Example: ID Allocation-Example: ID Allocation
example, progress reporting, Example: Progress Reporting from Multiple Threads-Example: Progress Reporting from Multiple Threads
example, statistics, Example: Statistics-Example: Statistics
wrapping behavior (add and sub), Fetch-and-Modify Operations
(see also overflows)
load and store operations, Atomic Load and Store Operations-Example: Lazy Initialization
compared to non-atomic operations, The Memory Model, Load and Store
example, lazy initialization, Example: Lazy Initialization
example, progress reporting, Example: Progress Reporting-Synchronization
example, stop flag, Example: Stop Flag-Example: Stop Flag
memory ordering (see memory ordering)
reference counting (see Arc)
atomic barriers (see fences)
atomic fences (see fences)
atomic types, Atomics, Atomics
compare_exchange, Compare-and-Exchange Operations
compare_exchange_weak, Compare-and-Exchange Operations
fetch_add, Fetch-and-Modify Operations
wrapping behavior, Fetch-and-Modify Operations
(see also overflows)
fetch_and, Fetch-and-Modify Operations
fetch_max, Fetch-and-Modify Operations
fetch_min, Fetch-and-Modify Operations
fetch_nand, Fetch-and-Modify Operations
fetch_or, Fetch-and-Modify Operations
fetch_store (see swap)
fetch_sub, Fetch-and-Modify Operations
wrapping behavior, Fetch-and-Modify Operations
(see also overflows)
fetch_update, Example: ID Allocation Without Overflow
fetch_xor, Fetch-and-Modify Operations
get_mut, Safety Through Runtime Checks
load, Atomic Load and Store Operations
store, Atomic Load and Store Operations
swap, Fetch-and-Modify Operations
ἄτομος, Atomics
atomic-wait crate, Building Our Own Locks
AtomicBool, Atomics
(see also atomic types)
locking using, Example: Locking, A Minimal Implementation
AtomicI8 (see atomic types)
AtomicI16 (see atomic types)
AtomicI32 (see atomic types)
AtomicI64 (see atomic types)
AtomicIsize (see atomic types)
AtomicPtr, Atomics
(see also atomic types)
compare-and-exchange, Example: Lazy Initialization with Indirection
lazy initialization, Example: Lazy Initialization with Indirection
AtomicU8 (see atomic types)
AtomicU16 (see atomic types)
AtomicU32 (see atomic types)
AtomicU64 (see atomic types)
AtomicUsize (see atomic types)
auto traits, Thread Safety: Send and Sync
B
b.ne (branch if not equal) instruction (ARM), Compare-and-exchange on ARM
barriers (see fences)
basics, Basics of Rust Concurrency-Summary
benchmarking, Impact on Performance, Benchmarking-Benchmarking
black_box, avoiding optimizations with, Impact on Performance, Benchmarking
binary semaphore, Semaphore
black_box, Impact on Performance, Benchmarking
blocking, Operating System Primitives
channel, Blocking-Blocking
condition variables, Condition Variables
futex wait operation, Futex
(see also futex)
mutexes, Locking: Mutexes and RwLocks
Once and OnceLock, Example: Lazy Initialization, Example: Lazy One-Time Initialization
semaphores, Semaphore
spin loop, A Minimal Implementation
thread parking (see thread parking)
boolean (atomic) (see AtomicBool)
borrowing, Borrowing and Data Races
bending the rules, Interior Mutability
error, Scoped Threads
exclusive, Interior Mutability
from multiple threads (Sync), Thread Safety: Send and Sync
immutable, Borrowing and Data Races
(see also shared)
local variables in a thread, Scoped Threads
mutable, Borrowing and Data Races
(see also exclusive)
shared, Interior Mutability
splitting, Borrowing to Avoid Allocation
undefined behavior, Interior Mutability
Box
from_raw, Example: Lazy Initialization with Indirection, Basic Reference Counting
into_raw, Example: Lazy Initialization with Indirection
leak, Leaking, Basic Reference Counting
unmovable type, wrapping in, Wrapping in Rust
btc (bit test and complement) instruction (x86), x86 lock prefix
btr (bit test and reset) instruction (x86), x86 lock prefix
bts (bit test and set) instruction (x86), x86 lock prefix
building our own
Arc, Building Our Own "Arc"-Summary
channels, Building Our Own Channels-Summary
condition variables, Condition Variable-Avoiding Spurious Wake-ups
mutexes, Mutex-Benchmarking
reader-writer locks, Reader-Writer Lock-Avoiding Writer Starvation
spin locks, Building Our Own Spin Lock-Summary
busy-looping, Building Our Own Spin Lock
(see also spinning)
C
C standard library, Interfacing with the Kernel
(see also libc)
cache coherence, Cache Coherence-The MESI protocol
protocol, Cache Coherence
MESI, The MESI protocol
MESIF, The MESI protocol
MOESI, The MESI protocol
write-through, The write-through protocol
cache lines, Caching
performance experiment, Impact on Performance-Impact on Performance
cache miss, The MESI protocol
caching (processors), Caching-Impact on Performance
(see also cache coherence)
compare-and-exchange operations, effect of, Impact on Performance
per core, Cache Coherence
performance experiment, Impact on Performance-Impact on Performance
cargo-show-asm, Processor Instructions
cas (compare and swap) instruction (ARM), ARM load-exclusive and store-exclusive
casa (compare and swap, acquire) instruction (ARM), ARM64: Weakly Ordered
casal (compare and swap, acquire and release) instruction (ARM), ARM64: Weakly Ordered
casl (compare and swap, release) instruction (ARM), ARM64: Weakly Ordered
cbnz (compare and branch on nonzero) instruction (ARM), ARM load-exclusive and store-exclusive
Cell, Cell
unsafe (see UnsafeCell)
channels
blocking, Blocking-Blocking
borrowing, Borrowing to Avoid Allocation
building our own, Building Our Own Channels-Summary
dropping, An Unsafe One-Shot Channel
one-shot, An Unsafe One-Shot Channel
safe interface, Safety Through Runtime Checks
Sender and Receiver types, Safety Through Types, Borrowing to Avoid Allocation
storing in Arc, Safety Through Types
avoiding, Borrowing to Avoid Allocation
unsafe interface, An Unsafe One-Shot Channel
Clone trait, Reference Counting, Reference Counting, Safety Through Types, Basic Reference Counting, Weak Pointers
closures
captured values
moving, Threads in Rust
naming, Reference Counting
spawning scoped threads using, Scoped Threads
spawning threads using, Threads in Rust
clrex (clear exclusive) instruction (ARM), ARM load-exclusive and store-exclusive
cmp (compare) instruction (ARM), Compare-and-exchange on ARM
cmpxchg (compare and exchange) instruction (x86), x86 compare-and-exchange instruction-x86 compare-and-exchange instruction
cmpxchg (compare-and-exchange) instruction (x86)
#[cold], Optimizing Further
compare-and-exchange operations (atomic), Compare-and-Exchange Operations-Example: Lazy One-Time Initialization
on ARM64, Compare-and-exchange on ARM-Compare-and-exchange on ARM
caching, effect on, Impact on Performance
compiler optimization, Compare-and-exchange on ARM
example, ID allocation, Example: ID Allocation Without Overflow
example, lazy initialization, Example: Lazy One-Time Initialization, Example: Lazy Initialization with Indirection-Example: Lazy Initialization with Indirection
memory ordering, Example: Locking
using for channel state, Safety Through Runtime Checks
using for mutex state, Avoiding Syscalls
using for reader-writer lock state, Reader-Writer Lock
using on AtomicPtr, Example: Lazy Initialization with Indirection
using to lock reference counter, Optimizing
weak, Compare-and-Exchange Operations
on ARM64, Compare-and-exchange on ARM
on x86-64, x86 compare-and-exchange instruction-x86 compare-and-exchange instruction
Compiler Explorer, Processor Instructions
compiler fence, Fences, An Experiment
compiler optimization
black_box, avoiding with, Impact on Performance, Benchmarking
#[cold], Optimizing Further
of compare-and-exchange loops, Compare-and-exchange on ARM
enabling, Processor Instructions, Impact on Performance
#[inline], Optimizing Further
reordering, Reordering and Optimizations
complex instruction set computer (CISC), Processor Instructions
concurrency, basics, Basics of Rust Concurrency-Summary
condition variables, Condition Variables-Condition Variables
building our own, Condition Variable-Avoiding Spurious Wake-ups
example, Condition Variables
memory ordering, Condition Variable
pthread_cond_t, POSIX
thundering herd problem, Avoiding Spurious Wake-ups
timeout, Condition Variables
using to build a channel, A Simple Mutex-Based Channel-A Simple Mutex-Based Channel
Windows, Slim reader-writer locks
Condvar, Condition Variables
(see also condition variables)
consume memory ordering, Consume Ordering
consuming arguments by value, Safety Through Types
contention (mutexes), Avoiding Syscalls, Optimizing Further
benchmarking, Benchmarking
Copy trait, An Unsafe One-Shot Channel, An Unsafe One-Shot Channel
atomic types, not implementing, Example: Progress Reporting from Multiple Threads
moving, Leaking
critical section (Windows), Lighter-Weight Objects
current thread, Threads in Rust, Threads in Rust, Thread Parking
cyclic structures (Arc), Weak Pointers
D
data races, Borrowing and Data Races
avoiding using atomics, Atomics, The Memory Model
Deref trait, Reader-Writer Lock, A Safe Interface Using a Lock Guard, Basic Reference Counting
DerefMut trait, Rust’s Mutex, Reader-Writer Lock, A Safe Interface Using a Lock Guard, Mutation
disassembler, Processor Instructions, Processor Instructions
dmb (data memory barrier) instruction (ARM), Memory Fences
drop function, Rust’s Mutex, A Safe Interface Using a Lock Guard, Weak Pointers
Drop trait, Rust’s Mutex, A Safe Interface Using a Lock Guard, A Safe Interface Using a Lock Guard, An Unsafe One-Shot Channel, Safety Through Runtime Checks, Safety Through Types, Basic Reference Counting, Testing It, Weak Pointers, Weak Pointers, Optimizing, Mutex
dword, Processor Instructions
E
--emit=asm (rustc), Processor Instructions
exclusive references, Interior Mutability
F
fair locks, macOS
false sharing, Impact on Performance
fences, Fences-Fences, Basic Reference Counting, Optimizing
on ARM64, Memory Fences
compiler fence, Fences, An Experiment
instructions, Memory Fences-Memory Fences
process-wide memory barriers, Fences
on x86-64, Memory Fences
fetch-and-modify operations (atomic), Fetch-and-Modify Operations-Example: ID Allocation
on ARM64, ARM load-exclusive and store-exclusive-ARM load-exclusive and store-exclusive
example, ID allocation, Example: ID Allocation-Example: ID Allocation
example, progress reporting, Example: Progress Reporting from Multiple Threads-Example: Progress Reporting from Multiple Threads
example, statistics, Example: Statistics-Example: Statistics
wrapping behavior (add and sub), Fetch-and-Modify Operations
(see also overflows)
on x86-64, x86 lock prefix-x86 lock prefix
fetch_store operation (atomic) (see swap operation)
fetch_update (atomic), Example: ID Allocation Without Overflow
FlushProcessWriteBuffers (Windows), Fences
forgetting (see leaking)
FreeBSD, umtx_op syscall, Futex Operations
(see also futex)
from_fn (array), Fences
futex, Linux-Priority Inheritance Futex Operations
cross-platform futex-like functionality, Building Our Own Locks
example, Futex
memory safety, Mutex
on other platforms, Futex Operations
operations (Linux), Futex Operations-Priority Inheritance Futex Operations
FUTEX_CLOCK_REALTIME, Futex Operations
FUTEX_CMP_REQUEUE, Futex Operations
FUTEX_PRIVATE_FLAG, Futex Operations
FUTEX_REQUEUE, Futex Operations
FUTEX_WAIT, Futex Operations
futex_waitv syscall, Futex Operations
FUTEX_WAIT_BITSET, Futex Operations
FUTEX_WAKE, Futex Operations
FUTEX_WAKE_BITSET, Futex Operations
FUTEX_WAKE_OP, Futex Operations
priority inheritance, Priority Inheritance Futex Operations
requeueing, Futex Operations, Avoiding Spurious Wake-ups
spurious wake-ups, Futex
timeout, Futex Operations, Condition Variable
wait operation, Futex
wake operation, Futex
G
globally consistent order, Sequentially Consistent Ordering
(see also sequentially consistent memory ordering)
Godbolt, Processor Instructions
good luck, Teaching Materials
guards
dropping, Rust’s Mutex
join guard, Scoped Threads
mutex guard, Rust’s Mutex, Mutex
read guard, Reader-Writer Lock, Reader-Writer Lock
spin lock guard, A Safe Interface Using a Lock Guard
write guard, Reader-Writer Lock, Reader-Writer Lock
H
hand, things getting out of, Blocking
happens-before relationships, Happens-Before Relationship-Relaxed Ordering
in Arc, Basic Reference Counting, Mutation
between threads, Happens-Before Relationship
locking and unlocking, Example: Locking, A Minimal Implementation
spawning and joining threads, Spawning and Joining
through a release-acquire pair, Release and Acquire Ordering, Release and Acquire Ordering
chaining, Release and Acquire Ordering
within the same thread, Happens-Before Relationship
hint::black_box, Impact on Performance, Benchmarking
hint::spin_loop, A Minimal Implementation
I
ID allocation
using compare_exchange_weak, Example: ID Allocation Without Overflow
using fetch_add, Example: ID Allocation-Example: ID Allocation
using fetch_update, Example: ID Allocation Without Overflow
ideas and inspiration, Ideas and Inspiration-Teaching Materials
if let statement
lifetime of temporaries, Lock Poisoning
ignorance, blissful, Relaxed Ordering
immutable references, Borrowing and Data Races
(see also shared references)
indivisible, Atomics
#[inline], Optimizing Further
inspiration, Ideas and Inspiration-Teaching Materials
Instant, Example: Statistics
instruction reordering (see reordering)
instructions, Processor Instructions-Compare-and-exchange on ARM
(see also ARM64 instructions; x86-64 instructions)
compare-and-exchange operations, x86 compare-and-exchange instruction-x86 compare-and-exchange instruction, Compare-and-exchange on ARM-Compare-and-exchange on ARM
fences, Memory Fences-Memory Fences
load and store operations, Load and Store-Load and Store
load-linked/store-conditional (LL/SC) instructions, Load-Linked and Store-Conditional Instructions-Load-Linked and Store-Conditional Instructions
memory ordering, Memory Ordering-Memory Fences
overview, Summary
read-modify-write operations, Read-Modify-Write Operations-ARM load-exclusive and store-exclusive
Intel processors, Understanding the Processor
interior mutability, Interior Mutability-UnsafeCell, An Unsafe Spin Lock, Weak Pointers
invalidation queues, Reordering
J
jne (jump if not equal) instruction (x86), x86 compare-and-exchange instruction
join method, Threads in Rust
JoinGuard, Scoped Threads
JoinHandle, Threads in Rust
joining threads, Threads in Rust
happens-before relationship, Spawning and Joining
K
kernel, Basics of Rust Concurrency, Operating System Primitives
interfacing with, Interfacing with the Kernel-Interfacing with the Kernel
kernel-managed objects (Windows), Heavyweight Kernel Objects
L
L1/L2/L3/L4 cache, Cache Coherence
label (assembly), Processor Instructions
lazy initialization
using compare_exchange, Example: Lazy One-Time Initialization
using compare_exchange and allocation, Example: Lazy Initialization with Indirection-Example: Lazy Initialization with Indirection
using load and store, Example: Lazy Initialization
ldadd (load and add) instruction (ARM), ARM load-exclusive and store-exclusive
ldadda (load and add, acquire) instruction (ARM), ARM64: Weakly Ordered
ldaddal (load and add, acquire and release) instruction (ARM), ARM64: Weakly Ordered
ldaddl (load and add, release) instruction (ARM), ARM64: Weakly Ordered
ldar (load-acquire register) instruction (ARM), ARM64: Weakly Ordered
ldaxr (load-acquire exclusive register) instruction (ARM), ARM64: Weakly Ordered
ldr (load register) instruction (ARM), Processor Instructions
ldxr (load exclusive register) instruction (ARM), ARM load-exclusive and store-exclusive
leaking, Scoped Threads, Leaking
by mistake, An Unsafe One-Shot Channel
a MutexGuard, Wrapping in Rust
“Leakpocalypse”, Scoped Threads
libc, Interfacing with the Kernel
pthreads functionality in, POSIX
libpthread, POSIX
(see also pthreads)
lifetime
elision, An Unsafe Spin Lock, Borrowing to Avoid Allocation
in a struct, A Safe Interface Using a Lock Guard
of mutex guard, Lock Poisoning
specifying using plain English, An Unsafe Spin Lock
static, Threads in Rust
linked list, Lock-Free Linked List
Linux
futex syscall, Futex-Priority Inheritance Futex Operations
(see also futex)
arguments, Futex Operations
futex_waitv syscall, Futex Operations
interfacing with the kernel, Interfacing with the Kernel
libc, role of, Interfacing with the Kernel
membarrier syscall, Fences
process-wide memory barrier, Fences
RCU, RCU
load and store operations (atomic), Atomic Load and Store Operations-Example: Lazy Initialization
on ARM64 and x86-64, Load and Store-Load and Store
compared to non-atomic operations, The Memory Model, Load and Store
example, lazy initialization, Example: Lazy Initialization
example, progress reporting, Example: Progress Reporting-Synchronization
example, stop flag, Example: Stop Flag-Example: Stop Flag
load-linked/store-conditional (LL/SC) loop, Load-Linked and Store-Conditional Instructions-Load-Linked and Store-Conditional Instructions
on ARM64, ARM load-exclusive and store-exclusive-ARM load-exclusive and store-exclusive
compiler optimization, Compare-and-exchange on ARM
lock poisoning, Lock Poisoning
lock prefix (x86), x86 lock prefix-x86 lock prefix
lock_api crate, Mutex
luck, good, Teaching Materials
M
machine code, Processor Instructions
machine instructions (see instructions)
macOS
futex-like functionality on, Building Our Own Locks
interfacing with the kernel, Interfacing with the Kernel, macOS
os_unfair_lock, os_unfair_lock
main thread, Threads in Rust
ManuallyDrop, Optimizing
MaybeUninit, An Unsafe One-Shot Channel, An Unsafe One-Shot Channel, An Unsafe One-Shot Channel
mem::forget, Scoped Threads
membarrier syscall, Fences
memory barriers (see fences)
memory fences (see fences)
memory model, The Memory Model
memory ordering, Atomics, Memory Ordering-Summary
on ARM64, ARM64: Weakly Ordered-ARM64: Weakly Ordered
compiler fence, Fences, An Experiment
consume, Consume Ordering
experiment, using relaxed instead of release and acquire, An Experiment-An Experiment
fences, Fences-Fences, Basic Reference Counting, Optimizing
happens-before relationship, Happens-Before Relationship-Relaxed Ordering, Release and Acquire Ordering
Miri, detecting problems with, Testing It
misconceptons about, Common Misconceptions-Common Misconceptions
out-of-thin-air values, Relaxed Ordering
at processor level, Memory Ordering-Memory Fences
reference counting, Basic Reference Counting, Basic Reference Counting, Mutation, Optimizing, Optimizing
relaxed, Atomics, Relaxed Ordering-Relaxed Ordering
(see also relaxed memory ordering)
release and acquire, Release and Acquire Ordering-Example: Lazy Initialization with Indirection
(see also release and acquire memory ordering)
locking and unlocking, A Minimal Implementation
sequentially consistent, Sequentially Consistent Ordering
(see also sequentially consistent memory ordering)
specifying using plain English, Reordering and Optimizations
total modification order, Relaxed Ordering, Release and Acquire Ordering, Safety Through Runtime Checks, Safety Through Runtime Checks
on x86-64, x86-64: Strongly Ordered-x86-64: Strongly Ordered
MESI cache coherence protocol, The MESI protocol
MESIF cache coherence protocol, The MESI protocol
mfence (memory fence) instruction (x86), Memory Fences
microinstructions, Read-Modify-Write Operations
Miri, Testing It
MOESI cache coherence protocol, The MESI protocol
mov (move) instruction (ARM), Compare-and-exchange on ARM
mov (move) instruction (x86), Load and Store
movable, not
critical section (Windows), Lighter-Weight Objects
Pin, Wrapping in Rust
pthread types, Wrapping in Rust
wrapping in Box, Wrapping in Rust
move closure, Threads in Rust
multi-copy atomicity, Memory Ordering
mutability, interior (see interior mutability)
mutable references, Borrowing and Data Races
(see also exclusive references)
Mutex, Mutex and RwLock, Rust’s Mutex
(see also mutexes)
mutexes, Locking: Mutexes and RwLocks-Reader-Writer Lock
building our own, Mutex-Benchmarking
as container, Reader-Writer Lock
contention, Avoiding Syscalls, Optimizing Further
example, Rust’s Mutex
fair, macOS
happens-before relationship, Example: Locking
into_inner, Rust’s Mutex
lifetime of mutex guard, Lock Poisoning
memory ordering, Example: Locking
Mutex type in Rust, Rust’s Mutex
os_unfair_lock (macOS), os_unfair_lock
in other languages, Reader-Writer Lock
poisoning, Lock Poisoning
pthread
wrapping in Rust, Wrapping in Rust
pthread_mutex_t, POSIX
recursive, Lighter-Weight Objects
robust, Priority Inheritance Futex Operations
Send requirement, Reader-Writer Lock
spin locks, Building Our Own Spin Lock
(see also spin locks)
spinning, Building Our Own Spin Lock, Optimizing Further
using to build a channel, A Simple Mutex-Based Channel-A Simple Mutex-Based Channel
MutexGuard, Rust’s Mutex
dropping, Rust’s Mutex
lifetime of, Lock Poisoning
mutual exclusion (see mutexes)
N
name of a thread, Threads in Rust
NetBSD, futex support, Futex Operations
(see also futex)
NonNull, Basic Reference Counting
O
-O flag (rustc), Processor Instructions, Impact on Performance
Once and OnceLock, Example: Lazy Initialization, Example: Lazy One-Time Initialization
one-shot channels, An Unsafe One-Shot Channel
OpenBSD, limited futex support, Futex Operations
(see also futex)
operating systems, Operating System Primitives
(see also Linux; macOS; Windows)
libraries shipped with, Interfacing with the Kernel
synchronization primitives, Interfacing with the Kernel
optimization (see compiler optimization)
or instruction (x86), x86 lock prefix, x86 compare-and-exchange instruction
Ordering, Atomics, Reordering and Optimizations
(see also memory ordering)
AcqRel, Release and Acquire Ordering
(see also release and acquire memory ordering)
Acquire, Release and Acquire Ordering
(see also release and acquire memory ordering)
Consume, Consume Ordering
Relaxed, Atomics, Relaxed Ordering
(see also relaxed memory ordering)
Release, Release and Acquire Ordering
(see also release and acquire memory ordering)
SeqCst, Sequentially Consistent Ordering
(see also sequentially consistent memory ordering)
os_unfair_lock (macOS), os_unfair_lock
other-multi-copy atomicity, Memory Ordering
out of order execution (see reordering)
out-of-thin-air values, Relaxed Ordering
output locking, Threads in Rust
overflows (atomic), Example: ID Allocation
(see also wrapping behavior)
aborting on, Example: ID Allocation
notification counter, Condition Variable
panicking on, Example: ID Allocation
preventing (compare-and-exchange), Example: ID Allocation Without Overflow
reference counter, Basic Reference Counting
usize, big enough, Avoiding Syscalls
overview of atomic instructions, Summary
ownership
moving, Threads in Rust, Safety Through Types
sharing, Shared Ownership and Reference Counting
transferring to another thread (Send), Thread Safety: Send and Sync
P
panicking
poisoned mutexes, Lock Poisoning
RefCell, borrowing, RefCell
thread name in panic messages, Threads in Rust
using a Condvar with multiple mutexes, Condition Variables
when joining a thread, Threads in Rust, Threads in Rust
when spawning a thread, Threads in Rust
parking (see thread parking)
parking lot-based locks, Parking Lot–Based Locks
parking_lot crate, Parking Lot–Based Locks
PhantomData, Thread Safety: Send and Sync, Blocking
Pin, Wrapping in Rust
pipelining, Reordering
pointers
atomic (see AtomicPtr)
neither Send nor Sync, Thread Safety: Send and Sync
NonNull, Basic Reference Counting
poisoning, lock, Lock Poisoning
POSIX, Interfacing with the Kernel
pthreads, POSIX-Wrapping in Rust
println, use of output locking, Threads in Rust
priority inheritance, Priority Inheritance Futex Operations
priority inversion, Priority Inheritance Futex Operations
privacy (modules), Condition Variable
process-wide memory barriers, Fences
processes, Basics of Rust Concurrency
processor architecture, Understanding the Processor
(see also ARM64; x86-64)
strongly ordered, x86-64: Strongly Ordered
weakly ordered, ARM64: Weakly Ordered
processor caching (see caching)
processor instructions (see instructions)
processor registers, Processor Instructions
return value, Load and Store
pthreads, POSIX-Wrapping in Rust
pthread_cond_t, POSIX, Avoiding Spurious Wake-ups
pthread_mutex_t, POSIX
dropping while locked, Wrapping in Rust
pthread_rwlock_t, POSIX
wrapping in Rust, Wrapping in Rust
Q
queue-based locks, Queue-Based Locks
R
racing, Example: Lazy Initialization
Rc, Reference Counting
RCU (read, copy, update), RCU, Lock-Free Linked List
reader-writer locks, Reader-Writer Lock-Reader-Writer Lock
avoiding accidental spinning, Avoiding Busy-Looping Writers
building our own, Reader-Writer Lock-Avoiding Writer Starvation
pthread_rwlock_t, POSIX
Send requirement, Reader-Writer Lock
SRW locks (Windows), Slim reader-writer locks
Sync requirement, Reader-Writer Lock
writer starvation, Reader-Writer Lock, Avoiding Writer Starvation
recursive locking, POSIX, Lighter-Weight Objects
reduced instruction set computer (RISC), Processor Instructions
RefCell, RefCell
RwLock compared to, Reader-Writer Lock
reference counting, Reference Counting-Reference Counting
(see also Arc)
references
exclusive, Interior Mutability
immutable, Borrowing and Data Races
(see also shared)
mutable, Borrowing and Data Races
(see also exclusive)
shared, Interior Mutability
registers, Processor Instructions
return value, Load and Store
relaxed memory ordering, Atomics, Happens-Before Relationship, Relaxed Ordering-Relaxed Ordering
counter-intuitive results, Happens-Before Relationship
misconceptions about, Common Misconceptions, Common Misconceptions
out-of-thin-air values, Relaxed Ordering
reference counting, Basic Reference Counting
total modification order, Relaxed Ordering, Release and Acquire Ordering, Safety Through Runtime Checks, Safety Through Runtime Checks
release and acquire memory ordering, Release and Acquire Ordering-Example: Lazy Initialization with Indirection
acquire fence, Fences, Fences, Basic Reference Counting, Mutation, Optimizing
on ARM64, ARM64: Weakly Ordered-ARM64: Weakly Ordered
example, lazy initialization, Example: Lazy Initialization with Indirection-Example: Lazy Initialization with Indirection
experiment, using relaxed instead, An Experiment-An Experiment
happens-before relationship, Release and Acquire Ordering, Release and Acquire Ordering
chaining, Release and Acquire Ordering
locking and unlocking, Example: Locking, A Minimal Implementation
reference counting, Basic Reference Counting, Mutation, Optimizing, Optimizing
release fence, Fences
on x86-64, x86-64: Strongly Ordered
--release flag (cargo), Processor Instructions, Impact on Performance
reordering (instructions), Reordering and Optimizations-Reordering and Optimizations, Reordering-Reordering
memory ordering, Memory Ordering
#[repr(align)], Impact on Performance
requeuing waiting threads, Futex Operations, Avoiding Spurious Wake-ups
ret (return) instruction (ARM), Processor Instructions
ret (return) instruction (x86), Processor Instructions
robust mutexes, Priority Inheritance Futex Operations
rustup, Processor Instructions
RwLock, Mutex and RwLock, Reader-Writer Lock
(see also reader-writer locks)
RwLockReadGuard, Reader-Writer Lock
RwLockWriteGuard, Reader-Writer Lock
S
safe interface, A Safe Interface Using a Lock Guard, Safety Through Runtime Checks, Safety Through Runtime Checks
safety requirements of unsafe functions, Borrowing and Data Races
scheduler, Operating System Primitives
scoped threads, Scoped Threads-Scoped Threads
semaphores, Semaphore
Send trait, Thread Safety: Send and Sync, A Simple Mutex-Based Channel, Blocking
error, Thread Safety: Send and Sync
implementing for Arc, Basic Reference Counting
requirement by Mutex and RwLock, Reader-Writer Lock
SeqCst (see sequentially consistent memory ordering)
sequence locks, Sequence Lock
sequentially consistent memory ordering, Sequentially Consistent Ordering
on ARM64, ARM64: Weakly Ordered
fence, Fences
misconceptions about, Common Misconceptions, Common Misconceptions
on x86-64, x86-64: Strongly Ordered
shadowing, Reference Counting
shared ownership, Shared Ownership and Reference Counting-Reference Counting
leaking, Leaking
reference counting, Reference Counting
statics, Statics
shared references, Interior Mutability
mutating atomics through, Atomics
slim reader-writer locks (Windows), Slim reader-writer locks, Queue-Based Locks
spawning threads, Threads in Rust
failing to, Threads in Rust
happens-before relationship, Spawning and Joining
scoped, Scoped Threads
spin locks
building our own, Building Our Own Spin Lock-Summary
cache lines, effect of, Impact on Performance
compare-and-exchange, (not) using, Impact on Performance
experiment, using wrong memory ordering, An Experiment-An Experiment
guard, A Safe Interface Using a Lock Guard
memory ordering, A Minimal Implementation
spin loop hint, A Minimal Implementation, Optimizing Further
spinning, Building Our Own Spin Lock, Optimizing, Operating System Primitives
avoiding accidental (reader-writer lock), Avoiding Busy-Looping Writers
splitting (borrowing), Borrowing to Avoid Allocation
spurious wake-ups, Thread Parking, Futex, Avoiding Spurious Wake-ups
SRW locks (Windows), Slim reader-writer locks, Queue-Based Locks
stack size, Threads in Rust
starvation, Reader-Writer Lock, Avoiding Writer Starvation
static lifetime, Threads in Rust
statics, Statics
stlr (store-release register) instruction (ARM), ARM64: Weakly Ordered
stlxr (store-release exclusive register) instruction (ARM), ARM64: Weakly Ordered
stop flag, Example: Stop Flag
store buffers, Reordering
store operations (atomic) (see load and store operations)
store-conditional (see load-linked/store-conditional)
str (store register) instruction (ARM), Processor Instructions
stress, reducing, Safety Through Runtime Checks
strongly ordered architecture, x86-64: Strongly Ordered
stxr (store exclusive register) instruction (ARM), ARM load-exclusive and store-exclusive
sub (subtract) instruction (x86), x86 lock prefix
swap operation (atomic), Fetch-and-Modify Operations
locking using, A Minimal Implementation
Sync trait, Thread Safety: Send and Sync, A Simple Mutex-Based Channel
implementing for Arc, Basic Reference Counting
implementing for channel, An Unsafe One-Shot Channel
implementing for mutex, Mutex
implementing for reader-writer lock, Reader-Writer Lock
implementing for spin lock, An Unsafe Spin Lock
requirement by RwLock, Reader-Writer Lock
syscalls, Interfacing with the Kernel
avoiding, Avoiding Syscalls, Avoiding Syscalls
SYS_futex (Linux), Futex
(see also futex)
arguments, Futex Operations
T
--target (rustc), Processor Instructions
teaching, Teaching Materials
thin air, out of, Relaxed Ordering
thread builder, Threads in Rust
thread name, Threads in Rust
Thread object, Blocking
id, Threads in Rust
unpark, Thread Parking, Blocking
thread parking, Thread Parking-Thread Parking, Safety Through Runtime Checks, Blocking, Futex
spurious wake-ups, Thread Parking
timeout, Condition Variables
example, Synchronization
thread safety, Reference Counting, Thread Safety: Send and Sync-Thread Safety: Send and Sync
(see also Send and Sync traits)
keeping objects on one thread, Blocking
ThreadId, Threads in Rust
threads, Basics of Rust Concurrency
joining, Threads in Rust
panicking, Threads in Rust, Threads in Rust
returning a value, Threads in Rust
scoped, Scoped Threads-Scoped Threads
spawning, Threads in Rust
thundering herd problem, Avoiding Spurious Wake-ups
time travel, Borrowing and Data Races
timeout
condition variables, Condition Variables
futex, Futex Operations, Condition Variable
thread parking, Condition Variables
example, Synchronization
total modification order, Relaxed Ordering, Release and Acquire Ordering, Safety Through Runtime Checks, Safety Through Runtime Checks
U
uncontended (mutexes), Avoiding Syscalls, Optimizing Further
benchmarking, Benchmarking
undefined behavior, Borrowing and Data Races
borrowing, Interior Mutability
data races, Borrowing and Data Races
Miri, detecting with, Testing It
time travel, Borrowing and Data Races
uninitialized memory, An Unsafe One-Shot Channel
Unix systems
interfacing with the kernel, Interfacing with the Kernel
libc, role of, Interfacing with the Kernel
unmovable
critical section (Windows), Lighter-Weight Objects
Pin, Wrapping in Rust
pthread types, Wrapping in Rust
wrapping in Box, Wrapping in Rust
unpark (Thread), Blocking
unparking (see thread parking)
unsafe code, Borrowing and Data Races
unsafe functions, Borrowing and Data Races
unsafe trait implementation, Thread Safety: Send and Sync
UnsafeCell, UnsafeCell, An Unsafe Spin Lock, Weak Pointers
get_mut, Safety Through Runtime Checks
unsound, Borrowing and Data Races
V
VecDeque, A Simple Mutex-Based Channel
W
waiting (see blocking)
WaitOnAddress (Windows), Address-Based Waiting
WakeByAddressAll (Windows), Address-Based Waiting
WakeByAddressSingle (Windows), Address-Based Waiting
Weak (see Arc; weak pointers)
weakly ordered architecture, ARM64: Weakly Ordered
experiment, using relaxed instead of release and acquire, An Experiment-An Experiment
Windows, Windows-Address-Based Waiting
condition variables, Slim reader-writer locks
critical section, Lighter-Weight Objects
FlushProcessWriteBuffers, Fences
interfacing with the kernel, Interfacing with the Kernel
kernel-managed objects, Heavyweight Kernel Objects
Native API, Windows
process-wide memory barrier, Fences
SRW locks, Slim reader-writer locks, Queue-Based Locks
WaitOnAddress, Address-Based Waiting
WakeByAddressAll, Address-Based Waiting
WakeByAddressSingle, Address-Based Waiting
Win32 API, Windows
windows crate, Windows
windows-sys crate, Windows
wrapping behavior (fetch_add and fetch_sub), Fetch-and-Modify Operations
(see also overflows (atomic))
wrapping unmovable object in Box, Wrapping in Rust
write-through cache coherence protocol, The write-through protocol
writer starvation, Reader-Writer Lock, Avoiding Writer Starvation
X
x86-64 (processor architecture), Understanding the Processor
other-multi-copy atomic, Memory Ordering
strongly ordered, x86-64: Strongly Ordered-x86-64: Strongly Ordered
x86_64-unknown-linux-musl target, Processor Instructions
x86-64 instructions
add, Processor Instructions
and, x86 lock prefix
btc (bit test and complement), x86 lock prefix
btr (bit test and reset), x86 lock prefix
bts (bit test and set), x86 lock prefix
cmpxchg (compare and exchange), x86 compare-and-exchange instruction-x86 compare-and-exchange instruction
jne (jump if not equal), x86 compare-and-exchange instruction
lock prefix, x86 lock prefix-x86 lock prefix
mfence (memory fence), Memory Fences
mov (move), Load and Store
or, x86 lock prefix, x86 compare-and-exchange instruction
overview, Summary
ret (return), Processor Instructions
sub (subtract), x86 lock prefix
xadd (exchange and add), x86 lock prefix
xchg (exchange), x86 lock prefix, x86-64: Strongly Ordered
xor, x86 lock prefix
xadd (exchange and add) instruction (x86), x86 lock prefix
xchg (exchange) instruction (x86), x86 lock prefix, x86-64: Strongly Ordered
xor instruction (x86), x86 lock prefix