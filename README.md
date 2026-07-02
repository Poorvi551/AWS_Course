# AWS_Course
AWS Notes

## Virtualization - virtual machines

<img width="924" height="509" alt="Screenshot 2026-07-02 175924" src="https://github.com/user-attachments/assets/1099fa0a-260a-4d01-9cfa-c97b8f6a7aec" />

<img width="926" height="507" alt="Screenshot 2026-07-02 180001" src="https://github.com/user-attachments/assets/996d5599-797d-4338-84ad-23071c23bde5" />

<img width="917" height="505" alt="Screenshot 2026-07-02 180027" src="https://github.com/user-attachments/assets/ec8db2f2-eae7-4b75-a59e-ce16007623d7" />

## But how to setup the virtualization?

* Layer Hypervisor
  <img width="927" height="501" alt="Screenshot 2026-07-02 180131" src="https://github.com/user-attachments/assets/c3956cc9-6845-44e0-b4a9-21c9a5ef9459" />

<img width="923" height="494" alt="Screenshot 2026-07-02 180231" src="https://github.com/user-attachments/assets/eff60481-e024-4f03-85c9-d872adb0e788" />

* Ex :- hypervisor is *oracle virtual box*.

## How Hypervisor works?

 * Virtual box share hardware resources from Host OS.
 * Separate set of virtual CPU, RAM, storage etc.
 * VMs are fully isolated (independent of hosted OS)

   <img width="926" height="520" alt="Screenshot 2026-07-02 180552" src="https://github.com/user-attachments/assets/68e4230c-ad25-445c-8e36-6cc653e730d4" />

### Benefits of VMs :

* We don't need new resources to use different OS.
* No risk of any issues with your primary key.
* testing any app on different OS. 

<img width="933" height="511" alt="Screenshot 2026-07-02 180634" src="https://github.com/user-attachments/assets/d9c6eacd-2dac-4678-ac20-bc4852b75a47" />

## Types of Hypervisor :

1. Type 1(Bare matel)
2. Type 2(Hosted 

<img width="927" height="509" alt="Screenshot 2026-07-02 180957" src="https://github.com/user-attachments/assets/2e1ef408-16f2-4580-b33a-e76cd4f5db78" />

### Type 1 (Bare matel)

* Those which get installed directly on the hardware and there will be same functionality of building different virtual machines by sharing the resources, but difference is that there will be no host OS present they will be directly setting it up on the hardware.

* Question might arise like without operating system how it can be installed..
* The answer is - the hyperviser which act as a mini os which has all the basic requirements that is required for the hardware for the setup is already existing in the hyperviser.

<img width="923" height="489" alt="Screenshot 2026-07-02 181314" src="https://github.com/user-attachments/assets/48781a0e-7a77-4d19-afee-697d27fb7cfd" />

<img width="912" height="516" alt="Screenshot 2026-07-02 182110" src="https://github.com/user-attachments/assets/cbddb444-f94e-4457-a289-ebabaf8ec161" />

### Type 2 (Hosted)

* It is called hosted because it works on top of host or primary systems like oracle virtual box in the image
<img width="919" height="493" alt="Screenshot 2026-07-02 181030" src="https://github.com/user-attachments/assets/dbd9a916-21f0-4891-ad1a-b9d4ce1f4ec3" />

### Why do companies use virtualization?

* Cheap
* Reduces :
     * workload
     * space
     * energy
* Easy backup using snapshot
* Easy recovery

## Cloud Computing 

