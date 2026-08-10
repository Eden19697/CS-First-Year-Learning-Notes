# CS First Year Learning Notes

This repository is for PDF notes and written summaries from my first-year CS self-study.

## Notes

| Chapter | Notes | Topics |
| --- | --- | --- |
| 01-04 | [Python DSA Fundamentals](notes/01-04-python-dsa-fundamentals.pdf) | `dict` / `list` / `set` patterns, stack, queue, linked list, recursion, binary search, sorting, and a beginner bug quick-reference table |
| 05 | [Tree / Binary Tree / BST](notes/05-tree-bst.pdf) | TreeNode structure, recursive traversals, BFS, node count, height, balance, BST operations, lower/upper validation, deletion, diagrams, and FAQ |
| 06 | [Hash Table / dict / set](notes/06-hash-tables.pdf) | dict-vs-set decision rule, five core hash-table templates (counting, dedup, index, grouping, intersection), two sum, contains duplicate, first unique character, is-anagram, group anagrams, intersection, Java-to-Python mindset conversion, and a bug comparison table |
| 07-08 | [CSV / JSON / OOP Project](notes/07-08-csv-json-oop.pdf) | reading/writing CSV with `csv.DictReader` and `csv.writer`, type conversion for CSV's all-string values, reading/writing nested JSON with `json.load`/`json.dump`, CSV-vs-JSON decision rule, a TodoManager mini-project combining a class with list-of-dict state and JSON persistence, and a bug comparison table |
| 09 | [Graphs](notes/09-graphs.pdf) | adjacency lists, DFS/BFS with a visited set, has-path, connected components, shortest path (BFS + distance), building a graph from edges, largest component, grid graphs (island counting), directed graphs, topological sort (Kahn's algorithm), and a bug comparison table |
| 10 | [Heap / Priority Queue](notes/10-heap-priority-queue.pdf) | min-heap basics via `heapq`, the "three universal questions" for heap problems, k-largest/kth-largest with a size-k heap, simulating a max heap with negation, priority queues with `(priority, data)` tuples, top-k-frequent, `heapify`, merging k sorted arrays, k-closest-points, Dijkstra's shortest path, and a bug/FAQ table |

The notes are written as compact review sheets that connect concepts, Python templates, common mistakes, and visual examples.

## Related Code Repository

The coding exercises are organized separately in:

- [CS First Year Learning](https://github.com/Eden19697/CS-First-Year-Learning)

The Python DSA Fundamentals notes correspond to chapters `01_data_structures_basics` through `04_recursion_search_sort`, the Tree / BST notes correspond to the `05_trees` chapter, the Hash Table notes correspond to the `06_hash_table` chapter, the CSV / JSON / OOP notes correspond to the `07_files_csv_json` and `08_oop_projects` chapters, the Graphs notes correspond to the `09_graphs` chapter, and the Heap / Priority Queue notes correspond to the `10_heap_priority_queue` chapter, in the code repository.
