# devops-project

commands to run 

docker build -t nikhilesh1402/devops-project . -f Dockerfile.app

docker push nikhilesh1402/devops-project

helm template Helm

helm upgrade --install devops-practical-app Helm

kubectl expose deployment web --type=NodePort --port=3000

minikube service devops-app-deploy --url
