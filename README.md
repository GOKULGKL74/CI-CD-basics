# CI-CD-basics

1.CI/CD -continuous integration /continuous deleivery
->automated steps 

  CI=>code -->unit testing ->static code changes-->Build -->End to end test -->docker img-->push
  CD=>docker img ->VM

  Pull request --revw(After ci)--merge
  commit -->ci/cd

  PIPELINE:
  1.Trigger -when* pipeline need to trigger(once chnges made)automatically
  2.stages -Build -push -test  [add steps to perfrm]
  3.variable-psswrd...,

  POOL -where to plce/run the pipeline
