# AWS_Course
AWS Notes

## Virtualization - virtual machines

* Virtualization is the process of creating multiple simulated environments or virtual machines from a single physical hardwae system, enabling more efficient resource use.

<img width="817" height="405" alt="Screenshot 2026-07-02 175924" src="https://github.com/user-attachments/assets/1099fa0a-260a-4d01-9cfa-c97b8f6a7aec" />

<img width="817" height="405" alt="Screenshot 2026-07-02 180001" src="https://github.com/user-attachments/assets/996d5599-797d-4338-84ad-23071c23bde5" />

<img width="817" height="405" alt="Screenshot 2026-07-02 180027" src="https://github.com/user-attachments/assets/ec8db2f2-eae7-4b75-a59e-ce16007623d7" />

## But how to setup the virtualization?

* Layer Hypervisor
  
<img width="817" height="405" alt="Screenshot 2026-07-02 180131" src="https://github.com/user-attachments/assets/c3956cc9-6845-44e0-b4a9-21c9a5ef9459" />

<img width="817" height="405" alt="Screenshot 2026-07-02 180231" src="https://github.com/user-attachments/assets/eff60481-e024-4f03-85c9-d872adb0e788" />

* Ex :- hypervisor is *oracle virtual box*.

## How Hypervisor works?

 * Virtual box share hardware resources from Host OS.
 * Separate set of virtual CPU, RAM, storage etc.
 * VMs are fully isolated (independent of hosted OS)

   <img width="817" height="405" alt="Screenshot 2026-07-02 180552" src="https://github.com/user-attachments/assets/68e4230c-ad25-445c-8e36-6cc653e730d4" />

### Benefits of VMs :

* We don't need new resources to use different OS.
* No risk of any issues with your primary key.
* testing any app on different OS. 

<img width="817" height="405" alt="Screenshot 2026-07-02 180634" src="https://github.com/user-attachments/assets/d9c6eacd-2dac-4678-ac20-bc4852b75a47" />

## Types of Hypervisor :

1. Type 1(Bare matel)
2. Type 2(Hosted 

<img width="817" height="405" alt="Screenshot 2026-07-02 180957" src="https://github.com/user-attachments/assets/2e1ef408-16f2-4580-b33a-e76cd4f5db78" />

### Type 1 (Bare matel)

* Those which get installed directly on the hardware and there will be same functionality of building different virtual machines by sharing the resources, but difference is that there will be no host OS present they will be directly setting it up on the hardware.

* Question might arise like without operating system how it can be installed..
* The answer is - the hyperviser which act as a mini os which has all the basic requirements that is required for the hardware for the setup is already existing in the hyperviser.

<img width="817" height="405" alt="Screenshot 2026-07-02 181314" src="https://github.com/user-attachments/assets/48781a0e-7a77-4d19-afee-697d27fb7cfd" />

<img width="817" height="405" alt="Screenshot 2026-07-02 182110" src="https://github.com/user-attachments/assets/cbddb444-f94e-4457-a289-ebabaf8ec161" />

### Type 2 (Hosted)

* It is called hosted because it works on top of host or primary systems like oracle virtual box in the image
<img width="817" height="405" alt="Screenshot 2026-07-02 181030" src="https://github.com/user-attachments/assets/dbd9a916-21f0-4891-ad1a-b9d4ce1f4ec3" />

### Why do companies use virtualization?

* Cheap
* Reduces :
     * workload
     * space
     * energy
* Easy backup using snapshot
* Easy recovery

# Cloud Computing 

### Cloud Computing : 

* On demand delivery of IT resources over the internet with pay-as-you-go pricing..
* Access computing resources(like servers, storage, dtabases, and software) over the internet, rather than owing and ,aintaining physical hardware.

* Many Companies provide cloud computing platform like:
  
<img width="817" height="405" alt="Screenshot 2026-07-02 183408" src="https://github.com/user-attachments/assets/b01447f9-96f2-4059-ba24-917b36fdb895" />

* Virtualization is the process of creating multiple simulated environments or virtual machines from a single physical hardwae system, enabling more efficient resource use.

###  Types of cloud computing :

  1. IaaS 
  2. PaaS
  3. SaaS

### 1. IaaS (Infrastructure as a service) 

<img width="817" height="405" alt="Screenshot 2026-07-02 183950" src="https://github.com/user-attachments/assets/e3597dc6-21c9-4b6c-ad12-5e9d915f98cd" />

* *Ex- icecream shop*

<img width="817" height="405" alt="Screenshot 2026-07-02 184105" src="https://github.com/user-attachments/assets/72516bef-5871-4911-bb6f-7d9cc8c53889" />

### 2. PaaS (Platform as a service)

<img width="817" height="405" alt="Screenshot 2026-07-02 184207" src="https://github.com/user-attachments/assets/e0fae57a-c6f1-4037-b588-ff52ea940fe1" />

* *Ex- icecream shop*
  
<img width="817" height="405" alt="Screenshot 2026-07-02 184306" src="https://github.com/user-attachments/assets/ad715c90-663c-4828-84ba-929800c55ed9" />

### 3. SaaS (Software as a service)

<img width="817" height="405" alt="Screenshot 2026-07-02 184355" src="https://github.com/user-attachments/assets/a3e552e1-e232-445b-be90-a68cf5981b13" />

* *Ex- icecream shop*
  
<img width="817" height="405" alt="Screenshot 2026-07-02 184539" src="https://github.com/user-attachments/assets/7243d393-3567-4f1c-a6f5-6ecd03b1eeb1" />

* Different types of cloud deployments :

    1. Public cloud,
    2.  Private cloud, and
    3.  Hybrid cloud. 

1. **Public Cloud :** A shared cloud environment where multiple users can access services over the internet, like AWS or Azure.
   
2. **Private Cloud :** A dedicated cloud environment for one organization, offering more control and privacy.

3. **Hybrid Cloud :** A mix of public and private clouds, allowing data and applications to move between them for flexibility. 

### * Few Features commonly offered by cloud providers :

1. Compute services
2. Storage services
3. Database services
4. Networking services
5. Container services
6. Serverless Computing
7. Machine Learning services
8. Identity and access management(IAM)
9. Monitoring and logging
10. Content Delivery Network (CDN)
11. Backup and Compliance Tools
12. Virtual Private Cloud(VPC)
13. Data Analytics services
14. API Management
