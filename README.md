# mule4-ai-sftp-test
Codeless Agent test with Mule 4 and SFTP

# Steps for publish logs to APP Insight
1. Update connection [applicationinsights.json](https://github.com/abhikt48/mule4-ai-sftp-test/blob/main/agent/applicationinsights.json)
2. Dowload and copy `applicationinsights-agent-3.5.2.jar` in agent folder
3. Import application in Anypoint Studio
4. Update SFTP server details
5. Run application with with VM argument `-javaagent:"***\agent\applicationinsights-agent-3.5.2.jar" `
