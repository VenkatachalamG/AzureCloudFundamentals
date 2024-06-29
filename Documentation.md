<h1>What is Cloud Computing?</h1>
    <p>Cloud Computing refers to the delivery of services over the internet (cloud) using a variety of computing resources and capabilities. These services include:</p>
    <ul>
        <li>Compute Power: Servers such as Windows and Linux, hosting environments, and virtual machines.</li>
        <li>Storage: File storage and databases for data management.</li>
        <li>Networking: Connectivity within cloud environments like Azure, as well as connections to external networks such as company networks.</li>
        <li>Analytics Services: Tools for data visualization and telemetry analysis.</li>
    </ul>

<h2>CapEx vs OpEx</h2>
    <table>
        <tr>
            <th></th>
            <th>Capital Expenditure (CapEx)</th>
            <th>Operational Expenditure (OpEx)</th>
        </tr>
        <tr>
            <td>Up front cost</td>
            <td>Significant</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Ongoing cost</td>
            <td>Low</td>
            <td>Based on usage</td>
        </tr>
        <tr>
            <td>Tax Deduction</td>
            <td>Over time</td>
            <td>Same year</td>
        </tr>
        <tr>
            <td>Early Termination</td>
            <td>No</td>
            <td>Anytime</td>
        </tr>
        <tr>
            <td>Maintenance</td>
            <td>Significant</td>
            <td>Low</td>
        </tr>
        <tr>
            <td>Value over time</td>
            <td>Lowers</td>
            <td>No change</td>
        </tr>
    </table>

<h2>What is a Consumption-Based Model?</h2>
    <p>The consumption-based model in cloud computing is a pricing model where customers are billed based on their actual resource usage. Key characteristics include:</p>
    <ul>
        <li>No Upfront Cost: Customers are not charged upfront; costs accrue based on usage.</li>
        <li>No Wasted Resources: Charges are incurred only for resources actively used. For example, blob storage that stores data incurs charges based on the space used, while running virtual machines incur charges for CPU, memory, etc., even when idle.</li>
        <li>Pay for What You Need: Flexibility to scale resources up or down based on demand.</li>
        <li>Stop Paying When You Don't: Costs cease when resources are no longer required.</li>
    </ul>

<h2>Consumption</h2>
    <p>Consumption is the virtual metric used to measure and bill resources in a cloud environment. It ensures efficient use of resources and cost management based on actual utilization.</p>
<h1>Service Model Responsibilities</h1>
    <p>Diagram representing the layers of an application, platform, and hardware in an organizational use case.</p>
    <p>In a cloud infrastructure, layers include application, platform, and hardware. The application layer involves software and services users interact with. The platform layer provides runtime environments, middleware, and operating systems. The hardware layer includes servers, storage, and networking components, managed by the cloud provider for seamless operation. Above the hardware and application platform layers in cloud infrastructure, there's a crucial management and orchestration layer. This layer coordinates resources across multiple servers and data centers, ensuring optimal performance, scalability, and fault tolerance. It integrates automation and monitoring tools to streamline operations and enhance the overall efficiency of cloud services delivery.</p>

<h2>Services included in a Service Model</h2>
    <ul>
        <li><b>Infrastructure as a Service (IaaS):</b> Infrastructure as a Service (IaaS) provides virtualized computing resources over the internet. It includes virtual machines, storage, and networking components that users can rent on-demand. With IaaS, businesses can scale their infrastructure without investing in physical hardware.</li>
        <li><b>Platform as a Service (PaaS):</b> Platform as a Service (PaaS) provides a platform allowing customers to develop, run, and manage applications without the complexity of building and maintaining the underlying infrastructure. PaaS offerings typically include development tools, database management systems, and middleware.</li>
        <li><b>Software as a Service (SaaS):</b> Software as a Service (SaaS) delivers software applications over the internet, on a subscription basis. Users access SaaS applications via a web browser, eliminating the need for installation and maintenance.</li>
    </ul>

