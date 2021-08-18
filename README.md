# TBC
რა უნდა შევასრულოთ : 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/tbc.png)


როგორ შევასრულე :

ვაყენებთ ოფიციალური ფეიჯიდან ლინუქსზე minikube, kubectl... ვუშვებთ ბრძანებას minikube start(რომელიც ქმნის Nodes) 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-1.JPG)
  
ვაყენებთ NGINX ს 

შევქმენი deployment.yaml ფაილი Nginx ის დაყენებისთვის, შევქმენი services.yaml დეფლოიმენთ ფაილი ქსელის კონფიგისთვის და შევქმენი size.yaml ფაილი სივრცის გამოსაყოფად(Provisioning) (სრული კონფიგი შეგიძლიათ ნახოთ GITHUB/TBC/deployments) 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-2.JPG)




Helm Chart Deployment... დავაყენე Helm შევქმენი deployment ფაილები values.yaml, Chart.yaml და deployment-helm.yaml(სრული კონფიგურაცია შეგიძლიათ ნახოთ GITHUB/TBC/deployments/Chart) ისევ ვაყენებთ nginx ს....

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/helmchart.JPG)

