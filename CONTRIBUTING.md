# 🤝 Contributing to Sha's Council Framework

## 🎯 What You Can Contribute
- New Council roles (e.g., THE ETHICIST, THE EXECUTOR)
- Debate protocol improvements
- Synthesis algorithm tweaks
- Platform adapters (Claude, Manus, local LLMs)
- Documentation, examples, tutorials

## 📝 How to Propose a New Role
1. Create a YAML file in `roles/proposed/` using this template:


```yaml
# roles/proposed/THE-ETHICIST.yaml
role:
  name: "THE ETHICIST"
  mandate: "Evaluate decisions through moral frameworks, justice, and long-term human impact"
  triggers: ["ethics", "moral", "justice", "long-term impact", "/ethics"]
  skills:
    - @veil-ignorance
    - @existential-risk
    - @values-elicit
    - @meaning-craft
    - @bias-audit
  interaction_rules:
    - "Always ask: 'Who benefits? Who bears cost?'"
    - "Flag utilitarian traps that ignore minority harm"
    - "Suggest stakeholder inclusion for marginalized voices"
  contribution_guidelines:
    - "Cite ethical frameworks (e.g., Rawls, Nussbaum) when making claims"
    - "Acknowledge cultural variability in moral reasoning"
    - "Avoid prescriptive judgments; frame as considerations"

