# Roadmap / 路线图

This roadmap focuses on building a classroom-ready coach-style AI tutor.
本路线图聚焦“可落地课堂”的教练型 AI 学习助手。

---

## Phase 0 (Now): Project Foundation / 项目基础

- [x] Public repository initialized
- [x] Bilingual README
- [x] MIT license
- [x] Contribution guide

- [x] 创建公开仓库
- [x] 完成中英双语 README
- [x] 增加 MIT 许可证
- [x] 完成贡献指南

---

## Phase 1 (Weeks 1-2): Tutor Policy MVP / 教学策略 MVP

- [ ] Define strict "no direct full answer" policy
- [ ] Design 4-level hint system
- [ ] Add "student must try first" rule
- [ ] Add reflection questions template

- [ ] 定义“默认不直接给全解”规则
- [ ] 设计四级提示机制
- [ ] 增加“学生先尝试再提问”机制
- [ ] 增加标准复盘问题模板

Deliverable / 交付物:
- `AGENT_POLICY.md` v0.1
- Prompt templates / 提示词模板

---

## Phase 2 (Weeks 3-4): Classroom Pilot / 课堂试点

- [ ] Pilot in 1-2 classes
- [ ] Collect interaction logs (no private data)
- [ ] Track confusion hotspots
- [ ] Measure completion rate and debugging rounds

- [ ] 在1-2个班级试点
- [ ] 采集课堂交互日志（不含隐私）
- [ ] 统计高频卡点
- [ ] 追踪完成率与调试轮次

Deliverable / 交付物:
- Pilot report v0.1 / 试点报告
- First evaluation rubric / 首版评价量表

---

## Phase 3 (Month 2): Teacher Console / 教师看板

- [ ] Student progress overview
- [ ] Error type distribution
- [ ] Alert students who are stuck
- [ ] Export class summary

- [ ] 学生进度总览
- [ ] 错误类型分布
- [ ] 卡点学生提醒
- [ ] 班级总结导出

Deliverable / 交付物:
- Teacher dashboard prototype / 教师看板原型

---

## Phase 4 (Month 3): Productization / 产品化

- [ ] Multi-class support
- [ ] Role-based permissions (admin/teacher/student)
- [ ] Model switching and cost control
- [ ] Basic safety + moderation layer

- [ ] 多班级支持
- [ ] 角色权限体系（管理员/老师/学生）
- [ ] 模型切换与成本控制
- [ ] 基础内容安全层

Deliverable / 交付物:
- v1.0 beta release / v1.0 测试版

---

## Success Metrics / 成功指标

- Student completion rate ↑
- Independent debugging attempts ↑
- Teacher intervention load ↓
- Parent satisfaction ↑

- 学生任务完成率提升
- 学生独立调试次数提升
- 老师救火成本下降
- 家长满意度提升

---

## Open Questions / 待探索问题

- When should the agent unlock full solution mode?
- How to score "thinking quality" fairly?
- How to adapt strategy by age/level?

- 在什么条件下允许完整解答？
- 如何客观评估“思考质量”？
- 如何按年龄段做策略分层？
