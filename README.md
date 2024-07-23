# AliceBob-CaseStudy
Test technique dans le cadre de la mission de "System and Network Engineer"

1. Create a Docker container that runs a nginx server over HTTP. The server must be available from outside the container, and serve the content of a directory that is situated outside of the container.
2. Add one or several containers to monitor the nginx container (RAM, CPU, storage, etc.). You can choose the monitoring tools you prefer. The point is to simulate an infrastructure with several nodes.
3. Add another container that will proxy the content of the nginx server over HTTPS. You can use a self-signed certificate.
4. Add SSH access to the monitoring container (or one of them, if you have several), and modify the sshd configuration for optimal security.
