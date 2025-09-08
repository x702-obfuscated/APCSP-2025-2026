# Big Idea 4: Computer Systems and Networks — Essential Knowledge

### Topic 4.1 — The Internet
* **CSN-1.A.1** A computing device is a physical artifact that can run a program. Examples: computers, tablets, servers, routers, smart sensors.
* **CSN-1.A.2** A computing system is a group of computing devices and programs working together for a common purpose.
* **CSN-1.A.3** A computer network is a group of interconnected computing devices capable of sending or receiving data.
* **CSN-1.A.4** A computer network is a type of computing system.
* **CSN-1.A.5** A path between two computing devices (sender → receiver) is a sequence of directly connected devices from start to end.
* **CSN-1.A.6** Routing is the process of finding a path from sender to receiver.
* **CSN-1.A.7** Bandwidth is the maximum amount of data that can be sent in a fixed amount of time.
* **CSN-1.A.8** Bandwidth is usually measured in bits per second.
* **CSN-1.B.1** The Internet is a network of interconnected networks using standardized, open protocols.
* **CSN-1.B.2** Internet access depends on connecting a device to an Internet-connected device.
* **CSN-1.B.3** A protocol is an agreed-upon set of rules that specify system behavior.
* **CSN-1.B.4** Internet protocols are open, allowing easy connection of new devices.
* **CSN-1.B.5** Routing on the Internet is usually dynamic, not predetermined.
* **CSN-1.B.6** Scalability is a system’s capacity to change in size/scale to meet new demands.
* **CSN-1.B.7** The Internet was designed to be scalable.
* **CSN-1.C.1** Information is passed as a data stream, containing chunks of data encapsulated in packets.
* **CSN-1.C.2** Packets include data and metadata for routing and reassembly.
* **CSN-1.C.3** Packets may arrive in order, out of order, or not at all.
* **CSN-1.C.4** IP, TCP, and UDP are common Internet protocols.
* **CSN-1.D.1** The World Wide Web (WWW) is a system of linked pages, programs, and files.
* **CSN-1.D.2** HTTP is a protocol used by the [WWW](http://WWW).
* **CSN-1.D.3** The WWW uses the Internet.

---

### Topic 4.2 — Fault Tolerance
* **CSN-1.E.1** The Internet was engineered to be fault-tolerant, with abstractions for routing and transmitting data.
* **CSN-1.E.2** Redundancy = inclusion of extra components to mitigate failures.
* **CSN-1.E.3** Network redundancy can be achieved by having multiple paths between devices.
* **CSN-1.E.4** If a device/connection fails, data can be rerouted through another path.
* **CSN-1.E.5** A system that supports failures and still functions is **fault-tolerant**.
* **CSN-1.E.6** Redundancy requires extra resources but provides fault tolerance.
* **CSN-1.E.7** Redundant routing options increase Internet reliability and scalability.

---

### Topic 4.3 — Parallel and Distributed Computing
* **CSN-2.A.1** Sequential computing: operations performed one at a time in order.
* **CSN-2.A.2** Parallel computing: program broken into smaller sequential operations, some executed simultaneously.
* **CSN-2.A.3** Distributed computing: multiple devices are used to run a program.
* **CSN-2.A.4** Efficiency of solutions can be compared by measuring task completion times.
* **CSN-2.A.5** Sequential solutions take as long as the sum of all steps.
* **CSN-2.A.6** Parallel solutions take as long as all sequential tasks plus the longest parallel task.
* **CSN-2.A.7** Parallel “speedup” = time of sequential solution ÷ time of parallel solution.
* **CSN-2.B.1** Parallel computing solutions have both parallel and sequential portions.
* **CSN-2.B.2** Parallel solutions can scale more effectively than sequential ones.
* **CSN-2.B.3** Distributed computing solves problems unsolvable on a single computer due to time or storage limits.
* **CSN-2.B.4** Distributed computing solves larger problems faster than a single computer.
* **CSN-2.B.5** Efficiency gains from parallel computing are limited by the sequential portion; at some point, adding more parallelism won’t improve efficiency.
