## What are EC2 instance types?

1. General purpose
2. Compute optimized
3. Storage optimized
4. Memory optimized
5. Accelerated computing


### General purpose instances

General purpose instances provide a balance of compute, memory, and networking resources. 

Applications:
*    application servers
*    gaming servers
*    backend servers for enterprise applications
*    small and medium databases

### Compute optimized instances

Compute optimized instances are ideal for compute-bound applications that benefit from high-performance processors. Like general purpose instances, you can use compute optimized instances for workloads such as web, application, and gaming servers.


However, the difference is compute optimized applications are ideal for high-performance web servers, compute-intensive applications servers, and dedicated gaming servers. You can also use compute optimized instances for batch processing workloads that require processing many transactions in a single group.

### Memory optimized instances

Memory optimized instances are designed to deliver fast performance for workloads that process large datasets in memory.

Applications:
*    high-performance database
*    workload that involves performing real-time processing of a large amount of unstructured data

### Accelerated computing instances

Accelerated computing instances use hardware accelerators, or coprocessors, for accelerated data processing.

Applications:
*    floating-point number calculations
*    graphics processing
*    data pattern matching
*    graphics applications
*    game streaming
*    application streaming

### Storage optimized instances

Storage optimized instances are designed for workloads that require high, sequential read and write access to large datasets on local storage.

Applications:
*    distributed file systems
*    data warehousing applications
*    high-frequency online transaction processing (OLTP) systems


> NOTE: In computing, the term input/output operations per second (IOPS) is a metric that measures the performance of a storage device. It indicates how many different input or output operations a device can perform in one second. Storage optimized instances are designed to deliver tens of thousands of low-latency, random IOPS to applications.