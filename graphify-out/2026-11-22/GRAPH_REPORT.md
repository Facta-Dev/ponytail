# Graph Report - .  (2026-11-22)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 1255 nodes · 1703 edges · 116 communities (106 shown, 10 thin omitted)
- Extraction: 95% EXTRACTED · 5% INFERRED · 0% AMBIGUOUS · INFERRED: 79 edges (avg confidence: 0.54)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `3d771a9e`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- register.tsx
- hooks.test.js
- __init__.py
- answer.py
- run.py
- tasks.py
- ponytail-runtime.js
- cursor-hooks.js
- uninstall.test.js
- index.js
- package.json
- band-import.test.js
- What You Must Do When Invoked
- ponytail-band-import.js
- Install
- ponytail-config.js
- ponytail-map.js
- correctness.js
- ponytail.mjs
- INSTALL.md
- README.es.md
- README.ja.md
- README.ko.md
- README.zh-CN.md
- README.md
- openclaw-skills.test.js
- check-rule-copies.js
- gemini-extension.test.js
- 2026-10-07-agentic.md
- Agentic benchmark: does ponytail cut code without cutting safety?
- commands.test.js
- hooks-windows.test.js
- opencode-plugin.test.js
- Agentic benchmark
- Benchmark
- Ponytail v4 hardening — A–F benchmark vs Caveman (2026-06-12)
- Cost verification: reproducing the "47-77% cheaper" claim (2026-06-17)
- Cursor hooks
- Rate Limiting in FastAPI
- Robustness audit: does ponytail degrade weak models? (2026-06-16)
- Agentic safety benchmark (2026-06-17): SUPERSEDED
- Comprehension & reuse: fixing #245 and #217
- graphify reference: extra exports and benchmark
- React Countdown Timer Component
- Ponytail Help
- Ponytail Help
- behavior.test.js
- Agentic benchmark: Ponytail 5 vs Ponytail vs no skill
- marketplace.json
- README.md
- Email Validation Function
- sessionStats
- ponytail-subagent.js
- check-versions.js
- activation-map.test.js
- copilot-plugin.test.js
- qoder-plugin.test.js
- loc.test.js
- Caveman vs Ponytail — 2026-06-12
- Debounce Search Input
- main
- caveman-SKILL.md
- Local model benchmark: llama3.2 via Ollama — 2026-06-15
- 2026-06-16-correctness-gate-fix.md
- graphify reference: query, path, explain
- csv-sum.md
- types.d.ts
- package.json
- grok-plugin.test.js
- kimi-plugin.test.js
- package-scripts.test.js
- package.test.js
- SKILL.md
- Ponytail Gain
- SKILL.md
- Ponytail
- SKILL.md
- Ponytail Gain
- SKILL.md
- SKILL.md
- Ponytail, lazy senior dev mode
- caveman.js
- ponytail.js
- graphify reference: add a URL and watch a folder
- graphify reference: commit hook and native CLAUDE.md integration
- graphify reference: incremental update and cluster-only
- Ponytail, lazy senior dev mode
- Deep Clone
- Group By
- Infinite Scroll
- Modal Dialog
- Number Formatting
- URL Parameters
- Ponytail, lazy senior dev mode
- Ponytail, lazy senior dev mode
- SKILL.md
- SKILL.md
- Ponytail, lazy senior dev mode
- graphify reference: GitHub clone and cross-repo merge
- graphify reference: transcribe video and audio
- react-countdown.md
- after-install.md
- CLAUDE.md
- CLAUDE.md
- extraction-spec.md
- ponytail-statusline.sh script
- opencode.json
- band

## God Nodes (most connected - your core abstractions)
1. `register()` - 31 edges
2. `Install` - 22 edges
3. `getPonytailInstructions()` - 18 edges
4. `_fail()` - 14 edges
5. `_ok()` - 14 edges
6. `normalizeMode()` - 13 edges
7. `getDefaultMode()` - 13 edges
8. `ponytailExtension()` - 13 edges
9. `_import()` - 12 edges
10. `finish()` - 12 edges

