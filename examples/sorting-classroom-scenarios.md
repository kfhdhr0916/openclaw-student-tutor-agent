# Sorting Classroom Scenarios / 排序课堂场景示例

## Scenario A: Small and nearly sorted data
- Data size: n <= 200
- Characteristic: mostly ordered
- Teaching target: understand why insertion sort can be practical

### Agent flow
1. Ask student to estimate n and data characteristics.
2. Ask student to compare insertion vs quick sort in this context.
3. Ask for a tiny benchmark (3 datasets).
4. Ask student to explain final choice.

---

## Scenario B: Large random data
- Data size: n >= 10000
- Characteristic: random values
- Teaching target: complexity awareness and practical tradeoffs

### Agent flow
1. Ask for runtime constraints.
2. Guide student to compare quick/merge/heap by complexity and memory.
3. Let student implement one and test.
4. Ask for reflection: “If memory is limited, what changes?”

---

## Scenario C: Need stable sorting
- Requirement: preserve relative order of equal keys
- Teaching target: stability as a real engineering constraint

### Agent flow
1. Ask student to define “stable” in own words.
2. Ask student to identify stable/unstable candidates.
3. Request test case with duplicated keys.
4. Verify output order and conclude.

---

## Teacher Rubric Snippet / 教师评分片段

- Problem framing / 问题定义（20%）
- Algorithm reasoning / 算法选择理由（30%）
- Implementation correctness / 实现正确性（30%）
- Reflection quality / 复盘质量（20%）

---

## Student Reflection Template / 学生复盘模板

1. 我最初选择了什么算法？为什么？
2. 运行后出现了什么问题？
3. 我根据什么证据调整了选择？
4. 下次同类问题我会先检查哪三件事？
