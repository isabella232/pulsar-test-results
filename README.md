# Pulsar Test Results

This repository stores the test results from candidate and official builds of Apache Pulsar. For candidate builds, testing
is done using Docker images built based on the candidate release tag. For official builds, the tests are run against
the official Docker images released by the project. For testing done on forked repositories, the GitHub tag and Docker Hub images references are
indicated.

## Test Plan Template

The tests are run primarily against Docker images running in Kubernetes to simulate a real production environment with
multiple copies brokers, bookies, etc to find issues that cannot be found in unit tests or when running in 
standalone mode. 

The following is the test plan template that we use for each release:

[Test Plan Template](https://github.com/kafkaesque-io/pulsar-test-results/blob/master/pulsar-test-plan.md)

We strive to continually expand and improve this test plan to ensure the highest quality releases of Apache Pulsar. Comments and suggestions are welcome.

## Results

### Apache Pulsar 2.5.1 Candidate 4

* Repository: [apache/pulsar](https://github.com/apache/pulsar)
* Tag: v2.5.1-candidate-4
* Docker Images: [kafkaesqueio/pulsar-all-v2.5.1-candidate-4](https://hub.docker.com/repository/docker/kafkaesqueio/pulsar-all-v2.5.1-candidate-4)
* Results: [v2.5.1-candidate-4](https://github.com/kafkaesque-io/pulsar-test-results/blob/master/results-apache-pulsar-v2.5.1-candidate-4.md)

### Apache Pulsar 2.5.2_kesque_2

* Repository: [kafkaesque-io/pulsar](https://github.com/kafkaesque-io/pulsar)
* Tag: 2.5.2_kesque_2
* Docker Images: [kafkaesqueio/pulsar-all](https://hub.docker.com/repository/docker/kafkaesqueio/pulsar-all)
* Results: [2.5.2_kesque_2](https://github.com/kafkaesque-io/pulsar-test-results/blob/master/results-apache-pulsar-2.5.2_kesque-2.md)


