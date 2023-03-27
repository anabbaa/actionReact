# actionReact

- workflows: build and test every pull request to your repository, or deploy merged pull requests to production
- job: define runner
  steps: shell command action
  -action: app performs a typicialy complex task frequently repetitive task
  -an example - go to actions then choose for example simple then click configure then name it - name your workflow name: then choose a name - define event: on: then name the event
  -Jobs then name your job a name from your choice then define the runner with key name - runs-on: for example ubuntu-latest
  -steps:
  --name: choose a name - run: to run a code in the shell

- amother example a file locally
  - in the root make a folder named obliged "github" inside it another folder also its name
    is obliged "workflows" then a file name it as you want here in steps you should triggered
    step of Get code because the runner does not have your code
  - after step uses the key word uses: then actons/name of action with version bytyping @v then number
  - with: some steps need configuration do it with key wor with: then enter and tap to another
    step go brack from your position
