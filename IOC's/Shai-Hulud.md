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





Appendix A: npm Compromised Package Versions
type	XrayID	Version
@beproduct/nestjs-auth	XRAY-981605	0.1.18;0.1.19;0.1.17;0.1.16;0.1.15;0.1.13;0.1.14;0.1.8;0.1.6;0.1.9;0.1.2;0.1.5;0.1.11;0.1.4;0.1.3;0.1.7;0.1.10;0.1.12
@dirigible-ai/sdk	XRAY-981587	0.6.3;0.6.2
@draftauth/client	XRAY-981621	0.2.2;0.2.1
@draftauth/core	XRAY-981600	0.13.1;0.13.2
@draftlab/auth	XRAY-981565	0.24.2;0.24.1
@draftlab/auth-router	XRAY-981599	0.5.1;0.5.2
@draftlab/db	XRAY-981569	0.16.2;0.16.1
@mesadev/rest	XRAY-981764	0.28.3
@mesadev/saguaro	XRAY-981773	0.4.22
@mesadev/sdk	XRAY-981754	0.28.3
@mistralai/mistralai	XRAY-981767	2.2.4;2.2.3;2.2.2
@mistralai/mistralai-azure	XRAY-981787	1.7.3;1.7.1;1.7.2
@mistralai/mistralai-gcp	XRAY-981783	1.7.3;1.7.1;1.7.2
@ml-toolkit-ts/preprocessing	XRAY-981622	1.0.2;1.0.3
@ml-toolkit-ts/xgboost	XRAY-981630	1.0.3;1.0.4
@opensearch-project/opensearch	XRAY-981790	3.5.3;3.8.0;3.7.0;3.6.2
@squawk/airport-data	XRAY-981753	0.7.8;0.7.7;0.7.6;0.7.5;0.7.4
@squawk/airports	XRAY-981785	0.6.6;0.6.5;0.6.4;0.6.3;0.6.2
@squawk/airspace	XRAY-981774	0.8.5;0.8.3;0.8.4;0.8.2;0.8.1
@squawk/airspace-data	XRAY-981671	0.5.7;0.5.5;0.5.6;0.5.4;0.5.3
@squawk/airway-data	XRAY-981770	0.5.8;0.5.7;0.5.6;0.5.5;0.5.4
@squawk/airways	XRAY-981786	0.4.6;0.4.4;0.4.5;0.4.3;0.4.2
@squawk/fix-data	XRAY-981762	0.6.8;0.6.7;0.6.6;0.6.5;0.6.4
@squawk/fixes	XRAY-981768	0.3.6;0.3.5;0.3.4;0.3.3;0.3.2
@squawk/flight-math	XRAY-981761	0.5.8;0.5.7;0.5.6;0.5.5;0.5.4
@squawk/flightplan	XRAY-981755	0.5.6;0.5.5;0.5.4;0.5.3;0.5.2
@squawk/geo	XRAY-981765	0.4.8;0.4.7;0.4.6;0.4.5;0.4.4
@squawk/icao-registry	XRAY-981780	0.5.6;0.5.5;0.5.4;0.5.3;0.5.2
@squawk/icao-registry-data	XRAY-981759	0.8.8;0.8.6;0.8.7;0.8.5;0.8.4
@squawk/mcp	XRAY-981760	0.9.5;0.9.4;0.9.3;0.9.2;0.9.1
@squawk/navaid-data	XRAY-981763	0.6.8;0.6.7;0.6.6;0.6.5;0.6.4
@squawk/navaids	XRAY-981791	0.4.6;0.4.5;0.4.4;0.4.3;0.4.2
@squawk/notams	XRAY-981772	0.3.10;0.3.9;0.3.8;0.3.7;0.3.6
@squawk/procedure-data	XRAY-981758	0.7.7;0.7.5;0.7.6;0.7.4;0.7.3
@squawk/procedures	XRAY-981782	0.5.6;0.5.4;0.5.5;0.5.3;0.5.2
@squawk/types	XRAY-981769	0.8.5;0.8.3;0.8.4;0.8.2;0.8.1
@squawk/units	XRAY-981664	0.4.7;0.4.5;0.4.6;0.4.4;0.4.3
@squawk/weather	XRAY-981788	0.5.10;0.5.8;0.5.9;0.5.7;0.5.6
@supersurkhet/cli	XRAY-981629	0.0.7;0.0.6;0.0.5;0.0.4;0.0.3;0.0.2
@supersurkhet/sdk	XRAY-981633	0.0.7;0.0.6;0.0.5;0.0.4;0.0.3;0.0.2
@tallyui/components	XRAY-981682	1.0.3;1.0.2;1.0.1
@tallyui/connector-medusa	XRAY-981673	1.0.3;1.0.2;1.0.1
@tallyui/connector-shopify	XRAY-981663	1.0.3;1.0.2;1.0.1
@tallyui/connector-vendure	XRAY-981677	1.0.3;1.0.2;1.0.1
@tallyui/connector-woocommerce	XRAY-981678	1.0.3;1.0.2;1.0.1
@tallyui/core	XRAY-981778	0.2.3;0.2.2;0.2.1
@tallyui/database	XRAY-981674	1.0.3;1.0.2;1.0.1
@tallyui/pos	XRAY-981675	0.1.3;0.1.2;0.1.1
@tallyui/storage-sqlite	XRAY-981757	0.2.3;0.2.2;0.2.1
@tallyui/theme	XRAY-981679	0.2.3;0.2.2;0.2.1
@tanstack/arktype-adapter	XRAY-981393	1.166.15;1.166.12
@tanstack/eslint-plugin-router	XRAY-981423	1.161.12;1.161.9
@tanstack/eslint-plugin-start	XRAY-981394	0.0.7;0.0.4
@tanstack/history	XRAY-981408	1.161.12;1.161.9
@tanstack/nitro-v2-vite-plugin	XRAY-981403	1.154.15;1.154.12
@tanstack/react-router	XRAY-981412	1.169.8;1.169.5
@tanstack/react-router-devtools	XRAY-981428	1.166.19;1.166.16
@tanstack/react-router-ssr-query	XRAY-981410	1.166.18;1.166.15
@tanstack/react-start	XRAY-981426	1.167.71;1.167.68
@tanstack/react-start-client	XRAY-981397	1.166.54;1.166.51
@tanstack/react-start-rsc	XRAY-981399	0.0.50;0.0.47
@tanstack/react-start-server	XRAY-981421	1.166.58;1.166.55
@tanstack/router-cli	XRAY-981420	1.166.49;1.166.46
@tanstack/router-core	XRAY-981409	1.169.8;1.169.5
@tanstack/router-devtools	XRAY-981425	1.166.19;1.166.16
@tanstack/router-devtools-core	XRAY-981414	1.167.9;1.167.6
@tanstack/router-generator	XRAY-981417	1.166.48;1.166.45
@tanstack/router-plugin	XRAY-981395	1.167.41;1.167.38
@tanstack/router-ssr-query-core	XRAY-981402	1.168.6;1.168.3
@tanstack/router-utils	XRAY-981401	1.161.14;1.161.11
@tanstack/router-vite-plugin	XRAY-981404	1.166.56;1.166.53
@tanstack/solid-router	XRAY-981429	1.169.8;1.169.5
@tanstack/solid-router-devtools	XRAY-981424	1.166.19;1.166.16
@tanstack/solid-router-ssr-query	XRAY-981419	1.166.18;1.166.15
@tanstack/solid-start	XRAY-981418	1.167.68;1.167.65
@tanstack/solid-start-client	XRAY-981400	1.166.53;1.166.50
@tanstack/solid-start-server	XRAY-981396	1.166.57;1.166.54
@tanstack/start-client-core	XRAY-981407	1.168.8;1.168.5
@tanstack/start-fn-stubs	XRAY-981422	1.161.12;1.161.9
@tanstack/start-plugin-core	XRAY-981388	1.169.26;1.169.23
@tanstack/start-server-core	XRAY-981416	1.167.36;1.167.33
@tanstack/start-static-server-functions	XRAY-981389	1.166.47;1.166.44
@tanstack/start-storage-context	XRAY-981390	1.166.41;1.166.38
@tanstack/valibot-adapter	XRAY-981406	1.166.15;1.166.12
@tanstack/virtual-file-routes	XRAY-981398	1.161.13;1.161.10
@tanstack/vue-router	XRAY-981405	1.169.8;1.169.5
@tanstack/vue-router-devtools	XRAY-981413	1.166.19;1.166.16
@tanstack/vue-router-ssr-query	XRAY-981392	1.166.18;1.166.15
@tanstack/vue-start	XRAY-981391	1.167.64;1.167.61
@tanstack/vue-start-client	XRAY-981415	1.166.49;1.166.46
@tanstack/vue-start-server	XRAY-981411	1.166.53;1.166.50
@tanstack/zod-adapter	XRAY-981427	1.166.15;1.166.12
@taskflow-corp/cli	XRAY-981614	0.1.29;0.1.28;0.1.27;0.1.26;0.1.25;0.1.24
@tolka/cli	XRAY-981591	1.0.5;1.0.6;1.0.4;1.0.3;1.0.2
@uipath/access-policy-sdk	XRAY-981571	0.3.1
@uipath/access-policy-tool	XRAY-981607	0.3.1
@uipath/admin-tool	XRAY-981593	0.1.1
@uipath/agent-sdk	XRAY-981606	1.0.2
@uipath/agent-tool	XRAY-981579	1.0.1
@uipath/agent.sdk	XRAY-981766	0.0.18
@uipath/aops-policy-tool	XRAY-981558	0.3.1
@uipath/ap-chat	XRAY-981560	1.5.7
@uipath/api-workflow-tool	XRAY-981553	1.0.1
@uipath/apollo-core	XRAY-981585	5.9.2
@uipath/apollo-react	XRAY-981776	4.24.5
@uipath/apollo-wind	XRAY-981617	2.16.2
@uipath/auth	XRAY-981631	1.0.1
@uipath/case-tool	XRAY-981574	1.0.1
@uipath/cli	XRAY-981578	1.0.1
@uipath/codedagent-tool	XRAY-981596	1.0.1
@uipath/codedagents-tool	XRAY-981572	0.1.12
@uipath/codedapp-tool	XRAY-981623	1.0.1
@uipath/common	XRAY-981567	1.0.1
@uipath/context-grounding-tool	XRAY-981598	0.1.1
@uipath/data-fabric-tool	XRAY-981602	1.0.2
@uipath/docsai-tool	XRAY-981620	1.0.1
@uipath/filesystem	XRAY-981636	1.0.1
@uipath/flow-tool	XRAY-981554	1.0.2
@uipath/functions-tool	XRAY-981555	1.0.1
@uipath/gov-tool	XRAY-981627	0.3.1
@uipath/identity-tool	XRAY-981559	0.1.1
@uipath/insights-sdk	XRAY-981564	1.0.1
@uipath/insights-tool	XRAY-981615	1.0.1
@uipath/integrationservice-sdk	XRAY-981624	1.0.2
@uipath/integrationservice-tool	XRAY-981566	1.0.2
@uipath/llmgw-tool	XRAY-981610	1.0.1
@uipath/maestro-sdk	XRAY-981563	1.0.1
@uipath/maestro-tool	XRAY-981592	1.0.1
@uipath/orchestrator-tool	XRAY-981616	1.0.1
@uipath/packager-tool-apiworkflow	XRAY-981628	0.0.19
@uipath/packager-tool-bpmn	XRAY-981581	0.0.9
@uipath/packager-tool-case	XRAY-981588	0.0.9
@uipath/packager-tool-connector	XRAY-981619	0.0.19
@uipath/packager-tool-flow	XRAY-981586	0.0.19
@uipath/packager-tool-functions	XRAY-981580	0.1.1
@uipath/packager-tool-webapp	XRAY-981590	1.0.6
@uipath/packager-tool-workflowcompiler	XRAY-981577	0.0.16
@uipath/packager-tool-workflowcompiler-browser	XRAY-981589	0.0.34
@uipath/platform-tool	XRAY-981594	1.0.1
@uipath/project-packager	XRAY-981613	1.1.16
@uipath/resource-tool	XRAY-981582	1.0.1
@uipath/resourcecatalog-tool	XRAY-981603	0.1.1
@uipath/resources-tool	XRAY-981604	0.1.11
@uipath/robot	XRAY-981626	1.3.4
@uipath/rpa-legacy-tool	XRAY-981562	1.0.1
@uipath/rpa-tool	XRAY-981609	0.9.5
@uipath/solution-packager	XRAY-981595	0.0.35
@uipath/solution-tool	XRAY-981583	1.0.1
@uipath/solutionpackager-sdk	XRAY-981561	1.0.11
@uipath/solutionpackager-tool-core	XRAY-981634	0.0.34
@uipath/tasks-tool	XRAY-981597	1.0.1
@uipath/telemetry	XRAY-981576	0.0.7
@uipath/test-manager-tool	XRAY-981568	1.0.2
@uipath/tool-workflowcompiler	XRAY-981584	0.0.12
@uipath/traces-tool	XRAY-981608	1.0.1
@uipath/ui-widgets-multi-file-upload	XRAY-981573	1.0.1
@uipath/uipath-python-bridge	XRAY-981557	1.0.1
@uipath/vertical-solutions-tool	XRAY-981625	1.0.1
@uipath/vss	XRAY-981632	0.1.6
@uipath/widget.sdk	XRAY-981635	1.2.3
agentwork-cli	XRAY-981611	0.1.4;0.1.5
cmux-agent-mcp	XRAY-981556	0.1.8;0.1.7;0.1.6;0.1.5;0.1.4;0.1.3
cross-stitch	XRAY-981779	1.1.7;1.1.5;1.1.6;1.1.4;1.1.3
git-branch-selector	XRAY-981575	1.3.7;1.3.6;1.3.5;1.3.4;1.3.3
git-git-git	XRAY-981601	1.0.12;1.0.11;1.0.10;1.0.9;1.0.8
ml-toolkit-ts	XRAY-981570	1.0.5;1.0.4
nextmove-mcp	XRAY-981612	0.1.7;0.1.6;0.1.5;0.1.4;0.1.3
safe-action	XRAY-981618	0.8.4;0.8.3
ts-dna	XRAY-981771	3.0.5;3.0.4;3.0.3;3.0.2;3.0.1
wot-api	XRAY-981777	0.8.3;0.8.4;0.8.2;0.8.1


Appendix B: PyPI Compromised Package Versions
type	XrayID	Version
guardrails-ai	XRAY-981784	0.10.1
mistralai	XRAY-981756	2.4.6