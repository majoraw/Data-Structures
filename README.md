# Interfaces

        Iterable<?> iterable;
        Collection<?> collection; // extends Iterable

        List<?> list; // extends Collection

        Set<?> set; // extends Collection
        SortedSet<?> sortedSet; // extends Set
        NavigableSet<?> navigableSet; // extends SortedSet

        Queue<?> queue; // extends Collection
        BlockingQueue<?> blockingQueue; // extends Queue
        TransferQueue<?> transferQueue; // extends BlockingQueue
        Deque<?> deque; // extends Queue
        BlockingDeque<?> blockingDeque; // extends BlockingQueue and Deque


        Map<?, ?> map;

        SortedMap<?, ?> sortedMap; // extends Map
        NavigableMap<?, ?> navigableMap; // extends SortedMap

        ConcurrentMap<?, ?> concurrentMap; // extends Map
        ConcurrentNavigableMap<?, ?> concurrentNavigableMap; // extends ConcurrentMap and NavigableMap
