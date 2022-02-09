# Spring Boot Reference Documentation

[`management.auditevents.enabled`](broken-reference)

Whether to enable storage of audit events.

`true`

[`management.cloudfoundry.enabled`](broken-reference)

Whether to enable extended Cloud Foundry actuator endpoints.

`true`

[`management.cloudfoundry.skip-ssl-validation`](broken-reference)

Whether to skip SSL verification for Cloud Foundry actuator endpoint security calls.

`false`

[`management.endpoint.auditevents.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.auditevents.enabled`](broken-reference)

Whether to enable the auditevents endpoint.

`true`

[`management.endpoint.beans.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.beans.enabled`](broken-reference)

Whether to enable the beans endpoint.

`true`

[`management.endpoint.caches.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.caches.enabled`](broken-reference)

Whether to enable the caches endpoint.

`true`

[`management.endpoint.conditions.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.conditions.enabled`](broken-reference)

Whether to enable the conditions endpoint.

`true`

[`management.endpoint.configprops.additional-keys-to-sanitize`](broken-reference)

Keys that should be sanitized in addition to those already configured. Keys can be simple strings that the property ends with or regular expressions.

[`management.endpoint.configprops.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.configprops.enabled`](broken-reference)

Whether to enable the configprops endpoint.

`true`

[`management.endpoint.configprops.keys-to-sanitize`](broken-reference)

Keys that should be sanitized. Keys can be simple strings that the property ends with or regular expressions.

`[password, secret, key, token, .*credentials.*, vcap_services, sun.java.command]`

[`management.endpoint.env.additional-keys-to-sanitize`](broken-reference)

Keys that should be sanitized in addition to those already configured. Keys can be simple strings that the property ends with or regular expressions.

[`management.endpoint.env.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.env.enabled`](broken-reference)

Whether to enable the env endpoint.

`true`

[`management.endpoint.env.keys-to-sanitize`](broken-reference)

Keys that should be sanitized. Keys can be simple strings that the property ends with or regular expressions.

`[password, secret, key, token, .*credentials.*, vcap_services, sun.java.command]`

[`management.endpoint.flyway.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.flyway.enabled`](broken-reference)

Whether to enable the flyway endpoint.

`true`

[`management.endpoint.health.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.health.enabled`](broken-reference)

Whether to enable the health endpoint.

`true`

[`management.endpoint.health.group.*`](broken-reference)

Health endpoint groups.

[`management.endpoint.health.probes.enabled`](broken-reference)

Whether to enable liveness and readiness probes.

`false`

[`management.endpoint.health.roles`](broken-reference)

Roles used to determine whether or not a user is authorized to be shown details. When empty, all authenticated users are authorized.

[`management.endpoint.health.show-components`](broken-reference)

When to show components. If not specified the 'show-details' setting will be used.

[`management.endpoint.health.show-details`](broken-reference)

When to show full health details.

`never`

[`management.endpoint.health.status.http-mapping.*`](broken-reference)

Mapping of health statuses to HTTP status codes. By default, registered health statuses map to sensible defaults (for example, UP maps to 200).

[`management.endpoint.health.status.order`](broken-reference)

Comma-separated list of health statuses in order of severity.

`[DOWN, OUT_OF_SERVICE, UP, UNKNOWN]`

[`management.endpoint.heapdump.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.heapdump.enabled`](broken-reference)

Whether to enable the heapdump endpoint.

`true`

[`management.endpoint.httptrace.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.httptrace.enabled`](broken-reference)

Whether to enable the httptrace endpoint.

`true`

[`management.endpoint.info.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.info.enabled`](broken-reference)

Whether to enable the info endpoint.

`true`

[`management.endpoint.integrationgraph.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.integrationgraph.enabled`](broken-reference)

Whether to enable the integrationgraph endpoint.

`true`

[`management.endpoint.jolokia.config.*`](broken-reference)

Jolokia settings. Refer to the documentation of Jolokia for more details.

[`management.endpoint.jolokia.enabled`](broken-reference)

Whether to enable the jolokia endpoint.

`true`

[`management.endpoint.liquibase.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.liquibase.enabled`](broken-reference)

Whether to enable the liquibase endpoint.

`true`

[`management.endpoint.logfile.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.logfile.enabled`](broken-reference)

Whether to enable the logfile endpoint.

`true`

[`management.endpoint.logfile.external-file`](broken-reference)

External Logfile to be accessed. Can be used if the logfile is written by output redirect and not by the logging system itself.

[`management.endpoint.loggers.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.loggers.enabled`](broken-reference)

Whether to enable the loggers endpoint.