<p><i>As a service means which party will manage the particular layer and all the layers below:</i></p>
<table>
        <thead>
            <tr>
                <th>Layer</th>
                <th>On-Premises</th>
                <th>IaaS</th>
                <th>PaaS</th>
                <th>SaaS</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Application</td>
                <td>User</td>
                <td>User</td>
                <td>User</td>
                <td>Cloud provider</td>
            </tr>
            <tr>
                <td>Data</td>
                <td>User</td>
                <td>User</td>
                <td>User</td>
                <td>Cloud provider</td>
            </tr>
            <tr>
                <td>Runtime</td>
                <td>User</td>
                <td>User</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
            </tr>
            <tr>
                <td>Middleware</td>
                <td>User</td>
                <td>User</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
            </tr>
            <tr>
                <td>Operating System</td>
                <td>User</td>
                <td>User</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
            </tr>
            <tr>
                <td>Virtualization</td>
                <td>User</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
            </tr>
            <tr>
                <td>Servers</td>
                <td>User</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
            </tr>
            <tr>
                <td>Networking</td>
                <td>User</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
            </tr>
            <tr>
                <td>Storage</td>
                <td>User</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
                <td>Cloud provider</td>
            </tr>
        </tbody>
    </table>

<h2>Cloud Deployment Model</h2>
<p>Cloud Deployment Model simply describes where the company resources are deployed, whether in a public cloud provider environment or a private datacenter.</p>

<h3>Public Cloud</h3>
    <p><b>Key Characteristics:</b></p>
    <ul>
        <li>Everything runs on cloud provider hardware.</li>
        <li>No local hardware.</li>
        <li>Some services share hardware with other customers.</li>
    </ul>
    <p><b>Advantages:</b></p>
    <ul>
        <li>No CapEx (No initial investment).</li>
        <li>High Availability.</li>
        <li>Agility.</li>
        <li>Pay as You Go pricing.</li>
        <li>No hardware maintenance.</li>
        <li>No deep technical skills required as the infrastructure is managed by the Cloud Provider. User organization can focus on developing User applications rather than worrying about infrastructure.</li>
    </ul>
    <p><b>Disadvantages:</b></p>
    <ul>
        <li>Not all security and compliance policies can be met because everything is managed by User CSP.</li>
        <li>No ownership over the physical infrastructure.</li>
        <li>Rare specific scenarios can’t be done as User don’t manage any infrastructure so User cannot configure the policies as per User requirement.</li>
    </ul>
    <p><b>Example: Microsoft Azure</b><br>
    Azure provides cloud services like virtual machines, databases, and AI services, integrated with Microsoft's ecosystem.</p>

<h3>Private Cloud</h3>
    <p><b>Key Characteristics:</b></p>
    <ul>
        <li>Everything runs on User own datacenter.</li>
        <li>Self-service should be provided.</li>
        <li>User maintain the hardware.</li>
    </ul>
    <p><b>Advantages:</b></p>
    <ul>
        <li>Can support any scenario.</li>
        <li>Total control over security and infrastructure.</li>
        <li>Can meet any security and compliance policy.</li>
    </ul>
    <p><b>Disadvantages:</b></p>
    <ul>
        <li>Initial investment is required (CapEx).</li>
        <li>Limited agility constrained by server capacity and team skills.</li>
        <li>Very dependent on skills & expertise of User team.</li>
    </ul>
    <p><b>Example: IBM Cloud</b><br>
    Offers a range of cloud computing services and solutions, including AI, analytics, and blockchain technology.</p>

<h3>Hybrid Cloud</h3>
    <p><b>Key Characteristics:</b></p>
    <ul>
        <li>Combines both Public & Private cloud.</li>
    </ul>
    <p><b>Advantages:</b></p>
    <ul>
        <li>Great flexibility.</li>
        <li>User can run any legacy apps in private cloud.</li>
        <li>Can utilize existing infrastructure.</li>
        <li>Meet any security & compliance requirements.</li>
        <li>Can take advantage of all public cloud benefits.</li>
    </ul>
    <p><b>Disadvantages:</b> Can be more expensive.
<h2>What is a Data Center?</h2>
    <p>A data center is a physical facility designed for hosting a group of networked servers including its own dedicated power supply, cooling systems, and networking infrastructure. These facilities are essential for ensuring continuous operations and optimal performance of servers and data storage.</p>

