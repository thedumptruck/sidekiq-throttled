## 0.4.0 (2016-05-17)

* [#14](https://github.com/sensortower/sidekiq-throttled/pull/14)
  Support dynamic configuration of limits and periods.
  ([@azach], [@ixti])


## 0.3.2 (2016-05-16)

* [#13](https://github.com/sensortower/sidekiq-throttled/issues/13)
  Fix throttled BasicFetch with strictly ordered queues on sidekiq 4.
  ([@palanglung], [@ixti])


## 0.3.1 (2016-05-15)

* Precalculate LUA script digests to reduce bandwidth upon nodes reload
  _(which might (and might not) happen if you run thousands of nodes)_.
  ([@ixti])


## 0.3.0 (2016-05-02)

* [#1](https://github.com/sensortower/sidekiq-throttled/issues/1):
  Add Sidekiq 4.0 support.
  ([@ixti])


## 0.2.0 (2016-02-29)

* [#6](https://github.com/sensortower/sidekiq-throttled/pull/6):
  Add dynamic key suffix functionality.
  ([@fhwang])


## 0.1.0 (2015-11-03)

* Initial release.


[@ixti]: https://github.com/ixti
[@fhwang]: https://github.com/fhwang
[@palanglung]: https://github.com/palanglung
[@azach]: https://github.com/azach
