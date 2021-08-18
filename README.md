# TBC
რა უნდა შევასრულოთ : 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/tbc.png)


როგორ შევასრულე :

ვაყენებთ K3S-ს ბრძანებით : sudo curl -sfL https://get.k3s.io | sh -
  
ვაყენებთ NGINX ს 

შევქმენი deployment.yaml ფაილი Nginx ის დაყენებისთვის, შევქმენი services.yaml დეფლოიმენთ ფაილი ქსელის კონფიგისთვის და შევქმენი size.yaml ფაილი სივრცის გამოსაყოფად(Provisioning) (სრული კონფიგი შეგიძლიათ ნახოთ GITHUB/TBC/deployments) 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/deployments.JPG)



![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/pvc.JPG)



Helm Chart Deployment... დავაყენე Helm შევქმენი deployment ფაილები values.yaml, Chart.yaml და deployment-helm.yaml(სრული კონფიგურაცია შეგიძლიათ ნახოთ GITHUB/TBC/deployments/Chart) ისევ ვაყენებთ nginx ს....

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/helmchart.JPG)

