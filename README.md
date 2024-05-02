# prerequisite ----> K8 cluster & deployment.yaml & sevice.yaml & ns 
# custom public  docker images
# git pubic repo
# git bash ----> Branch ---->main---->dev-----
# Pull request to merge changes form dev to main  branch
# Create new NS using ns.yaml 
# k8s-agrocd -deployment
# https://github.com/argoproj/argo-cd/releases
# kubectl create namespace argocd
# kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v2.11.0-rc2/manifests/install.yaml
# gitbash - kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
# kubectl port-forward svc/argocd-server -n argocd 8080:443
 
