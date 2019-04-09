v1.5.0 - 2019-04-09T14:43:45
----------------------------

* Clear goss_templates variable on every run to prevent test plans from
  being applied to the wrong host groups

v1.4.1 - 2018-11-15T22:31:38
----------------------------

* Optimize role by splitting away install tasks from test tasks

v1.4.0 - 2018-08-14T01:35:16
----------------------------

* Update goss to v0.3.6

v1.3.0 - 2018-08-14T00:14:23
----------------------------

* Add the ability to retry tests (with delay) in-case they need the
  system to warm up or the tests fail intermittently because of external
  conditions

v1.2.0 - 2018-07-17T20:38:16
----------------------------

* Force facts to be refreshed on role run

v1.1.0
------

* Optimize test times by increasing concurrency
  (GO_MAX_CONCURRENT = 4 * num_cpus)
* Minor fixes

v1.0.0
------

* Initial release
