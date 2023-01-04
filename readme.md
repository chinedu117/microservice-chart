## Package chart
helm package charts/microservice

## Generate index
helm repo index --url https://chinedu117.github.io/microservice-chart .


## Install
helm repo add microservice-chart https://chinedu117.github.io/microservice-chart

then 

helm install microservice-chart/microservice -n NAMESPACE 