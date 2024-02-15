z1.. **ISA** - (Instruction Set Architecture or simply Computer Architecture ) In computer science, an instruction set architecture (ISA), also called computer architecture, is an abstract model of a computer.

2.. **CISC** - (Complex Instruction Set Computer) The fundamental goal of CISC is that a single instruction will handle all evaluating, loading,
    and storing operations, similar to how a multiplication command will handle evaluating, loading, and storing data, which is why it’s complicated.
             __performance__

3.. **RISC** - The fundamental goal of RISC is to make hardware simpler by employing an instruction set that consists of only a few basic steps used for 
     evaluating, loading, and storing operations. A load command loads data but a store command stores data.
              __power__

4.. **ARM** - (Advanced RISC Machines) An Arm processor is one of a family of central processing units (CPUs) based
      on the reduced instruction set computer (RISC) architecture for computer processors. [Closed Source]

5.. **RISC-V** - RISC-V is an open standard instruction set architecture based on established reduced instruction set computer principles.
       Unlike most other ISA designs, RISC-V is provided under royalty-free open-source licenses. [Open Source]

6.. **Node** - A node is a point of intersection or connection within a network. In computing, a node can refer to a computer, device, 
              or component that is part of a larger network.

7.. **Peripherals** - when data are recieved from or delivered to to a device, that device is reffered to as peripherals

8.. **Cilium** - Cilium is a highly scalable Kubernetes Container Network Interface (CNI). It provides cloud-native networking connectivity, 
     security, and observability for container-based workloads, such as in Kubernetes and Docker. It provides visibility and control over network traffic, and offers advanced security features.

9.. **Proxmox** - Proxmox Virtual Environment (Proxmox VE) is an open-source server management platform for enterprise virtualization

10.. **XEN** - Xen is a free and open-source hypervisor that allows multiple operating systems to run on the same hardware at the same time. Xen inserts a virtualization layer between the 
    system hardware and the virtual machines. 
      Xen is a type-1 hypervisor, which means it can be installed directly on hardware without the need for a host operating system

11..  **SRAM** - Static random access memory is the that type of RAM that is fast, has more storage but less memory than DRAM. This type of RAM uses transistors
       instead of capacitors and stores cpu cache. The bits are stored in voltage and consumes less power and generates less heat. This has lower
        latency and high data transfer speed.

             {cache-}a hardware or software component that stores data so that future requests for that data can be served faster;
                      the data stored in a cache might be the result of an earlier computation or a copy of data stored elsewhere.

12.. **DRAM** - dynamic random access memory is the that type of RAM that is slower ,less costlier, has more greater memory access ,uses capacitors
                 has higher latency. These type of RAM uses capacitorsand stores bits in the form of electrical energy and has a greater latency
                  and uses more power and generates more heat.

13.. **DDR SDRAM** - Double data rate synchronous data random access memory class of memory integrated circuits used in computers. DDR SDRAM, also retroactively called 
                     DDR1 SDRAM, has been superseded by DDR2 SDRAM, DDR3 SDRAM, DDR4 SDRAM and DDR5 SDRAM.

14.. **GDDR SDRAM** - Graphics DDR SDRAM is a type of synchronous dynamic random-access memory specifically designed for applications requiring high 
                    bandwidth, e.g. graphics processing units. 

15.. **Kernal** - The kernel is a computer program at the core of a computer's operating system and generally has complete control over everything 
                  in the system. A kernel is the core component of an operating system. Using interprocess communication and system calls, 
                  it acts as a bridge between applications and the data processing performed at the hardware level.

16.. **API** - An application programming interface is a way for two or more computer programs to communicate with each other.
                      It is a type of software interface, offering a service to other pieces of software

17.. **Containers** - A container is a standard unit of software that packages up code and all its dependencies so 
             the application runs quickly and reliably from one computing

18.. **docker** - Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. 
                    . The software that hosts the containers is called Docker Engine.

19.. **kubernetes** (K8S)- Kubernetes is an open-source container orchestration system for automating software deployment, scaling, and management.


20.. **x86**- an x86 is a family of complex instruction set computer instruction set architectures initially developed by Intel.

21.. **ALU** - an arithmetic logic unit performs the computer's data processing functions

22.. **EDVAC** - Electronic Discrete Variable Computer

