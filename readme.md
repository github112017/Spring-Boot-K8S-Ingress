 # Usage
1. Run mvn clean install


2. Build Docker images for each module, like: `docker build -t medici/employee:1.1 `

3. In `/kubernetes` directory for each file : `kubectl apply -f <filename>.yaml` 

4. Run using skaffold docker run gcr.io/k8s-skaffold/skaffold:latest skaffold <<command>> 
 