<h2>Regions</h2>
    <ul>
        <li><b>Geographical area on the planet.</b></li>
        <li><b>One but usually more data centers connected with low-latency network (<2 milliseconds).</b></li>
        <li><b>Location for your services.</b></li>
        <li><b>Some services are available only in certain regions.</b></li>
        <li><b>Some services are global services, as such are not assigned/deployed in specific region.</b></li>
        <li><b>Globally available with 50+ regions.</b></li>
    </ul>

<h2>Availability Zone</h2>
    <p>A regional feature in cloud infrastructure involves the grouping of physically separate facilities within a geographical region. These facilities are strategically located to enhance reliability and resilience against data center failures. By dispersing infrastructure across multiple sites within a region, cloud providers ensure that services remain accessible and operational even in the event of localized disruptions or failures, thereby maintaining continuity and minimizing downtime for users and applications.</p>

<h2>Two Service Categories</h2>
    <ul>
        <li><b>Zonal services (Virtual Machines, Disks, etc.).</b></li>
        <li><b>Zone-redundant services (SQL, Storage, etc.).</b></li>
    </ul>

<h2>Not all Regions</h2>
    <p>Not all regions in cloud computing infrastructure are uniformly supported, as availability varies based on geographic location and provider infrastructure deployment strategies. A supported region typically consists of three or more availability zones, with each zone comprising one or more data centers.</p>

<h2>Region Pair</h2>
    <ul>
        <li><b>Each region is paired with another region making it a region pair.</b></li>
        <li><b>Region pairs are static and cannot be chosen (manually).</b></li>
        <li><b>Each pair resides within the same geography with exception being Brazil South with its region pair residing in United States.</b></li>
        <li><b>Physical isolation with at least 300 miles distance (when possible).</b></li>
    </ul>

<h3>Example of some Region-Pairs:</h3>
    <table>
        <thead>
            <tr>
                <th>REGION PAIR A</th>
                <th>REGION PAIR B</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>EAST US</td>
                <td>WEST US</td>
            </tr>
            <tr>
                <td>UK WEST</td>
                <td>UK SOUTH</td>
            </tr>
            <tr>
                <td>NORTH EUROPE (Ireland)</td>
                <td>WEST EUROPE (Netherlands)</td>
            </tr>
            <tr>
                <td>EAST ASIA (Hong Kong)</td>
                <td>SOUTHEAST ASIA (Singapore)</td>
            </tr>
        </tbody>
    </table>
<h2>Azure Resources</h2>
<p>Azure Resources are the objects that are used to manage the various Azure services that we create. Each Resource represents or contains information about a resource or service lifecycle. Each time we create an Azure Resource, it is created as a .config JSON file.</p>