23.. **Compiler** -  a compiler is a computer program that translates computer code written in one programming language into another language.
                 This translate source code from a high-level programming language to a low-level programming language to create an executable program.
                  {Used in java,c++,Go,c#}

![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/08ebca98-b1f7-46a7-9f40-43a01eef23e7)


24.. **Interpreter** - an interpreter is a computer program that directly executes instructions written in a programming or scripting language, without requiring 
                    them previously to have been compiled into a machine language program.
                          {Used in python,java script, ruby}

25.. **Iteration** -  a sequence of instructions or code being repeated until a specific end result is achieved.

26.. **Iterables** - Iterable is an object which can be looped over or iterated over with the help of a for loop. Objects like lists, tuples, sets, dictionaries, strings, etc.
                     are called iterables. In short and simpler terms, iterable is anything that you can loop over.

27.. **Autoscaling**
- Manual scaling -update the size of auto scaling group(ASG)
- -  dynamic scaling - 
- - - simple step scaling - when a cloudwatch is triggered(examole cpu>70%), then add 2 units
                        - when a cloudwatch is triggered(CPU<30%) then remove 1 unit 
- - - target tracking scaling - the average ASG CPU to stay around 40%
- - - scheduled scaling - anticipate a scaling based on usage pattern
                       - increase the min capacity to 10 at 5am on fridays

28.. **Serverless** - refers to a way of building and running applications without needing to manage the underlying servers. Instead, developers focus solely on writing and deploying code. The cloud provider takes care of the infrastructure, scaling, and maintenance, allowing for faster development, automatic scaling based on demand, and cost savings because you only pay for the resources your code uses when it runs.

29.. **RAID** - Redundant Array of Independent Discs is a data storage virtualization technology that combines multiple physical disk drive components into one or more logical units for the purposes of data redundancy, performance improvement, or both.
- RAID 0 - **Mirroring** -
- RAID 1 - **Slicing** - writing one set of data in disc 1 and other in disc 2. This totally doubled the performance but the problem that arose wast that if one disc was damaged the other one was unreadable automatically.
- RAID 5 - Data and parity are striped evenly across all of the disks, so no single disk is a bottleneck. Striping also enables users to reconstruct data in case of a disk failure enabling both mirroring and slicing.
- RAID 6 - RAID 6 (Striping with Dual Distributed Parity) It is a data-striping process that utilizes two disks as a backup. The data is striped in the form of blocks and is stored across multiple partitions, including the backup disks. That way, it remains accessible even after two consecutive failures.
- RAID 10 - 
- - - - there are two types of RAID systems, first RAID 10(4 discs required) and second RAID 01 (also 4 discs)

30.. **IOPS** - (Input Output Processing per Second)

40.. **Redundancy** - a system design in which a component is duplicated so if it fails there will be a backup.

41.. **URL** - Unified Resource Locator - Address of an link

42.. **Vendor lock in** -  a situation where the cost of switching to a different vendor is so high that the customer is essentially stuck with the original vendor.

43.. **Round Robin** - Time slices are assigned to each process in equal portions and in circular order, handling all processes without priority. When using load balancers ,the load is simuntaneously distributed between the different instances. This is called round robin.

44.. **Source code management tool**- Source code management (SCM) is used to track modifications to a source code repository. SCM tracks a running history of changes to a code base and helps resolve conflicts when merging updates from multiple contributors. 

45.. **CI/CD**-:
- - - Continuous integration is the practice of integrating all your code changes into the main branch of a shared source code repository early and often, automatically testing each change when you commit or merge them, and automatically kicking off a build. With continuous integration, errors and security issues can be identified and fixed more easily, and much earlier in the development process.
- - - Continuous delivery is a software development practice that works in conjunction with CI to automate the infrastructure provisioning and application release process.Once code has been tested and built as part of the CI process, CD takes over during the final stages to ensure it's packaged with everything it needs to deploy to any environment at any time. CD can cover everything from provisioning the infrastructure to deploying the application to the testing or production environment.
    -  In Continuos deployment ,it involves automating the deployment process of successfully tested code to various environments (like testing, staging, or production). Continuous Deployment implies automatically deploying every successful change to production

46..**OCR(OPTICAL CHARACTER RECOGNITION)**- the electronic or mechanical conversion of images of typed, handwritten or printed text into machine-encoded text, whether from a scanned document, a photo of a document, a scene photo or from subtitle text superimposed on an image

47..**ACL** - Access Control List,contains rules that grant or deny access to certain digital environments.

48(a)..**IN-TRANSIT ENCRYPTION**- defends your data, after a connection is established and authenticated, against potential attackers by: Removing the need to trust the lower layers of the network which are commonly provided by third parties.

48(b)..**AT REST ENCRYPTION**- encryption that is used to help protect data that is stored on a disk (including solid-state drives) or backup media. What this basically does is , if there's a data and someone wants to access it, only would he be able to do that if he has the key for it i.e the data is stored and can only be accessed through decryption key

49.. **Q(*)**- [Qlearning(the ability of an ai to have choices and upon choosing the schoice,stepping into a different situation)+A*(it is an Search Algorithm that is a simple and efficient search algorithm that can be used to find the optimal path between two nodes in a graph.)]an alleged internal project by OpenAI dedicated to the application of artificial intelligence in logical and mathematical reasoning. Q-star is also considered as the reason why the founder and cfo of oopen ai Sam Altman was fired out f the company. This technology can help solving the mathematical problems that were previously impossible to solve . This technology has the capabilities to take humanity a further and more importantly a very huge step in the field of modernisation.This is like teaching an ai to be a quick learner and a good problem solver.

50..**A*algorithm**- A* is an informed search algorithm, or a best-first search, meaning that it is formulated in terms of weighted graphs: starting from a specific starting node of a graph, it aims to find a path to the given goal node having the smallest cost (least distance travelled, shortest time, etc.).

![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/50622a57-b0a5-443d-ac62-bc770cdadc6f)

51.. **IAM SERVICES**-Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access.

52..**Web Sockets**- a computer communications protocol, providing simultaneous two-way communication channels over a single Transmission Control Protocol (TCP) connection.
![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/9a317849-d559-45fe-81e4-e139f4a9a68c)

53..**SSL(SECURE SOCKET LAYER)**-an encryption-based Internet security protocol.a security protocol that creates an encrypted link between a web server and a web browser. Companies and organizations need to add SSL certificates to their websites to secure online transactions and keep customer information private and secure.[HACKING]

54..**TSL(TRANSPORT SECURITY LAYER)**-

55.. **Network Port**- A network port is a process-specific or an application-specific software construct serving as a communication endpoint, which is used by the Transport Layer protocols of Internet Protocol suite, such as User Diagram Protocol (UDP) and Transmission Control Protocol (TCP).
- 20, 21: FTP (File Transfer Protocol)
- 22: SSH (Secure Shell)
- 23: Telnet
- 25: SMTP (Simple Mail Transfer Protocol)
- 53: DNS (Domain Name System)
- 80: HTTP (Hypertext Transfer Protocol)
- 110: POP3 (Post Office Protocol version 3)
- 143: IMAP (Internet Message Access Protocol)
- 443: HTTPS (HTTP Secure)
- 3306: MySQL Database

56.. **RDP**-(Remote dESKTOP protocol)RDP stands for Remote Desktop Protocol. It's a proprietary protocol developed by Microsoft that enables users to remotely access and control a computer over a network connection.With RDP, a user can log into a remote computer from another location as if they were sitting in front of it

57..**Instance Store**-An instance store provides temporary block-level storage for your instance. This storage is located on disks that are physically attached to the host computer. Instance store is ideal for temporary storage of information that changes frequently, such as buffers, caches, scratch data, and other temporary content. 

58.. **Virtual Hosting**-Virtual hosting is a method for hosting multiple domain names (with separate handling of each name) on a single server (or pool of servers). This allows one server to share its resources, such as memory and processor cycles, without requiring all services provided to use the same host name.
![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/91e912ce-9033-4c09-bf31-b3e47a327646)

59..**Reverse Proxy**- a server that sits in front of web servers and forwards client (e.g. web browser) requests to those web servers. Reverse proxies are typically implemented to help increase security, performance, and reliability.

60..**NGINX**- Nginx is a web server that can also be used as a reverse proxy, load balancer, mail proxy and HTTP cache.

61..**Load Balancing**-Load balancing refers to efficiently distributing incoming network traffic across a group of backend servers, also known as a server farm or server pool.
Different load balancing algorithms provide different benefits; the choice of load balancing method depends on your needs:

- **Round Robin – Requests are distributed across the group of servers sequentially.*

- **Least Connections – A new request is sent to the server with the fewest current connections to clients. The relative computing capacity of each server is factored into determining which one has the least connections.*

- **Least Time – Sends requests to the server selected by a formula that combines the fastest response time and fewest active connections.*

- **Hash – Distributes requests based on a key you define, such as the client IP address or the request URL.*

- **IP Hash – The IP address of the client is used to determine which server receives the request.*

- **Random with Two Choices – Picks two servers at random and sends the request to the
one that is selected by then applying the Least Connections algorithm.*

61.. **End To End Encryption**- End-to-end encryption is a security method that keeps your communications secure. With end-to-end encryption, no one, including Google and third parties, can read eligible messages as they travel between your phone and the phone you message.

62.. **OSI Layers(open System Intercommunication)**- a conceptual framework used to describe the functions of a networking system.

63..**Daemons**- Daemons are processes that run unattended. They are constantly in the background and are available at all times. Daemons are usually started when the system starts, and they run until the system stops. A daemon process typically performs system services and is available at all times to more than one task or user.

64.. 
# Process of a simple func as r=1+1 \n print(r)

   1) **Tokenization**- 
     - a) {In Python}Python tokenization basically refers to splitting up a larger body of text into smaller lines, words or even creating words for a non-English language
     - b) {In Blockchain}Tokenization is the process of replacing sensitive data with unique identification symbols that retain all the essential information about the data without compromising its security.

   2)**CST(concrete syntax tree)** -

   3)**AST(abstract syntax tree)** -


![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/f2c4dcba-4584-4d0d-a129-b60510cca972)

   4)**Type deduction**- 

   5)**Bytecode**-After the conversion into bytes the python virtual machine gives the result.









