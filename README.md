SCALA-Tuning-App
================

Example logstash, logstash-forwarder and kibana configurations for consuming various logs from a SCALA environment to help with tuning and optimizing a SCALA Log Analsyis solution

scala-unity-eif-receiver-logstash.conf

Example configuration for consuming the distributed EIF receiver logs (UnityEifReceiver_eif_inst_N.log), dealing with multilines, parsing into structured fields using grok and extracting metrics from within.

scala-unity-eif-receiver-logs.json

Example logstash-forwarder configuration for shipping the logs from distributed EIF receiver systems

SCALA EIF Receiver Tuning Kibana App-v1

A kibana dashboard showing key UnityEIFReceiver metrics such as batch size, number successful, number failed, total indexed volume, etc.
