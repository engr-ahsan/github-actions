## Repository Dispatch
Manually trigger the workflow through api 

https://api.github.com/repos/{username}/{repo-name}/dispatches

Body: {
    "event_type": "Specified in the workflow.yml",
    "client_payload" : {
        // Optional information it will be available on github object inside the job
    }
}

Also need a personal access token. And use it for Authentication
