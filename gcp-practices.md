## 1. Always skip resource creation is default VPC
```
IAM & Admin -> Organization Policies -> Search -> Skip default network creation
```

With the above changes no default vpcs will be created.


## 2. Reserved IP address by google in CIDR
```
10.1.2.0/24   - **CIDR**  -  256 is allowed - But only 254 is available
10.1.2.0      - First IP reservered
10.1.2.1      - Second IP reservered
10.1.2.254    - Second to last is reserved
10.1.2.255    - Last is also reserved
```

## 3. Types of VPC
```
1. **Default VPC-** Created by the GCP with VPC and single subnet
2. **Auto VPC-** Default VPC with subnet regions with **/20** with some firewall rules
3. **Custom VPC-** No Subnet and IP ranges are also flexible
```
