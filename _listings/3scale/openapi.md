swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3scale Service Management API
  description: the-api-for-managing-3scale-services-
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /stats/applications/{application_id}/usage.{format}:
    get:
      summary: Application Usage by Metric
      description: Application usage by metric.
      operationId: application_ops
      x-api-path-slug: statsapplicationsapplication-idusage-format-get
      parameters:
      - in: path
        name: application_id
        description: id of the application
      - in: path
        name: format
        description: Response format
      - in: query
        name: granularity
        description: Granularity of the results
      - in: query
        name: metric_name
        description: System name of metric for which to get data
      - in: query
        name: period
        description: 'Period, combined with since give the stats for the time range
          [since '
      - in: query
        name: provider_key
        description: Your api key with 3scale
      - in: query
        name: since
        description: Time range start
      - in: query
        name: skip_change
        description: Skip period over period calculations (setting this to true will
          increase the performance of the call)
      - in: query
        name: timezone
        description: Timezone to do the calculations in
      - in: query
        name: until
        description: Time range end
      responses:
        200:
          description: OK
      tags:
      - Application
      - Usage
      - By
      - Metric
  /stats/services/{service_id}/usage.{format}:
    get:
      summary: Service Usage by Metric
      description: Service usage by metric.
      operationId: service_ops
      x-api-path-slug: statsservicesservice-idusage-format-get
      parameters:
      - in: path
        name: format
        description: Response format
      - in: query
        name: granularity
        description: Granularity of the results
      - in: query
        name: metric_name
        description: System name of metric for which to get data
      - in: query
        name: period
        description: 'Period, combined with since give the stats for the time range
          [since '
      - in: query
        name: provider_key
        description: Your api key with 3scale
      - in: path
        name: service_id
        description: id of the service
      - in: query
        name: since
        description: Time range start
      - in: query
        name: skip_change
        description: Skip period over period calculations (setting this to true will
          increase the performance of the call)
      - in: query
        name: timezone
        description: Timezone to do the calculations in
      - in: query
        name: until
        description: Time range end
      responses:
        200:
          description: OK
      tags:
      - Service
      - Usage
      - By
      - Metric