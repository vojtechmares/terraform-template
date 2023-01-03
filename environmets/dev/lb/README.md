# env / dev / lb

Static load balancer for Kubernetes cluster. Use labels (DigitalOcean & Hetzner Cloud) or Target Groups (AWS) to target nodes/subnets.

If you are using Kubernetes Ingress Controller for a given cloud which provisions it's own `Service` with `spec.type: LoadBalancer`, this root module is not necessary.
