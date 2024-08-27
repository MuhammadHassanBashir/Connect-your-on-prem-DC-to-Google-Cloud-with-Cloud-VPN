# Connect-your-on-prem-DC-to-Google-Cloud-with-Cloud-VPN

Connect your on prem Data-center to google cloud vpn. And the vpn will connect to your google cloud vpc network, so the resource under vpc can have access of on-prem datacenter. In my case i would be using cloud run resource. Becasue my cloud run need to get access of on-prem data center. 

use the below link to configure **HA VPN** in google cloud. It is an advance and Highly available vpn. You can connect 2 ISP's static ip with it at the same time for making it highly available...

## Link For GCP HA VPN with vyro device

    https://blog.searce.com/connect-your-on-prem-dc-to-google-cloud-with-cloud-vpn-edc0bd27657d

## Link for GCP Classic VPN

    https://medium.com/@wilsonhsukdnhc/create-a-classic-vpn-between-on-premises-and-cloud-a594f8e732b1

## Link for GCP HA VPN with simulated on-prem environment(like on simple ubuntu machine)

    https://medium.com/@sruffilli/setting-up-a-simulated-on-prem-environment-for-gcp-90dcbb2d57f8

## Link for GCP HA VPN (VPC Networking: Cloud HA-VPN)

    In which we are basically connect 2 vpc having resoures with HA VPN..

    https://www.cloudskillsboost.google/focuses/6270?catalog_rank=%7B%22rank%22%3A2%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=35648090
