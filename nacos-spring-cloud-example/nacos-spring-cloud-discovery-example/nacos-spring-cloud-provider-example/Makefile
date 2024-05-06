

NacosImg:=docker.io/hefabao/springboot-nacosprivider:v0.1


deploy:
	-kubectl delete -f k8s.yaml
	kubectl apply -f k8s.yaml


all:
	-mvn clean compile package
	docker build -t ${NacosImg} .
