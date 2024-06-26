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
<h1>Service Models Responsibilities</h1>
    <p>Diagram representing the layers of an application, platform, and hardware in an organizational use case.</p>
    <p>In a cloud infrastructure, layers include application, platform, and hardware. The application layer involves software and services users interact with. The platform layer provides runtime environments, middleware, and operating systems. The hardware layer includes servers, storage, and networking components, managed by the cloud provider for seamless operation. Above the hardware and application platform layers in cloud infrastructure, there's a crucial management and orchestration layer. This layer coordinates resources across multiple servers and data centers, ensuring optimal performance, scalability, and fault tolerance. It integrates automation and monitoring tools to streamline operations and enhance the overall efficiency of cloud services delivery.</p>

    <h2>Service Models Responsibilities</h2>
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
    <p><b>Disadvantages:</b></p>
    <ul>
        <li>Can be more expensive.</li>
        <li>Complicated to manage due to larger landscape.</li>
        <li>Most dependent on IT skills & expertise from all three models.</li>
    </ul>
    <p><b>Example: VMware Cloud Foundation</b><br>
    Integrates private and public cloud infrastructure, providing a unified environment for managing applications across different platforms.</p>
