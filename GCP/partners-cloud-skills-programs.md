GCP links



* Google Compute Engine
* Virtual Private Cloud
* Cloud Logging
* Cloud Monitoring
* Networking
* Cloud Shell
* Cloud IAM
* Cloud SDK
* Google Cloud Storage
* Cloud Identity
* Load Balancing
* Resource Manager
* Deployment Manager
* Google Kubernetes Engine

https://docs.google.com/document/d/1oUbxxhSsRLsps6JCZ-qo5lMEF0Q6FbiLfs77F1p0afo/edit

ACE - Reference Links

https://googlecourses.qwiklabs.com/course_templates/67
https://googlecourses.qwiklabs.com/course_templates/38
https://cloud.google.com/free/docs/aws-azure-gcp-service-comparison


The Cloud Girl ○ https://github.com/priyankavergadia/GCPSketchnote ● Developer Cheat Sheet ○ https://googlecloudcheatsheet.withgoogle.com/ ● Google Cloud product list ○ https://cloud.google.com/terms/services ● 21 products explained in under 2 minutes ○ https://cloud.google.com/blog/topics/inside-google-cloud/21-google-clo ud-tools-each-explained-under-2-minutes


2 gcloud compute zones list
3 gcloud compute zones list | grep us-central1
4 gcloud config set compute/zone us-central1-b
5 gcloud compute instances --help
6 gcloud compute instances create myvm2 --machine-type="n1-standard-1" --image-project "debian-cloud" --image-family "debian-10" --subnet "default"

Lab Reference
1 - compute engine
https://partner.cloudskillsboost.google/catalog_lab/1154
1 - launch instance CLI
https://partner.cloudskillsboost.google/catalog_lab/320
1 - attach disk
https://partner.cloudskillsboost.google/catalog_lab/559


gcloud compute instances create gcelab --zone us-central1-c
2 gcloud compute disks create mydisk --size=100GB --zone us-central1-c
3 gcloud compute disks create --help
4 history
5 gcloud compute instances attach-disk gcelab --disk mydisk --zone us-central1-c
6 gcloud compute ssh gcelab
7 gcloud compute instances attach-disk gcelab --disk mydisk --zone us-central1-c
8 gcloud compute ssh gcelab
9 history
10 gcloud compute disk --help
11 gcloud compute disks --help
12 gcloud compute disks list


Linux commands for formatting
lsblk
3 ls -l /dev/disk/by-id/
4 sudo mkfs.ext4 -F -E lazy_itable_init=0,lazy_journal_init=0,discard /dev/disk/by-id/scsi-0Google_PersistentDisk_persistent-disk-1
5 sudo mkdir /mnt/mydisk
6 sudo vi /etc/fstab
7 cat /etc/fstab
8 sudo mount -a

1-Autoscaling with cloud monitoring
https://partner.cloudskillsboost.google/catalog_lab/756

Slide 2 VPC
2 - VPC
https://partner.cloudskillsboost.google/catalog_lab/1030

2-VPC Peering
https://partner.cloudskillsboost.google/catalog_lab/935



Challenge Lab –Firewall → https://partner.cloudskillsboost.google/catalog_lab/2728

VPN - https://partner.cloudskillsboost.google/catalog_lab/620


Cross Region LB : https://partner.cloudskillsboost.google/catalog_lab/805


Autoscaling + LB https://partner.cloudskillsboost.google/catalog_lab/2139

===
Tasks
Create an Internal Load Balancer
https://partner.cloudskillsboost.google/focuses/11632?catalog_rank=%7B%22rank%22%3A2%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=16809788


HTTP Load Balancer with Cloud Armor
https://partner.cloudskillsboost.google/focuses/11633?catalog_rank=%7B%22rank%22%3A1%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog

Network Tiers - Optimizing Network Spend
https://partner.cloudskillsboost.google/focuses/11629?parent=catalog


===

CDN : https://cloud.google.com/media-cdn/docs/choose-cdn-product

LoadBalancer : https://cloud.google.com/load-balancing/docs/choosing-load-balancer

Cloud Nat : https://partner.cloudskillsboost.google/focuses/42431?catalog_rank=%7B%22rank%22%3A2%2C%22num_filters%22%3A1%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=22970106


Cloud DNS :
https://partner.cloudskillsboost.google/focuses/16369?catalog_rank=%7B%22rank%22%3A1%2C%22num_filters%22%3A1%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=22970116

Cloud Logging : https://partner.cloudskillsboost.google/catalog_lab/2587


GKE – >https://partner.cloudskillsboost.google/catalog_lab/911

Statefulsets → https://partner.cloudskillsboost.google/catalog_lab/327

Hpa.yml
apiVersion: autoscaling/v1
kind: HorizontalPodAutoscaler
metadata:
creationTimestamp: null
name: php-apache
spec:
maxReplicas: 10
minReplicas: 1
scaleTargetRef:
apiVersion: apps/v1
kind: Deployment
name: php-apache
targetCPUUtilizationPercentage: 50
status:
currentReplicas: 0
desiredReplicas: 0
 Example Cloud RUN -> https://partner.cloudskillsboost.google/catalog_lab/3390

Cloud RUN Challenge - https://partner.cloudskillsboost.google/quests/152

==
Cloud FUnctions
==
https://partner.cloudskillsboost.google/catalog_lab/924
===
App Engine : https://partner.cloudskillsboost.google/catalog_lab/698


Note : Demo Object Storage and Classes (Req. by Shrinivas)

Cloud SQL https://partner.cloudskillsboost.google/catalog_lab/925



Cloud Spanner : https://partner.cloudskillsboost.google/catalog_lab/930

Firestore : https://partner.cloudskillsboost.google/catalog_lab/2163
 Extra : https://partner.cloudskillsboost.google/catalog_lab/2166

Video Firestore : https://www.youtube.com/watch?v=KVRxsRPhmoo

BigTable : https://partner.cloudskillsboost.google/catalog_lab/712

Big Query : https://lh3.googleusercontent.com/7wH2NXrrzsSYdBNwepEeuW7mc-ZeSNaADVT-D5KDMje96iQYF4-QeH9z7lTWBnZ3_2jBQSEYoIkl=e14-rw-lo-sc0xffffff-w953


IAM : https://partner.cloudskillsboost.google/catalog_lab/686

IAM Custom Role - https://partner.cloudskillsboost.google/focuses/11638?catalog_rank=%7B%22rank%22%3A2%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=22354365


Service Account : https://partner.cloudskillsboost.google/catalog_lab/956


Bastion : https://partner.cloudskillsboost.google/catalog_lab/1389