## Surprising Connections (you probably didn't know these)
- `readMode()` --calls--> `normalizeMode()`  [EXTRACTED]
  .opencode/plugins/ponytail.mjs → hooks/ponytail-config.js
- `persistMode()` --calls--> `normalizeMode()`  [EXTRACTED]
  .opencode/plugins/ponytail.mjs → hooks/ponytail-config.js
- `persistMode()` --calls--> `writeDefaultMode()`  [EXTRACTED]
  .opencode/plugins/ponytail.mjs → hooks/ponytail-config.js
- `setup()` --calls--> `getPonytailInstructions()`  [EXTRACTED]
  .opencode/plugins/ponytail.mjs → hooks/ponytail-instructions.js
- `server()` --calls--> `getPonytailInstructions()`  [EXTRACTED]
  .opencode/plugins/ponytail.mjs → hooks/ponytail-instructions.js

## Import Cycles
- None detected.

## Communities (116 total, 10 thin omitted)

### Community 0 - "register.tsx"
Cohesion: 0.08
Nodes (71): RFC-4180, boardHtml(), day(), duration(), elapsed(), esc(), fmtTokens(), json() (+63 more)

### Community 1 - "hooks.test.js"
Cohesion: 0.03
Nodes (62): assert, bandFlag, claudeEnv, codebuddyConfigDir, codebuddyEnv, codebuddyHome, codebuddyState, codexData (+54 more)

### Community 2 - "__init__.py"
Cohesion: 0.07
Nodes (39): Any, build_injected_context(), _config_dir(), _default_mode(), _fallback_instructions(), _filter_skill_body_for_mode(), _handle_mode_command(), _make_skill_command_handler() (+31 more)

### Community 3 - "answer.py"
Cohesion: 0.10
Nodes (39): _cells(), _fixed_diff(), _gate_ok(), judge_reply(), main(), _pair_call(), pairwise(), Path (+31 more)

### Community 4 - "run.py"
Cohesion: 0.11
Nodes (37): aggregate(), _base_cmd(), chat_code_loc(), _claude_version(), code_stats(), _count(), _git(), git_diff_stats() (+29 more)

### Community 5 - "tasks.py"
Cohesion: 0.13
Nodes (30): _contained(), _fail(), _find(), _find_class(), _import(), _import_pkg(), _ok(), Path (+22 more)

### Community 6 - "ponytail-runtime.js"
Cohesion: 0.09
Nodes (32): activate(), claudeDir, {
  clearMode,
  cursorRuleNotice,
  cursorRulePath,
  isCodeBuddy,
  isCodex,
  isCopilot,
  isCursor,
  readMode,
  setMode,
  writeHookOutput,
}, { execFileSync }, finish(), fs, { getDefaultMode, getClaudeDir, isShellSafe }, { getPonytailInstructions } (+24 more)

### Community 7 - "cursor-hooks.js"
Cohesion: 0.09
Nodes (25): isShellSafe(), fs, hooksPath(), install(), isPonytailHook(), { isShellSafe }, os, path (+17 more)

### Community 8 - "uninstall.test.js"
Cohesion: 0.06
Nodes (29): assert, claudeDir, configDir, configPath, cursorDir, cursorFlagPath, cursorHooksPath, env (+21 more)

### Community 9 - "index.js"
Cohesion: 0.13
Nodes (22): normalizeMode(), normalizePersistedMode(), RUNTIME_MODES, { DEFAULT_MODE, normalizeMode, normalizePersistedMode }, filterSkillBodyForMode(), fs, getFallbackInstructions(), getPonytailInstructions() (+14 more)

### Community 10 - "package.json"
Cohesion: 0.08
Nodes (25): author, name, url, bugs, url, description, exports, ./plugin (+17 more)

### Community 11 - "band-import.test.js"
Cohesion: 0.09
Nodes (23): assert, at(), { CSV_HEADER, replyCost, sessionStats, csvRow, mergeRows, run }, early, env, fs, later, merged (+15 more)

