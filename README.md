## End to End Machine Learning Project
#AWS Deployment

docker build -t testdockergshah.azurecr.io/mltest:latest .

docker login testdockergshah.azurecr.io # Container registry

docker push testdockergshah.azurecr.io/mltest:latest
