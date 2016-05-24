# jmh-demo
JMH ist ein Werkzeug für das Durchführen von Microbenchmarks. Es ist generell davon abzuraten solche Benchmarks selber mit Schleife und Systemzeit zu messen, da hierbei viel unberücksichtigt bleibt. JMH ist von den OpenJdk-Entwicklern entworfen, daher kann man hier wohl davon ausgehen, dass in dem Framework entsprechendes Wissen über die JVM berücksichtigt wurde.

Dies ist ein kleines Beispiel-Projekt in dem zu Demonstrationszwecken einfach die Laufzeit der Summenbildung, Average- und Max-Ermittlung per Java 8 Streams gemessen wird.
Der Benchmark kann entweder Direkt aus der IDE heraus angestoßen werden über Aufruf der Main-Methode, in diesem Fall greifen die dort konfigurierten Optionen. Alternativ kann auch das Archiv benchmark.jar, welches durch den Build erzeugt wird, gestartet werden.
