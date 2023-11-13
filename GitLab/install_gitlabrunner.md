# GitLab Runner
## Amazon Linux 2023
Gravitonにバージョン15.5.0のGitRunnerをインストールする。
```sh
curl -LJO "https://gitlab-runner-downloads.s3.amazonaws.com/v15.5.0/rpm/gitlab-runner_aarch64.rpm"
sudo dnf install git
sudo rpm -i gitlab-runner_aarch64.rpm
```