### Community 12 - "What You Must Do When Invoked"
Cohesion: 0.08
Nodes (24): For /graphify add and --watch, For /graphify query, For the commit hook and native CLAUDE.md integration, For --update and --cluster-only, /graphify, Honesty Rules, Interpreter guard for subcommands, Part A - Structural extraction for code files (+16 more)

### Community 13 - "ponytail-band-import.js"
Cohesion: 0.14
Nodes (21): csvRow(), field(), fs, { getClaudeDir }, HAIKU_55_LONG, ledgerDir(), mergeRows(), OPUS (+13 more)

### Community 14 - "Install"
Cohesion: 0.09
Nodes (22): Antigravity CLI, Claude Code, CodeWhale, Codex, Cursor, Devin CLI, Gemini CLI, GitHub Copilot CLI (+14 more)

### Community 15 - "ponytail-config.js"
Cohesion: 0.14
Nodes (17): fs, getConfigDir(), getConfigPath(), getHideStatus(), getQoderDir(), getQuietStartup(), normalizeConfigMode(), os (+9 more)

### Community 16 - "ponytail-map.js"
Cohesion: 0.13
Nodes (16): BUDGET, buildMap(), { execFileSync }, fs, LANG, listFiles(), namesIn(), path (+8 more)

### Community 17 - "correctness.js"
Cohesion: 0.14
Nodes (12): CHECKS, correctnessTimeoutMs(), exec(), { execSync }, fs, os, path, python() (+4 more)

### Community 18 - "ponytail.mjs"
Cohesion: 0.21
Nodes (15): getDefaultMode(), __dirname, { getDefaultMode, normalizeMode, writeDefaultMode }, { getPonytailInstructions }, { parseCommandFile, parseSkillFile }, persistMode(), readCommands(), readMode() (+7 more)

### Community 19 - "INSTALL.md"
Cohesion: 0.14
Nodes (10): Before you write, Ponytail, lazy senior dev mode, The smallest complete change, Adapter Rule, Agent Portability, Portable Behavior, Supported Adapters, Before you write (+2 more)

### Community 20 - "README.es.md"
Cohesion: 0.13
Nodes (14): Antes / después, Comandos, Cómo funciona, El prompt, Historial de estrellas, Instalación, La auditoría, reconstruida, La revisión, reconstruida (+6 more)

### Community 21 - "README.ja.md"
Cohesion: 0.13
Nodes (14): 5.3 の新機能：バンド, Ponytail で作られたもの, よくある質問, インストール, コマンド, スター履歴, スポンサー, ビフォー / アフター (+6 more)

### Community 22 - "README.ko.md"
Cohesion: 0.13
Nodes (14): 5.3의 새 기능: 밴드, Ponytail로 이미 만든 것, 다시 만든 감사, 다시 만든 리뷰, 라이선스, 명령어, 설치, 수치 (+6 more)

### Community 23 - "README.zh-CN.md"
Cohesion: 0.13
Nodes (14): 5.3 新功能：信息栏, Star 历史, 之前 / 之后, 命令, 安装, 审查，从头重建, 审计，从头重建, 工作原理 (+6 more)

### Community 24 - "README.md"
Cohesion: 0.13
Nodes (14): Already built with Ponytail, Before / after, Commands, FAQ, How it works, Install, License, New in 5.3: the band (+6 more)

### Community 25 - "openclaw-skills.test.js"
Cohesion: 0.21
Nodes (12): DESCRIPTIONS, fs, NAMES, outPath(), path, render(), ROOT, sourceBody() (+4 more)

### Community 26 - "check-rule-copies.js"
Cohesion: 0.17
Nodes (9): agents, canonical, copies, fs, INVARIANTS, path, root, skill (+1 more)

### Community 27 - "gemini-extension.test.js"
Cohesion: 0.18
Nodes (11): assert, fs, loadManifest(), path, read(), REUSED_COMMANDS, REUSED_SKILLS, root (+3 more)

