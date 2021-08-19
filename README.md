# TBC
რა უნდა შევასრულოთ : 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/tbc.png)


როგორ შევასრულე :

ვაყენებთ ოფიციალური ფეიჯიდან ლინუქსზე(ubuntu) minikube, kubectl... ვუშვებთ ბრძანებას minikube start(რომელიც ქმნის Nodes) 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-1.JPG)
  
ვაყენებთ NGINX ს 

შევქმენი deployment.yaml ფაილი Nginx ის დაყენებისთვის, შევქმენი services.yaml დეფლოიმენთ ფაილი ქსელის კონფიგისთვის და შევქმენი size.yaml ფაილი სივრცის გამოსაყოფად(Provisioning) (სრული კონფიგი შეგიძლიათ ნახოთ GITHUB/TBC/deployments) 

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-2.JPG)




Helm Chart Deployment... დავაყენე Helm შევქმენი deployment ფაილები values.yaml, Chart.yaml და deployment-helm.yaml(სრული კონფიგურაცია შეგიძლიათ ნახოთ GITHUB/TBC/deployments/Chart) ისევ ვაყენებთ nginx ს....

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-4-1.JPG)



დოკერი დაყენებულია, კონტეინერი გაშვებულია, მუშაობს...


![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-4.JPG)



helm ის დახმარებით ვაყენებთ prometheus-ს და grafana-ს...

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-10.JPG)


შემდეგ პრომეთეუსს ვუკეთებთ პორტ ფორვარდინგს და შევდივართ localhost:9090 ის მეშვეობით ბრაუზერიდან...

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-6.JPG)


ამის შემდეგ ტერმინალში ვაგენერირებთ გრაფანას ადმინის Random პაროლს ვაკეთებთ ისევ პორტ ფორვარდინგს და ბრაუზერიდან შევდივართ localhost:3000 ის მეშვეობით...

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-7.JPG)

შეგვყავს User: admin და პაროლი რომელიც დავაგენერირეთ ტერმინალში...

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-8.JPG)

გრაფანას და პრომეთეუსის დასაკავშირებლად Data Source-ში ვუთითებთ შიდა DNS, რომელიც მოგვცა სერვისმა რომელსაც უკავშირდება პრომეთეუსი...

ამის შემდეგ ვამატებთ Dashboard-ს გრაფანას პანელში...

![alt text](https://s3.eu-west-1.amazonaws.com/by.bucket-exadel/TBC-9.JPG)
