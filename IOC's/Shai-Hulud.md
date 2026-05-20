Network IOCs
hxxp[:]//filev2[.]getsession[.]org/file/ - encrypted credential upload and retrieval path
hxxps[:]//83.142.209.194/transformers.pyz - PyPI remote payload URL
hxxps[:]//83.142.209.194/v1/models - PyPI second-stage retrieval endpoint
hxxps[:]//83.142.209.194/v1/weights - PyPI credential exfiltration endpoint
hxxps[:]//83.142.209.194/audio.mp3 - PyPI destructive second-stage media download
seed1[.]getsession[.]org, seed2[.]getsession[.]org, seed3[.]getsession[.]org - Session/Oxen seed nodes
/json_rpc with get_n_service_nodes - Session service-node discovery path
hxxps[:]//api[.]github[.]com/search/commits?q=FIRESCALE - PyPI fallback C2 discovery through signed GitHub commit messages
hxxps[:]//api[.]github[.]com/user/repos - creates public GitHub dead-drop repositories
hxxps[:]//api[.]github[.]com/repos/<owner>/<repo>/contents/results/ - commits exfiltrated result JSON to GitHub dead-drop repositories
hxxps[:]//api[.]github[.]com/graphql - createCommitOnBranch repository write path
git-tanstack[.]com - campaign infrastructure
api[.]masscan[.]cloud - campaign infrastructure
83.142.209.194 - campaign infrastructure
Hashes
NPM payloads:

29c729852fce5a53e30a1541d9fec79c915b2e13f1eda94a5978cf0aae0d88d9
2ec78d556d696e208927cc503d48e4b5eb56b31abc2870c2ed2e98d6be27fc96
ab4fcadaec49c03278063dd269ea5eef82d24f2124a8e15d7b90f2fa8601266c
D4a2086ea18f5e39cd867b8b06918a524eabb21d45ea98aad07357b98173458a
PyPI payload __init__.py:

2a314ea8be337e1ca9ec833ed13ed854d9fd38bce0a519cf288f3bec8d9e6f30
Updated PyPI transformers.pyz payload:

5245eb032e336b85cff0dbb3450d591826bf2ef214fd30d7eba1a763664e151b
Files
/tmp/transformers.pyz - PyPI downloaded payload path
~/.local/bin/pgmonitor.py - PyPI second-stage persistence payload
/usr/bin/pgmonitor.py - PyPI second-stage persistence payload when running as root
Linux dead-man switch:

~/.config/systemd/user/gh-token-monitor.service
~/.local/bin/gh-token-monitor.sh
~/.config/gh-token-monitor/
MacOS dead-man switch:

~/Library/LaunchAgents/com.user.gh-token-monitor.plist
~/.local/bin/gh-token-monitor.sh
~/.config/gh-token-monitor/
Other Indicators
Shai-Hulud: Here We Go Again - decoded GitHub dead-drop repository description
PUSH UR T3MPRR - PyPI GitHub exfiltration repository description
FIRESCALE - PyPI fallback C2 discovery keyword in GitHub commit search
pgsql-monitor.service - PyPI second-stage systemd persistence service
Linux Dead-man switch service - gh-token-monitor.service
MacOS Dead-man switch plist - ~/Library/LaunchAgents/com.user.gh-token-monitor.plist