![pic3](https://github.com/VenkatachalamG/AzureCloudFundamentals/assets/119162683/5f716093-bb4d-4786-84ad-bda60f023a71)
<h5>An Example of an Azure Resource Group JSON Config File</h5>

<h2>Azure Resource Groups</h2>
<p>Azure Resource Groups are logical collection or grouping of Azure Resources. They were created as a tool to group Azure Resources to manage them. There are many ways in which Azure Resources can be grouped. Some logically defined ones are:</p>
<ul>
   <li><h3>Grouped by Resource Type</h3>
<p>This is a kind of grouping where the goal or need is to group the resources by the category of the resource. For example, you could group all SQL resources under one resource group and group all Web Apps Resource in another resource group.</p>

![Picture1](https://github.com/VenkatachalamG/AzureCloudFundamentals/assets/119162683/7b7b8b11-de38-4ffc-b98e-6d18e21e0e02)
<h5>An Example of Grouping Azure Resources by Resource Type</h5></li>

   <li><h3>Grouped by Application Lifecycle</h3>
<p>This is a kind of grouping where the goal or need is to group the resources by the lifecycle of the application being developed so that you can test and deploy environments separately and apply any configurations, policies or any network rules easily and efficiently.</p></li>

![Picture2](https://github.com/VenkatachalamG/AzureCloudFundamentals/assets/119162683/c796967c-e1c8-4068-838d-c148da6a6246)
<h5>An Example of Grouping Azure Resources by Application Lifecycle/Environments</h5>

   <li><h3>Grouped by Department, Location, Billing</h3>
<p>This is a kind of grouping where the goal or need is to group the resources by the amount of costs of each resource for efficient billing purposes, by the department type so that teams can quickly access their application resources and track and report on cloud spending by department, or by the location so you can apply data sovereignty and security rules easily for data.</p></li>
</ul>
<p>As there is not one single policy that can satisfy all the needs of an organization, organizations tend to use a combination of all the above-mentioned grouping types. Combining these criteria allows for a more tailored and efficient organization of resources, providing better control and visibility in managing Azure environments.</p>

<h2>Resource Manager</h2>
<p>We can provision our Azure Resources and create Azure Resource Groups and basically access our Azure Account through various methods. We can use the Azure portal, use Azure CLI, through a REST API, or through some SDKs. But all of them eventually go through a single point of management and authentication called the Azure Resource Manager (ARM). The Azure ARM is a centralized management layer for all resources and is linked with the Entra ID (previously known as Azure Active Directory or Azure AD) for authentication and authorization of users. Therefore, the two features of Azure ARM are unified language and control access and resources.</p>

![pic4](https://github.com/VenkatachalamG/AzureCloudFundamentals/assets/119162683/7863c705-c506-44a3-8ff0-4c3ac14dba79)
<h5>The dashboard view of the Azure Resource Manager</h5>

🚀<b>Snapshots for the creation of Azure Resources, Resource Groups : <a link href="Snapshots/Azure Resources,RGs">Click here</a></b>
<h1>Virtualization</h1>
  <p>
    Virtualization is a technology that allows the emulation of physical machines, enabling multiple virtual machines to run on a single physical host (computer). A Virtual Machine (or VM) is an emulation of a physical computer system having virtual resources like CPU, memory, storage etc. Each VM can have different virtual hardware configurations configured to the needs of specific applications. This feature allows for the installation of different operating systems on each VM, providing total separation of environments. Such separation extends to file systems, services, ports, middleware, and configuration settings, ensuring that each VM operates independently and securely without interference from others.
  </p>
<h1>Virtual Machine Scale Sets</h1>
  <p>
    Infrastructure as a Service (IaaS) offers a set of identical virtual machines equipped with built-in auto scaling features, ensuring that resources can dynamically adjust to meet varying demands. This capability is particularly beneficial for workloads that require scalability, such as web services and batch processing. With IaaS, users can efficiently manage both manual and auto-scaled workloads, ensuring optimal performance and cost-efficiency. The flexibility to scale resources up or down as needed makes IaaS an ideal choice for applications with fluctuating or unpredictable usage patterns, providing a robust and responsive infrastructure for a wide range of computing needs.
  </p>

<h1>Containers</h1>
  <p>
    Using the host's operating system, virtualization can emulate entire operating systems, with Virtual Machines (VMs) emulating the underlying hardware. However, there are more lightweight options available that do not require a full operating system, reducing development effort, maintenance, and compute and storage requirements. These lightweight virtual environments can respond quicker to changes in demand, offering greater agility and efficiency. Designed for almost any scenario, these solutions provide flexibility and scalability, making them suitable for a variety of applications and workloads, from development and testing to production and high-demand environments.
    <br>
    Examples include Docker, Docker Compose, Kubernetes, LXC (Linux Containers), etc.
  </p>

<h1>Azure Container Instances</h1>
  <p>
    The simplest and fastest way to run a container in Azure is through Platform as a Service (PaaS) with serverless containers. Designed for small and simple web apps/services, background jobs, and scheduled scripts, this approach offers efficient, scalable solutions without the need for managing underlying infrastructure.
  </p>

<h1>Azure Kubernetes Service (AKS)</h1>
  <p>
    Kubernetes, an open-source container orchestration platform, offers highly scalable and customizable solutions as a Platform as a Service (PaaS). It is designed for high-scale container deployments, capable of managing a vast array of applications and services, making it ideal for any large-scale containerized environment.
  </p>

<h1>App Service</h1>
  <p>
    Azure App Service is designed as an enterprise-grade web application service, offering Platform as a Service (PaaS) capabilities. It supports multiple programming languages and containers, providing a versatile and scalable solution for deploying and managing web applications in a robust and efficient manner.
  </p>
<h1>Azure Functions (Function Apps)</h1>
  <p>
    As a Platform as a Service (PaaS), Azure Functions offers a serverless environment with two hosting and pricing models: a consumption-based plan and a dedicated plan. Designed for micro and nano-services, it provides a scalable and cost-effective solution for running small, modular functions without managing infrastructure.
  </p>
🚀<b>Snapshots for the creation of Azure Virtual Machines, VM Scale sets, Containers, App Service : <a link href="Snapshots/Azure VM, Scale Sets, App Service, Container Instances">Click here</a></b>
<h1>Azure Networking Components</h1>

<h2>Azure Virtual Network</h2>
    <p>
        A Virtual Network (VNet) in Azure represents logically isolated networking components that can be segmented into one or more subnets. These subnets are discrete sections within the VNet, allowing for organized and efficient management of resources. Subnets enable the communication of resources with each other, the internet, and on-premises networks, providing flexibility and connectivity across different environments. The main purpose of having subnets is:
    </p>
    <ul>
        <li>Allowing users/customers to allocate IP addresses more smartly and efficiently for their resources</li>
        <li>Allowing users/customers to group multiple resources together so that they can apply custom security rules to the required resources</li>
    </ul>
    <p>
        Each VNet is scoped to a single region, ensuring that all resources within it are region-specific. However, VNet peering facilitates cross-region communication, enabling VNets in different regions to communicate seamlessly. You can connect or communicate between two VNets in different regions either through VNet Peering or through a Virtual Private Gateway (VPN Gateway).
    </p>

![Picture1](https://github.com/VenkatachalamG/AzureCloudFundamentals/assets/119162683/6257fd0c-626c-4642-b498-7fd3f851237e)
<b>Figure showing how two VNets can be communicated</b>

<h2>Azure Load Balancer</h2>
    <p>
        Azure Load Balancer provides even traffic distribution, supporting both inbound and outbound scenarios to ensure optimal performance and reliability in high-availability scenarios. It effectively manages traffic for applications using both TCP (Transmission Control Protocol) and UDP (User Datagram Protocol), handling both internal and external traffic seamlessly. With port forwarding capabilities, Azure Load Balancer can direct traffic to specific ports based on your configurations. Designed to scale, it can manage up to millions of flows, making it a robust solution for applications requiring high traffic volumes and reliability.
    </p>

<h2>VPN Gateway</h2>
    <p>
        The specific type of virtual network gateway used for on-premises to Azure traffic over the public internet is called a VPN Gateway. A VPN Gateway is a type of virtual network gateway that sends encrypted traffic between your virtual network and your on-premises location over the public internet. You can also use a VPN Gateway to send encrypted traffic between Azure virtual networks. Each virtual network can have only one VPN Gateway, but the gateway can connect to multiple on-premises locations using site-to-site VPN connections.
    </p>

<h2>Application Gateway</h2>
    <p>
        Application Gateway is another kind of load balancer that specializes in handling HTTPS or web traffic. So when you want to route incoming traffic from HTTPS onto your virtual machines or App Service services, you could use an Application Gateway to do the job for you.
    </p>

<h2>Content Delivery Network</h2>
    <p>
        A Content Delivery Network (CDN) is designed to optimize the delivery of web content by reducing latency and improving load times. By distributing content across a network of servers located in various geographic locations, CDNs ensure that users can access data from a server that is physically closer to them. These servers, known as Points of Presence (POPs), cache content to provide faster and more efficient access. This significantly enhances the user experience, as it allows for quicker retrieval of web content, ensuring that users receive the information they need with minimal delay.
    </p>
    <p>
        Note:
        <ul>
            <li>When creating a Virtual Machine, you can go to the Search in the navigation panel. There, search for ‘Diagram’ and then click on ‘Diagram’ to view a graphical representation of the networks and Network Security Groups (NSGs) that are associated with a VM. There you can view the structure of a Virtual Machine VNet consisting of the IP address configurations, VM’s public IP Addresses, and the network security group of a VM. </li><br>

   ![sample networking diagram of VN of a VM](https://github.com/VenkatachalamG/AzureCloudFundamentals/assets/119162683/1876fdaa-329b-470d-9ae9-242e4ca4caa3)
   <p><b>Diagram showing the network structure of a VNet of a Virtual MAchine</b></p>
  <li>Point-of-Presence (POP) locations are the locations that are closest to users in a CDN service. Users can access their data with minimal latency thanks to these POP locations. Microsoft has over 120 POP locations.</li>
        </ul>
    </p>
🚀<b>Snapshots for the creation of Azure Virtual Networks, VNet in a Virtual MAchine Resource : <a link href="Snapshots/Azure VNet">Click here</a></b>
<h1>Data Types</h1>
    <p>
        Structured data is characterized by its strict schema representation, typically organized in tables where each row has a predefined schema. This data format often involves defined relationships between tables, making it suitable for use in relational databases. Semi-structured data, on the other hand, can also be represented in tables but lacks a strict schema, with the primary requirement being a unique key identifier for each row. This flexibility allows for variations in data structure while still maintaining some level of organization. Unstructured data encompasses a wide range of file formats, including binary files, application files, images, movies, and other media. This type of data does not have any specific schema or structure, making it versatile but often more challenging to manage and analyze.
    </p>

<h1>Storage Account</h1>
    <p>
        A group of services that include blob storage, queue storage, table storage, and file storage is designed to store files, messages, and semi-structured data. These services are highly scalable, capable of handling up to petabytes of data, and offer exceptional durability with availability rates ranging from 99.999999999% (11 nines) to 99.99999999999999% (16 nines). Additionally, they are the most cost-effective per gigabyte storage options available, making them ideal for various storage needs while ensuring data reliability and accessibility.
    </p>
    <p>
        Azure Storages are typically divided into these main categories:
    </p>
    <ul>
        <li>Azure Blob Storage</li>
        <li>Azure Queue Storage</li>
        <li>Azure Table Storage</li>
        <li>Azure File Storage</li>
    </ul>

<h2>Blob Storage</h2>
    <p>
        A BLOB (Binary Large Object) is designed for the storage of files of any kind. This storage solution offers three varieties of storage tiers to accommodate varying access needs: the Hot tier for frequently accessed data, the Cool tier for infrequently accessed data which offers lower availability but high durability, and the Archive tier for data that is rarely, if ever, accessed. This tiered approach allows for optimized cost management and efficient data storage solutions based on usage patterns. The Hot tier has the highest price in terms of storage rate, while the Archive Tier has the highest price for data retrieval rate.
    </p>

![Picture1](https://github.com/VenkatachalamG/AzureCloudFundamentals/assets/119162683/45cc05ca-5d9a-4338-9117-59e46a53078b)<br>
<b>Diagram to show structure of Blob Storage</b>
<h2>Queue Storage</h2>
    <p>
        Storage for small pieces of data, such as messages, is designed for scalable asynchronous processing. This type of storage ensures that data can be processed efficiently and independently of the application's main flow, allowing for better handling of workloads that require decoupling and parallel processing. Messages are put into a queue which are picked up by services for execution. Queue Storage helps to offload applications efficiently and its scalability ensures that it can handle varying loads, making it an ideal solution for systems that need to manage large volumes of messages or data fragments asynchronously.
    </p>

<h2>Table Storage</h2>
    <p>
        Storage for semi-structured data, commonly referred to as NoSQL storage, is designed to accommodate data without the need for foreign joins, foreign keys, relationships, or a strict schema. This flexibility allows for rapid access and manipulation of data, making it suitable for applications requiring high performance and scalability. Additionally, NoSQL storage supports a wide range of programming interfaces and SDKs, enabling developers to integrate and interact with the data seamlessly across various platforms and languages.
    </p>

<h2>Disk Storage</h2>
    <p>
        Disk emulation in the cloud provides persistent storage for Virtual Machines, offering flexibility and scalability for various computing needs. This storage solution comes in different sizes and types, such as SSD and HDD, catering to different performance requirements. Additionally, it features various performance tiers to optimize for speed and cost-efficiency. Cloud disks can be either unmanaged or managed, giving users the option to handle storage management themselves or rely on the cloud provider for automated management and maintenance.
    </p>

![Picture2](https://github.com/VenkatachalamG/AzureCloudFundamentals/assets/119162683/88ec4724-5e06-448a-ad42-4a0b183a9ea1)<br>
<b>Sketch of a Disk Storage</b>
