Solution contains 2 projects. One project is web hosted WebApi application, second project is self-hosted WebApi application.
Samples demonstrate how to send WebApi system traces to ApplicationInsights.
Open the solution and look for ITraceWriter interface implementation.
You can debug applications without providing correct instrumentation key: all telemetry will be available in the VS output
and Debugging Tools windows (last one is only for web-hosted application).
Note that most of default modules and telemetry initializers were removed from applicationInsights.configs because they are not important for this sample.
