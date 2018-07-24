WTF IS SRE?

Gilberto Vargas

Kueski


---

When Site Reliability Engineering was born?

- Google developed the basis of SRE, along with DevOps culture.
- The raise of deployments after DevOps increased the failures in production systems.
- Some systems requires high availability.
- There were frustration on the teams for the outages.

---

Site Reliability Engineering is:

- Monitoring
- Toil reduction & automation
- Risk in a daily basis
- Failure is a teacher
- Incident management
- Service levels
- Software development
- Debugging
- Releases

---

DevOps vs SRE

- DevOps is not SRE
- SRE is DevOps
- DevOps is infrastructure as code
- SRE creates as many metrics
- DevOps automates developers work as far as possible
- SRE automates operational work

---

SRE in agile

- SRE guards bussines objectives
- SRE pushes the team to do not introduce failure to systems
- SRE pushes the team to introduce failure to systems

---

Monitoring: low level

- The 4 golden signals
  - Traffic: How many users/requests is the system having.
  - Errors: How much failure is the system having.
  - Lattency: How much time the system is taking to respond.
  - Saturation: How resources are being used (RAM, CPU, disk, network, etc).

---

Monitoring: high level

- Business transactions
  - How many sells were made
  - How many users requested for the service
  - How many users were at each step of the pipeline

---

Alerting

- Logs: Are only consulted when something happens.
- Paging event: Create a page task that is not urgent.
- SMS/DM alert: Implies that something is really wrong and needs to be attended now.

---

Alerts

- Alerts should ALWAYS imply human intervention.
- Alerts can trigger scripts.

---

Incident response

- Diagnose.
- Debugging.
- Partial fix, stop bleeding.
- Fix affected transactions.
- Root cause dianose.
- Postmortem.

---

Diagnose & Debugging

- Take a look into metrics.
- Take a look into recent deployments.
- Review logs.
- Replicate the issue out of production.
- Track the root cause.

---

Postmortem

- Completely blameless.
- Hide who caused the problem.
- Highlight the causes.
- Create action items to avoid that happens again.

---

Incident Management

- Roles during incidents
  - Comander: Is accountable about the problem and takes the lead on the team.
  - Communicator: Coordinates the communication between the teams.
  - Executor: The people that works on the actual issue.
  - Investigators: A team that investigates the issue and tries to get to the root cause.

---

Balance

- Being on call
- Time for collecting feeback
- Time for postmortems
- Time for automation

---

Service Level

- Service Level Interactions (SLI): How many transactions are being performed at each moment.
- Service Level Objectives (SLO): The numbers that business wants to achieve in the period.
- Service Level Agreement (SLA): The abailability that the team agrees.

---

SLI

- Monitoring has a very high impact on this.
- Count the number of transactions.
- Count the number of errors.
- Monitor the ratio between transactions performed correctly and errors.

---

SLO

- Along with all the teams in the company, their own goals are being defined.
- IMO SLO is more important than SLA.
- Determine de incidents priority based on the time it would take break SLO.

---

SLA

- An agreement between Software teams and bussines/clients.
- It is designed to enforce the team to always fulfill SLO.
- It can take legal consequences.
- The higher the SLA it will be more expensive.

---

Releases

- SRE team must be aware of all releases.
- DevOps runs deployments within a CI/CD pipeline.
- SRE can roll back any release if it has an impact on production.

---

Failure and chaos

- When releases are smooth, chaos should be auto-inflicted.
- Study what happens when a system is down.
- Fix any issue found during the experiment.

---

Maintenance

- Automate maintenance as possible.
- Risk is reduced when maintenance is automated.
- Toil reduction.

---

Toil

- Work that can be automated and has not being automated.
- Manual operation.
- Work required to keep the system running.

---

Questions?

---

Contact:

- https://github.com/tachomex
- https://www.linkedin.com/in/tachomex/
- https://kueski.com/careers
