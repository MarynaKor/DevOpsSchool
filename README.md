# This is an excercise for working with Metrics.
Here is the full description of all the excercises.
- - -

Ex0 :  Expose all the metrics to .../actuator/prometheus.
       Setze alle Metriken auf den Endpunkt .../actuator/prometheus aus

Ex1 : Build a Conatiner for Prometheus, which can be reached through http://localhost:9090 and shows your applications metrics.
      Baue einen Container für Prometheus, der mit http://localhost:9090  abrufbar ist und die Metriken von dem vorherigen Endpunkt anzeigt.

Ex2 : Create your own Metric, which shows the functionality of the counter service application. (Suggestion: Create a metric for the iteration in the updating process)
      Erstelle eine eigene Metrik, die den fachliche Prozess des Counter Service abbildet. Eine Idee wäre die Iteration in der Aktualisierung Aufruf /overwrite/positions oder 
      /overwrite/projects zu nehmen.

Ex3 :  Based on the previous metric, create a rule in Prometheus, which shows that the iteration is only running through as many times as there are active projects.
       Anhand dieser Metrik erstelle eine Regel in Prometheus, mit der überprüft wird das die Schleife in einem bestimmten Zeitspanne nicht zu oft durchläuft.

Ex4 :
       Build another container for the Alertmanager.

       