`true`

[`management.endpoint.mappings.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.mappings.enabled`](broken-reference)

Whether to enable the mappings endpoint.

`true`

[`management.endpoint.metrics.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.metrics.enabled`](broken-reference)

Whether to enable the metrics endpoint.

`true`

[`management.endpoint.prometheus.enabled`](broken-reference)

Whether to enable the prometheus endpoint.

`true`

[`management.endpoint.quartz.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.quartz.enabled`](broken-reference)

Whether to enable the quartz endpoint.

`true`

[`management.endpoint.scheduledtasks.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.scheduledtasks.enabled`](broken-reference)

Whether to enable the scheduledtasks endpoint.

`true`

[`management.endpoint.sessions.enabled`](broken-reference)

Whether to enable the sessions endpoint.

`true`

[`management.endpoint.shutdown.enabled`](broken-reference)

Whether to enable the shutdown endpoint.

`false`

[`management.endpoint.startup.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.startup.enabled`](broken-reference)

Whether to enable the startup endpoint.

`true`

[`management.endpoint.threaddump.cache.time-to-live`](broken-reference)

Maximum time that a response can be cached.

`0ms`

[`management.endpoint.threaddump.enabled`](broken-reference)

Whether to enable the threaddump endpoint.

`true`

[`management.endpoints.enabled-by-default`](broken-reference)

Whether to enable or disable all endpoints by default.

[`management.endpoints.jmx.domain`](broken-reference)

Endpoints JMX domain name. Fallback to 'spring.jmx.default-domain' if set.

`org.springframework.boot`

[`management.endpoints.jmx.exposure.exclude`](broken-reference)

Endpoint IDs that should be excluded or '\*' for all.

[`management.endpoints.jmx.exposure.include`](broken-reference)

Endpoint IDs that should be included or '\*' for all.

`*`

[`management.endpoints.jmx.static-names`](broken-reference)

Additional static properties to append to all ObjectNames of MBeans representing Endpoints.

[`management.endpoints.migrate-legacy-ids`](broken-reference)

Whether to transparently migrate legacy endpoint IDs.

`false`

[`management.endpoints.web.base-path`](broken-reference)

Base path for Web endpoints. Relative to the servlet context path (server.servlet.context-path) or WebFlux base path (spring.webflux.base-path) when the management server is sharing the main server port. Relative to the management server base path (management.server.base-path) when a separate management server port (management.server.port) is configured.

`/actuator`

[`management.endpoints.web.cors.allow-credentials`](broken-reference)

Whether credentials are supported. When not set, credentials are not supported.

[`management.endpoints.web.cors.allowed-headers`](broken-reference)

Comma-separated list of headers to allow in a request. '\*' allows all headers.

[`management.endpoints.web.cors.allowed-methods`](broken-reference)

Comma-separated list of methods to allow. '\*' allows all methods. When not set, defaults to GET.

[`management.endpoints.web.cors.allowed-origin-patterns`](broken-reference)

Comma-separated list of origin patterns to allow. Unlike allowed origins which only supports '\*', origin patterns are more flexible (for example 'https://\*.example.com') and can be used when credentials are allowed. When no allowed origin patterns or allowed origins are set, CORS support is disabled.

[`management.endpoints.web.cors.allowed-origins`](broken-reference)

Comma-separated list of origins to allow. '\*' allows all origins. When credentials are allowed, '\*' cannot be used and origin patterns should be configured instead. When no allowed origins or allowed origin patterns are set, CORS support is disabled.

[`management.endpoints.web.cors.exposed-headers`](broken-reference)

Comma-separated list of headers to include in a response.

[`management.endpoints.web.cors.max-age`](broken-reference)

How long the response from a pre-flight request can be cached by clients. If a duration suffix is not specified, seconds will be used.

`1800s`

[`management.endpoints.web.discovery.enabled`](broken-reference)

Whether the discovery page is enabled.

`true`

[`management.endpoints.web.exposure.exclude`](broken-reference)

Endpoint IDs that should be excluded or '\*' for all.

[`management.endpoints.web.exposure.include`](broken-reference)

Endpoint IDs that should be included or '\*' for all.

`[health]`

[`management.endpoints.web.path-mapping.*`](broken-reference)

Mapping between endpoint IDs and the path that should expose them.

[`management.health.cassandra.enabled`](broken-reference)

Whether to enable Cassandra health check.

`true`

[`management.health.couchbase.enabled`](broken-reference)

Whether to enable Couchbase health check.

`true`

[`management.health.db.enabled`](broken-reference)

Whether to enable database health check.

`true`

