# Interview Prep Topic Map

This catalog supplies the course roadmap and individual assessment targets. The order below is a suggested learning route, adjustable to the learner. Current colors and review dates live only in progress.md. Expand grouped entries into individual subtopics as they are assessed; do not assign one status to a whole group.

## Recommended course route

| Module | What the learner will learn |
| --- | --- |
| 1. Baseline and foundations | Explain brute force, reason about correctness, analyze complexity, and test edge cases |
| 2. Arrays, strings, and hashing | Traverse and transform sequences; choose useful lookup/state representations |
| 3. Sequence techniques and searching | Reason about prefix sums, pointers, windows, sorting, and binary-search boundaries |
| 4. Linked lists, stacks, and queues | Manage links and ordered state; reason about pointer safety and invariants |
| 5. Recursion, trees, and heaps | Model recursive work, traverse hierarchical data, and prioritize candidates |
| 6. Graphs | Model relationships, traverse components, handle dependencies, and find paths |
| 7. Backtracking and dynamic programming | Define choices and states, reuse subproblems, and justify transitions |
| 8. Greedy and advanced structures | Justify local choices; use tries and bit operations where appropriate |
| 9. Mixed interview practice | Transfer skills to unlabeled problems, communicate decisions, and adapt to follow-ups |

Language knowledge can run alongside DSA. Backend/databases, system design, and behavioral preparation are parallel tracks selected according to interview goals. Any programming language is welcome; C++ and Java below are starter catalogs. Teach only selected language/role tracks, extending the catalog when needed. Subtopic coverage below defines what each track can teach. Initial coverage is ⚪ until assessed.

## Data structures and algorithms

- Arrays/strings: traversal, hashing, prefix sums, two pointers, sliding windows
- Linked lists: reversal, fast/slow pointers, merging, cycle detection
- Stacks/queues: stack simulation, monotonic stacks, queue/deque operations
- Binary search: basic search, boundaries, search on answer, rotated arrays
- Trees/BSTs: traversal, recursion, construction, validation, lowest common ancestor
- Heaps: priority queues, top-k, merging sorted inputs
- Graphs: BFS, DFS, connected components, topological sort, union-find, shortest paths
- Recursion/backtracking: state, choices, pruning, subsets/permutations, search
- Dynamic programming: state definition, transitions, base cases, memoization, bottom-up, space optimization, 1D DP, 2D DP
- Greedy: choice justification, intervals, counterexamples
- Other: tries, bit manipulation, sorting, selection
- Cross-cutting: invariants, reconstruction from brute force, correctness arguments, edge cases, overflow, time/space analysis, testing and communication

## Selected-language fundamentals

- Core semantics and types; numeric behavior; mutability and object/value semantics
- Collections and standard-library operations, including their time/space costs
- Functions, recursion, scope, errors, and common implementation pitfalls
- Idiomatic testing and debugging; runtime/compiler behavior when relevant
- Role-specific concurrency or frameworks only when needed

Record assessed language subtopics with a language prefix. Keep algorithm concepts shared across languages and implementation evidence scoped to the language used.

## Java (optional starter track)

- Core Java and OOP; equals/hashCode; collections; HashMap internals
- Streams; exceptions; generics
- Concurrency; synchronization; executor framework; CompletableFuture

## C++ (optional starter track)

- References/pointers; stack/heap; object lifetime; RAII
- Smart pointers; STL containers; iterators; const correctness
- Copy/move semantics; templates; concurrency

## Backend and databases (select role-relevant frameworks)

- HTTP/API semantics; validation; error handling; idempotency
- Spring: dependency injection, bean lifecycle, configuration, transactions
- JPA/Hibernate: mappings, fetching, N+1 queries, persistence context
- SQL: joins, grouping, subqueries, window functions
- Indexes, query plans, transactions, isolation, locking, schema design

## System design

- Requirements, scale estimates, read/write patterns
- API design, data models, high-level architecture, database choice
- Caching, scaling, availability, consistency, failure modes, observability
- Queues, replication, partitioning, rate limiting and tradeoffs as relevant

## Behavioral

- Ownership and impact; collaboration; conflict; ambiguity
- Failure and learning; prioritization; leadership
- Situation clarity, personal contribution, reasoning, results, reflection
