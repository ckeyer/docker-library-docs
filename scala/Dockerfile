FROM ckeyer/java:8-jre

RUN wget -O /tmp/scala.tgz http://downloads.typesafe.com/scala/2.11.7/scala-2.11.7.tgz && \
	cd /usr/local && \
	tar zxf /tmp/scala.tgz && \
	rm /tmp/scala.tgz && \
	mv scala-2.11.7 scala && \
	ln -s /usr/local/scala/bin/scala /usr/local/bin/scala && \
	ln -s /usr/local/scala/bin/scalac /usr/local/bin/scalac && \
	ln -s /usr/local/scala/bin/fsc /usr/local/bin/fsc && \
	ln -s /usr/local/scala/bin/scaladoc /usr/local/bin/scaladoc && \
	ln -s /usr/local/scala/bin/scalap /usr/local/bin/scalap && \
	cp scala/lib/* $JAVA_HOME/lib

ENV _SCALA_HOME=/usr/local/scala

