##CVE-2019-19781

###VERSION

10.5, 11.1, 12.0, 12.1, 13.0

1. Traversal to vpns folder, traversal in the NSC_HEADER  + http://newbm.pl to write a malicious bookmark to the /netscaler/portal/templates/ folder (1st HTTP request),
2. Passing that template through the Template Toolkit  (2nd  request)

### TOOLS

https://github.com/trustedsec/cve-2019-19781

### POC

![alt text](https://pbs.twimg.com/media/EN9bekfXUAER8m6?format=jpg&name=4096x4096)

![alt text](https://pbs.twimg.com/media/EN9beklX4AM4F5Y?format=jpg&name=4096x4096)

## REFERENCE

https://www.youtube.com/watch?v=v_qpiebydk4