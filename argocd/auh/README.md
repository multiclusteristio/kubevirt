to check ports

kubectl exec -n <ns> <pod> -- netstat -tuln 

ubectl exec -n <ns> <pod> -- ss -tuln