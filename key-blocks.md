# Key Building Blocks

Attach a workflow to a repository, which then the workflow includes N amount of jobs and in turn those jobs contain N amount of steps

- code repository
  - workflow 1
    - job1
      - step1
      - step2
      - ...
    - job2
      - step1
      - step2
      - ...
    - ...
  - workflow 2l
    - job1
      - step1
      - step2
      - ...
    - job2
      - step1
      - step2
      - ...
    - ...
  - ...

## Workflows

Attached to GitHub repositories, these are triggered upon manual or scheduled Events.

## Jobs

Attached to workflows, these define a runner (execution environment). Jobs run in parallel by default, but we can configure to be sequential. Jobs can also run conditionally.

## Steps

Attached to jobs.They execute a shell script or Action (predefined scripts).
Steps are executed in order and can also be conditional.
