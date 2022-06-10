# Just Ran secured kafka without notes
ERROR [KafkaServer id=1] Fatal error during KafkaServer startup. Prepare to shutdown (kafka.server.KafkaServer)
org.apache.kafka.common.config.ConfigException: Invalid value javax.net.ssl.SSLHandshakeException: No available authentication scheme for configuration A client SSLEngine created with the provided settings can't connect to a server SSLEngine created with those settings.
	at org.apache.kafka.common.security.ssl.SslFactory.configure(SslFactory.java:100)