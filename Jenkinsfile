@Library("library") _

jDeploy {
  [
    gitURL = 'https://github.com/joshchu00/finance-deployment.git',
    gitBranch = 'master',
    deployPrivateKey = 'Jenkins',
    deployInventory = 'finance-gcp-test',
    deployImage = 'joshchu00/ansible:latest-alpine',
    deployPlaybook = 'finance.yml'
  ]
}
