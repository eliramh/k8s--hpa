### K8S - practice

-------------

  Create deployment and autoscale by number of request in the last 30 seconds
  Write yourself the yaml files (practice)
   - Namespace
   - Deployment
   - Service
   - HPA


 Install Prometheus in your cluster


Add Prometheus HPA query based upon request. 
(you can test it with curl -v http://<ip>:port
		Prometheus query:
			sum(rate(http_server_requests_seconds_count[1m]))
