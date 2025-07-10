# Achieving High Write Availability in Distributed Systems Through Multi-Leader Replication
* Author: Naveen Srikanth Pasupuleti
* Published In : International Journal on Science and Technology (IJSAT)
* Publication Date: June 2022
* E-ISSN: 2229-7677
* Impact Factor: 9.88
* Link: [Read the paper](https://www.ijsat.org/research-paper.php?id=5841)

**Abstract**:\
In distributed systems, accurate time synchronization is vital for maintaining consistency and coordination among nodes. Traditional Network Time Protocol (NTP) often suffers from high synchronization delays, especially in large-scale systems with many nodes and high network latency. These delays can lead to inconsistencies in data replication and hinder time-sensitive operations. This paper proposes the use of Chrony Sync, a more efficient time synchronization method, to significantly reduce synchronization times. By optimizing synchronization, Chrony enhances system performance, consistency, and reliability in large distributed environments.

**Sync Time**:\
Sync time, or time synchronization, refers to the process of aligning the clocks on two or more devices or systems to ensure they display the same time.

**Key Contributions:** 
* **Algorithm Development** \
  Designed and optimized Chrony sync time algorithm to achieve high write availability in distributed systems.
* **Performance Comparison** \
  Conducted bench marking between NTP Sync time and Chrony sync time.
* **Research Leadership** \
  Led the research and technical implementation , focusing on advancing distributed database through algorithm innovation.

**Relevance & Real-World Impact**
* **Scalable Time Synchronization:**\
Chrony provides more consistent and efficient synchronization than NTP as system size increases, supporting better scalability.

* **Enhanced Write Consistency:**\
Accurate time sync reduces write conflicts and improves reliability in distributed environments, making it better suited for time-critical operations.

* **Academic Recognition :** \
    Chrony's effectiveness in distributed time synchronization has been acknowledged in research communities for its role in improving coordination, reliability, and write consistency across large-scale systems. Its adoption is increasingly recommended in scholarly discussions on time-critical distributed computing.

* **Educational Impact:** \
    The comparison between NTP and Chrony serves as a practical case study in distributed systems curricula, illustrating the importance of time synchronization in maintaining consistency and availability. It enhances students' understanding of real-world challenges in system design and performance optimization.

**Experimental Results (Summary)**


| Cluster Size (Nodes) | NTP Sync Time (minutes) | Chrony Sync Time (minutes) | Improvement (%) |
| ---------------------| ----------------------- | -------------------------- | ----------------|
| 3                    | 8                       | 1                          | 87.5            |
| 5                    | 10                      | 1                          | 90              |
| 7                    | 13                      | 2                          | 84.6            |
| 9                    | 16                      | 2                          | 87.5            |
| 11                   | 18                      | 3                          | 83.3            |

**Citation**
* **Optimizing Read Performance in Distributed Systems Using Chrony Sync Process.**
*   Naveen Srikanth Pasupuleti
*   International Journal on Science and Technology
*   E-ISSN-2229-7677

**License**
* This research is shared for academic and research purposes. For commercial use, please contact the author.

**Resources**
* [IJSAT Website](https://www.ijsat.org/)

**Author Contact** 
  * LinkedIn: https://www.linkedin.com/in/naveensrikanth | Email: connect.naveensrikanth@gmail.com
