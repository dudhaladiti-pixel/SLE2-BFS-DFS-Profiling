# SLE-2: BFS vs DFS Profiling

## Objective

To compare the performance of **Breadth-First Search (BFS)** and **Depth-First Search (DFS)** using Python and **py-spy**.

## Algorithms

* Breadth-First Search (BFS)
* Depth-First Search (DFS)

Both algorithms are tested on the same graph.

## Tools Used

* Python
* py-spy
* GitHub

## Files

* `bfs.py` – BFS implementation
* `dfs.py` – DFS implementation
* `bfs_for_pyspy.py` – BFS profiling code
* `dfs_for_pyspy.py` – DFS profiling code
* `bfs_profile.svg` – BFS profiling result
* `dfs_profile.svg` – DFS profiling result
* `AI_Contribution_Log.md` – AI usage record

## How to Run

```bash
python bfs.py
python dfs.py
```

Install py-spy:

```bash
pip install py-spy
```

Run profiling:

```bash
py-spy record -o bfs_profile.svg -- python bfs_for_pyspy.py
py-spy record -o dfs_profile.svg -- python dfs_for_pyspy.py
```

## Conclusion

BFS and DFS were implemented and profiled on the same graph. The py-spy results are used to observe and compare their execution behaviour and performance.
