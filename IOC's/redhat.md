Supply Chain Attack Campaign

Red Hat Cloud Services Package Compromise
The Red Hat Cloud Services Package Compromise is a malicious npm supply chain incident involving compromised @redhat-cloud-services package versions that execute an obfuscated credential-harvesting payload through a preinstall hook during npm install. The payload targets developer workstations and CI/CD environments, collecting GitHub Actions secrets, npm tokens, cloud credentials, Kubernetes and Vault material, SSH keys, and other sensitive files, with exfiltration through encrypted outbound channels and GitHub-based dead-drop mechanisms. The malicious versions appear to have been published through trusted upstream CI/CD publishing infrastructure, turning legitimate Red Hat Cloud Services packages into install-time credential theft and potential supply-chain propagation vehicles.

Ecosystems: npm

First discovered
2026-06-01
Last activity
2026-06-01
Affected Package Artifacts
95
Package Artifacts Last 7 Days
95
vs previous 7 days
Affected packages
Package Artifact	Published	Detected ▼
npm
@redhat-cloud-services/vulnerabilities-client
2.1.11

2026-06-01 14:24:19 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/vulnerabilities-client
2.1.9

2026-06-01 13:46:27 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/tsc-transform-imports
1.2.4

2026-06-01 13:45:14 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/topological-inventory-client
3.0.13

2026-06-01 14:24:29 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/topological-inventory-client
3.0.11

2026-06-01 13:46:30 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/sources-client
3.0.11

2026-06-01 13:46:25 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/rule-components
4.7.5

2026-06-01 14:23:16 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/rule-components
4.7.3

2026-06-01 13:45:26 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/remediations-client
4.0.7

2026-06-01 14:24:22 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/remediations-client
4.0.5

2026-06-01 13:46:28 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/rbac-client
9.0.6

2026-06-01 14:24:26 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/rbac-client
9.0.4

2026-06-01 13:46:28 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/quickstarts-client
4.0.14

2026-06-01 14:24:12 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/quickstarts-client
4.0.12

2026-06-01 13:46:14 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/patch-client
4.0.7

2026-06-01 14:24:22 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/patch-client
4.0.5

2026-06-01 13:46:25 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/notifications-client
6.1.7

2026-06-01 14:24:18 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/notifications-client
6.1.5

2026-06-01 13:46:24 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/javascript-clients-shared
2.0.11

2026-06-01 14:24:09 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/javascript-clients-shared
2.0.9

2026-06-01 13:46:17 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/integrations-client
6.0.7

2026-06-01 14:24:12 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/integrations-client
6.0.5

2026-06-01 13:46:16 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/insights-client
4.0.7

2026-06-01 14:24:26 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/insights-client
4.0.5

2026-06-01 13:46:29 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/host-inventory-client
5.0.6

2026-06-01 14:24:22 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/host-inventory-client
5.0.4

2026-06-01 13:46:25 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-pf-mcp
0.6.4

2026-06-01 14:25:10 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-pf-mcp
0.6.2

2026-06-01 13:47:11 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-kessel-mcp
0.3.4

2026-06-01 14:25:11 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-kessel-mcp
0.3.2

2026-06-01 13:47:10 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-feo-mcp
0.3.4

2026-06-01 14:25:10 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/hcc-feo-mcp
0.3.2

2026-06-01 13:47:14 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-utilities
7.4.4

2026-06-01 14:23:17 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-utilities
7.4.2

2026-06-01 13:45:27 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-translations
4.4.4

2026-06-01 14:23:15 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-translations
4.4.2

2026-06-01 13:45:25 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-testing
1.2.2

2026-06-01 13:45:19 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-remediations
4.9.5

2026-06-01 14:23:08 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-remediations
4.9.3

2026-06-01 13:45:19 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-notifications
6.9.5

2026-06-01 14:23:16 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-notifications
6.9.3

2026-06-01 13:45:25 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-config-utilities
4.11.5

2026-06-01 14:23:09 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-config-utilities
4.11.3

2026-06-01 13:45:22 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-config
6.11.6

2026-06-01 14:23:09 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-config
6.11.4

2026-06-01 13:45:20 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-advisor-components
3.8.6

2026-06-01 14:23:17 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-advisor-components
3.8.4

2026-06-01 13:45:26 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components
7.7.5

2026-06-01 14:23:18 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/frontend-components
7.7.3

2026-06-01 13:45:29 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/eslint-config-redhat-cloud-services
3.2.4

2026-06-01 14:23:04 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/eslint-config-redhat-cloud-services
3.2.2

2026-06-01 13:45:18 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/entitlements-client
4.0.12

2026-06-01 13:46:13 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/config-manager-client
5.0.7

2026-06-01 14:24:08 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/config-manager-client
5.0.5

2026-06-01 13:46:13 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/compliance-client
4.0.6

2026-06-01 14:24:26 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/compliance-client
4.0.4

2026-06-01 13:46:29 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/entitlements-client
4.0.14

2026-06-01 14:24:09 UTC	2026-06-01 15:17:14 UTC
npm
@redhat-cloud-services/chrome
2.3.4

2026-06-01 14:23:11 UTC	2026-06-01 15:15:51 UTC
npm
@redhat-cloud-services/chrome
2.3.2

2026-06-01 13:45:23 UTC	2026-06-01 15:15:51 UTC
npm
@redhat-cloud-services/types
3.6.2

