## 🎯 Основной принцип

* Senior Data Engineer ≠ "алгоритмист уровня ICPC", от тебя ждут **хорошей базовой алгоритмической подготовки** + умения рассуждать, писать чистый код, использовать структуры данных правильно.
* Не обязательно решать все 2000 задач Leetcode. Нужно **покрыть типовые паттерны**, которые встречаются чаще всего.

---

## 🔑 Что нужно знать (20% → 80%)

### 1. Базовые структуры данных

* **Массивы, строки** → слайдинг-виндоу, два указателя, prefix sum.
* **Хэш-таблицы (dict, set)** → поиск дубликатов, подсчет частот, grouping.
* **Стек / очередь / deque** → монотонный стек/очередь, задачи на "next greater element", sliding window maximum.
* **Heap (приоритетная очередь)** → top-k, merge k-lists, median in stream.
* **Деревья** → обходы (DFS/BFS), работа с бинарным деревом, BST.
* **Графы** → BFS/DFS для поиска путей, топологическая сортировка.

### 2. Ключевые алгоритмы

* **Поиск и сортировка** (binary search, quick/merge sort базово).
* **Два указателя + sliding window** (subarray problems).
* **Dynamic Programming (DP)** — только базовые паттерны:

  * Fibonacci / climbing stairs.
  * 0/1 knapsack / subset sum.
  * Longest increasing subsequence.
  * DP по строкам: LCS, edit distance.
* **Графы**:

  * BFS/DFS.
  * Dijkstra (shortest path).
  * Union-Find (connected components, cycle detection).

### 3. Must-know задачи (Leetcode patterns)

* Two Sum / Subarray Sum = K.
* Longest Substring Without Repeating Characters.
* Merge Intervals.
* Valid Parentheses.
* Min Stack.
* Sliding Window Maximum.
* Binary Search on sorted array / rotated sorted array.
* Lowest Common Ancestor in BST/Binary Tree.
* Number of Islands (BFS/DFS).
* Top K Frequent Elements (heap + hash map).

---

## 📅 План подготовки (2–4 недели при ограниченном времени)

### Неделя 1: Базовые структуры

* Повторить Python-структуры (`list`, `dict`, `set`, `heapq`, `collections.deque`).
* Решить 20 задач на **массивы, строки, хэши**.
* Освоить **sliding window** + **двух указателей** (очень часто спрашивают!).

### Неделя 2: Стек, очередь, heap

* Задачи на **стек** (valid parentheses, min stack, monotonic stack).
* **Heap/priority queue**: top-k, merge k sorted lists.
* Несколько задач на **BFS/DFS** (islands, graph traversal).

### Неделя 3: Деревья + DP

* Обходы дерева (DFS, BFS).
* 5 задач на **BST** (поиск, LCA, insert, validate BST).
* DP-паттерны: stairs, LIS, edit distance.

### Неделя 4: Систематизация

* Повторить **binary search** задачи (rotated array, first/last occurrence).
* Повторить **топ-40 задач Leetcode (must-do list)**.
* Потренироваться **писать код без ошибок за 10–15 минут**.

---

## ⚡ Фокус (что реально даёт 80% результата)

1. **Скользящее окно + два указателя**
2. **Хэш-таблицы для подсчётов**
3. **DFS/BFS на графах и деревьях**
4. **Бинарный поиск**
5. **Heap (top-k, median, merge)**
6. **Базовый DP (stairs, knapsack, LIS, LCS)**
