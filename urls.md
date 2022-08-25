URL01 (Git repo): `https://github.com/ty-codes/autodeploy-ci-cd-pipeline/tree/master`  
URL02 (S3 bucket): `http://udapeoplefrontend742256c.s3-website-us-east-1.amazonaws.com/#/employees`  
URL03 (CloudFront Frontend URL - blue): `d256fx48ch9zf2.cloudfront.net/#/employees`  
URL04 (deployed application backend in EC2):  `ec2-54-227-118-65.compute-1.amazonaws.com:3030`
URL05 (Prometheus server):  `ec2-52-91-24-69.compute-1.amazonaws.com:9090`  

SCREENSHOT01 (job failed because of compile errors): ![](assets/SCREENSHOT01.png)  
SCREENSHOT02 (job failed because of unit tests): ![](assets/SCREENSHOT02.png)  
SCREENSHOT03 (job failed because of vulnerable packages): ![](assets/SCREENSHOT03.png)  
SCREENSHOT04 (Alert from failed build): ![](assets/SCREENSHOT04.png) ![](assets/SCREENSHOT04_slack.png)  
SCREENSHOT05 (Infrastructure creation job failure): ![](assets/SCREENSHOT05.png)  
SCREENSHOT06 (Smoke test job failure): ![](assets/SCREENSHOT06.png)  
SCREENSHOT07 (Failed smoke test rollback): ![](assets/SCREENSHOT07.png)  
SCREENSHOT08 (Promotion job success): ![](assets/SCREENSHOT08.png)  
SCREENSHOT09 (Cleanup job success): ![](assets/SCREENSHOT09.png)  
SCREENSHOT10 (Deploy filtered to master branch only): ![](assets/SCREENSHOT10.png)  
SCREENSHOT11_cpu_usage (Graph of EC2 instance including available mem, disk space and CPU usage): ![](assets/SCREENSHOT11_cpu_usage.png)  
SCREENSHOT11_disk_usage (Graph of EC2 instance including available mem, disk space and CPU usage): ![](assets/SCREENSHOT11_disk_usage.png)
SCREENSHOT11_memory (Graph of EC2 instance including available mem, disk space and CPU usage): ![](assets/SCREENSHOT11_memory.png)
SCREENSHOT12b (Screenshot of alert sent by Prometheus): ![](assets/SCREENSHOT12b.png)  
URL02_SCREENSHOT (S3 Static bucket): ![](assets/URL03_SCREENSHOT.png) 
URL03_SCREENSHOT (Cloudfront Distribution): ![](assets/URL03_SCREENSHOT.png)  
URL04_SCREENSHOT (Prometheus Server): ![](assets/URL04_SCREENSHOT.png)  
URL05_SCREENSHOT (Prometheus server UP): ![](assets/URL05_SCREENSHOT.png)  