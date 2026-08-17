### Olajuwon Okeniyi

I build small systems end to end — provision the infrastructure, script the
operations, wire a pipeline around the result, then write up what broke and
how I found it.

**Administering systems** — [my-cloud-homelab](https://github.com/OlajuwonOkeniyi/my-cloud-homelab):
an AWS instance defined entirely in Terraform, with Docker, systemd, CloudWatch
alarms, SNS alerting, and CI checking the Terraform and the bootstrap shell on
every push.

**Administering pipelines** — [portfolio-auto-deploy](https://github.com/OlajuwonOkeniyi/portfolio-auto-deploy):
a gated GitHub Actions pipeline — validate, stage, deploy, tag — with date-based
versioning, an audited deploy log, and one-click rollback.

**Writing code** — [pdf-quiz-generator](https://github.com/OlajuwonOkeniyi/pdf-quiz-generator)
(95 tests, CI across three Python versions) and
[file-sync-automator](https://github.com/OlajuwonOkeniyi/file-sync-automator)
(content-hash diffing instead of timestamps, 79 tests).

Every README below has a section on the defects the project surfaced and how
they were found. That's the part worth reading — anyone can claim a system
works; these say what broke first.

Boston, MA · Linux, AWS, Terraform, Bash, Python
