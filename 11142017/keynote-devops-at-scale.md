# VS Team Servcie

* 2 teams (vsteam services team, and tfs team), 1 master 40 feature teams, ship every 3 weeks.
* every 4 months they take a release branch to release a major version.
* use feature flags to expose things getting push into production
* use powershell to control deploymeni or Web UI
* "Circuit breakers" stop cascading failers in a comlex distriubuted system
** Originated at Netflix
** three states, Closed (good), Open (bad), Half-Open (ok, maybe)
* Shield team members handle customer issues.
* lessons learned
** Telemetry is everything
** Root cause everything
** Repair items fixed in 2 sprints (or sooner)
** shield team
* wrap-up
** control exposure w/ feature flags
** limit failure with ciruit breakers
** Root cause everything
** design fast reliable test

learn more aka.ms/learndevops
@tfsbuck
blogs.msdn.com/buckh
