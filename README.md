# DataAgent

**Agent-as-a-Service for data analysis.**

DataAgent converts business questions into governed queries, executable analysis, and explainable findings.

面向数据分析的 Agent：把业务问题转化为受治理的查询、可执行分析与可解释结论。

## Agent loop

| Stage | Responsibility |
|---|---|
| Data | Tables, metrics, metadata, lineage, permissions |
| Models | Text-to-SQL, analysis planner, insight reasoner |
| Training | Query SFT, execution-based preference optimization |
| Inference | Query planning, code execution, result synthesis |
| Harness | Warehouse, BI, notebook, permission tools |
| Eval | Execution accuracy, insight validity, safety |

## Initial scope

- Ground every query in catalog and lineage metadata.
- Separate exploratory analysis from governed reporting.
- Return the query, result, and assumptions together.

## Roadmap

- [ ] Semantic layer and permission contract
- [ ] Text-to-SQL evaluation set
- [ ] Executable analysis loop
- [ ] Insight validation
- [ ] BI integration

## Engineering principles

- Never fabricate data or metric definitions.
- Make calculations reproducible.
- Treat permission boundaries as hard constraints.

