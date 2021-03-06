.. _elasticsearch_connector_changelog:

Changelog
=========

Version 3.3.0
-------------

* `PR-69 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/69>`_ - Fix map output for String keyed maps.
* `PR-83 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/83>`_ - ST-336: Move slf4j-simple into test scope so it is not pulled into the packaged version.

Version 3.2.2
-------------

* `PR-89 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/89>`_ - Increase flush timeout in BulkProcessorTest to make the test more reliable when the test server has other CPU load.

Version 3.2.1
-------------

No changes

Version 3.2.0
-------------

* `PR-34 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/34>`_ - CC-331: update config options docs
* `PR-47 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/47>`_ - Allow for multiple Elasticsearch HTTP URLs
* `PR-53 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/53>`_ - CC-392: Fix mapping existence check
* `PR-54 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/54>`_ - CC-393: don't use offset as document version when key.ignore=true
* `PR-49 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/49>`_ - Schema.Type.BYTES should map to 'binary' ES datatype
