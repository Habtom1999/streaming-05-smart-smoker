# Streaming-05-Smart-Smoker

This project implements a data producer for streaming sensor data from a smart smoker system. The sensor data is stored in a CSV file, and the producer reads and sends it to RabbitMQ queues.

**Author:** Habtom Woldu  
**Date:** May 27, 2024

## Getting Started

### Before You Begin

Ensure the following requirements are met:

- RabbitMQ server is running.
- Pika library is installed in the active Python environment.

### Key Features

- Reading sensor data from a CSV file.
- Sending data to RabbitMQ queues.
- Simulating sensor data streaming at a rate of one value every 30 seconds.

### How to Use the Producer

1. Clone the repository to your local machine.
2. Make sure RabbitMQ is running.
3. Install Pika:

   ```bash
   pip install pika

# Usage

1. Run the Python file in the terminal:

   ```bash
   python bbq_producer_smoker.py

![alt text](image.png)
![alt text](image-1.png)
![alt text](RabbitMQ.png)
![alt text](image-3.png)


