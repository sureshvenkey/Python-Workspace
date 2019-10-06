# Configuring awscli credencials
Steps to configure aws credencials  
C:\Users\venkatraj\Desktop\boto3>pip install awscli --user  
C:\Users\venkatraj\Desktop\boto3>aws configure  
AWS Access Key ID [None]: XXXXXXXXXXXXXXXXXXXXXX  
AWS Secret Access Key [None]: XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX  
Default region name [None]: ap-south-1  
Default output format [None]: json  
C:\Users\venkatraj\Desktop\boto3>  

# Code  
Code Name | Description
----------|-------------
delete_ec2_unused_vol.py | Deletes unused volumes i.e. volume unassigned with any ec2 instance with no tags.
inventory_ec2_instances_and_volumes.py | Creates a inventory in the form of csv file for ec2 instance and volumes.
list_ec2_volumes_with_boto3_filters.py | How to use boto3 filter for tags
list_ec2_volumes_with_default_filters.py | How to use default filter for tags, helpfull in deleting volumes where key=value pair not matching tags.
tag_ec2_vol_csv.py | Tag volumes based on csv input file, csv file format, "Volume_ID","Key","Value" The script check whether same key=value pair available in in volume tags and tages volumes. If same key is available with change in value, then the script modifies the tag. 

# For more details
Mail me: sureshvenkey@gmail.com


