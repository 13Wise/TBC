# TBC
რა უნდა შევასრულოთ : 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/tbc.png)


როგორ შევასრულე :

 Kubernetes - დავაყენე შემდეგი ბრძანებებით(Windows):

  ვაყენებთ - VirtualBox
  
  ვაყენებთ - kubectl
  
  ვანეყებთ - minikube
  
  PowerShell - იდან ვუშვებთ ბრძანებას : minikube start --cpus=4 --memory=8gb --disk-size=20gb
  
  ორი Node ის დაყენებისთვის ვუშვებთ ბრძანებას : minikube start --nodes 2 -p multinode-test
  
  ![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/nodes.JPG)
  
  
ვაყენებთ NGINX ს 

შევქმენი deployment.yaml ფაილი Nginx ის დაყენებისთვის, შევქმენი services.yaml დეფლოიმენთ ფაილი ქსელის კონფიგისთვის და შევქმენი size.yaml ფაილი სივრცის გამოსაყოფად(Provisioning) (სრული კონფიგი შეგიძლიათ ნახოთ GITHUB/TBC/deployments) 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/deployments.JPG)



![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/pvc.JPG)


