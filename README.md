# Poorti: Order Fulfillment Manager

Poorti is a suite of microservices designed to streamline order fulfillment processes in various fulfillment facilities, including mini-warehouses and retail stores. This open-source solution automates key workflows, manages inventory, and provides a scalable architecture for modern businesses.

## Features

* **Automated Order Fulfillment:** Seamlessly handle picking, packing, and shipping processes.
* **Inventory Management:** Efficiently manage receiving, cycle counting, and inventory availability.
* **Microservices Architecture:**  Decoupled and headless services ensure horizontal and vertical scalability, allowing the system to grow with your business.
* **Integration-Ready:**  Built on the Moqui Framework, Poorti can easily integrate with your existing systems and tools.

## Getting Started

### Prerequisites

Make sure you have the following installed:

* **Moqui Framework:** [https://github.com/moqui/moqui-framework](https://github.com/moqui/moqui-framework)
* **Data Model (Mantle-UDM):** [https://github.com/hotwax/mantle-udm](https://github.com/hotwax/mantle-udm)
* **Service Library (OMS-USL):** [https://github.com/hotwax/oms-usl](https://github.com/hotwax/oms-usl)
* **Java Development Kit (JDK):** Version 11 or higher 

### Installation & Configuration

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/hotwax/poorti.git
   ```
2. **Set up Moqui Framework:**
   * Follow the Moqui Framework's installation guide [Moqui Setup](https://www.moqui.org/docs/framework/Run+and+Deploy) to get it up and running.
3. **Integrate Poorti:**
   * Detailed instructions for configuring Poorti within your Moqui environment can be found in the [Poorti Setup Guide](docs/setup.md).

## Contributing

We welcome contributions! Here's how you can get involved:

1. **Fork the Repository:** Click the "Fork" button on GitHub.
2. **Create a Branch:** `git checkout -b feature/your-feature-name`
3. **Make Changes:** Code, test, and document your improvements.
4. **Commit:** `git commit -m "Your detailed commit message"`
5. **Push:** `git push origin feature/your-feature-name`
6. **Open a Pull Request:** Explain your changes and their benefits.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Support & Community

* **Questions or Issues:** Please open an issue on the [GitHub repository](https://github.com/hotwax/poorti/issues).