### Community 28 - "2026-10-07-agentic.md"
Cohesion: 0.22
Nodes (5): Changes to the ruleset need a benchmark, Contributing, Development, Everything else, New skills come from me

### Community 29 - "Agentic benchmark: does ponytail cut code without cutting safety?"
Cohesion: 0.18
Nodes (11): A contamination bug we found in our own numbers, Agentic benchmark: does ponytail cut code without cutting safety?, Axis 1: lines of code on real features (12 tasks), Axis 2: does minimizing drop a guard? (6 tasks), Conclusion, Limitations (so this can't be the next thing someone debunks), Reproduce, Setup (+3 more)

### Community 30 - "commands.test.js"
Cohesion: 0.18
Nodes (10): assert, commands, debtCopies, debtSamples, fs, path, piSource, root (+2 more)

### Community 31 - "hooks-windows.test.js"
Cohesion: 0.18
Nodes (8): assert, fs, HOST_PLUGIN_MANIFESTS, os, path, root, { spawn, execFileSync }, test

### Community 32 - "opencode-plugin.test.js"
Cohesion: 0.18
Nodes (8): assert, fs, os, path, { pathToFileURL }, statePath, test, tmp

### Community 33 - "Agentic benchmark"
Cohesion: 0.20
Nodes (10): Agentic benchmark, Arms, Completeness judge (`complete.py`), Metrics, Over-engineering judge (`judge.py`), Reproduce, Results, Tasks (+2 more)

### Community 34 - "Benchmark"
Cohesion: 0.20
Nodes (10): Benchmark, Claude (Haiku / Sonnet / Opus), Current numbers: Ponytail 5 (2026-10-07), Independent benchmarks, Median results (10 runs, 2026-06-13; cost re-verified at 30 runs, 2026-06-17), Metrics, Notes, Prerequisites (+2 more)

### Community 35 - "Ponytail v4 hardening — A–F benchmark vs Caveman (2026-06-12)"
Cohesion: 0.20
Nodes (9): Acceptance criteria (brief §5.6), Addendum: same-model control arm (control2, added same day), Build phase — non-blank LOC / .py files (scorer-verified), Correctness, Extension phase (tasks C, D — surprise requests, git-measured), Ponytail v4 hardening — A–F benchmark vs Caveman (2026-06-12), Residual (honest notes), Safety — adversarial probes (independently executed) (+1 more)

### Community 36 - "Cost verification: reproducing the "47-77% cheaper" claim (2026-06-17)"
Cohesion: 0.20
Nodes (9): Claude (pooled, 30 reps, USD for 5 tasks), Cost verification: reproducing the "47-77% cheaper" claim (2026-06-17), Gemini, Method, Notes, OpenAI (10 reps, USD for 5 tasks), Results, Takeaway (+1 more)

### Community 37 - "Cursor hooks"
Cohesion: 0.20
Nodes (10): Automated compatibility check, Behavior, Client source check, Cursor 3.20.17 on Windows, 2026-09-14, Coexistence with `.cursor/rules/ponytail.mdc`, Contract, Cursor hooks, Install and uninstall, Limitations (+2 more)

### Community 38 - "Rate Limiting in FastAPI"
Cohesion: 0.20
Nodes (10): 1. **Using `slowapi` (Recommended - Easiest)**, 2. **Using `limits` Library (More Control)**, 3. **Custom Middleware (Full Control)**, 4. **Per-User Rate Limiting (With Authentication)**, 5. **Redis-Based Rate Limiting (Production)**, 6. **Complete Example with Multiple Endpoints**, Comparison Table, Rate Limiting in FastAPI (+2 more)

### Community 39 - "Robustness audit: does ponytail degrade weak models? (2026-06-16)"
Cohesion: 0.22
Nodes (8): Conclusion, Edge-case traps (n=20/cell), Method, Reproduce, Robustness audit: does ponytail degrade weak models? (2026-06-16), The fix that wasn't, TL;DR, Validators: the email slip is provider-specific

### Community 40 - "Agentic safety benchmark (2026-06-17): SUPERSEDED"
Cohesion: 0.22
Nodes (9): Agentic safety benchmark (2026-06-17): SUPERSEDED, Finding 1: the code-size gap collapses with a fair baseline, Finding 2: minimizing lines without a floor drops safety, Finding 3: over-engineering did not appear (null result, two ways), Reproduce, Results, TL;DR, What this does and does not show (+1 more)

### Community 41 - "Comprehension & reuse: fixing #245 and #217"
Cohesion: 0.22
Nodes (8): #217: rung shipped, failure did not reproduce, Comprehension & reuse: fixing #245 and #217, Haiku: a model ceiling, not a regression, Regression check: did the rule edits break anything?, Results — `trace-transfer`, n=6, root-cause-fix rate, The #245 reproducer, The fix, Verdict

### Community 42 - "graphify reference: extra exports and benchmark"
Cohesion: 0.22
Nodes (8): graphify reference: extra exports and benchmark, Step 6b - Wiki (only if --wiki flag), Step 7 - Neo4j export (only if --neo4j or --neo4j-push flag), Step 7a - FalkorDB export (only if --falkordb or --falkordb-push flag), Step 7b - SVG export (only if --svg flag), Step 7c - GraphML export (only if --graphml flag), Step 7d - MCP server (only if --mcp flag), Step 8 - Token reduction benchmark (only if total_words > 5000)

### Community 43 - "React Countdown Timer Component"
Cohesion: 0.22
Nodes (9): Advanced Timer with Formatted Display, Basic Countdown Timer, CSS Styling, Custom Hook Version, Features, React Countdown Timer Component, Styled Component with Animations, Usage Examples (+1 more)

### Community 44 - "Ponytail Help"
Cohesion: 0.22
Nodes (8): Band (Claude Code), Configure Default Mode, Deactivate, Levels, More, Ponytail Help, Skills, Update

### Community 45 - "Ponytail Help"
Cohesion: 0.22
Nodes (8): Band (Claude Code), Configure Default Mode, Deactivate, Levels, More, Ponytail Help, Skills, Update

### Community 46 - "behavior.test.js"
Cohesion: 0.29
Nodes (5): CHECKS, assert, behavior, check(), test

### Community 47 - "Agentic benchmark: Ponytail 5 vs Ponytail vs no skill"
Cohesion: 0.25
Nodes (8): Agentic benchmark: Ponytail 5 vs Ponytail vs no skill, Correctness and safety, Per task, Replies, Reproduce, Results, Setup, Tests

### Community 48 - "marketplace.json"
Cohesion: 0.25
Nodes (7): description, name, owner, name, url, plugins, $schema

### Community 49 - "README.md"
Cohesion: 0.25
Nodes (5): Debounce, Without Ponytail, 116 lines of code, Rate Limiting, Without Ponytail, 128 lines of code, Examples

### Community 50 - "Email Validation Function"
Cohesion: 0.25
Nodes (7): Comparison, Email Validation, Email Validation Function, More Robust Version (with additional checks), Using a Third-Party Library (Recommended for Production), With Ponytail, 3 lines of code, Without Ponytail, 75 lines of code

### Community 51 - "sessionStats"
Cohesion: 0.29
Nodes (8): human(), modelId(), ms(), promptText(), replyCost(), sessionStats(), slim(), toolResult()

### Community 52 - "ponytail-subagent.js"
Cohesion: 0.29
Nodes (7): readMode(), finish(), { getPonytailInstructions }, inject(), mode, { readMode, writeHookOutput }, vm

### Community 53 - "check-versions.js"
Cohesion: 0.25
Nodes (6): distinct, fs, path, root, VERSION_FILES, versions

### Community 54 - "activation-map.test.js"
Cohesion: 0.25
Nodes (7): assert, fs, os, path, root, { spawnSync }, test

### Community 55 - "copilot-plugin.test.js"
Cohesion: 0.25
Nodes (6): assert, fs, path, REQUIRED_COMMAND_FILES, root, test

### Community 56 - "qoder-plugin.test.js"
Cohesion: 0.25
Nodes (6): assert, fs, path, root, SKILL_DIRS, test

### Community 57 - "loc.test.js"
Cohesion: 0.33
Nodes (5): assert, cases, loc, score(), test

### Community 58 - "Caveman vs Ponytail — 2026-06-12"
Cohesion: 0.29
Nodes (6): Caveman vs Ponytail — 2026-06-12, Ponytail v1 (before this benchmark), Ponytail v2 (after fixes), Ponytail v3 (skill file compressed), v1 findings, Verdict (v3)

### Community 59 - "Debounce Search Input"
Cohesion: 0.29
Nodes (7): Advanced: Debounce with Cancel & Immediate Options, Basic Debounce Function, Debounce Search Input, Enhanced Version with Loading State, HTML Example, Key Benefits, With Ponytail, 10 lines of code

### Community 60 - "main"
Cohesion: 0.47
Nodes (5): load(), main(), Cells from results.json plus answer-judge rows from answer.json, as one list of, sign_p(), metrics

### Community 61 - "caveman-SKILL.md"
Cohesion: 0.33
Nodes (5): Auto-Clarity, Boundaries, Intensity, Persistence, Rules

### Community 62 - "Local model benchmark: llama3.2 via Ollama — 2026-06-15"
Cohesion: 0.33
Nodes (5): Key findings, Local model benchmark: llama3.2 via Ollama — 2026-06-15, Reproduce, Results (n=5, median), Takeaway

### Community 63 - "2026-06-16-correctness-gate-fix.md"
Cohesion: 0.33
Nodes (5): Claude re-score of committed responses through the fixed gate, Correctness under Ponytail: gate fixes + GPT-mini reproduction (2026-06-16), GPT arms (needs OPENAI_API_KEY in ../.env), The gate bugs, TL;DR

### Community 64 - "graphify reference: query, path, explain"
Cohesion: 0.33
Nodes (5): For /graphify explain, For /graphify path, graphify reference: query, path, explain, Step 0 — Constrained query expansion (REQUIRED before traversal), Step 1 — Traversal

### Community 65 - "csv-sum.md"
Cohesion: 0.33
Nodes (5): Alternative methods:, CSV Sum, Python code to read sales.csv and sum the 'amount' column, With Ponytail, 3 lines of code, Without Ponytail, 20 lines of code

### Community 66 - "types.d.ts"
Cohesion: 0.33
Nodes (5): Band, claude-code, PluginState, Tests, Tokens

### Community 67 - "package.json"
Cohesion: 0.33
Nodes (5): name, private, scripts, test, type

### Community 68 - "grok-plugin.test.js"
Cohesion: 0.33
Nodes (5): assert, fs, path, root, test

### Community 69 - "kimi-plugin.test.js"
Cohesion: 0.33
Nodes (5): assert, fs, path, root, test

### Community 70 - "package-scripts.test.js"
Cohesion: 0.33
Nodes (5): assert, fs, path, root, test

### Community 71 - "package.test.js"
Cohesion: 0.33
Nodes (5): assert, fs, path, root, test

### Community 72 - "SKILL.md"
Cohesion: 0.40
Nodes (4): 1. Map first, 2. Look for, 3. Check before you report, 4. Output

### Community 73 - "Ponytail Gain"
Cohesion: 0.40
Nodes (4): Boundaries, Honesty boundary, Ponytail Gain, Scoreboard

### Community 74 - "SKILL.md"
Cohesion: 0.40
Nodes (4): 1. Understand first, 2. Look for, 3. Check before you report, 4. Output

### Community 75 - "Ponytail"
Cohesion: 0.40
Nodes (4): Before you write, Levels, Ponytail, The smallest complete change

### Community 76 - "SKILL.md"
Cohesion: 0.40
Nodes (4): 1. Map first, 2. Look for, 3. Check before you report, 4. Output

### Community 77 - "Ponytail Gain"
Cohesion: 0.40
Nodes (4): Boundaries, Honesty boundary, Ponytail Gain, Scoreboard

### Community 78 - "SKILL.md"
Cohesion: 0.40
Nodes (4): 1. Understand first, 2. Look for, 3. Check before you report, 4. Output

### Community 79 - "SKILL.md"
Cohesion: 0.40
Nodes (4): Before you write, Levels, Ponytail, The smallest complete change

### Community 80 - "Ponytail, lazy senior dev mode"
Cohesion: 0.50
Nodes (3): Before you write, Ponytail, lazy senior dev mode, The smallest complete change

### Community 81 - "caveman.js"
Cohesion: 0.50
Nodes (3): fs, path, system

### Community 82 - "ponytail.js"
Cohesion: 0.50
Nodes (3): fs, path, system

### Community 83 - "graphify reference: add a URL and watch a folder"
Cohesion: 0.50
Nodes (3): For /graphify add, For --watch, graphify reference: add a URL and watch a folder

### Community 84 - "graphify reference: commit hook and native CLAUDE.md integration"
Cohesion: 0.50
Nodes (3): For git commit hook, For native CLAUDE.md integration, graphify reference: commit hook and native CLAUDE.md integration

### Community 85 - "graphify reference: incremental update and cluster-only"
Cohesion: 0.50
Nodes (3): For --cluster-only, For --update (incremental re-extraction), graphify reference: incremental update and cluster-only

### Community 86 - "Ponytail, lazy senior dev mode"
Cohesion: 0.50
Nodes (3): Before you write, Ponytail, lazy senior dev mode, The smallest complete change

### Community 87 - "Deep Clone"
Cohesion: 0.50
Nodes (3): Deep Clone, With Ponytail, Without Ponytail

### Community 88 - "Group By"
Cohesion: 0.50
Nodes (3): Group By, With Ponytail, Without Ponytail

### Community 89 - "Infinite Scroll"
Cohesion: 0.50
Nodes (3): Infinite Scroll, With Ponytail, Without Ponytail

### Community 90 - "Modal Dialog"
Cohesion: 0.50
Nodes (3): Modal Dialog, With Ponytail, Without Ponytail

### Community 91 - "Number Formatting"
Cohesion: 0.50
Nodes (3): Number Formatting, With Ponytail, Without Ponytail

### Community 92 - "URL Parameters"
Cohesion: 0.50
Nodes (3): URL Parameters, With Ponytail, Without Ponytail

### Community 93 - "Ponytail, lazy senior dev mode"
Cohesion: 0.50
Nodes (3): Before you write, Ponytail, lazy senior dev mode, The smallest complete change

### Community 94 - "Ponytail, lazy senior dev mode"
Cohesion: 0.50
Nodes (3): Before you write, Ponytail, lazy senior dev mode, The smallest complete change

### Community 95 - "SKILL.md"
Cohesion: 0.50
Nodes (3): Boundaries, Output, Scan

### Community 96 - "SKILL.md"
Cohesion: 0.50
Nodes (3): Boundaries, Output, Scan

### Community 97 - "Ponytail, lazy senior dev mode"
Cohesion: 0.50
Nodes (3): Before you write, Ponytail, lazy senior dev mode, The smallest complete change

## Knowledge Gaps
- **714 isolated node(s):** `$schema`, `name`, `description`, `name`, `url` (+709 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **10 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `metrics` connect `main` to `band-import.test.js`?**
  _High betweenness centrality (0.050) - this node is a cross-community bridge._
- **Why does `pairwise()` connect `answer.py` to `main`?**
  _High betweenness centrality (0.049) - this node is a cross-community bridge._
- **Why does `sign_p()` connect `main` to `answer.py`?**
  _High betweenness centrality (0.048) - this node is a cross-community bridge._
- **What connects `$schema`, `name`, `description` to the rest of the system?**
  _747 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `register.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.0758714969241285 - nodes in this community are weakly interconnected._
- **Should `hooks.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.03076923076923077 - nodes in this community are weakly interconnected._
- **Should `__init__.py` be split into smaller, more focused modules?**
  _Cohesion score 0.06976744186046512 - nodes in this community are weakly interconnected._