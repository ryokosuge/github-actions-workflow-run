# Github Actions workflow_run

## 試したこと

- first-action -> second-action -> third-actionとworkflowを流したい

## わかったこと

- workflow_runがtriggerで実行されるactionは default branchで動く
    - workflow_runで実行されたworkflowをworkflow_runのtriggerにする場合、branchはdefault branchにしないと実行されない
