# K8s-BAZA
Overview
This repository contains the necessary steps and configurations to set up a Kubernetes cluster in Yandex Cloud and synchronize it with a virtual machine acting as the master node. The instructions provided here will guide you through the entire process, from creating the cluster to configuring your local environment to interact with it.

Prerequisites
Before you begin, ensure you have the following:

A Yandex Cloud account.
kubectl installed on your local machine.
yc (Yandex Cloud CLI) installed and configured.
A virtual machine in Yandex Cloud to act as the master node.
![Screenshot from 2025-01-19 11-50-08](https://github.com/user-attachments/assets/a6342cfe-cb04-4c00-835c-56643dba65d9)
![Screenshot from 2025-01-19 11-49-53](https://github.com/user-attachments/assets/37d40ef5-e3d4-43c2-87b4-4bab0e14f149)
Pods Deployment Scaling
![Screenshot from 2025-01-20 19-26-59](https://github.com/user-attachments/assets/434d5a9e-007e-48f6-8c7b-68d6de550bcf)
![Screenshot from 2025-01-20 19-27-15](https://github.com/user-attachments/assets/4fdb01de-3e19-43f4-97ce-ada66328cd37)
![Screenshot from 2025-01-20 19-28-00](https://github.com/user-attachments/assets/b26731b0-e653-42d7-bff0-64011361f694)
![Screenshot from 2025-01-20 19-33-16](https://github.com/user-attachments/assets/66e2a589-fb3a-4aa3-9186-431046302425)
Horizontal pod autoscalling CPU-percent=80
![Screenshot from 2025-01-20 19-43-41](https://github.com/user-attachments/assets/bc699b28-da78-4d5f-b2aa-fc4e93a34695)
Deployment rollout 
![Screenshot from 2025-01-20 19-53-44](https://github.com/user-attachments/assets/a3bbdb5a-207c-474b-b90c-a2846eabe873)
Manifest-file replicas
![Screenshot from 2025-01-20 20-03-27](https://github.com/user-attachments/assets/abf27251-4408-4836-aae9-82d2d17d19e5)
Replicas results
![Screenshot from 2025-01-20 20-07-16](https://github.com/user-attachments/assets/46dca57c-14a8-40ba-ae74-3e8a1f748ea6)
Deployment , 2pods ,services - LoadBalancer,Multiservice....
![Screenshot from 2025-01-22 14-06-43](https://github.com/user-attachments/assets/e991ccd3-2c16-430f-b68c-6f20b934c0ba)
![Screenshot from 2025-01-22 14-06-34](https://github.com/user-attachments/assets/91699313-8b37-4140-960f-f0712c49d485)
![Screenshot from 2025-01-22 14-06-16](https://github.com/user-attachments/assets/f8082ba6-4b5d-4834-ba90-282aff121c30)
![Screenshot from 2025-01-22 14-05-58](https://github.com/user-attachments/assets/9bc258c6-df04-41f7-8713-5cf3f0e686a2)
![Screenshot from 2025-01-22 14-05-40](https://github.com/user-attachments/assets/1ecfccfe-e638-4920-b834-77b0ebc4cb0f)
