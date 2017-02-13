1)	Characteristics of Big Data:
           Volume
The quantity of generated and stored data. The size of the data determines the value and potential insight- and whether it can actually be considered big data or not.
    Variety
The type and nature of the data. This helps people who analyze it to effectively use the resulting insight.
          Velocity
In this context, the speed at which the data is generated and processed to meet the demands and challenges that lie in the path of growth and development.
          Variability
Inconsistency of the data set can hamper processes to handle and manage it.
          Veracity
The quality of captured data can vary greatly, affecting accurate analysis.

2)Possible solutions to handle Big data;
Scale up:
•	Increase the configuration of a single system,like capacity,RAM,Data transfer speed,etc.
•	Complex,costly,and a time consuming process.
Scale out:
•	Use multiple commodity machines and distribute the load of storage/processing among them.
•	Economical and quick to implement as it focuses on distribution of load.
•	Instead of having a single system with of 10TB of storage and 80GB of RAM,use 40 Machines with 256GB of Storage and 2GB of RAM.

              3)Scaling up:
	It refers to architecture that uses a fixed controller resource for all processing. Scaling capacity happens by adding storage shelves up to the maximum number permitted for that controller. In order to maintain high availability, such architectures typically use dual controllers. However, the majority of them act as “active-passive” which creates a situation whereby the array’s performance is limited by the performance of a single controller. It leads to waste of 50 percent resources under normal operations and the industry has really moved away from it.
          Scaling out:
It refers to architecture that doesn’t rely on a single controller and scales by adding processing power coupled with additional storage. It’s also important to remember that with scale-out, all architectures are not created equal. (Some vendors build a unified management that utilizes multiple, independent arrays and call it scale-out, which is, technically speaking, false.) In true scale-out architecture, the data and the metadata are distributed across all nodes and all SSDs in the system. Modern scale-out architectures also implement global deduplication across the entire data set.

