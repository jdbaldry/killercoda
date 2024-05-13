![Loki Quickstart](../../assets/loki-ile.png)


# "What is Loki" Sandbox Enviroment

[![What is Loki](https://img.youtube.com/vi/1uk8LtQqsZQ/0.jpg)](https://www.youtube.com/watch?v=1uk8LtQqsZQ)

## Sandbox Overview

This online sandbox is part of the How to get started with Loki video. In this sandbox, you will learn how to use Grafana Loki in monolithic store and query your logs. Here is a run through of the architecture:

* **Loki**: Loki is a horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. It is designed to be very cost-effective and easy to operate. It does not index the contents of the logs, but rather a set of labels for each log stream.

* **Alloy**: Alloy the new Otel Collector created by Grafana Labs. It is a new way to collect, process, and ship logs, metrics and traces. We will be using Alloy to collect logs from our application.

* **Carnivorous Greenhouse**: Carnivorous Greenhouse is a simple application that generates logs. This allows users to create an account, login and collect metrics from a series of hungry plants. All of these actions generate logs that are sent to Loki. The application can also be toggled to generate errors.

* **Grafana**: Ofcourse the architecture would not be complete without Grafana. Grafana will be used to visualize the logs generated by the Carnivorous Greenhouse application. We will be making use of a new feature in Grafana 11 called Explore Logs.

## Housekeeping

This environment runs an install script on startup automatically. Your training environment is ready to go once the script has completed and you see the following message:

```plaintext
WHAT IS LOKI?
```

Continue to the next step to find the tutorial environment navigation URLs.

## Reporting Issues
If you encounter any issues with the environment, please report them to the [GitHub repository](https://github.com/grafana/killercoda)