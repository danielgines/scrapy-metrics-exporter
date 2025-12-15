# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2025-12-15

### Added
- Initial release of scrapy-metrics-exporter
- Real-time metrics collection via Scrapy signals
- Automatic export of all numeric Scrapy stats
- HTTP server on port 9410 with /metrics endpoint
- Support for custom metrics via Scrapy stats API
- Prometheus/OpenMetrics format export
- Counters for items scraped/dropped, requests, and responses
- Gauges for pending and active requests
- Dynamic metric creation without configuration
- Comprehensive documentation with Google Style docstrings

### Features
- Zero configuration required for basic usage
- Automatic collection of all Scrapy stats
- Real-time counters via signals
- Periodic stats updates (configurable interval)
- Support for custom pipeline and spider metrics
- Non-blocking operation (metrics failures don't affect spider)

[0.1.0]: https://github.com/danielgines/scrapy-metrics-exporter/releases/tag/v0.1.0
