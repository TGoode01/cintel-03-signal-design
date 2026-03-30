# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
The dataset includes system performance metrics with columns for requests, errors, and total latency in milliseconds. Each row represents a snapshot of system activity and performance.

### Signals
I used the original signals and added one new one:

- **error_rate** – percentage of failed requests
- **success_rate** – percentage of successful requests
- **avg_latency_ms** – average response time per request
- **throughput** – number of requests handled

### Experiments
I modified the original project by adding a new signal called **success_rate** to better understand system reliability. I also added a graph to visualize how latency and error rate change across observations.

### Results
The results showed that the system has a consistently low error rate and a high success rate. The graph also showed that as the number of requests increases, the average latency slightly increases.

### Interpretation
This means the system is reliable but may slow down under higher demand. From a business perspective, this insight helps identify when performance improvements may be needed to maintain a smooth user experience during peak usage.