2026-06-01 13:45:15 UTC	2026-06-01 15:12:24 UTC
npm
@redhat-cloud-services/tsc-transform-imports
1.2.6

2026-06-01 14:23:03 UTC	2026-06-01 14:55:33 UTC
npm
@redhat-cloud-services/sources-client
3.0.13

2026-06-01 14:24:22 UTC	2026-06-01 14:31:15 UTC
npm
@redhat-cloud-services/types
3.6.4

2026-06-01 14:23:03 UTC	2026-06-01 14:29:20 UTC
npm
@redhat-cloud-services/host-inventory-client
5.0.3

2026-06-01 10:55:09 UTC	2026-06-01 11:06:04 UTC
npm
@redhat-cloud-services/topological-inventory-client
3.0.10

2026-06-01 10:55:23 UTC	2026-06-01 11:02:04 UTC
npm
@redhat-cloud-services/notifications-client
6.1.4

2026-06-01 10:54:58 UTC	2026-06-01 11:01:50 UTC
npm
@redhat-cloud-services/chrome
2.3.1

2026-06-01 10:54:42 UTC	2026-06-01 11:01:45 UTC
npm
@redhat-cloud-services/frontend-components
7.7.2

2026-06-01 10:55:00 UTC	2026-06-01 11:01:44 UTC
npm
@redhat-cloud-services/integrations-client
6.0.4

2026-06-01 10:54:36 UTC	2026-06-01 11:01:44 UTC
npm
@redhat-cloud-services/patch-client
4.0.4

2026-06-01 10:55:09 UTC	2026-06-01 11:01:35 UTC
npm
@redhat-cloud-services/quickstarts-client
4.0.11

2026-06-01 10:54:31 UTC	2026-06-01 11:01:33 UTC
npm
@redhat-cloud-services/rule-components
4.7.2

2026-06-01 10:54:59 UTC	2026-06-01 11:01:33 UTC
npm
@redhat-cloud-services/compliance-client
4.0.3

2026-06-01 10:55:21 UTC	2026-06-01 11:01:33 UTC
npm
@redhat-cloud-services/hcc-feo-mcp
0.3.1

2026-06-01 10:54:27 UTC	2026-06-01 11:01:31 UTC
npm
@redhat-cloud-services/vulnerabilities-client
2.1.8

2026-06-01 10:55:10 UTC	2026-06-01 11:01:30 UTC
npm
@redhat-cloud-services/frontend-components-translations
4.4.1

2026-06-01 10:54:47 UTC	2026-06-01 11:01:30 UTC
npm
@redhat-cloud-services/remediations-client
4.0.4

2026-06-01 10:54:59 UTC	2026-06-01 11:01:29 UTC
npm
@redhat-cloud-services/hcc-pf-mcp
0.6.1

2026-06-01 10:54:27 UTC	2026-06-01 11:01:28 UTC
npm
@redhat-cloud-services/frontend-components-remediations
4.9.2

2026-06-01 10:54:26 UTC	2026-06-01 11:01:26 UTC
npm
@redhat-cloud-services/javascript-clients-shared
2.0.8

2026-06-01 10:54:26 UTC	2026-06-01 11:01:25 UTC
npm
@redhat-cloud-services/frontend-components-config-utilities
4.11.2

2026-06-01 10:54:36 UTC	2026-06-01 11:01:25 UTC
npm
@redhat-cloud-services/sources-client
3.0.10

2026-06-01 10:55:04 UTC	2026-06-01 11:01:25 UTC
npm
@redhat-cloud-services/insights-client
4.0.4

2026-06-01 10:55:21 UTC	2026-06-01 11:01:24 UTC
npm
@redhat-cloud-services/rbac-client
9.0.3

2026-06-01 10:55:21 UTC	2026-06-01 11:01:24 UTC
npm
@redhat-cloud-services/frontend-components-notifications
6.9.2

2026-06-01 10:54:53 UTC	2026-06-01 11:01:24 UTC
npm
@redhat-cloud-services/frontend-components-advisor-components
3.8.2

2026-06-01 10:54:58 UTC	2026-06-01 11:01:23 UTC
npm
@redhat-cloud-services/hcc-kessel-mcp
0.3.1

2026-06-01 10:54:26 UTC	2026-06-01 11:01:22 UTC
npm
@redhat-cloud-services/config-manager-client
5.0.4

2026-06-01 10:54:25 UTC	2026-06-01 11:01:22 UTC
npm
@redhat-cloud-services/frontend-components-utilities
7.4.1

2026-06-01 10:54:59 UTC	2026-06-01 11:01:22 UTC
npm
@redhat-cloud-services/frontend-components-config
6.11.3

2026-06-01 10:54:36 UTC	2026-06-01 11:01:20 UTC
npm
@redhat-cloud-services/tsc-transform-imports
1.2.2

2026-06-01 10:54:15 UTC	2026-06-01 11:00:40 UTC
npm
@redhat-cloud-services/eslint-config-redhat-cloud-services
3.2.1

2026-06-01 10:54:20 UTC	2026-06-01 11:00:35 UTC
npm
@redhat-cloud-services/frontend-components-testing
1.2.1

2026-06-01 10:54:21 UTC	2026-06-01 11:00:33 UTC
npm
@redhat-cloud-services/types
3.6.1

2026-06-01 10:54:09 UTC	2026-06-01 11:00:31 UTC
npm
@redhat-cloud-services/entitlements-client
4.0.11

2026-06-01 10:54:20 UTC	2026-06-01 11:00:22 UTC