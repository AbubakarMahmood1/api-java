# Requirements
- The web API shall have a mean time between failures (MTBF) of at least 30 days under normal operating conditions.
- The web API shall continue to provide service with no more than 1% of requests failing, even in the presence of simulated faults (e.g., server crashes or network failures).
- The web API shall have a documented and tested disaster recovery plan, with a recovery time objective (RTO) of 4 hours in the event of a catastrophic failure.
- The web API shall implement comprehensive monitoring with alerts for critical system metrics (e.g., response time, error rates), and the operations team shall acknowledge and respond to alerts within 15 minutes.
- The web API shall have a rollback mechanism for deployments, allowing for the quick and reliable rollback to a previous version in case of unexpected issues.
- The web API shall maintain data integrity with a checksum mechanism, ensuring that data corruption is detected and prevented.
- The web API shall gracefully degrade functionality during peak loads, ensuring that essential services remain available even when the system is under stress.
- The web API shall incorporate redundant components for critical services, with automatic failover mechanisms in place.
- The development team shall regularly review system reliability metrics, aiming for a 2% month-over-month improvement in key reliability indicators.
- The web API shall provide advance notification of planned downtime to users and stakeholders, with a minimum notice period of 48 hours.


# # Reference(s)
- https://landing.google.com/sre/sre-book/toc/
- https://www.iso.org/standard/35733.html
- https://csrc.nist.gov/publications/detail/sp/800-160/vol-2/final