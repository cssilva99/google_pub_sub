
<p align="center">
  <img src="https://www.gstatic.com/devrel-devsite/prod/v6232d39b819e6f3f0d0469b61d4a8d052d92d47f9a3e29f5f1349f2b86c8f657/google/images/lockup.svg" width="300" alt="Google Cloud Logo">
</p>

# Google Cloud Pub/Sub: Messaging and Event Streaming

This repository contains resources and guides based on the step-by-step video tutorial of an exercise performed via the **Google Cloud Console**, focusing on **Pub/Sub (Publish/Subscribe)** architecture.

## 📺 Video Tutorial
Watch the detailed Pub/Sub exercise here:
[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?style=for-the-badge&logo=youtube)](https://youtu.be/wORmT5TUk30)

---

## 🛠️ Prerequisites
To follow this exercise via the GCP Console, ensure you have:

* **Google Cloud Project:** An active project with billing enabled.
* **Pub/Sub API:** Enabled in your GCP project.
* **Network Permissions:** IAM roles such as `Pub/Sub Editor` or `Owner` to manage topics and subscriptions.

---

## 🚀 About the Service: Google Cloud Pub/Sub
**Google Cloud Pub/Sub** is an asynchronous and scalable messaging service that decouples services that produce events from services that process events. It is a core component for building event-driven architectures and real-time data integration pipelines.

### Key Components:
- **Topic:** A named resource to which messages are sent by publishers.
- **Subscription:** A named resource representing the stream of messages from a single, specific topic, to be delivered to the subscribing application.
- **Publisher:** An application that creates and sends messages to a topic.
- **Subscriber:** An application with a subscription to a topic to receive messages from it.

### Why Use Pub/Sub?
- **Decoupling:** Services communicate without needing to know about each other.
- **Scalability:** Handles millions of messages per second with low latency.
- **Reliability:** Guarantees "at-least-once" delivery and offers durable storage.

---

## 💰 Pricing Model
Pub/Sub pricing is based primarily on the volume of data transmitted:

| Charge Type | Description | Model |
| :--- | :--- | :--- |
| **Throughput** | Data volume published, pushed, or pulled. | **Pay-as-you-go** (per GB) |
| **Storage** | Unacknowledged messages stored in the system. | **Free for 7 days** (then standard rates) |
| **Snapshots** | Capturing the state of a subscription. | **Standard Storage Rates** |

**Summary:** You are billed based on the amount of data processed. The first **10 GB** of throughput per month is usually covered under the GCP Free Tier.

---

## 📖 Instructions
1. **Navigate to Pub/Sub** in your Google Cloud Console.
2. **Follow** the practical exercise demonstrated in the video [at this link](https://youtu.be/wORmT5TUk30).
3. **Perform** the following steps as shown:
    - Create a **Topic**.
    - Create a **Subscription** for that topic.
    - **Publish** a test message to the topic.
    - **Pull** and verify the message from the subscription.

---
*Created by [Code Klaudia](https://www.youtube.com/@CodeKlaudia)*
