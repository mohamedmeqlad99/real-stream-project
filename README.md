# Real-Time Customer Reviews Simulation

## Overview

This project simulates real-time customer reviews for a multitude of products using sockets. The reviews are processed and analyzed in real-time, providing sentiment analysis and storing the processed data for visualization. The architecture integrates several components:

- **Sockets**: Capture raw data in real-time.
- **Kafka**: Buffers and manages the flow of real-time data.
- **Spark**: Processes the data stream.
- **OpenAI**: Provides sentiment analysis capabilities.

## Architecture

1. **Sockets**: Entry point for capturing real-time customer review data.
2. **Kafka**: Serves as a buffer and ensures smooth data flow.
3. **Spark**: Processes the incoming data streams.
4. **OpenAI**: Performs sentiment analysis on the data.

## Features

- Real-time data capture and processing.
- Sentiment analysis using OpenAI.
- Efficient data storage and retrieval.
- Visualization-ready data endpoint.

## Prerequisites

Before setting up the project, ensure you have the following installed:

- Java 8+
- Apache Kafka
- Apache Spark
- Python 3.6+
- Required Python libraries: `pyspark`, `kafka-python`, `openai`

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/mohamedmeqlad99/real-stream-project.git
   cd real-stream-project
