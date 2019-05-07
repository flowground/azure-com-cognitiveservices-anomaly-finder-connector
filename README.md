# ![LOGO](logo.png) Anomaly Finder Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Anomaly Finder Client API (version 2.0).

Generated from: https://api.apis.guru/v2/specs/azure.com/cognitiveservices-AnomalyFinder/2.0/swagger.json<br/>
Generated at: 2019-05-07T17:37:42+03:00

## API Description

The Anomaly Finder API detects anomalies automatically in time series data. It supports two functionalities, one is for detecting the whole series with model trained by the timeseries, another is detecting last point with model trained by points before. By using this service, business customers can discover incidents and establish a logic flow for root cause analysis.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Find anomalies for the entire series in batch.

> The operation will generate a model using the entire series, each point will be detected with the same model. In this method, points before and after a certain point will be used to determine whether it's an anomaly. The entire detection can give user an overall status of the time series.

### Detect anomaly status of the latest point in time series.

> The operation will generate a model using points before the latest one, In this method, only history points are used for determine whether the target point is an anomaly. Latest point detecting matches the scenario of real-time monitoring of business metrics.

## License

**flow**ground :- Telekom iPaaS / azure-com-cognitiveservices-anomaly-finder-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
