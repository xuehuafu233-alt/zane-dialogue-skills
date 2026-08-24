# Zane Dialogue Skills

面向 AI 时代问题定义、长期协作和主体性判断的可复用 Skills。它们不要求用户拥有专家 Skill，也不依赖 Zane 的个人资料。

## 当前包含

- `zane-question-intent-translator`：把自然语言问题转成真实意图、当前决定和可复制提示词；专家或其他 Skill 只是可选下游。
- `zane-agent-identity-card-builder`：为一次性或长期协作 AI 定义身份、判断、记忆、纠错和关系安全边界。
- `zane-self-insight`：基于事实、体验、自我叙述、外部脚本和待验证模式进行自我认识，并回到现实行动。

## 安装

```bash
npx -y skills add xuehuafu233-alt/zane-dialogue-skills -g --all
```

## 方法边界

这里的“问题转译”不是把句子改成统一模板，而是识别用户真正想推进的进展，明确这轮要促成的决定，再生成普通 AI 也能执行的输入。这里的“身份卡”也不是角色扮演，而是可纠正、有限权力、有记忆边界的协作协议。

作者：Zane
