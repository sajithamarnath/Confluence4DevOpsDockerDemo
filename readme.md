# Test app for Confluence4DevOpsDockerDemo

This is a quick app cobbled together for the purposes of demonstrating a basic CI/CD workflow with Docker Hub on using Amazon Cloud.
All the Open Source Tools used. Hence the cost is Zero.

## Instructions for use

1. Prepare all Code Files.
2. Move code files from Local to GitHub (using GitBash or DesktopGit).
3. Initializing a Git repo and making a remote of it on GitHub.
4. Need to have account on - GitHUb, CircleCI, Docker Hub, Tutum and AWS.
5. Trigger Token = 630fc55c-ff9f-4428-9bf0-07013850342f
6. Trigger URL = https://registry.hub.docker.com/u/sajithamarnath/confluence4devopsdockerdemo/trigger/630fc55c-ff9f-4428-9bf0-07013850342f/
7. Curl Site = curl -H "Content-Type: application/json" --data '{"build":true}' -X POST 
8. Redirect URL - https://cloud.docker.com/api/app/v1/service/58dd277d-ae94-4894-9247-bcf9288f60a5/trigger/5acf8820-77be-4a2d-9f21-1f90ce0120fd/call/
9. OpsGenie API Key: ad4c1c06-655c-4503-92f3-0c0163cb0529
10. OpsGenie URL: https://api.opsgenie.com/v1/json/circleci?apiKey=ad4c1c06-655c-4503-92f3-0c0163cb0529
