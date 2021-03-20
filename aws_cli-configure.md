# AWS CLI

- [Configuration basics](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html)

### Linux install 
```bash
$curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
$unzip awscliv2.zip
$sudo ./aws/install
```


```bash
[root@localhost opt]# aws configure
AWS Access Key ID [None]: AKIARBESE5J***I3P7
AWS Secret Access Key [None]: +tq0tqlYxXasv5ddff6XEMLZVkffasweGssGQDBA****
Default region name [None]: 
Default output format [None]: yaml

[root@localhost opt]# aws s3 cp logstash-7.10.1-linux-aarch64.tar.gz s3://awsaccresssca002
upload: ./logstash-7.10.1-linux-aarch64.tar.gz to s3://awsaccresssca002/logstash-7.10.1-linux-aarch64.tar.gz
[root@localhost opt]# aws s3 ls 
2021-03-20 13:20:18 awsaccresssca002

[root@localhost opt]# aws s3 ls awsaccresssca002
2021-03-20 13:28:19  348009216 logstash-7.10.1-linux-aarch64.tar.gz
2021-03-20 13:22:49        194 new_user_credentials.csv

```

