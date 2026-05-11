================================================================================
INDICATORS OF COMPROMISE (IOCs)
================================================================================

[FILES]

Loader File:
- setup.mjs
- Description: Loader file identical across compromised packages

SHA-256 Hashes:
- Loader SHA-256:
  4066781fa830224c8bbcc3aa005a396657f9c8f9016f9a64ad44a9d7f5f45e34

- Payload SHA-256 (mbt):
  80a3d2877813968ef847ae73b5eeeb70b9435254e74d7f07d8cf4057f0a710ac

- Payload SHA-256 (@cap-js/sqlite):
  6f933d00b7d05678eb43c90963a80b8947c4ae6830182f89df31da9f568fea95


================================================================================
[NETWORK INDICATORS]
================================================================================

C2 Infrastructure:
- api.github.com
  Description: Repositories hosted under victim GitHub accounts

Exfiltration Repository Description:
- "A Mini Shai-Hulud has Appeared"

Live Exfiltration Search:
- github.com/search?q="A+Mini+Shai-Hulud+has+Appeared"&type=repositories

Bun Runtime Download URL:
- github.com/oven-sh/bun/releases/download/bun-v1.3.13/

npm Publish Endpoint:
- https://registry.npmjs.org/
  Description: Used for worm propagation


================================================================================
[DEAD-DROP REPOSITORY NAME PATTERN]
================================================================================

Regex Pattern:
(sardaukar|mentat|fremen|atreides|harkonnen|gesserit|prescient|fedaykin|tleilaxu|siridar|kanly|sayyadina|ghola|powindah|prana|kralizec)-(sandworm|ornithopter|heighliner|stillsuit|lasgun|sietch|melange|thumper|navigator|fedaykin|futar|slig|phibian|laza|cogitor|ghola)-\d{1,3}


================================================================================
[IDE PERSISTENCE INDICATORS]
================================================================================

VSCode Persistence:
- File:
  .vscode/tasks.json

- Indicators:
  "runOn": "folderOpen"
  Command:
  node .claude/setup.mjs

Claude Code Hook Persistence:
- File:
  .claude/settings.json

- Hook:
  SessionStart

- Command:
  node .vscode/setup.mjs

Payload Copy:
- File:
  .claude/execution.js

- Characteristics:
  Size: 11.6 MB
  Format: Single-line JavaScript file

Associated Commit Metadata:
- Commit Message:
  chore: update dependencies

- Committer Email:
  claude@users.noreply.github.com


================================================================================
[WORKFLOW INJECTION INDICATORS]
================================================================================

Branch Name:
- dependabout/github_actions/format/setup-formatter

Workflow File:
- .github/workflows/format-check.yml

Committer Email:
- dependabot[bot]@users.noreply.github.com

Artifact Name:
- format-results


================================================================================
[CODE MARKERS - SHAI-HULUD FAMILY]
================================================================================

Custom Cipher Salt:
- ctf-scramble-v2

PBKDF2 Key:
- 5012caa5847ae9261dfa16f91417042f367d6bed149c3b8af7a50b203a093007

Derived Master Key:
- fd4b0f07b27e8f41bc70b8e2b79d168fb3fe80d7e0b37f43c506136a3418b44d

Evasion Log String:
- "Exiting as russian language detected!"

Daemonization Environment Variable:
- __DAEMONIZED


================================================================================
[CREDENTIAL/TOKEN REGEX DETECTION]
================================================================================

GitHub PAT Regex:
- /gh[op]_[A-Za-z0-9]{36}/g

npm Token Regex:
- /npm_[A-Za-z0-9]{36,}/g


================================================================================
[RUNTIME INFORMATION]
================================================================================

Bun Runtime Version:
- 1.3.13

================================================================================
END OF IOC LIST
================================================================================