[`management.health.db.ignore-routing-data-sources`](broken-reference)

Whether to ignore AbstractRoutingDataSources when creating database health indicators.

`false`

[`management.health.defaults.enabled`](broken-reference)

Whether to enable default health indicators.

`true`

[`management.health.diskspace.enabled`](broken-reference)

Whether to enable disk space health check.

`true`

[`management.health.diskspace.path`](broken-reference)

Path used to compute the available disk space.

[`management.health.diskspace.threshold`](broken-reference)

Minimum disk space that should be available.

`10MB`

[`management.health.elasticsearch.enabled`](broken-reference)

Whether to enable Elasticsearch health check.

`true`

[`management.health.influxdb.enabled`](broken-reference)

Whether to enable InfluxDB health check.

`true`

[`management.health.jms.enabled`](broken-reference)

Whether to enable JMS health check.

`true`

[`management.health.ldap.enabled`](broken-reference)

Whether to enable LDAP health check.

`true`

[`management.health.livenessstate.enabled`](broken-reference)

Whether to enable liveness state health check.

`false`

[`management.health.mail.enabled`](broken-reference)

Whether to enable Mail health check.

`true`

[`management.health.mongo.enabled`](broken-reference)

Whether to enable MongoDB health check.

`true`

[`management.health.neo4j.enabled`](broken-reference)

Whether to enable Neo4j health check.

`true`

[`management.health.ping.enabled`](broken-reference)

Whether to enable ping health check.

`true`

[`management.health.rabbit.enabled`](broken-reference)

Whether to enable RabbitMQ health check.

`true`

[`management.health.readinessstate.enabled`](broken-reference)

Whether to enable readiness state health check.

`false`

[`management.health.redis.enabled`](broken-reference)

Whether to enable Redis health check.

`true`

[`management.health.solr.enabled`](broken-reference)

Whether to enable Solr health check.

`true`

[`management.health.status.order`](broken-reference)

`[DOWN, OUT_OF_SERVICE, UP, UNKNOWN]`

[`management.info.build.enabled`](broken-reference)

Whether to enable build info.

`true`

[`management.info.defaults.enabled`](broken-reference)

Whether to enable default info contributors.

`true`

[`management.info.env.enabled`](broken-reference)

Whether to enable environment info.

`false`

[`management.info.git.enabled`](broken-reference)

Whether to enable git info.

`true`

[`management.info.git.mode`](broken-reference)

Mode to use to expose git information.

`simple`

[`management.info.java.enabled`](broken-reference)

Whether to enable Java info.

`false`

[`management.metrics.data.repository.autotime.enabled`](broken-reference)

`true`

[`management.metrics.data.repository.autotime.percentiles`](broken-reference)

[`management.metrics.data.repository.autotime.percentiles-histogram`](broken-reference)

`false`

[`management.metrics.data.repository.metric-name`](broken-reference)

Name of the metric for sent requests.

`spring.data.repository.invocations`

[`management.metrics.distribution.buffer-length.*`](broken-reference)

Number of histograms for meter IDs starting with the specified name to keep in the ring buffer. The longest match wins, the key \`all\` can also be used to configure all meters.

[`management.metrics.distribution.expiry.*`](broken-reference)

Maximum amount of time that samples for meter IDs starting with the specified name are accumulated to decaying distribution statistics before they are reset and rotated. The longest match wins, the key \`all\` can also be used to configure all meters.

[`management.metrics.distribution.maximum-expected-value.*`](broken-reference)

Maximum value that meter IDs starting with the specified name are expected to observe. The longest match wins. Values can be specified as a double or as a Duration value (for timer meters, defaulting to ms if no unit specified).

[`management.metrics.distribution.minimum-expected-value.*`](broken-reference)

Minimum value that meter IDs starting with the specified name are expected to observe. The longest match wins. Values can be specified as a double or as a Duration value (for timer meters, defaulting to ms if no unit specified).

[`management.metrics.distribution.percentiles.*`](broken-reference)

Specific computed non-aggregable percentiles to ship to the backend for meter IDs starting-with the specified name. The longest match wins, the key 'all' can also be used to configure all meters.

[`management.metrics.distribution.percentiles-histogram.*`](broken-reference)

Whether meter IDs starting with the specified name should publish percentile histograms. For monitoring systems that support aggregable percentile calculation based on a histogram, this can be set to true. For other systems, this has no effect. The longest match wins, the key 'all' can also be used to configure all meters.

[`management.metrics.distribution.slo.*`](broken-reference)

Specific service-level objective boundaries for meter IDs starting with the specified name. The longest match wins. Counters will be published for each specified boundary. Values can be specified as a double or as a Duration value (for timer meters, defaulting to ms if no unit specified).

[`management.metrics.enable.*`](broken-reference)

Whether meter IDs starting with the specified name should be enabled. The longest match wins, the key 'all' can also be used to configure all meters.

[`management.metrics.export.appoptics.api-token`](broken-reference)

AppOptics API token.

[`management.metrics.export.appoptics.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`500`

