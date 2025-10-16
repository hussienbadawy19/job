name: hello-world
on: push
jobs:
  my-job: 
    runs-on: ubuntu-latest
    steps:
      - name: my-step
        run: echo "hello World"
      - name: my-step-2
        run: echo "heyyy"
  my-job2:
    runs-on: ubuntu-latest 
    needs: my-job
    steps:
      - name: my-task
        run: echo "the task is here if job1 succeeded"
