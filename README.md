# k8s-set-multi-cluster

I wrote this tool to automate the process of setting up a kubernetes multlicluster using Kind.
While setting it up manually, I had to debug quite a few things back and forth. So this tool will set up a multiple kubernetes
"kind" and use kubefed as an orchestrator over the individual clusters.