[`management.metrics.export.appoptics.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`5s`

[`management.metrics.export.appoptics.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.appoptics.floor-times`](broken-reference)

Whether to ship a floored time, useful when sending measurements from multiple hosts to align them on a given time boundary.

`false`

[`management.metrics.export.appoptics.host-tag`](broken-reference)

Tag that will be mapped to "@host" when shipping metrics to AppOptics.

`instance`

[`management.metrics.export.appoptics.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.appoptics.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.appoptics.uri`](broken-reference)

URI to ship metrics to.

`https://api.appoptics.com/v1/measurements`

[`management.metrics.export.atlas.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.atlas.config-refresh-frequency`](broken-reference)

Frequency for refreshing config settings from the LWC service.

`10s`

[`management.metrics.export.atlas.config-time-to-live`](broken-reference)

Time to live for subscriptions from the LWC service.

`150s`

[`management.metrics.export.atlas.config-uri`](broken-reference)

URI for the Atlas LWC endpoint to retrieve current subscriptions.

`http://localhost:7101/lwc/api/v1/expressions/local-dev`

[`management.metrics.export.atlas.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.atlas.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.atlas.eval-uri`](broken-reference)

URI for the Atlas LWC endpoint to evaluate the data for a subscription.

`http://localhost:7101/lwc/api/v1/evaluate`

[`management.metrics.export.atlas.lwc-enabled`](broken-reference)

Whether to enable streaming to Atlas LWC.

`false`

[`management.metrics.export.atlas.meter-time-to-live`](broken-reference)

Time to live for meters that do not have any activity. After this period the meter will be considered expired and will not get reported.

`15m`

[`management.metrics.export.atlas.num-threads`](broken-reference)

Number of threads to use with the metrics publishing scheduler.

`4`

[`management.metrics.export.atlas.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.atlas.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.atlas.uri`](broken-reference)

URI of the Atlas server.

`http://localhost:7101/api/v1/publish`

[`management.metrics.export.datadog.api-key`](broken-reference)

Datadog API key.

[`management.metrics.export.datadog.application-key`](broken-reference)

Datadog application key. Not strictly required, but improves the Datadog experience by sending meter descriptions, types, and base units to Datadog.

[`management.metrics.export.datadog.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.datadog.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.datadog.descriptions`](broken-reference)

Whether to publish descriptions metadata to Datadog. Turn this off to minimize the amount of metadata sent.

`true`

[`management.metrics.export.datadog.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.datadog.host-tag`](broken-reference)

Tag that will be mapped to "host" when shipping metrics to Datadog.

`instance`

[`management.metrics.export.datadog.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.datadog.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.datadog.uri`](broken-reference)

URI to ship metrics to. If you need to publish metrics to an internal proxy en-route to Datadog, you can define the location of the proxy with this.

`https://api.datadoghq.com`

[`management.metrics.export.defaults.enabled`](broken-reference)

Whether to enable default metrics exporters.

`true`

[`management.metrics.export.dynatrace.api-token`](broken-reference)

Dynatrace authentication token.

[`management.metrics.export.dynatrace.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.dynatrace.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.dynatrace.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.dynatrace.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.dynatrace.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.dynatrace.uri`](broken-reference)

URI to ship metrics to. Should be used for SaaS, self managed instances or to en-route through an internal proxy.

[`management.metrics.export.dynatrace.v1.device-id`](broken-reference)

ID of the custom device that is exporting metrics to Dynatrace.

[`management.metrics.export.dynatrace.v1.group`](broken-reference)

Group for exported metrics. Used to specify custom device group name in the Dynatrace UI.

[`management.metrics.export.dynatrace.v1.technology-type`](broken-reference)

Technology type for exported metrics. Used to group metrics under a logical technology name in the Dynatrace UI.

`java`

[`management.metrics.export.dynatrace.v2.default-dimensions.*`](broken-reference)

Default dimensions that are added to all metrics in the form of key-value pairs. These are overwritten by Micrometer tags if they use the same key.

[`management.metrics.export.dynatrace.v2.enrich-with-dynatrace-metadata`](broken-reference)

Whether to enable Dynatrace metadata export.

`true`

[`management.metrics.export.dynatrace.v2.metric-key-prefix`](broken-reference)

Prefix string that is added to all exported metrics.

[`management.metrics.export.elastic.api-key-credentials`](broken-reference)

Base64-encoded credentials string. Mutually exclusive with user-name and password.

[`management.metrics.export.elastic.auto-create-index`](broken-reference)

Whether to create the index automatically if it does not exist.

`true`

[`management.metrics.export.elastic.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.elastic.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.elastic.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.elastic.host`](broken-reference)

Host to export metrics to.

`http://localhost:9200`

[`management.metrics.export.elastic.index`](broken-reference)

Index to export metrics to.

`micrometer-metrics`

[`management.metrics.export.elastic.index-date-format`](broken-reference)

Index date format used for rolling indices. Appended to the index name.

`yyyy-MM`

[`management.metrics.export.elastic.index-date-separator`](broken-reference)

Prefix to separate the index name from the date format used for rolling indices.

`-`

[`management.metrics.export.elastic.password`](broken-reference)

Login password of the Elastic server. Mutually exclusive with api-key-credentials.

[`management.metrics.export.elastic.pipeline`](broken-reference)

Ingest pipeline name. By default, events are not pre-processed.

[`management.metrics.export.elastic.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.elastic.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.elastic.timestamp-field-name`](broken-reference)

Name of the timestamp field.

`@timestamp`

[`management.metrics.export.elastic.user-name`](broken-reference)

Login user of the Elastic server. Mutually exclusive with api-key-credentials.

[`management.metrics.export.ganglia.addressing-mode`](broken-reference)

UDP addressing mode, either unicast or multicast.

`multicast`

[`management.metrics.export.ganglia.duration-units`](broken-reference)

Base time unit used to report durations.

`milliseconds`

[`management.metrics.export.ganglia.enabled`](broken-reference)

Whether exporting of metrics to Ganglia is enabled.

`true`

[`management.metrics.export.ganglia.host`](broken-reference)

Host of the Ganglia server to receive exported metrics.

`localhost`

[`management.metrics.export.ganglia.port`](broken-reference)

Port of the Ganglia server to receive exported metrics.

`8649`

[`management.metrics.export.ganglia.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.ganglia.time-to-live`](broken-reference)

Time to live for metrics on Ganglia. Set the multi-cast Time-To-Live to be one greater than the number of hops (routers) between the hosts.

`1`

[`management.metrics.export.graphite.duration-units`](broken-reference)

Base time unit used to report durations.

`milliseconds`

[`management.metrics.export.graphite.enabled`](broken-reference)

Whether exporting of metrics to Graphite is enabled.

`true`

[`management.metrics.export.graphite.graphite-tags-enabled`](broken-reference)

Whether Graphite tags should be used, as opposed to a hierarchical naming convention. Enabled by default unless "tagsAsPrefix" is set.

[`management.metrics.export.graphite.host`](broken-reference)

Host of the Graphite server to receive exported metrics.

`localhost`

[`management.metrics.export.graphite.port`](broken-reference)

Port of the Graphite server to receive exported metrics.

`2004`

[`management.metrics.export.graphite.protocol`](broken-reference)

Protocol to use while shipping data to Graphite.

`pickled`

[`management.metrics.export.graphite.rate-units`](broken-reference)

Base time unit used to report rates.

`seconds`

[`management.metrics.export.graphite.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.graphite.tags-as-prefix`](broken-reference)

For the hierarchical naming convention, turn the specified tag keys into part of the metric prefix. Ignored if "graphiteTagsEnabled" is true.

`[]`

[`management.metrics.export.humio.api-token`](broken-reference)

Humio API token.

[`management.metrics.export.humio.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.humio.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`5s`

[`management.metrics.export.humio.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.humio.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.humio.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.humio.tags.*`](broken-reference)

Humio tags describing the data source in which metrics will be stored. Humio tags are a distinct concept from Micrometer's tags. Micrometer's tags are used to divide metrics along dimensional boundaries.

[`management.metrics.export.humio.uri`](broken-reference)

URI to ship metrics to. If you need to publish metrics to an internal proxy en-route to Humio, you can define the location of the proxy with this.

`https://cloud.humio.com`

[`management.metrics.export.influx.api-version`](broken-reference)

API version of InfluxDB to use. Defaults to 'v1' unless an org is configured. If an org is configured, defaults to 'v2'.

[`management.metrics.export.influx.auto-create-db`](broken-reference)

Whether to create the Influx database if it does not exist before attempting to publish metrics to it. InfluxDB v1 only.

`true`

[`management.metrics.export.influx.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.influx.bucket`](broken-reference)

Bucket for metrics. Use either the bucket name or ID. Defaults to the value of the db property if not set. InfluxDB v2 only.

[`management.metrics.export.influx.compressed`](broken-reference)

Whether to enable GZIP compression of metrics batches published to Influx.

`true`

[`management.metrics.export.influx.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.influx.consistency`](broken-reference)

Write consistency for each point.

`one`

[`management.metrics.export.influx.db`](broken-reference)

Database to send metrics to. InfluxDB v1 only.

`mydb`

[`management.metrics.export.influx.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.influx.org`](broken-reference)

Org to write metrics to. InfluxDB v2 only.

[`management.metrics.export.influx.password`](broken-reference)

Login password of the Influx server. InfluxDB v1 only.

[`management.metrics.export.influx.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.influx.retention-duration`](broken-reference)

Time period for which Influx should retain data in the current database. For instance 7d, check the influx documentation for more details on the duration format. InfluxDB v1 only.

[`management.metrics.export.influx.retention-policy`](broken-reference)

Retention policy to use (Influx writes to the DEFAULT retention policy if one is not specified). InfluxDB v1 only.

[`management.metrics.export.influx.retention-replication-factor`](broken-reference)

How many copies of the data are stored in the cluster. Must be 1 for a single node instance. InfluxDB v1 only.

[`management.metrics.export.influx.retention-shard-duration`](broken-reference)

Time range covered by a shard group. For instance 2w, check the influx documentation for more details on the duration format. InfluxDB v1 only.

[`management.metrics.export.influx.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.influx.token`](broken-reference)

Authentication token to use with calls to the InfluxDB backend. For InfluxDB v1, the Bearer scheme is used. For v2, the Token scheme is used.

[`management.metrics.export.influx.uri`](broken-reference)

URI of the Influx server.

`http://localhost:8086`

[`management.metrics.export.influx.user-name`](broken-reference)

Login user of the Influx server. InfluxDB v1 only.

[`management.metrics.export.jmx.domain`](broken-reference)

Metrics JMX domain name.

`metrics`

[`management.metrics.export.jmx.enabled`](broken-reference)

Whether exporting of metrics to JMX is enabled.

`true`

[`management.metrics.export.jmx.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.kairos.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.kairos.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.kairos.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.kairos.password`](broken-reference)

Login password of the KairosDB server.

[`management.metrics.export.kairos.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.kairos.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.kairos.uri`](broken-reference)

URI of the KairosDB server.

`http://localhost:8080/api/v1/datapoints`

[`management.metrics.export.kairos.user-name`](broken-reference)

Login user of the KairosDB server.

[`management.metrics.export.newrelic.account-id`](broken-reference)

New Relic account ID.

[`management.metrics.export.newrelic.api-key`](broken-reference)

New Relic API key.

[`management.metrics.export.newrelic.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.newrelic.client-provider-type`](broken-reference)

Client provider type to use.

[`management.metrics.export.newrelic.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.newrelic.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.newrelic.event-type`](broken-reference)

The event type that should be published. This property will be ignored if 'meter-name-event-type-enabled' is set to 'true'.

`SpringBootSample`

[`management.metrics.export.newrelic.meter-name-event-type-enabled`](broken-reference)

Whether to send the meter name as the event type instead of using the 'event-type' configuration property value. Can be set to 'true' if New Relic guidelines are not being followed or event types consistent with previous Spring Boot releases are required.

`false`

[`management.metrics.export.newrelic.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.newrelic.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.newrelic.uri`](broken-reference)

URI to ship metrics to.

`https://insights-collector.newrelic.com`

[`management.metrics.export.prometheus.descriptions`](broken-reference)

Whether to enable publishing descriptions as part of the scrape payload to Prometheus. Turn this off to minimize the amount of data sent on each scrape.

`true`

[`management.metrics.export.prometheus.enabled`](broken-reference)

Whether exporting of metrics to Prometheus is enabled.

`true`

[`management.metrics.export.prometheus.histogram-flavor`](broken-reference)

Histogram type for backing DistributionSummary and Timer.

`prometheus`

[`management.metrics.export.prometheus.pushgateway.base-url`](broken-reference)

Base URL for the Pushgateway.

`http://localhost:9091`

[`management.metrics.export.prometheus.pushgateway.enabled`](broken-reference)

Enable publishing via a Prometheus Pushgateway.

`false`

[`management.metrics.export.prometheus.pushgateway.grouping-key.*`](broken-reference)

Grouping key for the pushed metrics.

[`management.metrics.export.prometheus.pushgateway.job`](broken-reference)

Job identifier for this application instance.

[`management.metrics.export.prometheus.pushgateway.password`](broken-reference)

Login password of the Prometheus Pushgateway.

[`management.metrics.export.prometheus.pushgateway.push-rate`](broken-reference)

Frequency with which to push metrics.

`1m`

[`management.metrics.export.prometheus.pushgateway.shutdown-operation`](broken-reference)

Operation that should be performed on shutdown.

`none`

[`management.metrics.export.prometheus.pushgateway.username`](broken-reference)

Login user of the Prometheus Pushgateway.

[`management.metrics.export.prometheus.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.signalfx.access-token`](broken-reference)

SignalFX access token.

[`management.metrics.export.signalfx.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.signalfx.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.signalfx.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.signalfx.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.signalfx.source`](broken-reference)

Uniquely identifies the app instance that is publishing metrics to SignalFx. Defaults to the local host name.

[`management.metrics.export.signalfx.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`10s`

[`management.metrics.export.signalfx.uri`](broken-reference)

URI to ship metrics to.

`https://ingest.signalfx.com`

[`management.metrics.export.simple.enabled`](broken-reference)

Whether, in the absence of any other exporter, exporting of metrics to an in-memory backend is enabled.

`true`

[`management.metrics.export.simple.mode`](broken-reference)

Counting mode.

`cumulative`

[`management.metrics.export.simple.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.stackdriver.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.stackdriver.connect-timeout`](broken-reference)

Connection timeout for requests to this backend.

`1s`

[`management.metrics.export.stackdriver.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.stackdriver.project-id`](broken-reference)

Identifier of the Google Cloud project to monitor.

[`management.metrics.export.stackdriver.read-timeout`](broken-reference)

Read timeout for requests to this backend.

`10s`

[`management.metrics.export.stackdriver.resource-labels.*`](broken-reference)

Monitored resource's labels.

[`management.metrics.export.stackdriver.resource-type`](broken-reference)

Monitored resource type.

`global`

[`management.metrics.export.stackdriver.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.stackdriver.use-semantic-metric-types`](broken-reference)

Whether to use semantically correct metric types. When false, counter metrics are published as the GAUGE MetricKind. When true, counter metrics are published as the CUMULATIVE MetricKind.

`false`

[`management.metrics.export.statsd.enabled`](broken-reference)

Whether exporting of metrics to StatsD is enabled.

`true`

[`management.metrics.export.statsd.flavor`](broken-reference)

StatsD line protocol to use.

`datadog`

[`management.metrics.export.statsd.host`](broken-reference)

Host of the StatsD server to receive exported metrics.

`localhost`

[`management.metrics.export.statsd.max-packet-length`](broken-reference)

Total length of a single payload should be kept within your network's MTU.

`1400`

[`management.metrics.export.statsd.polling-frequency`](broken-reference)

How often gauges will be polled. When a gauge is polled, its value is recalculated and if the value has changed (or publishUnchangedMeters is true), it is sent to the StatsD server.

`10s`

[`management.metrics.export.statsd.port`](broken-reference)

Port of the StatsD server to receive exported metrics.

`8125`

[`management.metrics.export.statsd.protocol`](broken-reference)

Protocol of the StatsD server to receive exported metrics.

`udp`

[`management.metrics.export.statsd.publish-unchanged-meters`](broken-reference)

Whether to send unchanged meters to the StatsD server.

`true`

[`management.metrics.export.wavefront.api-token`](broken-reference)

API token used when publishing metrics directly to the Wavefront API host.

[`management.metrics.export.wavefront.batch-size`](broken-reference)

Number of measurements per request to use for this backend. If more measurements are found, then multiple requests will be made.

`10000`

[`management.metrics.export.wavefront.enabled`](broken-reference)

Whether exporting of metrics to this backend is enabled.

`true`

[`management.metrics.export.wavefront.global-prefix`](broken-reference)

Global prefix to separate metrics originating from this app's white box instrumentation from those originating from other Wavefront integrations when viewed in the Wavefront UI.

[`management.metrics.export.wavefront.sender.flush-interval`](broken-reference)

`1s`

[`management.metrics.export.wavefront.sender.max-queue-size`](broken-reference)

`50000`

[`management.metrics.export.wavefront.sender.message-size`](broken-reference)

[`management.metrics.export.wavefront.source`](broken-reference)

Unique identifier for the app instance that is the source of metrics being published to Wavefront. Defaults to the local host name.

[`management.metrics.export.wavefront.step`](broken-reference)

Step size (i.e. reporting frequency) to use.

`1m`

[`management.metrics.export.wavefront.uri`](broken-reference)

URI to ship metrics to.

`https://longboard.wavefront.com`

[`management.metrics.mongo.command.enabled`](broken-reference)

Whether to enable Mongo client command metrics.

`true`

[`management.metrics.mongo.connectionpool.enabled`](broken-reference)

Whether to enable Mongo connection pool metrics.

`true`

[`management.metrics.system.diskspace.paths`](broken-reference)

Comma-separated list of paths to report disk metrics for.

`[.]`

[`management.metrics.tags.*`](broken-reference)

Common tags that are applied to every meter.

[`management.metrics.use-global-registry`](broken-reference)

Whether auto-configured MeterRegistry implementations should be bound to the global static registry on Metrics. For testing, set this to 'false' to maximize test independence.

`true`

[`management.metrics.web.client.max-uri-tags`](broken-reference)

Maximum number of unique URI tag values allowed. After the max number of tag values is reached, metrics with additional tag values are denied by filter.

`100`

[`management.metrics.web.client.request.autotime.enabled`](broken-reference)

Whether to automatically time web client requests.

`true`

[`management.metrics.web.client.request.autotime.percentiles`](broken-reference)

Computed non-aggregable percentiles to publish.

[`management.metrics.web.client.request.autotime.percentiles-histogram`](broken-reference)

Whether percentile histograms should be published.

`false`

[`management.metrics.web.client.request.metric-name`](broken-reference)

Name of the metric for sent requests.

`http.client.requests`

[`management.metrics.web.server.max-uri-tags`](broken-reference)

Maximum number of unique URI tag values allowed. After the max number of tag values is reached, metrics with additional tag values are denied by filter.

`100`

[`management.metrics.web.server.request.autotime.enabled`](broken-reference)

Whether to automatically time web server requests.

`true`

[`management.metrics.web.server.request.autotime.percentiles`](broken-reference)

Computed non-aggregable percentiles to publish.

[`management.metrics.web.server.request.autotime.percentiles-histogram`](broken-reference)

Whether percentile histograms should be published.

`false`

[`management.metrics.web.server.request.ignore-trailing-slash`](broken-reference)

Whether the trailing slash should be ignored when recording metrics.

`true`

[`management.metrics.web.server.request.metric-name`](broken-reference)

Name of the metric for received requests.

`http.server.requests`

[`management.server.add-application-context-header`](broken-reference)

Add the "X-Application-Context" HTTP header in each response.

`false`

[`management.server.address`](broken-reference)

Network address to which the management endpoints should bind. Requires a custom management.server.port.

[`management.server.base-path`](broken-reference)

Management endpoint base path (for instance, '/management'). Requires a custom management.server.port.

[`management.server.port`](broken-reference)

Management endpoint HTTP port (uses the same port as the application by default). Configure a different port to use management-specific SSL.

[`management.server.ssl.ciphers`](broken-reference)

Supported SSL ciphers.

[`management.server.ssl.client-auth`](broken-reference)

Client authentication mode. Requires a trust store.

[`management.server.ssl.enabled`](broken-reference)

Whether to enable SSL support.

`true`

[`management.server.ssl.enabled-protocols`](broken-reference)

Enabled SSL protocols.

[`management.server.ssl.key-alias`](broken-reference)

Alias that identifies the key in the key store.

[`management.server.ssl.key-password`](broken-reference)

Password used to access the key in the key store.

[`management.server.ssl.key-store`](broken-reference)

Path to the key store that holds the SSL certificate (typically a jks file).

[`management.server.ssl.key-store-password`](broken-reference)

Password used to access the key store.

[`management.server.ssl.key-store-provider`](broken-reference)

Provider for the key store.

[`management.server.ssl.key-store-type`](broken-reference)

Type of the key store.

[`management.server.ssl.protocol`](broken-reference)

SSL protocol to use.

`TLS`

[`management.server.ssl.trust-store`](broken-reference)

Trust store that holds SSL certificates.

[`management.server.ssl.trust-store-password`](broken-reference)

Password used to access the trust store.

[`management.server.ssl.trust-store-provider`](broken-reference)

Provider for the trust store.

[`management.server.ssl.trust-store-type`](broken-reference)

Type of the trust store.

[`management.trace.http.enabled`](broken-reference)

Whether to enable HTTP request-response tracing.

`true`

[`management.trace.http.include`](broken-reference)

Items to be included in the trace. Defaults to request headers (excluding Authorization and Cookie), response headers (excluding Set-Cookie), and time taken.

`[request-headers, response-headers, errors]`
