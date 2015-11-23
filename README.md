# push-waffle
Load a json of issues into a git repo

## setting up cohort curriculum

1. globally install push-waffle `npm install -g push-waffle`
1. Create cohort repo e.g. *moa-2016* in dev-academy-phase0 org
2. Add `students.json` to repo, e.g.
  ```
  {
    student_github_names: [
      'peterjacobson',
      'pietguersen',
      'jamanius',
      'joshuavial'
    ]
  }
  ```
3. Clone/navigate to [curriculum-private](https://github.com/dev-academy-phase0/curriculum-private)
4. `git pull` to get latest changes
5. run push-waffle `push-waffle 4-assignments.json`
